# Object

### Object?

Any function, array, or regular expression is an object except primitive type. Thus, an object is a set of properties and methods that represent the actions that can be referenced.

### Object Use

Multiple values ​​can be grouped \(objects\) into a single value. In addition, objects can be stored in one memory names, and it can assign it to a variable.

```javascript
var user = {
    name: 'lee',
    location: 'Seoul',
    greeting: function(){
        console.log('hello! ${this.name}') 
    }

```



Object Value

= 객체는 property들의 집합으로 자바스크립트에 모든 값은 property에 값으로 사용할 수 있다. 단 값이 함수일 경우 일반 함수와 구분하기 위해 Method라 부른다.

객체 타입 \(Object / Reference Type\)

= 변경이 가능한 다양한 타입의 값들을 하나의 단위로 구성한 복합적인 자료 구조이다. \(Data Structure\)

