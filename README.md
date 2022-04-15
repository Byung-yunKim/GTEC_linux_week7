# GTEC_linux_week7

2022.04.15.fri

grep: 파일에 특정 패턴 문자열 찾기   
-> grep [옵션] [찾을 문자열] [대상 파일들]   

grep ubuntu test -> 문자열에 ubuntu가 들어가면 서치

grep -i ubuntu test -> 대문자까지 포함해서 문자열에 ubuntu가 들어가면 서치

grep -w ubuntu test -> 문자열이 ubuntu인 것을 서치

grep -n ubuntu test -> ubuntu가 들어간 문자열의 행 표시

grep -r ubuntu * -> ubuntu가 들어간 문자열이 있는 모든 파일 서치   
-> r옵션을 쓰지 않으면 전체 파일 서치 불가

grep [aef] ubuntu test -> 문자열에 a, e, f가 들어가는 문자열 서치

grep [a-d] ubuntu test -> 문자열에 a,b,c,d가 들어가는 문자열 서치

find: 파일명 검색   
-> find [찾을 위치] -name [찾을 파일명]

find . -name test -> 현재 디렉토리 안에서 test라는 이름의 파일명 서치

find / -name bash -> 모든 디렉토리에서 bash라는 이름의 파일명 서치

find /etc -name bash -> /etc 디렉토리에서 bash라는 이름의 파일명 서치

find /usr - name 'file*' | more -> 파일을 다 보여주지 않고 1페이지만 보이고 끊어서 보여줌   
-> 엔터 키 입력 시 한 개 파일을 출력, 스페이스바 입력 시 한 페이지 출력

ps: 프로세스 출력

ps -e -> 실행 중인 모든 프로세스 출력

ps -f -> 자세한 항목 추가

PPID -> 부모 아이디

sudo apt-get update   
sudo apt-get install apahce2   
sudo apache2 restart
