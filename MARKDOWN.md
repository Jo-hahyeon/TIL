# MARKDOWN 문법(syntax)
![search pstatic](https://user-images.githubusercontent.com/121528432/209982749-5d7b5e7e-f68a-4fb2-b0c6-683957dcd367.jpg)


## 제목(Header)
`<h1>`부터 `<h6>`까지 제목을 표현할 수 있습니다.

![image](https://user-images.githubusercontent.com/121528432/209986951-a399eae3-aabb-43ad-9f23-3bc8fabec965.png)


제목1(h1)과 제목2(h2)는 다음과 같이 표현할 수 있습니다.

![image](https://user-images.githubusercontent.com/121528432/209987001-78421e4e-8ddf-462a-abd3-de66a9540874.png)

## 강조(Emphasis)

각각 `<em>`, `<strong>`, `<del>` 태그로 변환됩니다.

밑줄을 입력하고 싶다면 `<u></u>` 태그를 사용하세요.

![image](https://user-images.githubusercontent.com/121528432/209988865-955b8515-af67-4a07-b616-f310677c8ffd.png)

이텔릭체는 *별표(asterisks)* or _언더바(underscore)_ 를 사용하세요.

두껍게는 **별표(asterisks)** or __언더바(underscore)__ 를 사용하세요.

**_이텔릭체_ 와 두껍게**를 같이 사용할 수 있습니다.

취소선은 ~~물결표시(tilde)~~ 를 사용하세요.

밑줄은 `<u></u>`를 사용하세요.


## 목록(List)

`<ol>`, `<ul>` 목록 태그로 변환됩니다.

![image](https://user-images.githubusercontent.com/121528432/209990284-a8fef026-8f35-479d-ac9a-5443844ecd90.png)

1. 순서가 필요한 목록

2. 순서가 필요한 목록
    - 순서가 필요하지 않은 목록(서브)
    - 순서가 필요하지 않은 목록(서브)

3. 순서가 필요한 목록
    1. 순서가 필요하지 않은 목록(서브)
    2. 순서가 필요하지 않은 목록(서브)

4. 순서가 필요한 목록

* 순서가 필요하지 않은 목록에 사용 가능한 기호
  - 대쉬(hyphen)
  - 별표(asterisks)
  - 더하기(plus sign)


## 링크(Links)

`<a>`로 변환됩니다.

![image](https://user-images.githubusercontent.com/121528432/209991121-b53a6db4-62ee-4635-b447-2d3b94380d9e.png)

[GOOGLE](https://google.com)

[NAVER](https://naver.com "링크 설명(title)을 작성하세요.")

[상대적 참조](../users/login)

[Dribbble][Dribbble link]

[GitHub][1]

문서 안에서 [참조 링크]를 그대로 사용할 수도 있습니다.

다음과 같이 문서 내 일반 URL이나 꺾쇠 괄호(`< >`, Angle Brackets)안의 URL은 자동으로 링크를 사용합니다.

구글 홈페이지: https://google.com
네이버 홈페이지: https://naver.com

[Dribbble link]: https://dribbble.com
[1]: https://github.com
[참조 링크]: https://naver.com "네이버로 이동합니다!"

## 이미지(Images)

`<img>`로 변환됩니다.
링크과 비슷하지만 앞에 `!`가 붙습니다.

![image](https://user-images.githubusercontent.com/121528432/209991596-00e94b26-33dc-4872-a577-2cad0e4811fb.png)

## 이미지에 링크

마크다운 이미지 코드를 링크 코드로 묶어 줍니다.

![image](https://user-images.githubusercontent.com/121528432/209991705-b52f5e16-c692-458c-b0f6-345f94d46c02.png)

![vue](https://user-images.githubusercontent.com/121528432/209991738-03aaef74-c763-4b4e-a494-29448e37a72d.png)

## 코드(Code) 강조

`<pre>`, `<code>`로 변환됩니다.
숫자 1번 키 왼쪽에 있는 `` ` `` (Grave)를 입력하세요

## 인라인(inline) 코드 강조

![image](https://user-images.githubusercontent.com/121528432/209992053-bd4d6902-5bd5-4448-ab5b-dfa6ee6a6d74.png)

`background`혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

## 블록(block) 코드 강조

`` ` ``를 3번 이상 입력하고 코드 종류도 적습니다.

![image](https://user-images.githubusercontent.com/121528432/209992300-1178b1ec-ff87-4878-b6b4-afb9b75195ff.png)


## 표(Table)

`<table>` 태그로 변환됩니다.

헤더 셀을 구분할 때 3개 이상의 `-`(hyphen/dash) 기호가 필요합니다.

헤더 셀을 구분하면서 `:`(Colons) 기호로 셀(열/칸) 안에 내용을 정렬할 수 있습니다.

가장 좌측과 가장 우측에 있는 `|`(vertical bar) 기호는 생략 가능합니다.

![image](https://user-images.githubusercontent.com/121528432/209992616-dfc5878a-428d-496a-bdbb-dc6ff2d38b59.png)

값 | 의미 | 기본값
---|:---:|---:
`static` | 유형(기준) 없음 / 배치 불가능 | `static`
`relative` | 요소 **자신**을 기준으로 배치 |
`absolute` | 위치 상 **_부모_(조상)요소**를 기준으로 배치 |
`fixed` | **브라우저 창**을 기준으로 배치 |


## 인용문(BlockQuote)

`<blockquote>` 태그로 변환됩니다.

![image](https://user-images.githubusercontent.com/121528432/209992871-21282647-b38b-4922-83f6-5e1ebf7594dc.png)

인용문(blockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

BREAK!

> 인용문을 작성하세요 !
>> 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
>>> 중중첩된 인용문 1      
>>> 중중첩된 인용문 2      
>>> 중중첩된 인용문 3      

## 수평선(Horizontal Rule)

![image](https://user-images.githubusercontent.com/121528432/209993136-0de3f38f-9afd-4ee9-bef3-b874f53148bf.png)

---
(Hyphens)

***
(Asterisks)

___
(Underscores)

## 줄바꿈(Line Breaks)

![image](https://user-images.githubusercontent.com/121528432/209993310-e00ed02a-0d24-4b5e-ba4c-16c216a46aba.png)

동해물과 백두산이 마르고 닳도록       
하느님이 보우하사 우리나라 만세       
무궁화 삼천리 화려 강산<br>
대한 사람 대한으로 길이 보전하세

> 일반 줄바꿈이 동작하지 않는 환경(설정 및 버전에 따라)의 경우, ‘2번의 띄어쓰기’나 `<br>`를 활용할 수 있습니다.
