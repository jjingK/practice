## css

- 선택자<sup>selector</sup>, 선언<sup>declaration</sup>으로 구분
- HTML 포함 방식
	- 외부 css 사용 
		<link rel="stylesheet" type="text/css" href="" >
	- 내부 css 사용
		<style></style>
	- 인라인 선언
- 선택자 종류

| 선택자 | 의미 | 예제 |
| --- | --- | --- |
| 범용 선택자 | 문서에 있는 모든 요소 | * [] |
| 타입 선택자 | 요소 이름 | h1, h2, h3 {} |
| 클래스 선택자 | class 속성 값 | .note {}  |
| 아이디 선택자 | id 속성 값 | #info {} |
| 자식 선택자 | 직계 자식 요소 | li > a {} |
| 자손 선택자 | 직계 포함 특성 요소 자손 | p a {} |
| 인접 선택자 | 바로 옆 요소 | h1 + p {}  |
| 일반 형제 선택자 | 형제 관계 요소 | h1 ~ p {} | 

※ 아래 두 선택자는 IE7 이상 지원

- 단계적 적용 방식
	- 후자 우선 원칙
	- 구체성
	- !important
- 상속<sup>inheritance</sup>
	- inherit: 부모의 요소를 상속함.
- css 버전 
	- 온라인 도구 
		- browsercam
		- browserlab.adobe.com
		- browsershots.org
		- crossbrowsertesting.com
	- 브라우저 별 오류 용어: 브라우저 변덕<sup>browser quirk</sup>, css 버그라 함.
		- 온라인 사이트 
			- http://quirksmode.org/css/selectors/
			- http://www.positioniseverything.net/
	
## color

- rgb: rgb(00, 100, 90)
- hex code: #ee3e80
- color name: DarkCyan
- CSS3 hsla: hsla(0, 0%, 78%, .5);

- 용어
	- 색조<sup>hue</sup> 
	- 채도<sup>saturation</sup>: 회색의 비율.즉, <b>색의 선명함</b> 채도가 높으면 색상이 선명, 채도가 낮으면 색상이 탁함
	- 명도<sup>brightness</sup>: 검은색의 비율. 즉, <b>색의 밝기</b> 명도가 높으면 색상이 밝음, 명도가 낮으면 색상이 어두움
	- 대비<sup>contrast</sup>: 전경색과 배경색의 대비를 통해 텍스트의 가독성을 높혀야 함. 짙은 배경에 밝은 색상의 텍스트를 사용할 경우 행간을 늘려 가독성을 높힘.
	- 투명도<sup>alpha</sup>: CSS3 속성, 투명도 
	
## text

- 서체
	- serif: 가는 장식선, 명조체, 가독성 높음
	- sans-serif: 장식이 없음, 고딕체, 작은 텍스트에 가독성이 높음 
	- monospace: 고정폭 폰트 동일한 너비 유지
	- non-monospace: monospace 반대용어 가변적 너비 
- 글자
	- baseline: 기준선
	- desender: 기준선 아래
	- ascender: cap height 위
	- cap height: 대문자의 윗부분까지 높이
	- x-height: 소문자 x의 높이
- 두께 
	- light
	- medium 
	- bold
	- bolder
- 스타일
	- normal
	- italic
	- oblique: 일반 폰트에서 기울임 (오블릭)
- 장평
	- condensed:narrow 
	- regular 
	- extended 
- 서체 우선 순위 지정<sup>font stack</sup>
- 브라우저 기본 글자 16px 
- 폰트 포맷 작성 순서 
	- eot
	- woff
	- ttf/otf
	- svg
- 
			
## 참고 

- [http://htmlandcssbook.com/code-samples/](http://htmlandcssbook.com/code-samples/)
