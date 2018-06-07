# Quest01

### `<head>` 

+ ##### `<title>`

  - HTML 문서의 제목을 정의 
  - HTML 문서에서 필수적으로 있어야함

+ ##### `<meta>`

  + 데이터에 대한 정보를 나타낸다.

  + 메타데이터는 화면에는 표시되지 않지만 기계는 해석할 수 있는 것

  + 페이지 설명, 문서의 작성자, 마지막으로 수정된 항목등을 포함

  + 메타 데이터는 항상 name과 value 쌍을 이룬다

  + <u>속성</u>

    + `charset` : 페이지에서 사용되는 문자 인코딩을 선언

      ```html
      <meta charset="UTF-8"> <!-- UTF-8은 모든 유니코드 문자를 표현할 수 있다 -->
      ```

    +  `content` :  `http-equiv`또는 `name`속성과 연관된 값을 제공,

    + `http-equiv` : content 속성의 정보 / 값에 대한 HTTP 헤더를 제공 ???????

    + `name` 

      **author** : 문서 작성사 이름 지정

      ```html
      <meta name="author" content="dasom">
      ```

      **description** : 페이지에 대한 설명, 검색 엔진이 검색 결과 표시할 때 보는 항목중 하나

      ```html
      <meta name="description" content="web study">
      ```

      **keywords** : 쉼표로 키워드 지정, 검색 엔진에게 페이지에 관련하여 알려준다

      ```html
      <meta name="keywords" content="HTML, meta tag, tag reference">
      ```

      **viewport** : 뷰포트 제어, viewport 는 페이지의 크기와 배율을 제어하는 방법에 대한 브라우저 지침을 제공한다. 

      width = device-width : 페이지의 너비를 장치의 화면 너비에 따라 설정(장치에 따라 다름).

      initial-scale = 1.0 : 브라우저가 페이지를 처음로드 할 때 초기 줌 레벨을 설정

      user-scalable  = no : 사용자가 웹페이지에서 줌을 사용할 수 없다, 디폴트는 yes

      ```html
      <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
      ```

+ `<base>`

  + 페이지의 모든 링크에 대한 기본 URL 및 기본 대상 지정

    ```html
    <head>
      <base href="https://www.w3schools.com/images/" target="_blank">
    </head>
    
    <body>
    <img src="stickman.gif" width="24" height="39" alt="Stickman">
    <a href="https://www.w3schools.com">W3Schools</a>
    </body>
    ```

+ `<noscript>` 

  +  브라우저에서 스크립트를 비활성화했거나 스크립트를 지원하지 않는 브라우저를 가지고있는 사용자를위한 대체 컨텐츠를 정의

    ```html
    <script>
    document.write("Hello World!")
    </script>
    <noscript>Your browser does not support JavaScript!</noscript>
    ```

    

--------

**[참고]**

https://www.w3schools.com/tags/att_meta_name.asp

https://developer.mozilla.org/ko/docs/Web/HTML/Element/meta

-------------

