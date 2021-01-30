# ChromApp

* event.preventDefault();    
    : 이벤트가 실행될때 디폴트로 작동하는것 막기    
        ex) 엔터누르고 새로고침X     
    
    html에서 필요한 내용을 가져온거라면 => queryselector        
    바로 js에서 생성하고 싶으면 => document.createElement()            

* local Storage에는 자바스크립트의 data를 저장할 수 없다.    
    자바스크립트는 string으로만 저장하려고함    
    ==> JSON.strigify()를 이용해서 자바스크립트 객체를 string으로 바꿔줌

* .filter(함수)    
```    const cleanToDos = toDos.filter(filterFn)
toDos 배열의 모든 아이템을 통해 filterFn함수를 실행해서,    
함수 결과 true인 아이템들로 새로운 배열을 만듦
```

``` .forEach     
    또한 .filter와 같이 list에 있는 모든 item을 위한 함수를 실행시킴
```

** TIP **     
자바스크립트에서 객체를 만들때,    
key이름과 value이름이 같을 시 그냥 하나만 써도 됨.    
