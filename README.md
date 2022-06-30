소속: 국립안동대학교, 기계공학과
========================

1 여름 계절학기(공학커뮤니케이션)
--------------------------------------

# 1.1 인공지능 개론
## 2.1 Machine learning 
### 3.1 Deep Learning
#### 4.1 경사하강법
##### 5.1 선형회귀 

2 BlockQute
-----------------

> This is a first blockqute.

> > This is a second blockqute.

> > > This is a third blockqute

순서가 있는 목록(번호 사용)
1. 첫번째

2. 두번째

3. 세번째

순서가 없는 목록(글머리 기호 사용: *, +, - 사용)

* Blue
  * Green
    * Red

+ Blue
  + Green
    + Red

- Blue
  - Green
    - Red


2022/06/21(화) 누리호 발사 성공

                 세계에서 7번째 우주 강국

누리호 성공 축하!!!! 

2022/06/21(화) 누리호 발사 성공
세계에서 7번째 우주 강국
누리호 성공 축하!!!!

          e_tot=0
          o_tot=0
          for x in range(1,101):
                   if x % 2 == 0 : e_tot += x
                      else: o_tot += x

          print('1 - 100 까지 짝수 합 : {0}, 홀수 합 : {1}'.format(e_tot,o_tot))


Code Block Method 1 
 <pre><code> {code} </code></pre> 이용방법

<pre>
<code>
class Car {
  private String modelName;
  private int modelYear;
  private String color;
  private int maxSpeed;
  private int currentSpeed;
Car(String modelName, int modelYear, String color, int maxSpeed) {
  this.modelName = modelName;
  this.modelYear = modelYear;
  this.color = color;
  this.maxSpeed = maxSpeed;
  this.currentSpeed = 0;
}
}
</code>
</pre>


Code Block Method 2
    “ ‘ ‘ ‘ “ 이용방법

```
import React from 'react';
function MyComponent(props) {
 if (props.isBar) {
  return <div>Bar</div>;
}
  return <div>Foo</div>;
}
export default MyComponent;
```


Code Block Method 3

       코드블럭 시작점(" ''' ")에 사용하는 언어를 선언하여 문법 강조 가능

``` js
import React from 'react';
function MyComponent(props) {
 if (props.isBar) {
  return <div>Bar</div>;
}
  return <div>Foo</div>;
}
export default MyComponent;
```


#### Draw line

* * *
***
*****
- - -
---------------

#### link

// example

Google Link: [google][googlelink]

[googlelink]: https://google.co.uk "Let's Go Google"



#### 외부링크

// example

[Google](https://google.co.uk)

[Naver](https://www.naver.com "Let's Go Naver")

#### 자동링크

// examle

Google Homepage: https://google.co.uk 
Naver Homepage: <https://naver.com>


#### Ehphasis

// examle

이텔릭체 *별표(asterisks)* 혹은 _언더바(underscore)_ 를 사용

두껍게는 ** 별표(asterisks)* 혹은 __언더바(underscore)__ 를 사용

**_이텔릭체_ 와 두껍게** 를 같이 사용할 수 있음

취소선은 ~~물결표시(tilde)~~ 를 사용


#### Image

* examle 1

![Street](다운로드.jpg "Andong")

* examle 2

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"


#### Footnote

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2]. 

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces. 
  This allows you to have a footnote with multiple lines.
[^note]: Named footnotes will still render with numbers instead of the text but allow easier identification and linking. 
  This footnote also has been made with a different syntax using 4 spaces for new lines.



#### Table

// example 1

| 값 | 의미 | 기본값 |
|---|:---:|---:|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 | |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 | |
| `fixed` | 브라우저 창을 기준으로 배치 | |

// example 2

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
