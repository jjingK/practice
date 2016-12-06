## HTML의 진화 

- 1997 HTML4
- 2000 XHTML 1.0 
	- XHTML 1.0 종류
		- 엄격한<sup>strict</sup>
		- 과도기적<sup>Transitional</sup> 
		- 프레임셋<sup>Frameset</sup> 
- 2014 HTML5

- doctype 
	- HTML5 
		<!doctype html>
	- HTML4
		<!doctype html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
	- 과도기적 
		<!doctype html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
	- 엄격한
		<!doctype html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
	- XML 선언
		<?xml version="1.0" ?> 


## 이미지 포맷

- jpeg: 다양한 색상으로 구성된 경우
- gif, png: 몇가지 색상이거나 넓은 영역에 동일한 색상으로 구성된 경우

- bitmap: 웹에서 사용할 이미지 72ppi 해상도가 적합
- vector: 해상도랑 관련없음 svg 

- HTML5 이미지 태그 

`
<figure>
	<img src="" alt="이미지" />
	<figcaption>이미지에 대한 캡션을 연결 할 수 있다.(html5 spec)</figcaption>
</figure>
`
