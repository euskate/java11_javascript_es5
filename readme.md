# 1. 자바스크립트의 정의와 역사

## 1-1. 자바스크립트란?

- 자바스크립트는 웹의 요소나 브라우저를 제어할 목적으로 만들어진 동적 문서를 만드는 웹 프로그래밍 언어입니다.
- HTML은 자동차의 뼈대, CSS는 자동차의 외관, Javascript는 자동차의 엔진으로 비교할 수 있습니다.
- 1995년 12월 4일 넷스케이프에서 근무하던 브랜든 아이크가 개발한 언어로서 현재는 표준 Javascript를 ECMAScript라고 부릅니다.

<br><br>

## 1-2. 자바스크립트의 주요 라이브러리

| 라이브러리 이름 | 설명 |
|---------------|-----------------------------------------------------------------------|
| jQuery | DOM 조작 및 제어를 위해 많이 사용하는 라이브러리 |
| Angular | 구글에서 제작한 프론트엔드용 클라이언트 사이드 JavaScript 프레임워크 |
| React | Facebook에서 만든 프론트엔드용 오픈소스 라이브러리 |
| Vue.js | 중국계 미국인 에반 유가 만든 사용자 인터페이스를 만들기 위한 프론트엔드용 프레임워크 |
| Node.js | 자바스크립트 기반의 서버 프로그래밍을 위한 런타임 환경 |
| Express.js | Node.js 환경을 기반으로 만들어진 웹 애플리케이션 프레임워크 |
| Deno | Node.js의 단점을 보완한 서버 프로그래밍을 위한 런타임 환경 |
| Svelte | Rich Harris가 2016년도 출시한 오픈소스 프론트엔드 웹 프레임워크 |
| Electron | GitHub에서 만든 HTML+CSS+Javascript 데스크톱 앱 프레임워크 |
| npm | Node.js 설치시 같이 설치디는 노드 패키지 매니저(Node Package Manager) |

<br><br>

### 1-3. 자바스크립트의 파생 언어

| 언어이름 | 설명 |
|---------------|-----------------------------------------------------------------------|
| TypeScript | 마이크로소프트에서 발표한 JavaScript에 정적 타입 개념을 추가한 신형 언어로 컴파일을 진행하면 Javascript가 만들어집니다. |
| CoffeeScript | JavaScript의 문법을 개선한 신형 언어 |
| AssemblyScript | TypeScript에서 WebAssembly로의 컴파일을 목적으로 또 다시 파생되어 나온 언어 |
| JavaScript.NET | JavaScript를 컴파일러용 언어로 개조한 언어 |
| ReasonML | 전직 페이스북 개발자가 만든 정적타입, 함수형 프로그래밍 기반 언어 |
| Vanilla JS | 외부의 라이브러리나 프레임워크를 이용하지 않는 순수 자바스크립트 |

### 1-4. 자바스크립트의 역사

- 자바스크립트는 1995년 넷스케이프에서 일하고 있던 브랜든 아이크에 의해 만들어졌습니다.
- 최초의 자바스크립트는 Mocha라는 이름으로 발표가 되었다가 이 후 LiveScript라는 이름을 거쳐 최종적으로 Javascript라는 이름을 갖게 되었습니다.
- Java와는 아무 연관이 없지만, 당시 Java의 유명세에 묻어가려는 마케팅적 이유로 이름이 붙여졌습니다.

| 버전 | 출시일 | 동등한 기술적 내용 | 넷스케이프 내비게이터 | 모질라 | 파이어폭스 | 인터넷 익스플로러 | 오페라 | 사파리 | 구글 크롬 |
|-----|----------|------------------------------------|---------|----------|----------|----------|----------|----------|----------|
| 1.0 | 1996년 3월 |  | 2.0 |  | 3.0 |  |  |  |			
| 1.1 | 1996년 8월 |  | 3.0 |  |  |  |  |  |			
| 1.2 | 1997년 6월 |  | 4.0-4.05 |  |  | 3 |  |  |		
| 1.3 | 1998년 10월 | ECMA-262 1st + 2nd edition | 4.06-4.7x |  | 4.0 | 5 |  |  |	
| 1.4 |  |  | 넷스케이프 서버 |  |  | 6 |  |  |
| 1.5 | 2000년 11월 | ECMA-262 3rd edition | 6.0 | 1.0 | 5.5 (JScript 5.5),<br>6 (JScript 5.6),<br>7 (JScript 5.7),<br>8 (JScript 5.8) | 7.0	 | 3.0-5 | 1.0-10.0.666 |
| 1.6 | 2005년 11월 | 1.5 + array extras + array and string generics + E4X |  | 1.5 |  |  |  |  |
| 1.7 | 2006년 10월 | 1.6 + Pythonic generators Archived 2013년 3월 2일 - 웨이백 머신 + iterators + let |  | 2.0 |  |  |  | 28.0.1500.95 |
| 1.8 | 2008년 6월 | 1.7 + generator expressions + expression closures |  | 3.0 |  | 11.50 |  |  |		
| 1.8.1 |  | 1.8 + native JSON support + minor updates |  | 3.5	|  |  |  |  |	
| 1.8.2 | 2009년 6월 22일 | 1.8.1 + minor updates |  | 3.6 |  |  |  |  |					
| 1.8.5 | 2010년 7월 27일 | 1.8.2 + new features for ECMA-262 5th edition compliance |  | 4.0 |  |  |  |  |

### 1-5. EcmaScript로의 전환

- 자바스크립트를 표준화하기 위해 1996년 11월 ECMA-262라는 표준안의 이름이 발표되면서 표준 자바스크립트를 ECMA Script라고 부르게 되었습니다. 약자로 ES라고도 합니다.

| 버전 | 발표시기 | 특징 |
|------|-----------|----------------------------------------------------------|
| ES1 | 1997년 6월 | ECMA-262 기술 규격 |
| ES2 | 1998년 6월 | ActiveX 탑재<br> xml request 기능 제공 |
| ES3 | 1999년 12월 | try/catch<br> Prototype<br> Hoisting<br> Scope<br> Closer|
| ES4 | 폐기(Abandoned) | |
| ES5 | 2009년 12월 | forEach, map, filter<br> reduce, some, every<br> Object에 대한 getter / setter 지원<br> 자바스크립트 strict 모드 지원<br> JSON 지원<br> bind() 메서드 지원 |
| ES6/ES2015 | 2015년 6월 | const and let<br> for…of<br> Spread Operator<br> iterator/generator<br> Promise<br> Default Parameter<br> Module import/export<br> class<br> template tag<br> Arrow function<br> Variable Parameter
| ES7/ES2016 | 2016년 6월 | Array.protorype.includes<br> Exponentiation oprator |
| ES8/ES2017 | 2017년 06월 | String padding<br> Object.values<br> Object.getOwnPropertyDescriptors<br> Trailing commas in function parameter lists and calls<br> Async functions |
| ES9/ES2018 | 2018년 06월 | Object Rest/Spread<br> Promise finally<br> Async iteration<br> 정규표현식 |
| ES10/ES2019 | 2019년 06월 | Object from Entries<br> flat, flatMap<br> Symbol, Description<br> Optional Catch | 
| ES11/ES2020 | 2020년 06월 | String.prototype.matchAll<br> BigInt<br> Promise.allSettled<br> globalThis<br> optional chaining operator<br> nullish coalescing operator
| ES12/ES2021 | 2021년 06월 | String.prototype.replaceAll<br> Promise.any<br> AggregateError<br> WeakReferences <br> Logical Assignment Operators | 
| ES13/ES2022 | 2022년 07월 | top-level await<br> Class field 개선<br> .at() method on the built-in indexables<br> Object.hasOwn<br> RegExp flag <br> Error.prototype.cause |
| ES14/ES2023 | 2023년 06월 | Array.prototype.findLast<br> Array.prototype.findLastIndex<br> Hashbang Grammar |


