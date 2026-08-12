# codyssey-1-1

## 1. 프로젝트 개요
이 프로젝트는 터미널, git/gitHub, Docker, Orbstack를 활용하여 개발 워크스테이션 환경을 구축하고 Docker의 기본적인 사용방법을 익히는 것을 목표로 한다. 터미널을 이용한 파일 및 권한 관리부터 Docker 이미지와 컨테이너의 실행, Dockerfile을 이용한 웹서버 이미지 제작, 포트매핑, 바인드 마운트 및 볼륨을 직접 실습한다. 또한 git을 설정하고 git hub 및 VS Code와 연동하고 실습 과정과 결과를 README에 기록하여 재현 가능한 개발 환경을 구축하는 것을 목표로 한다. 

## 2. 실행 환경
- os: macOS 15.7.5
- CPU: Architecture: x86_64
- Terminal: VS code Integrated Terminal
- Shell: zsh
- git version: 2.54.0
- Docker 실행 환경: Orbstack
- Docker version: 28.5.2

## 2-1. 환경 명령어 로그
~~~bash
#1. OS
sw_vers
#2. CPU
uname -m
#3. shell
echo $SHELL
#4. git version
git --version
#5. Doker version
Docker --version
~~~


## 3. 수행 항목 체크리스트
- [x] 터미널 기본 조작 및 권한 관리
- [ ] Docker 설치 완료
- [o] Docker 정상 동작 확인

## 3-1. 터미널 명령어 로그
- 터미널을 이용한 깃허브 저장소와 vs code연결하기
~~~bash
#1. 깃허브 저장소 연결
git clone https://github.com/duckcode13/codyssey-1-1.git
~~~
