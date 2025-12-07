
#### Description

There is some interesting information hidden around this site [http://mercury.picoctf.net:5080/](http://mercury.picoctf.net:5080/). Can you find it?

![[Pasted image 20251207001055.png]]

First part in the source code 
![[Pasted image 20251207001118.png]]

Second part in the mycss.css

![[Pasted image 20251207001143.png]]


Checking with Robots.txt we can see it is on apache server and revealed 3rd part 
![[Pasted image 20251207001657.png]]


Part 4 flag in .htaccess since it is running in apache we can check with hidden endpoint such as this .htaccess 
![[Pasted image 20251207002613.png]]


Looking into /DS_Store 
![[Pasted image 20251207002113.png]]



Final Flag : picoCTF{th4ts_4_l0t_0f_pl4c3s_2_lO0k_35844447}



