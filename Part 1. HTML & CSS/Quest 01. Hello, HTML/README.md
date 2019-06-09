# Quest 01. Hello, HTML


## Introduction
* HTML은 HyperText Markup Language의 약자로, 웹 브라우저에 내용을 표시하기 위한 가장 기본적인 언어입니다. 이번 퀘스트를 통해 HTML에 관한 기초적인 사항들을 알아볼 예정입니다.

## Topics
* 브라우저의 역사
  * Mosaic
  * Netscape
  * Internet Explorer
  * Firefox
  * Chrome
  * Safari (for iOS)
  * Edge
* HTML 표준의 역사
  * HTML 4.01
  * XHTML 1.0, XHTML 1.1
  * XHTML 2.0
  * HTML5
    * HTML 5.3
* HTML 문서의 구조
* HTML 문서의 엘리먼트
  * Semantic elements
  * Block-level elements vs Inline elements

## Resources
* [MDN - HTML](https://developer.mozilla.org/ko/docs/Web/HTML)
* [모던 웹 디자인을 위한 HTML5+CSS3 입문](http://www.yes24.com/24/Goods/15683538?Acode=101), 한빛미디어
* [웹 디자인 2.0 고급 CSS](http://www.yes24.com/24/Goods/2808075?Acode=101), 에이콘출판사
* [StatCounter Global Stats](http://gs.statcounter.com/)

## Checklist
* HTML 4.x 이후의 HTML 표준의 변천사는 어떻게 되나요?
  * 1999년에 HTML 4.01이 제정되고, HTML을 XML 형태로 사용할 수 있도록 XHTML 1.1이 2001년에 별도로 제정되었다.2005년에 W3C에서 XHTML 2.0를 만들었으나 실제 사용하기에 매우 어려웠고, 웹브라우저 업체들이 만든 WHATWG라는 표준화 기구에서 만든 Web Application 1.0은 기존 HTML과 하위 호환성을 갖는 유연한 표준안이었다. 결국 2007년에 W3C는 XHTML 2.0를 포기하고 WHATWG의 표준안을 수용하여 HTML5 표준안을 2014년에 확정했다.
* MS와 IE는 왜 역사에 오점을 남기게 되었을까요?
  *
* `<section>`과 `<div>`, `<header>`, `<footer>`, `<article>` 엘리먼트의 차이점은 무엇인가요?
  * section과 div 모두 구획화를 목적으로 하나 section은 전형적으로 제목을 가지고 있는 컨텐츠의 주제 그룹을 말하며 일반적인 컨테이너로 사용하지 않는다. 스타일링이 목적인 경우 div를 사용한다.
  * div 요소는 의미 있는 다른 요소가 적절하지 않을 때만 사용해야 한다.
  * header 요소는 소개나 탐색 관련 그룹을 나타낸다.
  * footer 요소는 일반적으로 작성자, 저작권 데이터, 관련 문서 링크 정보를 포함한다.
  * article 요소는 포럼의 글, 매거진 및 신문의 기사, 블로그의 글 등이 포함되며, 일반적으로 제목(headline)을 자식으로 포함하여 식별된다.
* 블럭 레벨 엘리먼트와 인라인 엘리먼트의 차이는 무엇일까요?
  * 인라인 요소는 콘텐츠의 흐름을 끊지 않고 요소를 구성하는 태그에 할당된 공간만 차지하며 줄바꿈을 강제하지 않는다. 반면에, 블록 요소는 줄바꿈을 유발해 언제나 새로운 줄에서 시작하고, 좌우 양쪽으로 최대한 늘어나 가능한 모든 너비를 차지한다.

## Quest
* [이 그림](github.png)은 github의 웹사이트 레이아웃입니다. 이 레이아웃의 정보를 HTML 문서로 표현해 보세요.
* CSS를 전혀 사용하지 않고, 문서의 구조가 어떻게 되어 있는지를 파악하여 구현해 보세요.
  * [CSS Naked Day](http://meiert.com/en/blog/20150319/css-naked-day/)는 매년 4월 9일에 CSS 없는 웹 페이지를 공개하여 내용과 마크업에 집중한 HTML 구조의 중요성을 강조하는 행사입니다.
* 폴더에 있는 `skeleton.html` 파일을 바탕으로 작업해 보시면 됩니다.