<br><hr><br>

# 2. 자바스크립트의 사용자 정의 변수/함수/배열/객체

- 변수(Variable) : 데이터를 저장할 저장소의 이름으로 변수라고 하는 것은 언제든지 그 값이 유동적으로 변할 수 있기 때문입니다.
- 함수(Function) : 복잡하거나 반복적으로 구현해야할 코드를 하나의 이름으로 정의하고, 호출하여 사용할 수 있도록 기능을 구현하는 코드 블록을 말합니다.
- 배열(Array) : 하나의 데이터만 저장하는 것이 아니라, 여러 데이터를 하나의 이름으로 연속하여 저장하는 자료 구조를 말합니다.
- 객체(Object) : 필요에 따라 여러 속성(Properties, 이름(name)과 값(value)로 구성)와 기능 구현 코드에 해당하는 메소드(Method)를 구성원으로 하는 집합체를 말합니다.

## 2-1. 변수에 대한 기본 문법

```javascript
var 변수명; //변수 선언
var 변수명 = 초기값;    //변수 선언과 초기값 부여
/* 자바스크립트는 다른 언어와 다르게 같은 이름의 변수를 var 선언자로 재선언하여 사용할 수 있습니다. */
```

<br><br>

## 2-2. 함수에 대한 기본 문법

```html
<script>
//함수의 정의 및 선언 방법1
function 함수명1() { ... }
//함수의 정의 및 선언 방법2
var 함수명2 = function() { ... };
</script>
<!-- 함수의 호출1 : 인라인 이벤트 -->
<button type="button" id="btn1" onclick="함수명1()">버튼1</button>
<button type="button" id="btn2">버튼2</button>
<script>
//함수의 호출2 : 이벤트리스너에 의한 이벤트    
document.getElementById("btn2").addEventListener("click", function() { 함수명2(); });    
</script>
```

<br><br>

## 2-3. 배열에 대한 기본 문법

```javascript
//배열 선언 및 초기화 방법1
var 배열명 = [값1, "값2",..... ];
//배열 선언 및 초기화 방법2
var 배열명 = new Array();
var 배열명 = new Array(숫자);
var 배열명 = new Array(값1, 값2,..값n);
```

<br><br>

## 2-4. 객체에 대한 기본 문법

```javascript
var 객체명 = {
    속성1:값1, 
    속성2:값2,....
    속성n:값n, 
    메소드1:function() {....},
    메소드2:function() {....},
     ...
    메소드n:function() {....} 
};
```

<br><br>

## 2-5. 변수/함수/배열/객체 사용의 예시 코드

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>자바스크립트 01</title>
    <!-- head 태그 사이에 있는 script는 body 요소가 로딩 되기 전에 
        해야 할 일을 기술합니다.  -->
    <script>
    /* 스크립트내의 각주 */

    </script>
</head>
<body>
    <h1>자바스크립트(Javascript)란?</h1>
    <p>자바스크립트는 웹의 요소나 브라우저를 제어할 목적으로 만들어진
        동적 문서를 만드는 웹 프로그래밍 언어입니다.</p>
    <hr>    
    <h2>자바스크립트의 레벨</h2>
    <p>자바스크립트의 정식 명칭은 EcmaScript라고 하며, 
        ES5(2009년 이전)와 ES6(2015년 이후)로 명확한 구분점을 가지고 있으며, 
        ES5 이하는 웹의 요소나 브라우저를 제어할 목적을 갖고 있으며,
        ES6 이상은 ES5 이하의 기능을 포함하며, 객체 지향적 프로그래밍 기법과 
        프론트엔트 프레임워크나 Node를 기반으로 VIEW단의 서버 프로그래밍을 
        할 수 있는 기능이 더 추가되었습니다.</p>
    <!-- body 요소와 그 하부 요소인 h1, p, h2, hr 등이 출력되고 난 후 
    실행해야 하는 내용을 기술하는 부분 --> 
    <hr>
    <h2>자바스크립트의 기본 - 각주, 변수, 함수, 배열, 객체</h2>
    <div id="msg"></div>   
    <hr>
    <button type="button" onclick="fnc1()">인라인 이벤트 버튼</button><br>
    <button type="button" id="btn2">이벤트리스너 이벤트 버튼</button><br>
    <button type="button" id="btn3">메소드 이벤트 버튼</button><br>
    <script>
    //변수의 정의 및 선언
    var data;
    var name_str = "김기태"; //문자열 변수 name_str
    var ageNum = 43;   //정수형 변수 ageNum 
    var heightNum = 173.52; //실수형 변수 heightNum
    var pass = false;   //논리형 변수 pass
    var a=20, b=30;

    var msg = document.getElementById("msg");   //DOM 요소 선택 
    
    //이벤트리스너에 의한 함수 호출
    document.getElementById("btn2").addEventListener("click", 
    function() { fnc2(); });

    //함수의 정의 
    function fnc1() {
        if(!confirm("함수1을 호출하셨습니다.\n확인 또는 취소를 눌러주세요")){
            msg.innerHTML = "<strong>취소를 누르셨습니다.</strong>";
        } else {
            msg.innerHTML = "<em>확인을 누르셨습니다.</em>";
        }
    }
    var fnc2 = function() { alert("함수2을 호출하셨습니다."); }
    
    var arr = ["김기태","김응원","김필규","김민아"];

    var obj = {name:"김민식", age:48, height:182.78, 
    method1:function () {   //메소드
        var wt = prompt("몸무게를 입력해주세요");
        msg.innerText = this.name + "님의 몸무게는 " + wt + "kg 입니다."
    }};

    document.getElementById("btn3").addEventListener("click", 
     function() { obj.method1(); } );
    </script>
