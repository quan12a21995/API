# AP
mbell.vn/test/updateData.php?Date=2-10-2017&Time=02-05-40&Temperature=20.15&Radiant=30.15&UseName=Den&code=1321060356
mbell.vn/test/getListData.php

 
- GET DATETIME NOW: 
http://127.0.0.1/projects/PHP/test/updateData.php?dateTimeNow=d/m/Y-H:i:s
- USENAME 
Anh_1321060356
Den_1321060356			

- UPDATA
http://127.0.0.1/projects/PHP/test/updateData.php?Date=12-08-2017&Time=02-05-40&Temperature=20.15&Radiant=30.15&UseName=Den&code=1321060356
http://localhost/API/updateData.php?UseName=Den&code=1321060356&Data="U":"123.22","I":"5.5"&Model=Inventer
http://localhost/API/updateData.php?UseName=QUAN&code=1234567890&Data="U":"123.22","I":"5.5"&Model=Inventer

API WEBSERVER: 
- Admin: 
+ create User http://127.0.0.1/projects/PHP/demo3/index.php?UseName=admin&code=12345678&createUseName=QUAN&createcode=1234567890
http://localhost/API/index.php?UseName=admin&code=12345678&createUseName=VIP60S&createcode=1234567890&Model=Inventer
http://localhost/API/index.php?UseName=admin&code=12345678&createUseName=Tuyen&createcode=123&Model=QLNL&createlat=21.037606&createlong=105.769140

- User
+ isCheckLogin : http://127.0.0.1/projects/PHP/demo3/index.php?UseName=QUAN&code=1234567890&action=isCheckLogin
http://localhost/API/index.php?UseName=QUAN&code=1234567890&action=isCheckLogin&Model=Inventer
+ getYearOfUser: http://127.0.0.1/projects/PHP/demo3/index.php?UseName=QUAN&code=1234567890&action=getYearOfUser
http://localhost/API/index.php?UseName=QUAN&code=1234567890&action=getYearOfUser&Model=Inventer
+ getMonthOfYear: http://127.0.0.1/projects/PHP/demo3/index.php?UseName=QUAN&code=1234567890&Year=2017&action=getMonthOfYear
http://localhost/API/index.php?UseName=QUAN&code=1234567890&Year=2018&action=getMonthOfYear&Model=Inventer
+ getDayOfMonth : http://127.0.0.1/projects/PHP/demo3/index.php?UseName=QUAN&code=1234567890&Year=2017&Month=10&action=getDayOfMonth
http://localhost/API/index.php?UseName=QUAN&code=1234567890&Year=2018&Month=01&action=getDayOfMonth&Model=Inventer
+ getFileOfDay : http://127.0.0.1/projects/PHP/demo3/index.php?UseName=QUAN&code=1234567890&Year=2017&Month=10&Day=15&action=getFileOfDay
http://localhost/API/index.php?UseName=QUAN&code=1234567890&Year=2018&Month=01&Day=15&action=getFileOfDay&Model=Inventer
+ getDataOfFile : http://127.0.0.1/projects/PHP/demo3/index.php?UseName=Q&code=123&Year=2017&Month=10&Day=17&action=getDataOfFile
http://localhost/API/index.php?UseName=QUAN&code=1234567890&Year=2017&Month=01&Day=14&action=getDataOfFile&Model=Inventer
+ downloadDayOfMonth: http://127.0.0.1/projects/PHP/demo3/index.php?Day=29&Month=10&UseName=Q&Year=2017&action=downloadDayOfMonth&code=123
http://localhost/API/index.php?UseName=QUAN&code=1234567890&Year=2017&Month=01&Day=14&action=downloadDayOfMonth&Model=Inventer
+ downloadMonthOfYear: http://127.0.0.1/projects/PHP/demo3/index.php?Month=10&UseName=Q&Year=2017&action=downloadMonthOfYear&code=123
http://localhost/API/index.php?UseName=QUAN&code=1234567890&Year=2017&Month=01&action=downloadMonthOfYear&Model=Inventer
+ getInforAccount: http://127.0.0.1/projects/PHP/demo3/index.php?UseName=QUAN&code=1234567890&action=getInforAccount 
http://localhost/API/index.php?UseName=QUAN&code=1234567890&action=getInforAccount
+ getCurrentData: http://127.0.0.1/projects/API/index.php?UseName=QUAN&code=1234567890&Year=2017&Month=12&Day=13&action=getCurrentData
http://localhost/API/index.php?UseName=QUAN&code=1234567890&Year=2017&Month=12&Day=13&action=getCurrentData&Model=Inventer