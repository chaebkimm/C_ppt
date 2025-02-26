# 1. C 소개

## 1.1 C 프로그램 소스

### 1.1.1 main 함수와 return 

1.1.1.1 코드 설명

<details open>
  <summary> 1.1.1.1.1 전체 코드 </summary>
<br>

```c
int main() {
  return 0;
}
```

</details>

<details>
  <summary> 1.1.1.1.2 문법: 함수 정의, 반환 문장 </summary>
<br>
  
#### 1.1.1.1.2.1 함수 정의: `int main ( ) { 문장들 }`

C 프로그램은 함수라고 불리는 세부 코드들로 구성되어 있다.
함수는 다른 함수나 자기자신을 실행할 수 있다. 
프로그램 시작시 `main` 함수가 실행되며 `main` 함수에서 다른 함수들을 실행한다. 
함수는 입력값을 받게 설정할 수 있고, 출력값을 주게 설정할 수 있다. 

함수의 출력값 종류, 이름, 입력값과 실행할 내용을 정하는 것을 함수를 정의한다고 한다. 
함수를 정의하는 문법은 `값종류 이름 ( 입력값리스트 ) { 문장들 }`이다. 
앞의 코드에서 `값종류`는 `int`, `이름`은 `main`, `입력값리스트`는 공백, `문장들`은 `return 0;`이다.  

#### 1.1.1.1.2.2 반환 문장: `return 수식 ;`

문장은 함수를 구성하는 요소다. 
문장 중의 하나인 반환 문장은 함수의 출력값을 설정하고, 함수 실행을 종료한다. 
`return` 다음에 `;` 전까지 있는 `수식`을 계산한 결과가 함수의 출력값이 된다. 
앞의 코드에서 반환하는 `수식`은 `0`이다. 

#### 1.1.1.1.2.3 수식: `값`, `값 + 수식`, `함수실행`, 등등 

수식은 값, 값에 연산하기, 함수 실행하기, 메모리에 저장하기의 조합을 의미한다.

#### 1.1.1.1.2.4 값: `숫자값`, `문자열값`, 등등

값에는 앞의 코드에서 쓴 숫자값 뿐만 아니라 문자, 문자열 등도 있다. 

#### 1.1.1.1.2.5 숫자값: `0`, `1`, 등등

숫자값은 `0`, `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`를 붙여 써서 표시한다. 

</details>

<details>
  <summary> 1.1.1.1.3 단어: <code>int</code>, <code>main</code>, <code>(</code>, <code>)</code>, <code>{</code>, <code>}</code>, <code>return</code>, <code>0</code>, <code>;</code> </summary>
<br>

#### 1.1.1.1.3.1 `int`

`int`는 값의 종류 중 정수값을 의미하는 단어다. 

#### 1.1.1.1.3.2 `main`

`main` 함수는 프로그램 시작시 실행되는 함수다. 

#### 1.1.1.1.3.3 `( )`

함수 정의에서 함수이름 뒤에 있는 `( )`는 안에 입력값리스트를 쓸 수 있다. 

#### 1.1.1.1.3.4 `{ }`

함수 정의에서 `( )` 뒤에 있는 `{ }`는 안에 실행할 문장들을 쓸 수 있다. 

#### 1.1.1.1.3.5 `return`

`return`은 반환 문장을 나타내는데 쓰이는 단어다. 

#### 1.1.1.1.3.6 `0`

`0`은 숫자 값을 나타낸다. 

#### 1.1.1.1.3.7 `;`

`;`는 문장의 끝을 표시한다. 

</details>


1.1.1.2 실습 

<details>
  <summary> 1.1.1.2.1 Visual Studio 설치 </summary>
<br>

1.1.1.2.1.1 Visual Studio 다운로드

1.1.1.2.1.2 Visual Studio 설치 구성

1.1.1.2.1.3 Visual Studio 화면

</details>

<details>
  <summary> 1.1.1.2.2 프로젝트 만들기 </summary>
<br>

1.1.1.2.2.1 새 프로젝트

