# 1. 내부 스크립트 외부로 분리하기
## 기본형   
``` Javascript
<srcipt src="JS 파일 경로"></script>
```   

# 2. 자료형
## 2.1 문자형
### 기본형   
``` javascript
var 변수 = "사용할 문자나 숫자";
//ex
var tag = "<h1> String </h1>";
```   

## 2.2 숫자형
### 기본형   
```javascript
var 변수 = 숫자;*** 또는 ***var 변수 = Number("문자형 숫자");
//ex
var t = Number("500") // "500" -> 500
```   

## 2.3 논리형
### 기본형   
```javascript
var 변수 = true or false; 또는 var 변수 = Boolean(데이터);

//ex
var t = 10>=100 //false   
var k = Boolean("hello") //true
```

## 2.4 null & undefined 데이터
* ***undefined*** : 변수에 값이 등록되기 전의 기본값
* ***null*** : 변수에 저장된 값이 null인 경우, 또는 변수에 저장된 데이터를 비우고자 할 때 사용하는 값

## 2.5 type of
### 기본형   
```javascript
typeof 변수 또는 데이터;
```

# 3. 삼항 조건 연산자
## 기본형   
```javascript
조건식 ? 자바스크립트 코드1 : 자바스크립트 코드 2;
```