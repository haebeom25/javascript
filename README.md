> # **변수(Variable)** 
### 선언
```javascript

let

const

```


### 특징
```javascript

let key;

key = value;

//선언 후 값을 넣어줄수 있다.
__________________________________

const key = value;

//선언과 동시에 값을 넣어주어야 한다.

```
<br>
<br/>
<br>
<br/>
<br>
<br/>

> # **자료형(DataType)**
## Number
```javascript
let number = 1
```
## String
```javascript
let string = ''
```
## Boolean
```javascript
let boolean = true
```
<br>
<br/>
<br>
<br/>
<br>
<br/>

> # **형변환(TypeChange)**
## Number()
```javascript
Number('1') // 1

Number('x') // NaN

Number(true) // 1

Number(false) // 0
```
## String()
```javascript
String(1) // '1'

String(true) // 'true'

String(false) // 'false'
```
## Boolean()
```javascript
Boolean( > 0 ) // true
Boolean( 0 ) // false
Boolean('') // false
Boolean('x') // true
```
<br>
<br/>
<br>
<br/>
<br>
<br/>

> # **연산자(Operator)**

## 연산자
```javascript
+  -  *  /
```
## 비교연산자
```javascript
== EQUAL
! NOT

&& AND
|| OR
```
<br>
<br/>
<br>
<br/>
<br>
<br/>

> # **조건문(If,Else)**

## 사용
```javascript
if(Boolean) {
    RUNNING
}
else {
    RUNNING
}
```
<br>
<br/>
<br>
<br/>
<br>
<br/>

> # **반복문(For, While)**
## 사용
```javascript
while(Boolean) {
    RUNNING
}
_________________

do {
    RUNNING
}while()
_________________

for(BEGIN; CONDITION; STEP) {
    RUNNING
}

BEGIN // for문 호출시 실행
CONDITION // Boolean
STEP // 반복될때마다 실행
_________________
```
<br>
<br/>
<br>
<br/>
<br>
<br/>

> # **함수(Function)**
## 선언
```javascript
//일반 함수
function name(value) {
    return value
}

//화살표 함수
let name = (value) => {
    return value
}
```
## 매개변수
```javascript
function name(...values) {
    return
}
values : []
```
<br>
<br/>
<br>
<br/>
<br>
<br/>

> # **배열(Array)**
## 사용
```javascript
let Array = [VALUE]
```
## 호출
```javascript
Array[0] // VALUE
```
## 응용
```javascript
Array.forEach((VALUE,INDEX,ARRAY)=> {
    RUNNING
})
```
<br>
<br/>
<br>
<br/>
<br>
<br/>

> # **객체(Object)**
## 사용
```javascript
let Object = { KEY : VALUE }
```
## 호출
```javascript
Object.KEY // VALUE
Object[KEY] // VALUE
```
<br>
<br/>
<br>
<br/>
<br>
<br/>

> # **메서드(Method)**
## 선언
```javascript
let Object = {
    KEY : function(VALUE) {
        RUNNING
    }
}
```
## 상속
```javascript
let Object = {
    KEY : function(VALUE) {
        RUNNING
    }
}

let Object2 = {   }
Object2.__proto__ = Object

Object2.KEY();

```
## 생성자 함수
```javascript
function name(value) {
    this.key = value
}

new Object(value);

Object {
    key : value
}

```

<br>
<br/>
<br>
<br/>
<br>
<br/>

> # **클래스(Class)**
## 선언
```javascript
class name {
    constructor(value) {
        this.key = value;
    }
}
```
## 호출
```javascript
let object = new name(value);
```
## 내장 함수
```javascript
class name {
    constructor(value) {
        this.key = value;
    }
    FunctionName() {
        RUNNING
    }
}
```
## 상속
```javascript
class name2 extends name {
}
```
