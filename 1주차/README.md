### 공부한내용

---

#### HTML

HTML(**H**yper**t**ext **M**arkup **L**anguage)은 웹 컨텐츠 작성에 이점을 주는언어이다.

다양한 태그들이 존재하여 크게 <head> <body> 등의 태그들이 있다.



### DOM

Document(문서) Object(객체) Model(모델)의 약자이다.

html을 이루는 태그들을 객체화 시켜 핸들링 하게 편하게 만든다.

브라우져가 HTML 페이지를 인식하는 방식을 의미한다.



EX)

var header = document.createElement('h2'); 

우선 document 객체에 접근해서 <h2> 태그를 생성한다.

var textNode = document.createTextNode('Hello DOM');

그 다음은 document 객체에 접근해서 TextNode를 생성하고 'Hello DOM'이라는 스트링을 넣어주고 있다.

header.appendChild(textNode);

위에서 생성한 <h2> 태그에 자식노드를 추가하고 있다.



