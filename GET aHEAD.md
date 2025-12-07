

#### Description

Find the flag being held on this server to get ahead of the competition [http://mercury.picoctf.net:45028/](http://mercury.picoctf.net:45028/)


![[Pasted image 20251207043106.png]]

Since the Chall name suggest GET a HEAD we simply intercepted the request using burp and changed the Req type from GET to HEAD and the flag is revealed 

![[Pasted image 20251207043122.png]]

Final Flag : picoCTF{r3j3ct_th3_du4l1ty_775f2530}
