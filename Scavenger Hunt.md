
#### Description

There is some interesting information hidden around this site [http://mercury.picoctf.net:5080/](http://mercury.picoctf.net:5080/). Can you find it?

![](Pasted%20image%2020251207001055.png)

First part in the source code 
![](Pasted%20image%2020251207001118.png)

Second part in the mycss.css

![](Pasted%20image%2020251207001143.png)


Checking with Robots.txt we can see it is on apache server and revealed 3rd part 
![](Pasted%20image%2020251207001657.png)


Part 4 flag in .htaccess since it is running in apache we can check with hidden endpoint such as this .htaccess 
![](Pasted%20image%2020251207002613.png)


Looking into /DS_Store 
![](Pasted%20image%2020251207002113.png)



Final Flag : picoCTF{th4ts_4_l0t_0f_pl4c3s_2_lO0k_35844447}



