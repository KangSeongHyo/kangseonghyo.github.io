# Jekyll

## 정의

- GitHub page에서 Liquid 언어를 기반으로 사이트를 만들어 주는 틀(정적 사이트 생성기)

  ***Note :*** Liquid는 Ruby로 만든 템플릿 언어

## 특징

- 마크다운으로 게시물 작성
- SNS 댓글 지원
- 파일형태를 글로 보여주는 형식

## 설치
#### 환경
- Window 10

### STEP 1 - Ruby 설치
- 윈도우용 Ruby+Devkit.msi 설치
- [https://rubyinstaller.org/downloads/](https://rubyinstaller.org/downloads/)

  ![이미지](/capture/K-001.png)

### STEP 2 - JeKyll 설치
- Ruby 실행 후 ``gem install jekyll bundler `` 입력

  ![이미지](/capture/K-002.png)

### STEP 3 - GitHub Page 로컬에서 실행
- git clone한 디렉토리로 이동
- ``chcp 65001`` 입력(인코딩)
- ``jekyll serve`` 입력(로컬서버 실행)

  ![이미지](/capture/K-003.png)

### STEP 4 - 결과
- ``localhost:4000`` 으로 접속

  ![이미지](/capture/K-004.png)
