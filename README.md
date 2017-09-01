# Channel.json
이 파일은 epg2xml(https://github.com/wonipapa/epg2xml)에서 사용하는 Channel 정보 파일이다.

## Channel.json
Channel.json 파일을 텍스트 편집기로 열어보면 각채널별 정보가 들어 있다.  
이중 "Enabled": 1로 되어 있는 부분을 "Enabled": 0으로 바꾸면 EPG정보를 가져오지 않는다.  
필요없는 채널정보를 가져오지 않게 하는 것으로 EPG 정보 수집시 시간을 단축할 수 있다.  
삭제된 채널등으로 인해서 오류 발생시에도 "Enabled": 0으로 변경하면 오류 발생을 차단할 수 있다. 
Enabled 항목은 epg2xml 1.2.3 버전에서는 없어질 예정이다.
현재 모든 채널이 "Enabled": 0로 설정되어 있다.
EPG 정보를 가져올 채널은 epg2xml.json의 MyChannel 항목에 등록하게 변경되었다

## 라이센스
BSD

## 변경사항
epg2xml에서 2017년 9월 1일 업데이트
