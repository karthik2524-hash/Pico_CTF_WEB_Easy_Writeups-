
#### Description

The factory is hiding things from all of its users.

Additional details will be available after launching your challenge instance.


![[Pasted image 20251207045547.png]]

Checking the requests made by the website using burpsuite reveals  something interesting which is a GET request to an /flag endpoint 
![[Pasted image 20251207045529.png]]

Using the repeater we can see there is check within the sending req which checks if admin = False 
![[Pasted image 20251207045618.png]]

Changing the value from False to True Admin = True 
![[Pasted image 20251207045643.png]]
Sending the request revealed the Flag 

![[Pasted image 20251207045658.png]]

Final Flag : picoCTF{th3_c0nsp1r4cy_l1v3s_4d184b0d}