</body>
</html>
```

<br><hr><br>

# 3. 자바스크립트의 출력과 메시지 창

## 3-1. 문서에 출력

```javascript
document.write("태그를 포함한 출력내용");
```

<br><br>

## 3-2. 요소에 출력

```javascript
document.getElementById("해당요소아이디").innerHTML = "태그를 포함한 출력내용";
document.getElementById("해당요소아이디").innerText = "출력내용";
```

<br><br>

## 3-3. 콘솔에 출력

```javascript
console.log("출력할 내용");
```

<br><br>

## 3-4. 알림창에 출력

```javascript
alert("출력제어문자를포함한메시지");
```

<br><br>

## 3-5. 확인창에 출력

```javascript
confirm("출력제어문자를포함한메시지");
```

<br><br>

## 3-6. 입력창에 입력과 출력

```javascript
변수명 = prompt("출력제어문자를포함한메시지");
```

## 3-7. 출력의 방향 예시 코드

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>자바스크립트 02</title>
    <style>
    * { margin: 0; padding: 0; }
    body { width:100%; overflow-x:hidden; }
    a { text-decoration: none; }
    .title { text-align: center; padding-top: 2rem; 
        padding-bottom: 0.8rem; }
    .btn-group, .activity, .rule { clear:both; width: 1280px; 
        margin: 20px auto; }    
    .btn-group:after, .activity:after, .rule:after { content:""; 
    display:block; width: 100%; clear: both; }
    .rule { padding-bottom: 24px; border-bottom:2px solid #333; }

    .btn-group button, .btn-group a { display:inline-block; 
        min-width:140px; height: 40px; line-height: 40px; text-align: center; 
    outline: none; border:3px solid #333; color:#333; font-size:18px; 
    margin:8px; border-radius:22px; box-sizing: border-box; cursor:pointer; }
    .btn-group button:hover, .btn-group a:hover { background-color: deepskyblue;
    color:#fff; }

    .activity { min-height:200px; margin-bottom:100px; }
    </style>
</head>
<body>
    <h1 class="title">자바스크립트의 출력 방향과 메시지창</h1>
    <hr>
    <div class="rule">
        <h2 class="title">스크립트의 적용 방식</h2>
        <ul>
            <li>인라인 스크립트 : 해당 태그에 직접 스크립트를 기입하는 방식</li>
            <li>내부 스크립트 : 해당 문서에 script 태그를 기입하여 스크립팅하는 방식</li>
            <li>외부 스크립트 : 별도의 .js 파일을 작성하여 여러 문서에서 script 태그로 삽입하는 방식</li>
        </ul>
    </div>
    <div class="rule">
        <h2 class="title">스크립트의 출력 방향</h2>
        <ul>
            <li>문서에 출력 : document.write()</li>
            <li>요소에 출력 : document.getElementById().innerHTML </li>
            <li>콘솔에 출력 : console.log()</li>
        </ul>
    </div>
    <div class="rule">
        <h2 class="title">메시지창</h2>
        <ul>
            <li>알림창 : alert("메시지")</li>
            <li>확인창 : confirm("메시지") </li>
            <li>입력창 : prompt("메시지")</li>
        </ul>
    </div>
    <div class="btn-group">
        <button id="btn1" type="button" onclick="fnc1()">문서에 출력</button>
        <button id="btn2" type="button" onclick="fnc2()">요소에 출력</button>
        <button id="btn3" type="button" onclick="fnc3()">콘솔에 출력</button>
        <button id="btn4" type="button" onclick="fnc4()">알림창 출력</button>
        <button id="btn5" type="button" onclick="fnc5()">확인창 출력</button>
        <button id="btn6" type="button" onclick="fnc6()">입력창 출력</button>
        <a href="javascript:;" id="btn7" onclick="fnc7()">링크버튼1</a>
        <a href="javascript:none;" id="btn8" onclick="fnc8()">링크버튼2</a>
    </div>
    <div class="activity">
        <div id="res1"></div>
        <div id="res2"></div>
        <div id="res3"></div>
    </div>
    <script>
    var fnc1 = function() { document.write("<h2>문서에 출력</h2>"); };    
    var fnc2 = function() { 
        document.getElementById("res1").innerHTML = "<h2>요소에 출력</h2>" };    
    var fnc3 = function() { console.log("콘솔에 출력"); };
    var fnc4 = function() { alert("알림창\n출력"); };
    var fnc5 = function() { 
        var res2 = document.getElementById("res2");
        if(confirm("확인창\n확인")){
            res2.innerHTML = "<em>확인 OK~!</em>";
        } else {
            res2.innerHTML = "<ins>취소 NOH~!</ins>";
        }    
    };
    var fnc6 = function(){
        var name = prompt("이름 입력 : ");
        var age = parseInt(prompt("나이 입력 : "));
        var iq = parseFloat(prompt("아이큐 입력 : "));
        var res3 = document.getElementById("res3");
        res3.style.color = "red";
        var tag = "<ul>";
        tag = tag + "<li>이름 : "+name+"</li>";     
        tag = tag + "<li>나이 : "+age+"</li>";
        tag = tag + "<li>아이큐 : "+iq+"</li>";
        tag = tag + "</ul>";
        res3.innerHTML = tag; 
    }
    var fnc7 = function() { 
        alert("인라인 이벤트인 링크버튼을 누르셨습니다."); };
    var fnc8 = function() { window.open("javascript01.html"); }
    </script>
</body>
</html>
```

<br><hr><br>

# 4. 자바스크립트의 연산자

- 자바스크립트의 연산자에는 산술 연산자, 대입 연산자, 비교 연산자, 증감 연산자, 논리 연산자, 비트 연산자, 삼항 연산자, 타입 연산자 등이 있습니다.

| 종류 | 연산자 | 연산자 설명 |
|---------------|--------------|---------------------------------------------------------------|
| 산술 연산자 | + | 더하기 |
|  | - | 빼기 |
|  | * | 곱하기 |
|  | / | 나누기 |
|  | % | 나머지 |
|  | ** | 거듭제곱 |
| 대입 연산자 | = | 오른쪽의 값을 왼쪽에 대입 |
|  | += | 왼쪽의 값을 오른쪽의 값과 더하기하여 왼쪽에 대입 |
|  | -= | 왼쪽의 값을 오른쪽의 값으로 빼기하여 왼쪽에 대입 |
|  | *= | 왼쪽의 값을 오른쪽의 값과 곱하기하여 왼쪽에 대입 |
|  | /= | 왼쪽의 값을 오른쪽의 값으로 나누기하여 왼쪽에 대입 |
|  | %= | 왼쪽의 값을 오른쪽의 값으로 나눈 나머지를 왼쪽에 대입 |
| 증감 연산자 | ++ | 1씩 증가, "++변수" 는 전위연산, "변수++" 는 후위연산 |
|  | -- | 1씩 감소, "--변수" 는 전위연산, "변수--" 는 후위연산 |
| 비교 연산자 | == | 같다 |
|  | != | 같지 않다 |
|  | === | 값과 타입이 모두 같다. |
|  | !== | 값 또는 타입이 같지 않다. |
|  | > | 초과(크다/후) |
|  | < | 미만(작다/전) |
|  | >= | 이상(크거나 같다/이후) |
|  | <= | 이하(크거나 같다/이전) |
| 논리 연산자 | && | AND연산, 주어진 조건이 모두 만족하면, 참, 그렇지 않으면, 거짓 |
|  | &#124;&#124; | OR연산, 주어진 조건이 어느 하나라도 만족하면, 참, 그렇지 않으면, 거짓 |
|  | ! | Not 연산, (반대로)참을 거짓으로, 거짓을 참으로 반환 |
| 비트 연산자 | & | 이진 AND연산, 2진수로 바꾸어 각 자리마다 모든 입력이 1이면, 1을 출력, 아니면, 0을 출력 |
|  | &#124; | 이진 OR연산, 2진수로 바꾸어 각 자리마다 어느 하나라도 입력이 1이면, 1을 출력, 아니면, 0을 출력 |
|  | ~ | 이진 Not연산=보수(Complement), 입력이 1이면, 0을 출력, 입력이 0이면, 1을 출력 => 반대로 |
|  | ^ | 이진 XOR연산, 2진수로 바꾸어 각 자리마다 입력이 서로 다르면, 1을 출력, 같으면, 0을 출력 |
| 삼항 연산자 | 조건 ? 참 : 거짓 | 조건이 만족하면, 참을 그렇지 않으면, 거짓을 반환 |
| 타입 연산자 | typeof 값 &#124; 변수 | 해당 값 또는 변수에 대한 타입을 반환 |

