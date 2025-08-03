####### PYTHON 음성 인식 스케줄러 개발 #######

✅ 1단계: 파이썬 설치

▶️ 파이썬 설치 여부 확인하기
Windows에서 cmd (명령 프롬프트) 열고 (intelliJ 내부 Terminal로 찾아도 됨)

명령어 
python --version

<img width="1110" height="341" alt="image" src="https://github.com/user-attachments/assets/ac743431-e532-4615-8cbd-31413b76d32a" />

✅ 2단계: 파이썬 설치 방법

📥 파이썬 다운로드
https://www.python.org/downloads/
→ 최신 버전(예: Python 3.12.x) 다운로드

설치할 때 꼭!! 아래 체크박스 체크:
✅ "Add Python to PATH" ** (환경변수 자동으로 잡아줌) 

그 다음 "Install Now" 클릭 후 설치

✅ 3단계: 다시 pip 확인하기
설치 끝나면 다시 cmd에서 아래 실행:

pip --version
(→ pip 23.x from ... 이렇게 나오면 성공!)
<img width="938" height="134" alt="image" src="https://github.com/user-attachments/assets/c5d957ee-109b-4eb1-a8a8-ceb778e9deb1" />

✅ 4단계: whisper 설치

pip install git+https://github.com/openai/whisper.git
pip install sounddevice
pip install scipy

까지 했는데... whisper는.. linux라 ㅠㅠ windows에서는 VM(가상머신)을 따로 파서, 거기서 linux에 깔아야된다고 한다.

✅ 5단계: powershell에서 관리자모드로 wsl Install
wsl --install
<img width="855" height="255" alt="image" src="https://github.com/user-attachments/assets/f59d41a4-33a6-4d22-a793-2ea8085e057d" />



