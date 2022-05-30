install docker-compact to visula studio
نصب جنگو باdocker-compact در ویژال استودیو 
پیش نیازها:

python 3.0
python3 3.0
visul studio code version==20
docker-compact version==19
==============================
مقدمه:
docker-compact فرآیند مدیریت کانترینهارا در داکر ساده تر می کند

برای نصب docker-compact از دستور زیر استفاده کنید:

$ mkdir -p ~/.docker/cli-plugins/ 
$ curl -SL https://github.com/docker/compose/releases/download/v2.3.3/docker-compose-linux-x86_64 -o ~/.docker/cli-plugins/docker-compose 

برای تأیید موفقیت آمیز بودن نصب، می توانید اجرا کنید:

$ docker compose version
خروجی مشابه این را خواهید دید:

         

          Output
         
Docker Compose version v2.3.3

