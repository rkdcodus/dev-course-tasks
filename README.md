# 리드미 작성 및 마크다운 실습
리드미 작성을 위한 마크다운 실습입니다.   
강의 내용 외 [Github Docs 기본 서식 구문](https://docs.github.com/ko/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)를 참고했습니다.

## 리드미의 목적 
- 완성된 프로그램의 설명서
  - 프로그램의 사용 방법, 레퍼런스를 작성합니다.
- 구현 중인 프로젝트의 현황
  - 현재 프로젝트의 현황, 주요 기능, 해결해야하는 문제 등을 작성합니다.
 
## 마크다운

- 마크다운 (markdown)은 **웹에서 텍스트를 훨씬 가독성 있게 만들어주는 하나의 기술**입니다.
- **README.md**의 `.md` 확장자는 markdown을 뜻합니다. 
 
## 마크다운 실습

### 제목의 섹션 링크를 활용해 "목차" 만들기

1. [Header](#1-Header)
2. [텍스트 스타일 변경](#2-텍스트-스타일-변경)
3. [인용문](#3-인용문)
4. [목록](#4-목록)
5. [코드 블럭](#5-코드-블럭)
6. [수평선](#6-수평선)
7. [링크](#7-링크)
8. [줄바꿈](#8-줄바꿈)
9. [작업 목록](#9-작업-목록)

### 1. Header
`#`을 사용해 Header를 표현합니다. H1~H6까지 표현 가능합니다.

  # Header1
  ## Header2
  ### Header3
  #### Header4
  ##### Header5
  ###### Header6

<br />

### 2. 텍스트 스타일 변경 
**별 2개로 만든 굵게**, __언더바 2개로 만든 굵게__   
*별 1개로 만든 이탤릭체*, _언더바 2개로 만든 이탤릭체_   
~~취소선은 물결 2개로~~   
***별 3개로 하면 굵게와 기울임체 모두 적용***   
`<sub></sub>` 이용해서 텍스트<sub>아래첨자 가능</sub>   
`<sup></sup>` 이용해서 텍스트<sup>위첨자 가능</sup>   


<br />


### 3. 인용문


> 인용문은 줄바꿈이
> 되지 않는다
> - 목록 1
> - 목록 2

<br />

### 4. 목록
`-`, `*`, `+`을 사용해 순서가 지정되지 않은 목록을 만들 수 있다.   
- 목록1
- 목록2

### 5. 코드 블럭

공백 4칸으로 들여쓰기를 하면..

    이렇게 표현된다.
    들여쓰기가 계속되는 한 계속된다.
    대신 들여쓰기가 시작하는 문장의 바로 윗줄은 빈줄이여야한다.

백틱을 사용해 코드블럭을 만들 수도 있다. 
```
markdown usage
```
개인적으로 백틱 사용하는 것이 편하다. 

<br />

### 6. 수평선

- - - 
`- - -`을 사용해 수평선을 만들 수 있다.


<br />

### 7. 링크

`[Google로 이동하기](https://google.com)`을 사용하면 링크를 만들 수 있다. 이미지도 같은 방식을 사용한다.
=> [Google로 이동하기](https://google.com)

<br />

### 8. 줄바꿈

새로 알게 된 사실 줄바꿈을 하려면 끝에 띄어쓰기 3칸을 한다.(이 분장 뒤에 띄어쓰기가 되어있음)      
이렇게   
그렇지 않으면 줄바꿈이 되지 않는다.
줄바꿈 안됨. 

### 9. 작업 목록
```
- [ ] 작업 목록을 만들 수 있다.
- [x] x를 넣으면 체크가 된다.
```
- [ ] 작업 목록을 만들 수 있다.
- [x] x를 넣으면 체크가 된다.

