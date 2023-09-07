### chapter 2
<h1>2.1.1 const, let</h1>
var 변수 선언은 이제 const, let으로 대체함.<br>

<h3>-스코프란?</h3>
<ul>
  <li>변수에 접근할 수 있는 범위</li>
  <li>함수 실행컨텍스트 내부의 변수 환경</li>
</ul>

<h3>-함수 스코프(var)</h3>
<ul>
  <li>자바스크립트는 기본적으로 함수 스코프를 따르는 언어</li>
  <li>함수에서 선언한 변수들은 해당 함수 내에서만 접근 가능</li>
  <li>새로운 함수가 생성되면 새로운 스코프 발생</li>
</ul>
<h3>-블록스코프(const, let)</h3>
<ul>
  <li>블록{}이 생성될 때마다 새로운 스코프가 형성되는 것</li>
  <li>기존 자바스크립트는 함수 스코프를 따르지만, let,const 등장으로 블록 스코프 형성 가능</li>
</ul>

<h1>2.1.2 템플릿 문자열</h1>
const num3 = 1; <br>
const num4 = 2; <br>
const result2 = 3; <br>
const string2 = `${num3} 더하기 ${num4}는 '${result2}'`;
console.logg(string2); //1 더하기 2는 '3'<br>
기존 따옴표 대신 백틱을 사용하면 깔끔하게 사용가능

<h1>2.1.3 객체 리터럴</h1>
