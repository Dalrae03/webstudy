```html
<!DOCTYPE html> <!--html 파일이라는 것을 알려줌-->
<html lang="kr"> <!--한국어 설정-->
<head> <!--사용자들에게는 안보이지만 브라우저가 html파일을 해석하는데 도움이 되는 정보들을 가지고있음-->
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title> <!--웹사이트 상단 책갈피 이름(?)-->
    <link rel = "stylesheet" href = "index.css"> <!--다른 곳에 저장되어있는 파일들을 이 html파일에 불러와라-->
    <!--link 안의 rel, type => 파일이 어떤 타입의 파일인지 가르키는 것-->
    <meta> <!--웹사이트가 어떤 정보를 담고 있는지 자세하게 알려주는 태그-->
    <!--사이트가 어디에 공유가 될 때 스크린 샷이랑 같이 뜨는 간략한 설명이 meta태그-->
    <style>
    </style> <!--Css코드를 쓸 수 있는 태그. 하지만 잘 안씀-->
</head>
<body>
    <!--텍스트 관련 태그-->
    <h1>난 그렇게 생각하지않아 승환</h1>  <!--가장 큰 굵은 글씨로 프린트 (제목으로 많이 씀)-->
    <h2>엔터키 누르고싶네</h2>
    <h3>학술제 가야할까요</h3>
    <h4>가야겠네요</h4>  <!--h6까지 있음-->
    <b>글씨체 굵게</b>
    <i>기울은 글씨</i>
    <p></p>  <!--기사 본문이 들어가는 태그. 글의 한 문단을 나타낼 때-->

    <!--미디어 관련 태그들-->
    <img src="이미지 주소"/>  <!--사진 불러오기-->
    <video>
        <source src="비디오 주소" controls>
    </video>
    <!--비디오 불러오기 controls => 재생버튼 같은 기타 조작창 가지고옴-->

    <a href = "https://www.youtube.com/">유튜브로 가기</a>  <!--엥커 -> 닻 => 링크연결 / href(속성) = 하이퍼링크 참조 값 / 유튜브 링크 - 속성 값-->
    <!--target="_blank" => 링크를 새 창을 하나 더 띄워서 열기-->
    <Tag></Tag>  <!--기능이 없는 태그도 있다 => 약간 의미있는 변수 같은거-->
    <br>  <!--공백한줄 만들어줌-->
    <div value = video>
        <a></a>
    </div>  <!--내용의 덩어리 하나를 만들어 주는 태그 / 요소하나하나 감쌀때 많이 쓴다-->
    <div class="box">박스</div>  <!--class="box"는 속성, class속성을 이용해서 css로 스타일링을 할 수 있음.-->
    <!--div,class 모두 합쳐서 엘레먼트라고 부른다.-->
		<script></script>  <!--자바스크립트 코드 입력할 때 사용 (style이랑 비슷한 의미같음)-->
    <strong></strong>  <!--강조할 때 사용, 요소의 콘텐츠 굵은 글씨로 표시-->
    <!--<b> 요소는 콘텐츠의 중요성보다는 텍스트 자체에 주의를 끌기 위해 사용되지만, <strong> 요소는 콘텐츠 자체의 중요성을 강조할 때 사용.

    
    <!--테이블 태그(표)-->
    <table>
        <thead>  <!--테이블에 칼럼은 몇개있고, 각 칼럼의 이름은 무엇인지 들어감-->
            <tr>
                <th>이름</th>
                <th>나이</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>디디</th>
                <th>2살</th>
            </tr>
            <tr>
                <th>달</th>
                <th>2살</th>
            </tr>
        </tbody>
    </table>

    <!--목록 태그(표)-->
    <ol>
        <li>디디</li>
        <li>달</li>
    </ol>  <!--ordered list. 숫자 붙은 리스트-->
    <ul>
        <li>디디</li>
        <li>달</li>
    </ul>  <!--unordered list. 숫자 안붙은 리스트, 블럭포인트 붙음-->

    <!--구역을 나누는 태그(표)-->
    <div>
    </div>  <!--html문서를 여러구역으로 나누고 싶을 때 사용. 한 줄 전체 공간을 차지. block element-->
    <span>
    </span>  <!--구역을 나누는 태그, 자기 내용물 만큼의 공간만 차지. inline element-->

    <!--인풋 태그. 유저에게 어떠한 정보를 받아야 할 때-->
    <input type="text"/>  <!--텍스트-->
    <input type="checkbox"/>  <!--체크박스-->
    <input type="radio"/>  <!--동그란 체크박스-->
    <input type="color"/>  <!--색깔-->
    <textarea></textarea>  <!--여러문장-->
    <select name="name">
        <option value="디디">디디</option>
        <option value="달">달</option>
    </select>  <!--옵션제공, 선택하는거-->

    <!--로그인 폼 예시-->
    <form>
        <input type="email" placeholder="이메일" />
        <input type="password" placeholder="비밀번호" />
        <button type="submit">로그인</button>
    </form>
</body>
</html>
```