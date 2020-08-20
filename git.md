## Git 기초

> GIt은 분산형 버전관리 시스템(DVCS)이다.

Git을 윈도우에서 활용하기 위해서는 (git bash)https://gitforwindows.org/를 설치해야 한다.

## 1. 저장소 초기화

```bash
$ git init
Initialized empty Git repository in /Users/mac/TIL/.git/

(master) $
```

* 로컬 저장소를 만들고 나면,  .git/ 폴더가 생성되고, bash에 (master) 라고 표기 된다.
* 반드시 저장소를 만들기 전에 원하는 디렉토리인지 확인하는 습관을 가지고, 저장소 내부에 저장소를 만들지는 말자.
  * 예) Desktop ->  git 저장소, TIL -> 다른 git 저장소(x)



## 2. add

작업한 내용을 커밋 대상 목록에 추가한다.

```bash
# 작업 후 상태
```

