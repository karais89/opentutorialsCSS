# opentutorialsCSS
생활코딩 css 수업

**CSS란?**

HTML이 웹페이지의 '뼈'라면 CSS는 '살'이라고 할 수 있습니다. 즉 HTML이 웹페이지의 정보를 표현한다면, CSS는 HTML을 보기 좋게 디자인하는 역할을 하는 언어입니다.

따라서 CSS를 공부하려면 선행지식으로 HTML을 요구합니다. 물론 HTML을 많이 알고 있을 필요는 없습니다. HTML이 무엇이고, 태그는 어떻게 사용하는지만 알고 있으면 CSS를 배울 수 있습니다. 하지만, CSS의 대상이 HTML이라는 점에서 CSS에게 있어서 HTML은 필연적입니다. 

**코스소개**

**수업**

CSS에 대한 기본적인 내용을 전달합니다. 선택자나 박스모델과 같은 중요한 내용을 포함합니다. 특히 HTML이 정보를 CSS가 디자인을 담당하게 된 맥락과 그에 따른 적합한 사용방법에 유의하면서 청강해주세요.

**LESS**

CSS의 미덕은 간결한 문법구조입니다만, 간단한 것은 자유롭지 못합니다. 다시 말해서 기능성이 떨어진다는 것이죠. LESS는 CSS의 부족한 기능성을 보강해서 javascript와 같이 동적인 프로그래밍 언어의 기능인 변수, 함수와 같은 기능을 제공합니다. 유지보수의 공수가 드라마틱하게 줄어듭니다.

**SASS**

SASS는 LESS의 동일한 기능을 제공하는 다른 솔루션입니다. LESS에 대한 설명을 참조하세요. (바로가기)

**Twitter Bootstrap**

트위터에서 자신들의 웹서비스를 위해서 사용하던 UI 프래임웍을 오픈소스로 공개한 것이 Bootstrap입니다. 이것을 이용하면 HTML의 엘리먼트에 CSS 클래스 네임만 부여하면 그에 해당하는 디자인이나, 컴포넌트가 생성됩니다.

# CSS 수업

코스소개

CSS는 HTML을 꾸며주는 언어입니다.  CSS를 이용하면 HTML로 만들어진 웹페이지를 질서정연한 문서로 만들수도 있고, 복잡한 UI(User Interface)들의 결합체인 웹에플리케이션으로 만들수도 있습니다.

공부방법

HTML이 이해할 것은 별로 없는데 외울 것이 많다면,  CSS는 외울 것도 많고, 이해해야 할 것도 조금 많은 편입니다.  선택자나 박스모델 같은 것은 처음에는 이해하기 조금 어려울수도 있습니다. 

이러한 개념들을 이해했다고 해도 실제로 다양한 개념들이 복합적으로 얽혀 있어서 당분간은 안개속에 있는 것 같은 느낌이 들수도 있습니다.

따라서, 강의만 보고 CSS를 마스터 했다고 생각하면 안타깝게도 오해입니다.

직접 코딩을 하면서 여러가지 문제에 부딪쳐봐야 합니다.(머는 안 그렇겠어요? ^^) 그러다보면 CSS의 선택자들을 이용해서 재활용성을 높이는 것에 관심을 갖게 되고, 또 브라우저 간의 특성들에 익숙해지면서 자유자재로 웹페이지를 디자인할 수 있게 됩니다. 

특히, 정보 표현 언어로서의 HTML과 정보를 디자인하는 언어로서의 CSS라는 관계를 이해하는 것이 중요합니다. 이 둘의 역활을 질서정연하게 조화시키면 검색엔진 최적화, 코드의 재활용성, 협업능력의 향상과 같은 목표들에 도달할 수 있을꺼에요. 

무엇보다 중요한 것은 사전찾는 법, 검색하는 법, 질문하는 법입니다. 

이것들이야 말로 생활코딩의 커리큘럼들이 여러분에게 알려드리고 싶은 것들입니다. 

그 시작점이 한글화된 CSS 사전입니다. 생활코딩 CSS 사전은 지금 만들고 있습니다.

생활코딩 밖에서 CSS에 대한 정보를 얻을 수 있는 곳을 소개해드리면 이렇습니다. 

