# 서버와 클라이언트
   클라이언트: 서버에게 요청하는 대상<br>
   서버: 요청받은 서비스를 알맞게 응답해주는 대상

# 웹(Web)
   요청과 응답이 일어나는 장소.

# 웹 브라우저(Web Browser)
   사용자의 요청에 맞는 주소로 찾아가서 인터넷 컨텐츠(문서와 그림, 파일 등)를<br>
   검색 및 열람 후 사용자에게 응답하기 위한 응용 프로그램의 총칭이다.

# 프로토콜(Protocol): 통신 규약
   클라이언트의 요청에 반드시 응답해야한다는 약속.

   - http:// (Hypertext Transfer Protocol)<br>
      클라이언트와 서버 간 텍스트로 통신하기 때문에<br>
      가로채어 본다면 누구든 내용을 볼 수 있다.<br>

   - https:// (Hypertext Transfer Protocol Secure Socket)<br>
      SSL 프로토콜을 이용해서 자원을 암호화한 뒤 통신하는 규약<br>

# IP(Internet Protocol)
   클라이언트가 찾아갈 서버의 고유한 값, 컴퓨터가 다른 컴퓨터와 구별될 수 있도록<br>
   중복이 없는 값으로 설정되며, 네트워크 상에서 사용된다.

# 도메인(Domain)
   IP 주소는 기억하고 이해하기 힘들기 때문에 이를 위해서 이름(별칭)을 붙일 수 있도록 한 것.

# WWW(World Wide Web)
   인터넷에 연결된 전 세계 컴퓨터들을 통해 사람들이 정보를 공유할 수 있는 정보 공간.

# W3C
   WWW를 위한 표준을 제정하고 관리하는 중립적인 기관이다.
   
---------------------------------------------------------------------------------
# 웹 표준(Web Standard)
   1. HTML(Hypertext Markup Language)
      웹 페이지에서 다른 페이지로 이동할 수 있도록 해주는 마크업 언어이다.<br>
      태그를 이용하여 문서나 데이터의 구조를 기술하는 언어이다.<br>

   3. CSS(Cascading Style Sheets)
      구체적으로 어떤 스타일로 요소가 표시되는 지를 정하는 규격이다.<br>
      HTML에 작성된 스타일을 따로 분리해서 일괄처리가 가능하도록 한다.<br>

   4. JS(Javascript)
      화면 쪽에서 연산이 가능한 스크립트 언어이다.
      사용자의 다양한 이벤트 처리, 비동기 통신 등을 자유롭게 사용할 수 있다.<br>
      HTML 안에서 태그형태로 JS를 사용할 수도 있으며, 외부 파일로 제작 후<br>
      포함시켜서 사용할 수도 있다. 유효성 검사, 통신 등을 담당한다.<br>

   5. XHTML(Extensible HTML)
      기존에 사용되던 HTML 규격이 가진 문제점을 극복하고 보다 다양한 분야에 응용될 수<br>
      있도록 해주는 여러가지 확장된 기능을 포함한다.<br>
      HTML과 XHTML은 사실상 큰 차이 없이 사용된다.<br>

   6. XML(Extensible Markup Language)
      어떠한 데이터를 설명하기 위해서 임의로 지은 태그로 데이터를 감싼다.<br>
      태그로 데이터를 설명하며, 이것이 데이터의 표시(Markup)가 되고 추가적인<br>
      데이터가 생기면 태그 추가와 태그 내부 내용을 추가할 수 있다.<br>
      따라서 데이터를 전달하는 데에 목적이 있다.<br>

      <?xml version="1.0">
      <user>
         <user-id>hds1234</user-id>
         <name>한동석</name>
      </user>
---------------------------------------------------------------------------------
Visual Stduio Code 설치
   https://code.visualstudio.com/Download

   Windows
      .zip, x64 클릭해서 다운로드

   MacOS
      .zip, Universal 클릭해서 다운로드
      
---------------------------------------------------------------------------------
# HTML의 요소
   <p> You are better </p>
   --- -------------- ----<br>
   (1)                           (2)                  (3)

   (1) 여는 태그(Opening tag): 요소의 이름(p)과 열고 닫는 꺽쇠 괄호로 구성된다.
   (2) 내용(Content): 요소의 내용이며, 단순한 텍스트를 의미한다.
   (3) 닫는 태그(Closing tag): 요소의 이름 앞에 슬래시(/)가 있다.

# HTML 주석
   <!-- 주석 -->

   1. 설명글을 작성할 때 사용한다.
   2. 지금 당장 사용하지 않는 코드를 숨기고 싶을 때 사용한다.

# 속성(Attribute)
   태그는 속성을 가질 수 있다.

   <p class="conversation"> You are much better </p>

   속성은 내용에 나타내고 싶지 않지만 추가적인 내용을 담고 싶을 때 사용한다.
   특히 id와 class 속성은 스타일에 관련된 내용이나 기타 연산등의 내용을 위해
   해당 태그를 찾을 수 있는 구분점 역할을 수행한다.

   - 속성 사용 시 주의사항
    1. 태그 이름 다음에 오는 속성은 태그 이름과 속성 사이에 공백이 있어야 하고,
       여러 속성이 있을 경우에도 공백으로 구분한다.
       <p id="p1" class="p-group"> You are pretty </p>

    2. 속성 이름 다음에는 등호(=)를 작성한다.
    3. 속성 값은 따옴표 안에 작성한다.
