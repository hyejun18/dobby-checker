# 도비 체커 dobby-checker
대학원 합격자 발표 여부 알리미

## Dependencies
제작자는 Google Colab에서만 test함.   
아마 알림음 때문에, 별도의 수정 없이는 Google Colab에서만 동작할 것으로 예상.   

## Usage
0. 변수 지정 부분에
+ 웹사이트 주소 (page_of_interest)
+ 게시글 목록이 있는 class 관련 정보 (list_prefix)
+ 알림음을 쓸 오디오 파일 (bell)
+ 웹사이트에 (프로그램이) 접속하여 확인할 시간 간격 (wait)
지정 후, 모든 코드 실행.   

## Trick for Google Colab
Google Colab은 사용자의 조작 없이 일정 시간이 지나면 런타임 연결이 끊김.   
이를 예방하기 위해, 아래의 블로그에서 trick을 배워옴.   
https://blog.naver.com/dsz08082/222019211109 (감사합니다. 넙죽)   

## Warning
프로그램이 혼자 멈추지 않음.   
사용자가 강제 종료하지 않으면, 계속해서 시끄러운 알람이 울릴 수 있음.

## 그래서 이 프로그램을 만든 사람은 어떻게 되었나요?
대학원에 합격하여 도비가 되었습니다~
