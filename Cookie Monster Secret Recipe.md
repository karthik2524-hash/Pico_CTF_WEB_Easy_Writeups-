
#### Description

Cookie Monster has hidden his top-secret cookie recipe somewhere on his website. As an aspiring cookie detective, your mission is to uncover this delectable secret. Can you outsmart Cookie Monster and find the hidden recipe?

Additional details will be available after launching your challenge instance.

![](Pasted%20image%2020251206211232.png)
Once the request is done we need to check the cookie section using Inspect option in Network tab 
since the challenge name suggests for cookies 

![](Pasted%20image%2020251206211303.png)

secret_recipe= cGljb0NURntjMDBrMWVfbTBuc3Rlcl9sMHZlc19jMDBraWVzXzc4QjRDMzkwfQ== which looks like base64 encoding and decoding it reveals the flag 

![](Pasted%20image%2020251206211410.png)

Final Flag : picoCTF{c00k1e_m0nster_l0ves_c00kies_78B4C390}


