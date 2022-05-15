## react-ts 레포

<hr>
<br>

## 설명

### &nbsp; 타입스크립트와 함께 사용하는 리액트, 벨로버트 8장 강의를 개인적으로 실습한

### &nbsp; 소스 코드입니다.

<br><br><br>

## typescript 작업 환경 세팅하기

<br>

## 1. 프로젝트 초기화하기

```bash
  $ yarn init -y
```

이렇게 명령어를 입력하면 package.json 파일이 생성된다.

<br> <br>

## 2. 필요한 패키지 설치하기

### 생성된 프로젝트(폴더)내에서 다음과 같이 명령어를 입력한다.

```bash
$ yarn add typescript ts-node
```

<br>

### 패키지 설명

## ● typescript

### → 타입스크립트를 사용할 수 있게 해준다.

<br>

## ● ts-node

### → 콘솔로 타입스크립트로 작성한 파일을 컴파일 하지 않고 실행할 수 있게 해준다.

<br> <br>

## 3.프로젝트에 타입스크립트 설정(config)하기

```bash
$ yarn run tsc --init
```

◎ tsconfig.json를 직접 내 작성할 수 있지만 이 명령어를 입력하면 tsconfig.json 파일이 자동으로 생성된다.
