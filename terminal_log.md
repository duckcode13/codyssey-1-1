## 3-1. 터미널 명령어 로그
- 터미널을 이용한 깃허브 저장소와 vs code연결하기
- 터미널 기본 명령어 사용하기
~~~bash
#1. 깃허브 저장소 연결
git clone https://github.com/duckcode13/codyssey-1-1.git

#2. 현재 디렉토리 위치 확인
pwd
출력 -> /users/wooil/codyssey-1-1

#3. 목록 확인
ls -la
출력 -> total 0
dtwxr-xr-x 3 wooil staff  96 Aug 13 15:00 .
drwxr-xr-x 4 wooil staff 128 Aug 13 15:00 ..
-re-r--r-- 1 wooil staff   0 Aug 13 15:00 .gitignore

#4. 작업 디렉토리 생성 및 이동
mkdir -p ~/codyssey/practice
cd ~/codyssey/practice
pwd
출력 -> /users/wooil/codyssey/practice

#5. 테스트용 빈 파일 생성 및 내용 작성
touch testfile.txt
echo "Hello Codyssey" > testfile.txt
cat testfile.txt
출력 -> Hello Codyssey

#6. 파일 복사, 이름 변경, 삭제
ls -l testfile.txt
chmod 644 testfile.txt
ls -l testfile.txt

chmod 755 .
ls -ld .
~~~