1.1.1.2.2.2 새 파일

1.1.1.2.2.3 코드 입력, 키보드 자판

1.1.1.2.2.4 실행

1.1.1.2.2.5 main이 없음 에러

1.1.1.2.2.6 괄호가 닫히지 않음 에러

1.1.1.2.2.7 생성된 파일들
  
</details>

### 1.1.2 주석

1.1.2.1 코드 설명

<details open>
  <summary> 1.1.2.1.1 전체 코드 </summary>
<br>

```c
/* 프로그램 시작점 */
int main() {
  return 0; /* 결과값을 0으로 함수 종료 */
}
```  
</details> 

<details>
  <summary> 1.1.2.1.2 문법: 주석 </summary>
<br>

#### 1.1.2.1.2.1 주석: `/* 주석 내용 */`

주석은 프로그램이 기계어로 번역될 때 제거되는 글이다. 
인간에게 프로그램 코드를 설명하기 위해 쓰인다.
`/*`부터 시작해서 `*/`가 나올 때까지 모든 글이 주석이 된다. 

</details> 

<details>
  <summary> 1.1.2.1.3 단어: /*, */ </summary>
<br>

#### 1.1.2.1.3.1 `/*`

주석의 시작을 의미하는 단어다. 

#### 1.1.2.1.3.2 `/*`

주석의 끝을 의미하는 단어다. 

</details> 

1.1.2.2 실습

<details>
  <summary> 1.1.2.2.2 코드 입력하기 </summary>
<br>

1.1.2.2.2.1 코드 입력하고 실행해보기

1.1.2.2.2.2 에러, 경고 메시지 확인하기

1.1.2.2.2.3 주석이 닫히지 않은 오류

1.1.2.2.2.4 괄호가 닫히지 않은 오류

1.1.2.2.2.5 커밋 및 푸시하기

</details>

### 1.1.3 함수 실행

1.1.3.1 코드 설명

<details>
  <summary> 1.1.3.1.1 문법: 함수 실행 </summary>
<br>

1.1.3.1.1.1 함수 실행: five()

</details> 

<details>
  <summary> 1.1.3.1.2 단어: 이름 </summary>
<br>

1.1.3.1.2.1 이름
  
</details> 

<details open>
  <summary> 1.1.3.1.3 전체 코드 </summary>
<br>

```c
/* 5를 반환한다 */
int five() {
  return 5;
}

/* five() 실행 결과를 반환한다 */
int main() {
  return five();
}
```  
</details> 

1.1.3.2 실습

<details>
  <summary> 1.1.3.2.1 GitHub 세팅하기 </summary>
<br>

1.1.3.2.1.1 이전 내용 저장하기

1.1.3.2.1.2 브랜치 변경하기

</details> 

<details>
  <summary> 1.1.3.2.2 코드 입력하기 </summary>
<br>

1.1.3.2.2.1 주의할 점

</details>

### 1.1.4 함수가 정의되기 전에 쓰는 C 프로그램: 함수 선언하기

1.1.4.1 코드 설명

<details>
  <summary> 1.1.4.1.1 문법: 함수 선언 </summary>
<br>

1.1.4.1.1.1 함수 선언: int five();

</details> 

<details>
  <summary> 1.1.4.1.2 새로운 단어 없음 </summary>
<br>

</details> 

<details open>
  <summary> 1.1.4.1.3 전체 코드 </summary>
<br>

```c
/* 5를 반환하는 함수 */
int five();

/* 5를 반환받아서 다시 반환한다 */
int main() {
  return five();
}

/* 5를 반환한다 */
int five() {
  return 5;
}
```
</details> 

1.1.4.2 실습

<details>
  <summary> 1.1.4.2.1 GitHub 세팅하기 (내용 없음) </summary>
<br>

</details> 

<details>
  <summary> 1.1.4.2.2 코드 입력하고 실행하기 </summary>
<br>

1.1.4.2.2.1 디버깅 기능으로 실행 순서 확인하기

1.1.4.2.2.2 함수가 선언되지 않은 오류

