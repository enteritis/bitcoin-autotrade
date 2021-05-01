# 비트코인 자동화 투자

### Reference
* https://youtube.com/playlist?list=PLU9-uwewPMe3KKFMiIm41D5Nzx_fx2PUJ

### Ubuntu 서버 명령어
* 깃허브 코드 가져오기: git clone https://github.com/enteritis/bitcoin-autotrade.git
* 현재 경로 상세 출력: ls -al
* 경로 이동: cd bitcoin-autotrade
* vim 에디터로 파일 열기: vim BitcoinAutoTradeWithSlack.py
* vim 에디터 입력: i
* vim 에디터 저장 후 닫기: :wq!
* vim 에디터 닫기: :q!
* ubuntu 서버 한국 시간으로 설정: sudo ln -sf /usr/share/zoneinfo/Asia/Seoul/etc/localtime
* 패키지 목록 업데이트: sudo apt update
* pip3 설치: sudo apt install python3-pip
* pip3로 pyupbit 설치: pip3 install pyupbit
* 백그라운드 실행: nohup python3 BitcoinAutoTradeWithSlack.py > output.log &
* 실행되고 있는지 확인: ps ax | grep .py
* 프로세스 종료(PID는 ps ax | grep .py를 했을때 확인 가능): kill -9 PID
