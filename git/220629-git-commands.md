# 2022. 06. 29 강의 리뷰

## 개념

- Shell : 운영체제의 kernel과 사용자를 이어주는 소프트웨어
- Kernel : 하드웨어와 응용프로그램을 이어주는 운영체제의 핵심 시스템소프트웨어
- Git : 버전관리시스템
- Github : 분산 버전관리툴인 git을 사용하는 프로젝트를 지원하는 웹호스팅 서비스

## Shell Command

```shell
$ pwd               현 위치 확인하기      # print working directory
$ cd ..             상위 디렉토리로 이동  # change directory
$ mkdir dev         프로젝트 디렉토리(dev) 생성
$ ls                폴더안의 리스트 확인
$ touch readme.md   파일(readme.md) 생성
$ mv readme.md bin  readme.md 를 bin으로 이동
$ rm -rf bin/       bin 폴더 삭제
$ rm readme.md      파일(readme.md) 삭제
$ vi readme.md      open interactive text editor
$ cat readme.md     파일 출력            # concatenate
$ cp readme.md      파일 복사
```

## Vim Command

```shell
 i     입력모드로 변경
:wq    입력 후 종료 # write and quit
```

##Process 
```shell
git status           상태 확인      # 빨간 readme.md 생김 (stage 에 올라가지 않음)
git add readme.md    stage에 올림
git status           상태 확인      # 초록 readme.md 생김 (stage 에 올라감)
git commit           추가 사항 작성 # docs-문서화작업  # feat-기능 개발 관련 # fix-오류 개선, 버그 패치 
git push origin main
```