</details>


### 1.1.5 소스 파일이 분리된 C 프로그램: 소스 파일 추가하기

1.1.5.1 코드 설명

<details>
  <summary> 1.1.5.1.1 새로운 문법 없음 </summary>
<br>

</details> 

<details>
  <summary> 1.1.4.1.2 새로운 단어 없음 </summary>
<br>

</details> 

<details open>
  <summary> 1.1.4.1.3 전체 코드 </summary>
<br>

소스 파일 1
```c
/* 파일: five.c */

/* 5를 반환한다 */
int five() {
  return 5;
}
```

소스 파일 2
```c
/* 파일: main.c */

/* 5를 반환하는 함수 */
int five();

/* 5를 반환받아서 다시 반환한다 */
int main() {
  return five();
}
```

실행하는 방법
```
gcc five.c main.c -o ex1.1.3.exe
```
</details> 

1.1.5.2 실습

<details>
  <summary> 1.1.5.2.1 GitHub 세팅하기 (내용 없음) </summary>
<br>

</details> 

<details>
  <summary> 1.1.5.2.2 코드 입력하고 실행하기 </summary>
<br>

1.1.5.2.2.1 소스 파일 추가하기

1.1.5.2.2.2 함수 코드를 못찾는 오류

</details>


### 1.1.6 라이브러리를 쓰는 C 프로그램: printf 써보기

1.1.6.1 코드 설명

<details>
  <summary> 1.1.6.1.1 문법: 지시, 문자열, printf 함수 </summary> 
<br>

1.1.6.1.1.1 지시: #include <stdio.h>

1.1.6.1.1.2 문자열: "Hello, world!"

1.1.6.1.1.3 printf 함수: printf("Hello, world!");
  
</details>

<details>
  <summary> 1.1.6.1.2 단어: #, include, <, >, stdio.h, printf, " </summary>
<br>

1.1.6.1.2.1 지시어: #

1.1.6.1.2.1 include 지시어: #include  

1.1.6.1.2.2 라이브러리 폴더 의미: < >

1.1.6.1.2.3 표준입출력 라이브러리: stdio.h

1.1.6.1.2.4 출력 라이브러리 함수: printf

1.1.6.1.2.5 문자열: " "
  
</details> 

<details open>
  <summary> 1.1.6.1.3 전체 코드 </summary>

```c
#include <stdio.h>

/* 화면에 Hello, world!를 출력하는 프로그램 */
int main() {
  printf("Hello, world!");
}
```
</details>

1.1.6.2 실습

<details>
  <summary> 1.1.6.2.1 GitHub 세팅하기 (내용 없음) </summary>
<br>

</details> 

<details>
  <summary> 1.1.6.2.2 코드 입력하고 실행하기 </summary>
<br>

1.1.6.2.2.1 파일을 못찾는 오류

1.1.6.2.2.2 함수 코드를 못찾는 오류

</details>

## 1.2 기계어와 컴퓨터 하드웨어

### 1.2.1 C 소스 파일이 기계어로 번역되는 과정 

<details>
  <summary> 1.2.1.1 텍스트 전처리 </summary>
<br>

1.2.1.1.1 줄바꿈 처리

1.2.1.1.2 주석 처리

1.2.1.1.3 공백문자 처리

1.2.1.1.4 전처리 지시어 처리

1.2.1.1.5 특수문자 처리 

1.2.1.1.6 인접한 문자열 값 합치기

1.2.1.1.7 C언어의 단어들로 변경
  
</details>

<details>
  <summary> 1.2.1.2 기계어로 번역 </summary>
<br>

1.2.1.2.1 기계어

1.2.1.2.2 어셈블리

1.2.1.2.3 코드 생성
  
</details>

<details>
  <summary> 1.2.1.3 기계어 코드 모으기 </summary>
<br>

1.2.1.3.1 기계어 라이브러리에서 해당 코드 가져오기

1.2.1.3.2 기계어 코드 합치기
  
</details>

### 1.2.2 컴퓨터 하드웨어