* css 한글 레퍼런스 (http://nsyang-textcube.blogspot.com/2009/06/css-%EC%82%AC%EC%A0%84.html)
* w3schools.com css reference (http://www.w3schools.com/cssref/default.asp)
* MDN CSS reference (https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

실습방법

타이핑해보지 않는 지식은 이론으로 머물뿐 경험이 되지 못합니다. 수업에서 등장하는 예제를 직접 타이핑해보세요. HTML 소개에서 했던 말을 그대로 옮겨봅니다. 

컴퓨터라는 것이 획 하나만 틀려도 엉뚱한 결과를 출력하기 때문에 이런 문제에 직면하면 당황하게 됩니다.

공부에 할애하려고 스스로에게 약정했던 시간을 훌쩍 넘어가면서 초조해집니다.

그런데 바로 그 순간에도 뇌는 HTML코드를 주시하면서 로직의 흐름,

문법적인 용법을 내 안으로 받아들이고 있다는 것을 기억하세요.

그 순간을 이겨내면 실력의 계단을 한칸 오른겁니다. 

## CSS란?

HTML이 정보를 표현한다면 CSS는 HTML을 시각적으로 꾸며주는 역할을 한다.

CSS를 통해서 기대되는 효과들

* 정보(HTML)과 디자인(CSS)를 분리할 수 있다.
* 정보를 수정하지 않고 디자인만 변경할 수 있다. (참고 : css Zen Garden)
* 검색엔진이 HTML을 해석 가능하도록 하기 때문에 더 많은 방문자들이 방문하도록 유도할 수 있다.
* HTML에서 디자인 분리함으로서 시각장애인을 위한 프로그램인 스크린리더가 HTML을 해석할 수 있도록 할 수 있다.

css Zen Garden http://www.csszengarden.com/

CSS는 HTML을 꾸며줌. HTML을 꾸며주는 언어가 별도로 존재하고 그 언어가 CSS 이다. 그러므로 HTML에 대한 어느 정도의 지식이 필요함.

전혀 모르면 html 공부를 해라.

## 실습방법과 개발도구

개발도구란?

개발도구란? 개발을 하는데 필요한 도구와 개발된 결과를 실행할 환경을 의미한다. HTML 수업에서 개발도구란 웹페이지의 소스를 만드는 에디터와 웹페이지를 실행할 웹브라우저와 같은 일련의 도구를 의미한다.

개발도구

**웹브라우저**
구글 크롬 사용(개발자 도구)

**인스펙터(inspector)**
* 웹페이지의 코드를 분석하고, 조작할 수 있는 도구
* 구글 개발자 도구 (Elements) 사용 https://opentutorials.org/course/580/2866

**에디터(editor)**
* 소스코드를 작성하는데 필요한 도구
* Aptana 사용 (http://www.aptana.com/) , 생활코딩 개발 도구 중 Aptana 편 참고 (https://opentutorials.org/course/128/2548)

**예제 사용법**

본 수업은 두가지 형태의 예제를 제공한다. 아래와 같다.

JSFIDDLE
라이브로 예제를 실행해 볼 수 있는 서비스다. 직접 코드를 변경 하면서 결과를 실시간으로 확인해볼 수 있다. 특별한 개발도구가 필요 없다는 것이 장점이다. 자세한 사용법은 생활코딩 수업을 참고하자.

생활코딩 jsfiddle 수업 바로가기(https://opentutorials.org/course/128/2833)
jsfiddle 바로가기 (https://jsfiddle.net/)

github.com
소스코드를 저장할 수 있는 서비스로 본 수업의 모든 예제 파일이 저장되어 있다. html 수업의 저장소 페이지로 이동한 후에 ZIP 파일을 다운로드하면 전체 코드를 다운받을 수 있다. (저장소로 바로가기)

## CSS의 사용

HTML에서 CSS 사용하기

1. inline 방식 (예제1)
    * 엘리먼트에 스타일을 직접 기술하는 방식
    * 셀렉트가 필요 없다.
    * CSS 선언이 분명해서 style tag 방식에 비해 엘리먼트에 영향을 주고 있는 CSS를 추적하기가 쉽다.
    * 코드가 많아지고, 의미와 디자인의 분리라는 CSS의 취지와 벗어난다.   
2. style tag 방식 (예제2)
    * style 태그에 기술하는 방식
    * inline 방식 대비 경제적으로 코딩할 수 있다.
    * 의미와 디자인의 분리라는 CSS의 취지에 부합한다.
3. 외부 파일 방식 (예제3)
    * CSS를 별도의 파일로 분리해서 링크하는 방식
    * 문법적으로는 style tag와 동일
    * 파일의 교체로 디자인을 변경할 수 있다는 점에서 유지보수가 편리하다.

html과 css서로 다른 문법 체계를 가지고 있음. 그러므로 브라우저에게 구별할수있는 규칙이 있음.

그 규칙을 배울 예정.

언제 무슨 방식을 쓰는가?? 제대로 된 코딩을하고 규모가 있는 것을 사용할때 style tag를 사용.

## 선택자

CSS의 효과가 적용될 태그를 지정
<pre>
Selector Declaration 
h1 {color:blue; font-size:12px; }

h1 = selector
괄호안 = Declaration

color = property
blue = value;
font-size = property
12px = value;
</pre>

Id 선택자

* id 속성은 전체 문서에서 하나의 태그를 식별하기 위해서만 사용됨
* 우선순위가 가장 높음
* css 선택자에서는 #을 사용해서 id임을 표시
* 다음 예제는 id값이 memo인 태그의 컨텐츠를 빨간색으로 표시하도록 함

Class 선택자

* class 속성은 일련의 태그를 그룹핑해서 하나처럼 제어하기 위해서 사용
* class 속성에는 공백으로 구분된 여러개의 class가 표시될 수 있음
* css선택자에서는 '.'을 사용해서 class임을 표시

type 선택자

* 특정 태그명을 가진 엘리먼트 전체를 제어하기 위해서 사용
* css선택자에서는 태그의 이름을 사용함

## 선택자의 조합

하위 선택자

* 특정 엘리먼트의 하위에 나오는 엘리먼트를 선택하는데 사용
* 부모가 먼저 나오고 자식이 나중에 나옴
* 공백을 통해서 부모와 자식을 구분

하나의 CSS선언을 여러개의 선택자에 적용하기

* 하나의 css선언을 여러 엘리먼트 셀렉터에 적용하고 싶을 때 사용
* 선택자와 선택자를 ',(콤마)'로 구분

자식선택자 -child selector

* 특정 엘리먼트의 직접적인 하위 엘리먼트에 대해서만 선택할 때 사용(하위 선택자와 다름)
* ie6는 지원되지 않음