<br>

## 연산자 우선 순위

| 우선순위 | 기능 | 연산자 |
|-----|-------------------------------|-------------------------------------------------|
| 1 | 괄호 | () |
| 2 | 증감/논리 연산자 | ++ -- ! |
| 3 | 산술 연산자 | * / % + - |
| 4 | 비교 연산자 | > >= < <= == === != !=== |
| 5 | 논리 연산자 | and(&&) or(&#124;&#124;) not(!)|
| 6 | 대입 연산자 | *= /= %= += -= |



<br><br>

## 4-1. 산술 연산자

```javascript
    var name1 = "김기태";   //문자열 초기화 -> string
    var su1 = 20;       //숫자 초기화 -> int
    var comp1 = true;   //논리값 초기화 -> bool
    var fl1 = 3.14; //실수 초기화 -> float

    var name2 = "유정환";
    var su2 = 12;
    var comp2 = false;
    var fl2 = 36.5;

    console.log("더하기");
    console.log(name1+name2);
    console.log(su1+su2);
    console.log(comp1+comp2);
    console.log(fl1+fl2);
    console.log("빼기");
    console.log(name1-name2);
    console.log(su1-su2);
    console.log(comp1-comp2);
    console.log(fl1-fl2);
    console.log("곱하기");
    console.log(name1*name2);
    console.log(su1*su2);
    console.log(comp1*comp2);
    console.log(fl1*fl2);
    console.log("나누기");
    console.log(name1/name2);
    console.log(su1/su2);
    console.log(comp1/comp2);
    console.log(fl1/fl2);
    console.log("나머지");
    console.log(su1%su2);
```

<br><br>

## 4-2. 대입 연산자

```javascript
    var x=200, y=300, z=100;
    document.write("<h2>대입 연산자</h2>");    x+=3;
    document.write("<br>x+=3 결과 : "+x);    x-=4;
    document.write("<br>x-=4 결과 : "+x);    x*=2;
    document.write("<br>x*=2 결과 : "+x);    x/=3;
    document.write("<br>x/=3 결과 : "+x);    x%=29;
    document.write("<br>x%=29 결과 : "+x);
```

<br><br>

## 4-3. 증감 연산자

```javascript
    var x=200, y=200;
    document.write("<hr><h2>증감 연산자</h2>");
    document.write("<br>x++ 결과 : "+(x++));
    document.write("<br>++y 결과 : "+(++y));
    document.write("<br>x-- 결과 : "+(x--));
    document.write("<br>--y 결과 : "+(--y));
```

<br><br>

## 4-4. 비교 연산자

```javascript
    var x=200, y=300;
    document.write("<hr><h2>비교연산</h2>"); 
    document.write("<br> x>y : "+(x>y));
    document.write("<br> x<y : "+(x<y));
    document.write("<br> x>=y : "+(x>=y));
    document.write("<br> x<=y : "+(x<=y));
    document.write("<br> x==y : "+(x==y));
    document.write("<br> x!=y : "+(x!=y));
    document.write("<br> x===y : "+(x===y));  //타입과 값이 모두 일치
    document.write("<br> x!==y : "+(x!==y));  //타입 또는 값이 다르면
```

<br><br>

## 4-5. 논리 연산자

```javascript
    var x=200, y=300;
    document.write("<br> x>y && y==200 : "+(x>y && y==200));
    document.write("<br> x>y || y==200 : "+(x<y || y==200));
    document.write("<br> !(x<y) : "+(!(x<y)));
```

<br><br>

## 4-6. 비트 연산자

```javascript
    var x=200, y=300;
    document.write("<hr><h2>비트연산</h2>");
    document.write("<br> x & y : "+(x & y));   //and
    document.write("<br> x | y : "+(x | y));  //or
    document.write("<br> x ^ y : "+(x ^ y));  //xor
    document.write("<br> y >> 2 : "+(y >> 2)); //오른쪽 shift => /2
    document.write("<br> y << 2 : "+(y << 2)); //왼쪽 shift => *2
    document.write("<br> ~y : "+(~y)); //complement(보수)
```

<br><br>

## 4-7. 삼항 연산자

```javascript
    var x=200, y=300;
    var a = (x>y) ? x : y;  
    document.write("<hr><h2>삼항 연산자</h2> -> (x>y) ? x : y => "+a+"<br><br>");   
```

<br><br>

## 4-8. 타입 연산자

```js
    var x=200, y=300;
    var a = typeof "김기태";
    document.write(a + "<br>");

    var a = typeof 1004;
    document.write(a + "<br>");

    var a = typeof 6.28;
    document.write(a + "<br>");
    document.write((typeof x) + "<br>");
```

<br><hr><br>

## 자바스크립트의 변수가 가지는 불용값

```comment
null과 undefined
자바스크립트에서 null이란 object 타입이며, 아직 '값'이 정해지지 않은 것을 의미합니다.

또한, undefined란 null과는 달리 '타입'이 정해지지 않은 것을 의미합니다.

따라서 자바스크립트에서 undefined는 초기화되지 않은 변수나 존재하지 않는 값에 접근할 때 반환됩니다.
```


<br><hr><br>

# 5. 자바스크립트의 객체

- 자바스크립트의 기본 타입은 객체(object)입니다. 객체(object)란 실생활에서 우리가 인식할 수 있는 사물로 이해할 수 있습니다.
- 객체는 여러 프로퍼티(property)나 메소드(method)를 같은 이름으로 묶어놓은 일종의 집합체입니다.
- 자바스크립트는 내장 객체(BOM, DOM, 데이터), 사용자 정의 객체로 구분합니다.

## 5-1. 사용자 정의 객체

### 5-1-1. 사용자 정의 객체 기본 문법

```javascript
var 객체명 = {속성1:값1, 속성2:값2,...속성n:값n,...메소드1:function(){....}};
```

<br>

### 5-1-2. 사용자 정의 객체 예시 코드

```javascript
    //재활용이 불가능한 사용자 정의 더미 객체
    var man1 = {name:"김기태", style:"미남", point:100};
    man1.nick = "김미남";   //항목 추가
    man1.style = "신사";    //항목의 값 변경
```

<br><br>

## 5-2. 생성자를 활용한 객체 생성

### 5-2-1. 생성자를 활용한 객체 기본 문법

```javascript
    //생성자 함수 정의
    function 생성자함수명(매개변수1, 매개변수2,... 매개변수n){
        this.필드1 = 매개변수1;
        this.필드2 = 매개변수2;
        .....
        this.필드n = 매개변수n;
        this.메소드 = function () {
            .....
        }
    }
    //객체 생성
    var 객체명 = new 생성자함수(값1, 값2,...값n);
```

<br>

### 5-2-2. 생성자를 활용한 객체 생성 예시 코드

```javascript
    //생성자(Constructor)를 활용한 객체 생성
    function People(no, name, age, style, target){
        this.no = no;
        this.name = name;
        this.age = age;
        this.style = style;
        this.print = function () {
            var res = document.getElementById(target);
            res.innerHTML = "<ul>";
            res.innerHTML = res.innerHTML + "<li>번호 : "+this.no+"</li>";    
            res.innerHTML = res.innerHTML + "<li>이름 : "+this.name+"</li>";    
            res.innerHTML = res.innerHTML + "<li>나이 : "+this.age+"</li>";    
            res.innerHTML = res.innerHTML + "<li>스타일 : "+this.style+"</li>";    
            res.innerHTML = res.innerHTML + "</ul>";
        }
    }

    var st1 = new People(1, "이종우", 22, "잘생김주의", "res1");
    var st2 = new People(2, "이종욱", 23, "못생김주의", "res2");
    var st3 = new People(3, "이종원", 24, "느낌함", "res3");
    var st4 = new People(4, "이종훈", 25, "노래잘함", "res4");

    st1.print();
    st2.print();
    st3.print();
    st4.print();

    //항목(Field) 추가
    st1.family = "전주이씨";
    st2.family = "경주이씨";

    
    //메소드(Method) 추가
    var html= "";
    st1.toString = function() {
        var res5 = document.getElementById("res5");
        html = "<p>";
        html = html + "<strong>본관 : "+this.family+"</strong>";    
        html = html + "<em>이름 : "+this.name+"</em>";
        html = html + "<em>나이 : "+this.age+"</em>";
        html = html + "</p>";  
        res5.innerHTML = html;  
    }
    st1.toString();

    //항목 제거 전 순회
    html = "";
    for(var field in st1){
        html += "<strong>"+field+"</strong> &nbsp; &nbsp; &nbsp;";
    }
    document.getElementById("res6").innerHTML = html;

    //항목(Field) 제거
    delete st1.family;

    //항목 제거 후 순회
    html = "";
    for(var field in st1){
        html += "<em>"+field+"</em> &nbsp; &nbsp; &nbsp;";
    }
    document.getElementById("res7").innerHTML = html;
```
<br><hr><br>

# 6. 사용자 정의 함수

## 6-1. 사용자 정의 함수 기본 문법

```javascript
//함수타입1 정의 : 매개변수X/반환X
function 함수1() { .... }

//함수타입2 정의 : 매개변수X/반환O
function 함수2() { 
    ....
    return 반환값 | 변수;
}

//함수타입3 정의 : 매개변수O/반환X
function 함수3(매개변수1, 매개변수2,...매개변수n) { .... }

//함수타입4 정의 : 매개변수O/반환O
function 함수4(매개변수1, 매개변수2,...매개변수n) { 
    .... 
    return 반환값 | 변수;
}

함수1(); //함수타입1 호출
var 반환을받는변수 = 함수2();   //함수타입2 호출
함수3(전달값);    //함수타입3 호출
var 반환을받는변수 = 함수4(전달값);   //함수타입4 호출
```

<br><br>

## 6-2. 사용자 정의 함수 예시 코드

```javascript
    //방법1 : function 함수명(매개변수명,...) { [return 값또는변수] }    
    //방법2 : var 함수명 = function(매개변수명,...) { [return 값또는변수] }
    function fnc1(){
        document.write("<br>fnc1 : 매개변수X, 리턴X<br>");
    }
    function fnc2(x){
        document.write(x+"<br>fnc2 : 매개변수O, 리턴X<br>");
    }
    function fnc3(){
        return "<br>fnc3 : 매개변수X, 리턴O<br>";
    }
    function fnc4(x){
        return x+"<br>fnc4 : 매개변수O, 리턴O<br>";
    }
    var res4 = fnc4("김기태");
    var res3 = fnc3();
    document.write(res4);
    document.write(res3);
    fnc2("김이태");
    fnc1();
```

<br><hr><br>

# 7. 조건문과 반복문

- 프로그램의 순차적인 흐름을 제어해야 할 때 사용하는 실행문을 제어문이라고 합니다. 이러한 제어문에는 조건문, 반복문, 기타 제어문 등이 포함됩니다.

<br><br>

## 7-1. 조건문

- 조건문이란 프로그램 내에서 주어진 표현식의 결과에 따라 별도의 명령을 수행하도록 제어하는 실행문입니다.
- 조건문 중에서 가장 기본이 되는 실행문은 if 문입니다.
- 자바스크립트에서 사용할 수 있는 조건문의 형태는 다음과 같습니다.
    1. if 문
    2. if / else 문
    3. if / else if / else 문
    4. switch 문

<br>

### 7-1-1. if문

- if 문은 표현식의 결과가 참(true)이면 주어진 실행문을 실행하며, 거짓(false)이면 아무것도 실행하지 않습니다.

#### if문 기본 문법

```javascript
    if (조건식) {
        조건식의 결과가 참일 때 실행하고자 하는 실행문;
    }
```

#### if문 예시 코드

```javascript
    var x = 10, y = 20;
    if (x == y) {  //동등 연산자는 "="이 아니라 "=="이다.
        document.write("x와 y는 같습니다.");
    }
    if (x < y) {
        document.write("x가 y보다 작습니다.");
    }

    if (x > y) // 실행될 실행문이 한 줄뿐이라면 중괄호({})를 생략할 수 있음.
        document.write("x가 y보다 큽니다.");
```

<br>

### 7-1-2. if~ else~ 문

- if 문과 같이 사용할 수 있는 else 문은 if 문의 표현식 결과가 거짓(false)일 때 주어진 실행문을 실행합니다.

#### if~ else~ 문 기본 문법

```javascript
    if (조건식) {
        조건식의 결과가 참일 때 실행하고자 하는 실행문;
    } else {
        조건식의 결과가 거짓일 때 실행하고자 하는 실행문;
    }
```

<br>

### 7-1-3. if~ else if~ else~ 문

- else if 문은 if 문처럼 표현식을 설정할 수 있으므로, 중첩된 if 문을 좀 더 간결하게 표현할 수 있습니다. 하나의 조건문 안에서 if 문과 else 문은 단 한 번만 사용될 수 있습니다. 하지만 else if 문은 여러 번 사용되어 다양한 조건을 설정할 수 있습니다.

#### if~ else if~ else~ 문 기본 문법

```javascript
    if (조건식1) {
        조건식1의 결과가 참일 때 실행하고자 하는 실행문;
    } else if (조건식2) {
        조건식2의 결과가 참일 때 실행하고자 하는 실행문;
    } else {
        조건식1의 결과도 거짓이고, 조건식2의 결과도 거짓일 때 실행하고자 하는 실행문;
    }
```

#### if~ else if~ else~ 문 예시 코드

```javascript
    var x = 10, y = 20;
    if (x == y) {
        document.write("x와 y는 같습니다.");
    } else if (x < y) {
        document.write("x가 y보다 작습니다.");
    } else { // x > y인 경우
        document.write("x가 y보다 큽니다.");
    }
```

<br>

### 7-1-4. switch 문

- switch 문은 if / else 문과 마찬가지로 주어진 조건 값에 따라 프로그램이 다른 명령을 수행하도록 하는 조건문입니다. 이러한 switch 문은 if / else 문보다 가독성 측면에서 더 좋습니다.

#### switch 문 기본 문법

```javascript
    switch (조건 값) {
        case 값1:
            조건 값이 값1일 때 실행하고자 하는 실행문;
            break;
        case 값2:
            조건 값이 값2일 때 실행하고자 하는 실행문;
            break;
        ...
        default:
            조건 값이 어떠한 case 절에도 해당하지 않을 때 실행하고자 하는 실행문;
            break;
    }
```

#### switch 문 예시 코드

```javascript
    var x = 10;
    switch (typeof x) {
        case "number":
            document.write("변수 x의 타입은 숫자입니다.");
            break;
        case "string":
            document.write("변수 x의 타입은 문자열입니다.");
            break;
        case "object":
            document.write("변수 x의 타입은 객체입니다.");
            break;
        default:
            document.write("변수 x의 타입을 잘 모르겠네요...");
            break;
    }
```

```javascript
    var day = new Date().getDay(); // 오늘의 요일을 반환함. (일요일: 0 ~ 토요일: 6)
    switch (day) {
        case 1: // 월요일인 경우
        case 2: // 화요일인 경우
        case 3: // 수요일인 경우
        case 4: // 목요일인 경우
        default: // 0부터 6까지의 값이 아닌 경우
            document.write("아직도 주말은 멀었네요... 힘내자구요!!");
            break;
        case 5: // 금요일인 경우
            document.write("오늘은 불금이네요!!");
            break;
        case 6: // 토요일인 경우
        case 0: // 일요일인 경우
            document.write("즐거운 주말에도 열심히 공부하는 당신~ 최고에요!!");
            break;
    }
```

<br><br>

## 7-2. 반복문

- 반복문이란 프로그램 내에서 똑같은 명령을 일정 횟수만큼 반복하여 수행하도록 제어하는 실행문입니다. 
- 프로그램이 처리하는 대부분의 코드는 반복적인 형태가 많으므로, 가장 많이 사용되는 실행문 중 하나입니다.
- 자바스크립트에서 사용할 수 있는 반복문의 형태는 다음과 같습니다.
    1. while 문
    2. do / while 문
    3. for 문
    4. for / in 문
    5. for / of 문

<br>

### 7-2-1. while 문

- while 문은 특정 조건을 만족할 때까지 계속해서 주어진 실행문을 반복 실행합니다.

#### while 문 기본 문법

```javascript
    while (조건식) {
        조건식의 결과가 참인 동안 반복적으로 실행하고자 하는 실행문;
    }
```

while 문은 우선 표현식이 참(true)인지를 판단하여 참이면 내부의 실행문을 실행합니다. 내부의 실행문을 전부 실행하고 나면, 다시 표현식으로 돌아와 또 한 번 표현식이 참인지를 판단하게 됩니다. 이렇게 표현식의 검사를 통해 반복해서 실행되는 반복문을 루프(loop)라고 합니다.

#### while 문 예시 코드

```javascript
    var i = 1;
    while (i < 10) { // 변수 i가 10보다 작을 때만 while 문을 반복함.
        document.write(i + "<br>");
        i++; // 반복할 때마다 변수 i를 1씩 증가시켜 변수 i가 10보다 커지면 반복문을 종료함.
    }
```

while 문 내부에 표현식의 결과를 변경하는 실행문이 존재하지 않을 경우 프로그램은 루프를 영원히 반복하게 됩니다.
이것을 무한 루프(infinite loop)에 빠졌다고 하며, 무한 루프에 빠진 프로그램은 영원히 종료되지 않습니다.
무한 루프는 특별히 의도한 경우가 아니라면 반드시 피해야 하는 상황입니다.
따라서, while 문을 작성할 때는 표현식의 결과가 어느 순간에는 거짓(false)을 갖도록 표현식를 변경하는 실행문을 반드시 포함해야 합니다.

※ while 문에서 실행될 실행문이 한 줄 뿐이라면 중괄호({})를 생략할 수 있습니다

<br>

### 7-2-2. do / while 문

- while 문은 루프에 진입하기 전에 먼저 표현식부터 검사합니다. 하지만 do / while 문은 먼저 루프를 한 번 실행한 후에 표현식을 검사합니다. 즉, do / while 문은 표현식의 결과와 상관없이 무조건 한 번은 루프를 실행합니다.

#### do / while 문 기본 문법

```javascript
    do {
        표현식의 결과가 참인 동안 반복적으로 실행하고자 하는 실행문;
    } while (표현식);
```

#### do / while 문 예시 코드

```javascript
    var i = 1, j = 1;
    while (i > 3) { // 변수 i의 초깃값은 1이기 때문에 이 while 문은 한 번도 실행되지 않음.
        document.write("i : " + (i++) + "<br>");
    }
    do { // 변수 j의 초깃값은 1이기 때문에 이 do / while 문은 단 한 번만 실행됨.
        document.write("j : " + (j++) + "<br>");
    } while (j > 3);
```

<br>

### 7-2-3. for 문

- for 문은 while 문과는 달리 자체적으로 초기식, 표현식, 증감식을 모두 포함하고 있는 반복문입니다. 따라서 while 문보다는 좀 더 간결하게 반복문을 표현할 수 있습니다.

#### for 문 기본 문법

```javascript
    for (초기식; 표현식; 증감식) {
        표현식의 결과가 참인 동안 반복적으로 실행하고자 하는 실행문;
    }
```

for 문을 구성하는 초기식, 표현식, 증감식은 각각 생략될 수 있습니다. 또한, 쉼표 연산자(,)를 사용하면 여러 개의 초기식이나 증감식을 동시에 사용할 수도 있습니다. for 문을 사용하면 앞선 예제의 while 문을 더욱 더 간결하게 표현할 수 있습니다.
for 문에서 실행될 실행문이 한 줄 뿐이라면 중괄호({})를 생략할 수 있습니다.

#### for 문 예시 코드

```javascript
    for (var i = 1; i < 10; i++) {
        document.write(i + "<br>");
    }
```

<br>

### 7-2-4. for / in 문

- for / in 문은 일반적인 for 문과는 전혀 다른 형태의 반복문입니다.
- for / in 문은 해당 객체의 모든 열거할 수 있는 프로퍼티(enumerable properties)를 순회할 수 있도록 해줍니다.

※ 열거할 수 있는 프로퍼티란 내부적으로 enumerable 플래그가 true로 설정된 프로퍼티를 의미합니다. 이러한 프로퍼티들은 for / in 문으로 접근할 수 있게 됩니다.

- 이 반복문은 루프마다 객체의 열거할 수 있는 프로퍼티의 이름을 지정된 변수에 대입합니다.
- 이렇게 대입받은 변수를 이용하면 루프 안에서 객체의 열거할 수 있는 프로퍼티에 순차적으로 접근할 수 있습니다.


#### for / in 문 기본 문법

```javascript
    for (변수 in 객체) {
        객체의 모든 열거할 수 있는 프로퍼티의 개수만큼 반복적으로 실행하고자 하는 실행문;
    }
```

#### for / in 문 예시코드1

- for / in 문을 사용하여 배열의 요소에 접근하는 예제

```javascript
    var arr = [3, 4, 5];
    for (var i = 0; i < arr.length; i++) { // 배열 arr의 모든 요소의 인덱스(index)를 출력함.
        document.write(i + " ");
    }
    for (var i in arr) { // 위와 같은 동작을 하는 for / in 문
        document.write(i + " ");
    }
```

#### for / in 문 예시코드2

- for / in 문을 사용하여 객체의 프로퍼티에 접근하는 예제

```javascript
    var obj = { name : "이순신", age : 20 };
    for (var i in obj) {
        document.write(i + "<br>");
    }
```

<br>

### 7-2-5. for / of 문

- for / of 문은 반복할 수 있는 객체(iterable objects)를 순회할 수 있도록 해주는 반복문입니다.
- 자바스크립트에서 반복할 수 있는 객체에는 Array, Map, Set, arguments 객체 등이 있습니다.
- 이 반복문은 루프마다 객체의 열거할 수 있는 프로퍼티의 값을 지정된 변수에 대입합니다.

#### for / of 문 기본 문법

```javascript
    for (변수 of 객체) {
        객체의 모든 열거할 수 있는 프로퍼티의 개수만큼 반복적으로 실행하고자 하는 실행문;
    }
```

#### for / of 문을 사용하여 배열의 요소에 접근

```javascript
    var arr = [3, 4, 5];
    for (var i = 0; i < arr.length; i++) { // 배열 arr의 모든 요소의 인덱스(index)를 출력함.
        document.write(arr[i] + " ");
    }
    for (var value of arr) { // 위와 같은 동작을 하는 for / of 문
        document.write(value + " ");
    }
```

#### for / of 문을 사용하여 Set 객체의 프로퍼티에 접근하는 예제

```javascript
    var arr = new Set([1, 1, 2, 2, 3, 3]);
    for (var value of arr) {
        document.write(value + " ");
    }
```

<br><br>

## 7-3. 기타 제어문

- 일반적으로 표현식의 검사를 통해 루프로 진입하면, 다음 표현식을 검사하기 전까지 루프 안에 있는 모든 실행문을 실행합니다. 하지만 continue 문과 break 문은 이러한 일반적인 루프의 흐름을 사용자가 직접 제어할 수 있게 해줍니다.
- label 문을 사용하면 continue 문과 break 문의 동작이 프로그램의 흐름을 특정 영역으로 이동시킬 수 있습니다.

<br>

### 7-3-1. label 문

- label 문은 프로그램 내의 특정 영역을 식별할 수 있도록 해주는 식별자입니다. label 문을 사용하면 continue 문과 break 문의 동작이 프로그램의 흐름을 특정 영역으로 이동시킬 수 있습니다.

#### label 문 기본 문법

```javascript
   label:
        식별하고자 하는 특정 영역
```

#### 

```javascript
    arrIndex:
        for (var i in arr) {
            document.write(i);
        }
```

<br>

### 7-3-2. continue 문

- continue 문은 루프 내에서 사용하여 해당 루프의 나머지 부분을 건너뛰고, 바로 다음 표현식의 판단으로 넘어가게 합니다. 보통 반복문 내에서 특정 조건에 대한 처리를 제외하고자 할 때 자주 사용됩니다. 
- 자바스크립트에서 continue 문은 다음과 같이 두 가지 형태로 사용할 수 있습니다. 
    1. continue;
    2. continue 라벨이름;


#### continue 문 예시 코드1

```javascript
    var exceptNum = 3;
    for (var i = 0; i <= 100; i++) {
        if (i % exceptNum == 0) // exceptNum의 배수는 출력하지 않음.
            continue;
        document.write(i + " ");
    }
```

#### continue 문 예시 코드2

```javascript
    gugudan:
        for (var i = 2; i <= 9; i++) {
            dan:
            for (var j = 1; j <= 9; j++) {
                if ((i*j) % 2 == 0)
                    continue dan;
                document.write(i + " * " + j + " = " + (i*j) + "<br>");
            }
        }
```

<br>

### 7-3-3. break 문

- break 문은 루프 내에서 사용하여 해당 반복문을 완전히 종료시키고, 반복문 바로 다음에 위치한 실행문으로 프로그램의 흐름을 이동시킵니다. 즉, 루프 내에서 표현식의 판단 결과에 상관없이 반복문을 완전히 빠져나가고 싶을 때 사용합니다.

#### break 문 예시코드1

```javascript
    var lectures = ["html", "css", "자바스크립트", "php"];
    var topic = "자바스크립트";
    for (var i = 0; i < lectures.length; i++) {
        if (lectures[i] == topic) {
            document.write(topic + " 과목은 " + (i + 1) + "번째 과목입니다.");
            break; // 원하는 값을 찾은 후에는 더 이상 for 문을 반복하지 않고 빠져나감.
        }
    }
```

#### break 문 예시코드2

```javascript
    gugudan: 
        for (var i = 2; i <= 9; i++) { 
            dan: for (var j = 1; j <= 9; j++) { 
                if (i > 3) break gugudan; 
                document.write(i + " * " + j + " = " + (i*j) + ""); 
            } 
        }
```

<br><hr><br>

# 8. 배열의 사용

- 자바스크립트에서 배열(array)은 이름과 인덱스로 참조되는 정렬된 값의 집합으로 정의됩니다.
- 배열을 구성하는 각각의 값을 배열 요소(element)라고 하며, 배열에서의 위치를 가리키는 숫자를 인덱스(index)라고 합니다.
- 자바스크립트에서 배열의 특징은 다음과 같습니다.
    1. 배열 요소의 타입이 고정되어 있지 않으므로, 같은 배열에 있는 배열 요소끼리의 타입이 서로 다를 수도 있습니다.
    2. 배열 요소의 인덱스가 연속적이지 않아도 되며, 따라서 특정 배열 요소가 비어 있을 수도 있습니다.
    3. 자바스크립트에서 배열은 Array 객체로 다뤄집니다.

<br><br>

## 8-1. 배열의 생성

### 8-1-1. 배열의 생성 기본 문법

- 배열의 생성 방법은 아래와 같이 세 가지 방법이 있습니다.

```javascript
var arr = [배열요소1, 배열요소2,...]; // 배열 리터럴을 이용하는 방법
var arr = Array(배열요소1, 배열요소2,...); // Array 객체의 생성자를 이용하는 방법
var arr = new Array(배열요소1, 배열요소2,...); // new 연산자를 이용한 Array 객체 생성 방법
```

<br>

### 8-1-2. 배열의 생성 예시 코드

```javascript
    var arrLit = [1, true, "JavaScript"];             // 배열 리터럴을 이용하는 방법
    var arrObj = Array(1, true, "JavaScript");        // Array 객체의 생성자를 이용하는 방법
    var arrNewObj = new Array(1, true, "JavaScript"); // new 연산자를 이용한 Array 객체 생성 방법
    document.write(arrLit + "<br>");                  // 1,true,JavaScript
    document.write(arrObj + "<br>");                  // 1,true,JavaScript 
    document.write(arrNewObj);                        // 1,true,JavaScript
```

<br><br>

## 8-2. 배열의 참조

- 자바스크립트에서 배열의 각 요소를 참조하고 싶을 때는 [] 연산자를 사용합니다.
- 자바스크립트에서는 배열 요소의 개수를 배열의 길이라고 합니다. 이러한 배열의 길이는 length 프로퍼티에 자동으로 갱신됩니다.
- 자바스크립트에서 인덱스는 언제나 0부터 시작합니다. 또한, 인덱스에는 음이 아닌 정수를 반환하는 임의의 표현식도 사용할 수 있습니다. 이러한 인덱스에는 232보다 작은 양수만을 사용할 수 있습니다.

### 8-2-1. 배열의 참조 기본 문법

```javascript
 배열이름[인덱스]
```

<br>

### 8-2-2. 배열의 참조 예시 코드

```javascript
    var arr = ["JavaScript"]; // 요소가 하나뿐인 배열을 생성함.
    var element = arr[0];     // 배열의 첫 번째 요소를 읽어서 대입함.
    arr[1] = 10;      // 배열의 두 번째 요소에 숫자 10을 대입함. 배열의 길이는 1에서 2로 늘어남.
    arr[2] = element; // 배열의 세 번째 요소에 변수 element의 값을 대입함. 배열의 길이는 2에서 3으로 늘어남.
    document.write("배열 arr의 요소에는 [" + arr + "]가 있습니다.<br>"); // 배열의 요소를 모두 출력함.
    document.write("배열 arr의 길이는 " + arr.length + "입니다.<br>");   // 배열의 길이를 출력함.
    delete arr[2];    // 배열의 세 번째 요소를 삭제함. 하지만 배열의 길이는 변하지 않음.
    document.write("배열 arr의 요소에는 [" + arr + "]가 있습니다.<br>"); // 배열의 요소를 모두 출력함.
    document.write("배열 arr의 길이는 " + arr.length + "입니다.");       // 배열의 길이를 출력함.
```

<br><br>

## 8-3. 배열 요소의 추가

### 8-3-1. 배열 요소의 추가시 기본 문법

- 자바스크립트에서 배열에 새로운 배열 요소를 추가하는 방법은 다음과 같습니다.

```javascript
arr.push(추가할 요소); // push() 메소드를 이용하는 방법
arr[arr.length] = 추가할 요소; // length 프로퍼티를 이용하는 방법
arr[특정인덱스] = 추가할 요소; // 특정 인덱스를 지정하여 추가하는 방법
```

<br>

### 8-3-2. 배열 요소의 추가시 예시 코드

```javascript
    var arr = [1, true, "Java"];
    arr.push("Script");           // push() 메소드를 이용하는 방법
    document.write(arr + "<br>"); // 1,true,Java,Script
    arr[arr.length] = 100;        // length 프로퍼티를 이용하는 방법
    document.write(arr + "<br>"); // 1,true,Java,Script,100
    arr[10] = "자바스크립트";     // 특정 인덱스를 지정하여 추가하는 방법
    document.write(arr + "<br>"); // 1,true,Java,Script,100,,,,,,자바스크립트
    document.write(arr[7]);       // undefined
```

```comment
위의 예제에서 배열 arr의 길이는 최종적으로 11이 됩니다.

이때 배열 요소가 존재하는 인덱스는 0, 1, 2, 3, 4, 10뿐이며, 나머지 인덱스에는 배열 요소가 존재하지 않습니다.

이렇게 인덱스에 대응하는 배열 요소가 없는 부분을 배열의 홀(hole)이라고 합니다.

자바스크립트에서는 이러한 배열의 홀(hole)을 undefined 값을 가지는 요소처럼 취급합니다.

따라서 위의 예제에서처럼 배열의 홀을 참조하게 되면 undefined 값을 반환하게 됩니다.
```

<br><br>

## 8-4. 배열의 순회(iteration)

- 배열의 모든 요소에 차례대로 접근하고 싶을 때는 for 문과 같은 반복문을 사용하여 접근할 수 있습니다.

### 8-4-1. 배열의 순회 예시 코드

```javascript
    var arr = [1, true, "JavaScript"];
    var result = "<table><tr>";
    for (var idx in arr) {
        result += "<td>" + arr[idx] + "</td>";
    }
    result += "</tr></table>";
    document.write(result);
```

<br><br>

## 8-5. Array 객체

- 자바스크립트에서 배열(array)은 정렬된 값들의 집합으로 정의되며, Array 객체로 다뤄집니다. 또한, 자바스크립트는 사용자가 배열과 관련된 작업을 손쉽게 할 수 있도록 다양한 메소드도 제공하고 있습니다.

<br>

### 8-5-1. Array 객체의 예시 코드

```javascript
    var arr = new Array(10, "문자열", false);
    document.write((typeof arr) + "<br>");    // object
    document.write((typeof arr[0]) + "<br>"); // number
    document.write((typeof arr[1]) + "<br>"); // string
    document.write(typeof arr[2]);            // boolean
```

<br><br>

## 8-6. 자바스크립트에서 배열 여부 확인

- 자바스크립트에서는 배열이라는 타입(type)을 별도로 제공하지 않습니다.
- 자바스크립트 배열은 객체(object) 타입이 되며, typeof 연산자를 사용하면 'object'를 반환합니다.
- 자바스크립트에서는 해당 변수가 배열인지 여부를 확인할 수 있도록 다음과 같은 방법들을 제공하고 있습니다.
    1. Array.isArray() 메소드
    2. instanceof 연산자
    3. constructor 프로퍼티

<br><br>

### 8-6-1. 배열 여부 확인 예시 코드

```javascript
    var arr = [1, true, "JavaScript"]; // 배열 생성
    document.write(typeof arr);        // object
    document.write(Array.isArray(arr));      // true
    document.write(Array.isArray("문자열")); // false
    document.write(arr instanceof Array); // true
    document.write(123 instanceof Array); // false

    function isArray(a) {
        return a.constructor.toString().indexOf("Array") > -1;
    }
    var arr = [1, true, "JavaScript"];          // 배열 생성
    document.write(arr.constructor);            // constructor 프로퍼티의 값 출력
    document.write(arr.constructor.toString()); // function Array() {[native code]}
    document.write(arr.constructor.toString().indexOf("Array")); // 10
    document.write(isArray(arr))                // true
```

<br><br>