<details>
  <summary> 1.2.2.1 연산장치 </summary>
<br>

1.2.2.1.1 트랜지스터

1.2.2.1.2 버퍼

1.2.2.1.3 게이트

1.2.2.1.4 덧셈기

1.2.2.1.5 클락
  
</details>

<details>
  <summary> 1.2.2.2 기억장치 </summary>
<br>

1.2.2.2.1 레지스터

1.2.2.2.2 메모리

1.2.2.2.3 스택

</details>

### 1.2.3 어셈블리 설명

<details>
  <summary> 1.2.3.1 어셈블리 문장 종류 </summary>
<br>

1.2.3.1.1 연산

1.2.3.1.2 기억

1.2.3.1.3 코드 실행 제어

1.2.3.1.4 다른 코드 호출
  
</details>

<details open>
  <summary> 1.2.3.2 return 0 프로그램의 어셈블리 </summary>
<br>

```assembly
main
1: 저장  저장소A  0
2: 반환
```
  
</details>

<details open>
  <summary> 1.2.3.3 return five() 프로그램의 어셈블리 </summary>
<br>

```assembly
main
1: 실행  3
2: 반환
five
3: 저장  저장소A  5  
4: 반환
```
  
</details>

### 1.2.4 실습

<details>
  <summary> 1.2.4.1 return 0 프로그램 자세히 보기 </summary> 
<br> 

1.2.4.1.1 어셈블리 

1.2.4.1.2 메모리
  
</details>

## 1.3 C의 역사

### 1.3.1 시대적 배경

<details>
  <summary> 1.3.1.1 컴퓨터 하드웨어 </summary> 
<br> 

1.3.1.1.1 진공관 

1.3.1.1.2 트랜지스터
  
</details>

<details>
  <summary> 1.3.1.2 컴퓨터 소프트웨어 </summary> 
<br> 

1.3.1.2.1 50, 60년대: FORTRAN, B

1.3.1.1.2 70년대: C, SQL

1.3.1.1.3 80년대: C++, MATLAB, Objective-C, LabVIEW

1.3.1.1.4 90년대: 파이썬, R, 자바, 자바스크립트 

1.3.1.1.5 21세기: Kotlin, Swift, Rust
  
</details>

### 1.3.2 공간적 배경

<details>
  <summary> 1.3.2.1 벨 연구소 </summary> 
<br> 

1.3.2.1.1 Unix 
  
</details>

## 1.4 알고리즘

### 1.4.1 계산기

<details open>
  <summary> 1.4.1.1 숫자 입력 받기 </summary> 
<br> 

한자리만 입력받을 때

```java
값: 정수

숫자n_버튼_함수 {
  값 = n
}

지우기_버튼_함수 {
  값 = 0
}
```

여러자리 입력받을 때
```java
값: 정수

숫자n_버튼_함수 {
  값 = 값 * 10 + n
}

지우기_버튼_함수 {
  값 = 값 / 10
}
```
  
</details>

<details>
  <summary> 1.1.2.2.1 GitHub 세팅하기 </summary>
<br>

1.1.2.2.1.1 Github 회원가입

1.1.2.2.1.2 수업 실습 템플릿 포크하기

1.1.2.2.1.3 Github Desktop 설치

1.1.2.2.1.4 포크한 리포지토리 클론하기

1.1.2.2.1.5 Visual Studio에서 열기

1.1.2.2.1.6 파일 변경 후 커밋하기

1.1.2.2.1.7 변경 내용 푸시하기

</details> 

### 1.4.2 그림 만들기

<details open>
  <summary> 1.4.2.1 그림 만들기 </summary> 
<br>

픽셀 하나 크기의 이미지 생성

```java
  픽셀만들기(0, 255, 0)
```

픽셀 여러개 이미지 생성  

```java
  픽셀추가(255, 0, 0)
  픽셀추가(0, 255, 0)
  픽셀추가(0, 0, 255)
  그림만들기(3, 1) // 가로 3, 세로 1 크기의 이미지 생성
```

</details>
