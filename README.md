# 1. C 소개

## 1.1 C 프로그램 소스

### 1.1.1 가장 간단한 C 프로그램: main에서 return 0하기 

1.1.1.1 코드 설명

<details>
  <summary> 1.1.1.1.1 문법: 함수 정의, 반환 문장 </summary>
<br>
  
1.1.1.1.1.1 함수 정의: int main() { 내용 }

1.1.1.1.1.2 반환 문장: return 0;

1.1.1.1.1.3 값: 0

</details>

<details>
  <summary> 1.1.1.1.2 단어: int, main, (, ), {, }, return, 0, ; </summary>
<br>

1.1.1.1.2.1 int

1.1.1.1.2.2 main

1.1.1.1.2.3 ( )

1.1.1.1.2.4 { }

1.1.1.1.2.5 return

1.1.1.1.2.6 0

1.1.1.1.2.7 ;

</details>

<details open>
  <summary> 1.1.1.1.3 전체 코드 </summary>
<br>

```c
int main() {
  return 0;
}
```

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

1.1.1.2.2.5 가능한 오류

1.1.1.2.2.6 생성된 파일들
  
</details>

### 1.1.2 친절한 C 프로그램: 주석 달기

1.1.2.1 코드 설명

<details>
  <summary> 1.1.2.1.1 문법: 주석 </summary>
<br>

1.1.2.1.1.1 주석: /*  */

</details> 

<details>
  <summary> 1.1.2.1.2 단어: /*, */ </summary>
<br>

1.1.2.1.2.1 /*

1.1.2.1.2.2 /*

</details> 

<details open>
  <summary> 1.1.2.1.3 전체 코드 </summary>
<br>

```c
/* 프로그램 시작점 */
int main() {
  return 0; /* 0을 반환한다 */
}
```  
</details> 

1.1.2.2 실습

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

<details>
  <summary> 1.1.2.2.2 코드 입력하기 </summary>
<br>

1.1.2.2.2.1 코드 입력하고 실행해보기

1.1.2.2.2.2 에러, 경고 메시지 확인하기

1.1.2.2.2.3 커밋 및 푸시하기

</details>

### 1.1.3 함수 두개로 구성된 C 프로그램: 함수 호출 해보기

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

1.1.3.2.1.1 브랜치 변경하기

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

</details>


#### 1.1.6 조금 더 복잡한 C 프로그램: printf 써보기

1.1.6.1 코드 설명

<details>
  <summary> 1.1.6.1.1 코드에서 쓰인 문법 </summary> 
<br>

1.1.6.1.1.1 #include <stdio.h>

1.1.6.1.1.2 printf("Hello, world!");
  
</details>

<details>
  <summary> 1.1.6.1.2 코드에서 쓰인 단어 </summary>
<br>

1.1.6.1.2.1 #include  

1.1.6.1.2.2 < >

1.1.6.1.2.3 stdio.h

1.1.6.1.2.4 printf

1.1.6.1.2.5 " "
  
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
  <summary> 1.1.6.2.2 코드 입력하고 실행하기 (내용 없음) </summary>
<br>

</details>

#### 1.2 컴퓨터 하드웨어와 어셈블리

1.2.1 하드웨어 설명

<details>
  <summary> 1.2.1.1 연산장치 </summary>
<br>

1.2.1.1.1 트랜지스터

1.2.1.1.2 버퍼

1.2.1.1.3 게이트

1.2.1.1.4 덧셈기

1.2.1.1.5 클락
  
</details>

<details>
  <summary> 1.2.1.2 기억장치 </summary>
<br>

1.2.1.2.1 레지스터

1.2.1.2.2 메모리

1.2.1.2.3 스택

</details>

1.2.2 어셈블리 설명

<details>
  <summary> 1.2.2.1 어셈블리 문장 종류 </summary>
<br>

1.2.2.1.1 연산

1.2.2.1.2 기억

1.2.2.1.3 코드 실행 제어

1.2.2.1.4 다른 코드 호출
  
</details>

<details>
  <summary> 1.2.2.2 return 0 프로그램의 어셈블리 </summary>
<br>

```
저장  레지스터A  0
종료
```
  
</details>

1.2.3 실습

<details>
  <summary> 1.2.3.1 return 0 프로그램 자세히 보기 </summary> 
<br> 

1.2.3.1.1 어셈블리 

1.2.3.1.2 메모리
  
</details>
