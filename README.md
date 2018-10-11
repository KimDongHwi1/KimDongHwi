# KimDongHwi

1.제목(Heading)
문서를 작성할 때 가장 기본이 되는 제목은 HTML의 <h1>~<h6> 태그와 유사합니다. #의 개수에 따라 글자의 크기가 달라집니다. 
#은 <h1>, ###은 <h3> ######은 <h6> // #이 적을수록 글자 크기가 거대합니다.

# Heading
### Heading
###### Heading



2.인용(Blockquotes)
인용은 >를 넣어서 작성합니다.

> 인용문구 입니다.
>> 두번째 인용 문구 입니다.



3.리스트
3-1 순서 없는 목록
* 첫 번째//코드
    * 두 번째
      * 세 번째
      
●첫 번째//결과
    ○두 번째
      ■세 번째
첫 번째 기호는 속이 찬 원, 두 번째 기호는 속이 빈 원, 세 번째 이상부터는 속이 찬 사각형으로 표시된다. * 말고도 +, -와 같은 기호를 사용해도 된다.


3-2
순서가 있는 리스트(Ordered List)
1. HTML//코드
2. CSS
3. JavaScript

1.HTML//결과
2.CSS
3.JavaScript

1. HTML//코드
1. CSS
1. JavaScript

1.HTML//결과
2.CSS
3.JavaScript

1. Frontend//코드
    1. HTML
    2. CSS
    3. JavaScript
        1. Vue.js
2. Backend

1.Frontend//결과
    1. HTML
    2. CSS
    3. JavaScript
        1. Vue.js
2. Backend



코드블럭(Code blocks)
코드블럭은 일반 문장 사이에 단어, 짧은 문장 단위로 표현할 수 있는 방법과 여러줄의 코드를 삽입하는 방법이 있습니다.

단어, 한 줄의 코드를 감싸는 경우 `를 앞뒤로 감쌉니다.

마크다운은 코드블럭을 `<pre>`와 `<code>`로 감쌉니다.
마크다운은 코드블럭을 <pre>와 <code>로 감쌉니다.

여러줄의 코드를 나타내는 코드블럭의 경우 코드블럭의 시작과 끝을 ```으로 감싸고 내부에 코드를 작성하면 됩니다.

function square(n) {
  return n * n;
}




수평선(Horizontal Rules)
문단과 문단 사이를 나눌 때 등 사용되는 수평선은 HTML의 <hr />과 같이 동작합니다.

* * *
***
*****
- - -
---------------------------------------





링크(Links)
HTML의 하이퍼링크와 같은 링크는 다음과 같이 작성합니다. title은 생략이 가능합니다.

[example](http://example.com "title")

검색엔진은 [구글](https://www.google.com "구글")을 사용합니다.
example

검색엔진은 구글을 사용합니다.





강조(Emphasis)
HTML의 <em>과 같은 동작을 하는 강조는 *, _가 있고 <strong>은 **와 __를 사용합니다. 취소선은 ~~을 사용합니다.

*강조*한 텍스트
_강조_한 텍스트


**강조**한 텍스트
__강조__한 텍스트


~~취소~~한 텍스트






이미지 삽입(Images)
이미지는 역시 HTML의 <img>태그와 동일하게 작동합니다. 대체 택스트를 삽입할 수 있으며, 링크 또는 로컬의 이미지파일을 연결할 수 있습니다.

![대체 텍스트](/경로/example.jpg)
![대체 텍스트](링크)
![Github](./public/img/3/github.png)
Github

![Github](https://assets-cdn.github.com/images/modules/open_graph/github-octocat.png)
