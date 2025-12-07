
#### Description

We’re in the middle of an investigation. One of our persons of interest, ctf player, is believed to be hiding sensitive data inside a restricted web portal. We’ve uncovered the email address he uses to log in: `ctf-player@picoctf.org`. Unfortunately, we don’t know the password, and the usual guessing techniques haven’t worked. But something feels off... it’s almost like the developer left a secret way in. Can you figure it out?

Additional details will be available after launching your challenge instance.

![[Pasted image 20251128232439.png]]

After view the source code of the webpage we can see some encoded test in comments further decoding it with cyberchef.io 

![[Pasted image 20251128232451.png]]

![[Pasted image 20251128232509.png]]

we can see it suggests to add a header "X-Dev-Access: yes"
Adding and sending request with the given username ctf-player@..... the flag is revealed 
![[Screenshot 2025-11-28 234428.png]]





Final Flag : picoCTF{brut4_f0rc4_b3a957eb}