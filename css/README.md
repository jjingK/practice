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
	| ------| ----| ---- |
	| 범용 선택자 | 문서에 있는 모든 요소 | * [] |
	| 타입 선택자 | 요소 이름 | h1, h2, h3 {} |
	| 클래스 선택자 | class 속성 값 | .note {}  |
	| 아이디 선택자 | id 속성 값 | #info {} |
	| 자식 선택자 | 직계 자식 요소 | li > a {} |
	| 자손 선택자 | 직계 포함 특성 요소 자손 | p a {} |
	| 인접 선택자 | 바로 옆 요소 | h1 + p {} | *IE7+
	| 일반 형제 선택자 | 형제 관계 요소 | h1 ~ p {} | *IE7+
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
			
			
## 참고 

- [http://htmlandcssbook.com/code-samples/](http://htmlandcssbook.com/code-samples/)