# 0. 사용된 함수 
0. `prompt()`
1. `alert()`
2. `location.reload()`
3. `location.href`

## 0.1 사용된 태그
1. `<p></p>` 태그는 paragraph, 즉 문단의 약자로, 하나의 문단을 만들 때 씀
2. `<br>` 줄바꿈
3. `<table></table>` 태그는 HTML 문서에서 표를 만드는 태그입니다.   
행과 열을 표현하기 위해 <tr>, <td>등의 태그와 함께 작성하게 됩니다.
예전에는 웹 페이지의 레이아웃을 구성할 때, `<table>` 태그를 이용하여 많이 구성하였는데 적당한 사용 방법이 아니므로 레이아웃 구성시에는 `<div>` 태그와 `CSS`를 이용 해 주세요.

`<tr>` 태그는 표의 **행**을 나타냅니다.   
`<td>` 태그는 표의 **열**을 나타내며, `<tr>` 태그 하위에 위치합니다.   
	
```javascript
<table>
	<tr>
		<td>섹션1</td>
		<td>섹션2</td>
	</tr>
	<tr>
		<td>섹션3</td>
		<td>섹션4</td>
	</tr>
	<tr>
		<td>섹션4</td>
		<td>섹션5</td>
	</tr>
</table>
```

# 1. if문
## 기본형
```javascript
if(조건식) {   
    자바스크립트 코드;   
}   
```   

## 조건식에 입력시 false로 반환되는 예시
1. 0
2. null
3. ""(빈문자)
4. undefined   
   
이외에는 다 true.

# 2. else문
## 기본형
```javascript
if(조건식){
    자바스크립트 코드1;
}else{
    자바스크립트 코드2;
}
```

# 3. confirm
* confirm() 메서드는 '04-3 브라우저 객체 모델'에서 자세히 설명.
* ***확인/취소 창***을 뛰우는 메소드
* 확인 = true, 취소 = false
## 기본형
```javascript
confirm("message");
```

# 4. else if문

# 5. 중첩 if문

# 6. switch문
## 기본형
```javascript
var 변수 = 초기값;
switch(변수) {
    case 값1 : 코드1;
    break;
    case 값2 : 코드2;
    break;

    default: 코드3;
}
```

# 7. while문
## 기본형
```javascript
var 변수 = 초기값;
while(조건문){
    자바스크립트 코드1;
    증감식;
}
```

# 8. do while문
## 기본형
```javascript
var 변수 = 초기값;

do{
    자바스크립트 코드;
    증감식;
}while(조건식)
```

# 9. for문
## 기본형
```javascript
for(초기값; 조건식; 증감식){
    자바스크립트 코드;
}
```

# 10. break문
## 기본형
```javascript
for(초기값; 조건식; 증감식){
    break; //밑에 코드 실행 안하고 강제종료
    자바스크립트 코드;
}
```   

```javascript
var 변수 = 초기값;
while(조건식){
    break; //밑에 코드 실행 안하고 강제종료
    자바스크립트 코드;
    증감식;
}
```

# 11. continue문
## 기본형

```javascript
for(초기값; 조건식; 증감식){
    continue; //다음에 오는 코드는 무시하고 증감식 바로 실행해! 라는 뜻
    자바스크립트 코드;
}
```   
```javascript
var 변수 = 초기값;
while(조건식){
    증감식;
    continue; // 다음에 오는 코드 무시하고 조건식에서 조건 검사 실행해! 라는 뜻
    자바스크립트 코드;
}
```

# 12. 중첩 for문
### 주로 "행", "열"을 가지는 표 만들때 사용.
