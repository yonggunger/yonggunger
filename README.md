# yonggunger

1. 회의실 예약 서비스를 만든다.
2. 프로세스
  달력에서 날짜를 선택한다 -> 
  해당 날짜의 회의실 리스트와 08:00~17:00 까지의 시간 테이블이 나온다. -> 
  이미 선택된 회의실/시간 은 회색으로 표시 -> 
  선택한 시간대는 파란색으로 표시 -> 
  시간대를 선택하고 예약 버튼을 누르면 팝업을 띄움 ->
  예약자명, 예약내용을 작성하고 확인을 누르면 서비스 호출 ->
  local DB(sqlite3) 에 데이터 저장한다.

3. 화이팅

### 하악하악 

실행법 : live-server ( https://github.com/tapio/live-server )

~~~
npm install
node index.js 
~~~

http://localhost:8181
