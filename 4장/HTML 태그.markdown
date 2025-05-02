
4-1장
<hn>제목</hn>
<h1>~<h6>

<p> 텍스트 단락

<br> 줄 변경

<blockquote> "" 인용문

<strong>굵게 강조할 테스트</strong> 주의사항 표시

<b>굵게 표시할 텍스트</b> 단순히 글자 굵게 표시

<em> 이탤릭체 강조 </em>
<i> 이탤릭체 표시 <i>
<cite> 저작물 제목 </cite>

<abbr>줄임말 표시
<code>소스코드 표시
<del>삭제된 텍스트 표시
<mark>하이라이트 표시
<small>글씨 작게 표시
<sub>아래첨자
<sup>위첨자

-------------
4-2장
<ol> 순서 있는 목록
    <li>항목1<li>
    <li>항목2<li>
</ol>

<ul> 순서 없는 목록
    <li>항목1</li>
    <li>항목2</li>
</ul>

<dl> 설명 목록
    <dt>이름</dt>
    <dd>값</dd>
</dl>

------------
4-3장
행/열 = row/column

<table>
    <caption>표 제목</caption> - 생략가능
    <thead> - 제목
        <tr>
            <th>1행 1열</td> 제목행 굵게 강조
            <th>1행 2열</td>
        </tr>
    </thead>
    </tbody> - 본문
        <tr>
            <td>2행 1열</td>
            <td>2행 2열</td>
        </tr>
    </tbody>
</table>

행/열 합치기
<td rowspawn="합칠 셀의 개수">내용</td>
<td colspawn="합칠 셀의 개수">내용</td>

<colgroup> 특정 열에 스타일 속성 지정
    <col style="background-color:#eee;">
    <col>
    <col style="width:150px;">
    <col style="width:150px;">
</colgroup>

-----
4-4장

<img src="이미지 파일 경로" alt="대체 텍스트" width="50%">

<figure></figure> 도표,일러스트,이미지,소스 코드 등 독립된 콘텐츠 표현
<figcaption>내용</figcaption> 이미지에 태그 붙이기

<figure> 여러 이미지에 같은 설명 글 붙이기
    <img src=>
    <img src=>
    <img src=>
    <figcaption>예시</figcaption>
</figure>

<img src="기본 이미지" srcset="[small.png 700w, large.png 1000w, 파일3,..]">
이미지 코드를 여러개 지정하고 조건에 따라 다른 이미지 표시
w사용시 파일이름 너비 / x사용시 장치의 픽셀 비율

-----
4-5장
<object width="너비" height="높이" data="파일"><object>
오디오/비디오/PDF등 멀티미디어 파일 삽입

<embed src="파일 경로" width="너비" height="높이">
오디오,비디오,이미지등 파일 삽입
html이 <audio><video><object> 태그 지원을 안할시 사용

<audio src="오디오 파일 경로" controls width="700"></audio>
<video src="비디오 파일 경로" controls></video>

컨트롤 바 오디오/비디오 파일 삽입
종류 : controls/autoplay/loop/muted/preload/width,height/poster="파일 이름"(썸네일)

-----
4-6장
117 페이지



