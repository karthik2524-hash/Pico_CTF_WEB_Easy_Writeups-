
#### Description

Additional details will be available after launching your challenge instance.

![[Pasted image 20251206231159.png]]
Intercepting the request with burpsuite we can see it is checking the opt 

![[Pasted image 20251206231505.png]]

![[Pasted image 20251206231519.png]]
since it is not configured properly it is not necessary to give OTP hence removing the field and sending the request revealed the flag 

![[Pasted image 20251206231828.png]]

Final Flag : picoCTF{#0TP_Bypvss_SuCc3$S_b3fa4f1a}

