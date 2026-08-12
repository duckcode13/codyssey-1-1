## 3-1. 터미널 명령어 로그
- 터미널을 이용한 깃허브 저장소와 vs code연결하기
- 터미널 기본 명령어 사용하기
~~~bash
#1. 깃허브 저장소 연결
git clone https://github.com/duckcode13/codyssey-1-1.git
#2. 현재 디렉토리 위치 확인
pwd
#3. 목록 확인
ls -la
#4. 작업 디렉토리 생성 및 이동
mkdir -p ~/codyssey/practice
cd ~/codyssey/practice
#5. 테스트용 빈 파일 생성 및 내용 작성
touch testfile.txt
echo "Hello Codyssey" > testfile.txt
cat testfile.txt
#6. 권한 실습 (파일 및 디렉토리 권한 변경)
ls -l testfile.txt
chmod 644 testfile.txt
ls -l testfile.txt

chmod 755 .
ls -ld .
~~~