# 웹 프론트 스터디
> 강의를 토대로 배운 내용 정리

## 들을 강의

nomad coders - 바닐라 JS로 크롭 앱 만들기

링크: https://nomadcoders.co/javascript-for-beginners

## 들을 강의 범위

* 07/29(금) ~ 08/05(금)
    * #2.7 ~ #3.8
* 08/05(금) ~ 08/12(금)
    * #4.0 ~ #6.2
* 08/12(금) ~ 08/19(금)
    * #7.0 ~ #8.2

## 정리

#### 07/29(금) ~ 08/05(금)

* #2.13
    * parseInt를 통해 string 타입 자료를 number 타입으로 바꿀 수 있다.
* #2.14
    * isNaN을 통해 자료형이 number 인지 판별할 수 있다.
* #3.1
    * html 태그의 id를 통해 자바스크립트가 html에 접근할 수 있다.
    * `document.getElementById(id);`
* #3.2
    * html 태그에 class, 태그 이름 등을 이용해 querySelector을 통해 접근할 수 있다.
    * 괄호 안에는 id인지 className 인지 tagName 인지를 명시해야 한다.
    * `document.querySelector(#id / .className / h1);`
* #3.3
    * addEventListener를 통해 다양한 이벤트를 추가할 수 있다.
    * `addEventListener("click", event)`
* #3.6
    * js를 통해 css에 접근해 값을 변경할 수 있다.
* #3.7
    * style을 바꾸는 방식이 아닌 해당 태그에 다른 class를 적용하는 방법으로도 css를 변경할 수 있다. 
* #3.8
    * classList의 toggle 메서드를 통해 토큰이 있을 때와 없을 때의 이벤트를 제어할 수 있다.
    
#### 08/05(금) ~ 08/12(금)

* #4.0
    * queryselector를 통해 input 태그와 그 value 값에 접근할 수 있다.
* #4.1
    * click 이벤트 발생 시 입력값에 대한 유효성 검증을 할 수 있다.
    * input 태그에 required 입력 시 해당 항목을 필수 입력 항목으로 정할 수 있다.
* #4.2
    * addEventListener에 들어간 function은 바로 실행되지 않고 브라우저가 그 실행 시기를 결정한다.
    * function의 argument를 채워넣는다면 그 안에 일어난 event에 대한 정보가 들어간다. 해당 정보는 object 형태이다.
* #4.3
    * preventDefault()를 이용해 브라우저의 새로고침을 막을 수 있다.
* #4.4
    * document.querySelector('...').classList.add / remove를 통해 적용된 html class를 추가하거나 없앨 수 있다.
    * document.querySelector('...').innertext를 통해 html안에 텍스트를 넣을 수 있다.
    * `${변수명}`을 통해 변수를 문자열 안에 포함시킬 수 있다. (작은 따옴표가 아닌 백틱기호 사용 필요)
* #4.5
    * localStorage.setItem/getItem/removeItem('', '')를 통해 브라우저의 로컬 스토리지에 값을 저장하거나 불러오거나 삭제할 수 있다.

#### 08/12(금) ~ 08/19(금)

* #5.0
    * setInterval 함수 개념에 대해 알 수 있다.
* #5.1
    * setTimeout 함수 개념에 대해 알 수 있다.
    * Date 객체의 다양한 함수에 대해 알 수 있다. (getDate() / getDay() / getFullYear() / getHours() / getMinutes() / getSeconds() 등) 
* #5.2
    * padStart 함수 개념에 대해 알 수 있다.
    * `padStart(<목표 문자열 길이>, <추가할 문자열>)`
* #6.0
    * Math 객체의 random 함수를 이용해 난수를 생성할 수 있다.
    * Math 객체의 ceil / floor / round 함수에 대해 알 수 있다.
    * length 함수를 이용해 배열의 길이를 알 수 있다.
* #6.1
    * createElement를 통해 javascript로 html 요소를 생성할 수 있다.
    * appendChild를 통해 html 요소를 body 태그 안에 추가할 수 있다.
    * `document.body.appendChild(<요소>)`
