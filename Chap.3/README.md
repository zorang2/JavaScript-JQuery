# 0. 사용된 함수
0. prompt()
1. alert()
2. location.reload()
3. location.href
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
