# SSH-And-Remote-server-
Setting up SSH server on linux and access remote server from windows using putty (a free, open-source terminal emulator and network file transfer application that allows users to connect to remote devices and computers) 

first you have to install SSH service on linux server 

$ sudo apt install service ssh 

Then you have to start the SSH service 

$ sudo apt service ssh start

$ sudo apt service ssh stop 


![Screenshot (36)](https://github.com/user-attachments/assets/d4fa7fa0-9711-4100-84e1-60e349a2d9da)

then you install the putty on linux and windows 
in linux 

$ sudo apt install putty

then install on windows
https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html


then you start ssh service  and enter the linux server ipaddress on putty in windows


![Screenshot (37)](https://github.com/user-attachments/assets/acf81fab-b5be-4911-8431-324183e84212)

then enter the credentials and access the remote linux server from windows 

![Screenshot (38)](https://github.com/user-attachments/assets/63477ff4-6718-432c-897d-0d0563cf5408)


