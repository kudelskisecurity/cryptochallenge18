For this year's crypto challenge we have 3 stages, but it's on a server which is receiving a lot of empty UDP packets and it sometimes reboots without notice,
very strange, but IT tells us they are working on it ... Here is how you access the API to query the oracle, good luck!

All challenges can be queried on the API under `cryptochall.ks.kgc.io`. Any submitted characters not in `[a-zA-Z0-9 ]` will generate an error.

To solve the first 2 challenges, you must write a program that creates valid signatures, in order to send the `/win` endpoint the message specified in the `/flag` one. That signed message must be successfully verified by the verification service. Obviously, your program should not just copy a signature received from the signing service, and we've thus blacklisted the winning messages.

The 3rd and final challenge is won by decrypting the flag. 

Denial of Service and bypassing the API is prohibited and not part of the challenge. 

Prizes have to be claimed at our "Kudelski Bash" party held at the Foundation Room Lounge in Mandalay Bay, Tuesday August 7th between (6-9pm) before the Black Hat briefings. We have five Ledger Nano S hardware wallets along with approximately $100 USD in ETH for you to win. 

- The first 5 people to complete all 3 challenges will receive a prize. 

Can't complete all 3 challenges? That doesn't mean you shouldn't participate, in the event that there aren't 5 people able to complete all 3 challenges the remaining prizes will go to the first runners-up to complete 2 of the 3.   

The ranking is established on the time of your submission to the email address provided.  

Please include your code and scripts, as well as a (short) write-up explaining your attack. `You must submit a response after each one of the challenges is completed.` Please use the following subject lines for the email. 

* Challenge 1 Completed
* Challenge 2 Completed
* Challenge 3 Completed

Your submission can be sent to our email address `cryptochallenge@kudelskisecurity.com`. 

We recommend that you encrypt your message, using the following public key:

```
-----BEGIN PGP PUBLIC KEY BLOCK-----
mQENBFszjFEBCAC3xFJpb4/zJ9y0VxtKgkBcb0Qiow1xhLN+8dQNH08pUrULDjXu
9XNM/ejDFMEHHDMAYG4xnQB/tXaHjiX4+OeUKAp8IOhMQhgzRi/ceZWYEcSBVeTw
7juUoSuI1ixKLLSdrr+amNtHwpP1hCa7JgMWTf+Brq1PZ2f+5sJ8mSzeIpC9ak6k
t88QfNhXKBvEm5lmoT0jIn3np906M6t6b5rcTPtembEhGfHb9vmzKGvPM13IRhDy
w2S2wn1doPCYlNLJtlVw9Iidt8pQ5zJDpnXaxfnsc3zSjYbJvG5NIkLSXzbqavEK
TnG4OY2dor+nk9yuwMWQRv/18LkeydFabB0LABEBAAG0SEt1ZGVsc2tpIFNlY3Vy
aXR5IENyeXB0b2NoYWxsZW5nZSA8Y3J5cHRvY2hhbGxlbmdlQGt1ZGVsc2tpc2Vj
dXJpdHkuY29tPokBNwQTAQgAIQUCWzOMUQIbAwULCQgHAgYVCAkKCwIEFgIDAQIe
AQIXgAAKCRDZeM53RBdstmGaB/9kyTAo+D73xqUM2pjPPVEFida8s/EBhCJNf+sx
ITtvJe/SFCto4mJlFwUNeVJnppDi7iL50Xi+RUvJPjBzkWChBovyOcS9KnM6hBFK
Pz3BfooAOstxAc9N5wxK4VuKKJ5hcGwtdP0k/eefUDLdCE6kH06TygptF3j3hhpP
rRV3/xaFQGjChdJdnKwpO+86ME/qgBODWoMfXLUe37xsWW+zRIdaQjbRlNh+hu2m
KXzZuJ5kOg9Vj9i8yVddqiFiYcSLI0wnj3EGZ1eEJYX1lKpOibYR41Rk4I42mz6r
6NcQuM6zQr854r3YD/D0mM2Y7OT3I5R8svMkgb1RwFYux7d4uQENBFszjFEBCADa
R5wHUVOtzwzOoTp1X5dsvojnG6/9UIn+Z/+5tJFZkxLs0CkBMPtEjR//39n5jqRi
6/iTcVNE+5UvJKny8Z/U8EN1ClcmlDqtwSI+7uqdxvFaSyqUhHy5ihnhQC4W+n8/
eCVWI07t8nDjad4Fd+rhdcSw8CW2FZkhxAA4iiL38MTzaydIhvJzAix4x8AFh0vS
NPUaaRjJoTt+sb9COrCuOyHYncHZV3w20gTNCSIXHiEBVrWIFwCYoaMZThUbz5f0
tMlS/lkXPIWc1CLFJs2ZbRAT6u840yV2dJ8zmHdQMC8kb3sRUKQfPkONayZAhIkx
j0adeaUgGzd/UeZfzW0HABEBAAGJAR8EGAEIAAkFAlszjFECGwwACgkQ2XjOd0QX
bLbnhAf8D2gQ+/SssNvWcxSqfojXSUlOour7vslgN8CLLBnavSJFfFNx43riQgSA
FRrY6m1Www0cS86wZrR2ireEbcXg3/vRB1SWiAFFsZ82JEYIHcan5eC9VXEuprG3
BSbpgIlY7s3UvmLBDPWNa366HPyJ2CkBqP9vIkJs0UJUddO8DHlh4X3YnuMRzmWY
6npFEhL9U/17LVuTFre4D9C8okWqupkWR1JrQ34IG3dxFMDzCJXOJqBlQdxXCVQE
n1U9gBH9JTBNZ0381wlyxTWl3Psr/zTh/8uLJHu/026gE4itixos7dapn3bHXWPS
EwSAbiCxuxDL77JNsRxVU/Bqe9pELA==
=8wY6
-----END PGP PUBLIC KEY BLOCK-----
``` 

## Hints
Throughout the competition we may drop some hints, so keep your eyes peeled for those.  

# Challenge 1

So, we have a implemented one of the latest well-documented signature algorithm to authenticate our messages. 
It's really cool and secure, you should try it!

We've setup an API to allow you to authenticate the messages you send us.

This challenge has four endpoints available on the API:
* `/chall1/sign` (POST) with one argument `data`
* `/chall1/verify` (POST) with two arguments `data` and `signature`
* `/chall1/win` (POST) sign the message returned by `/flag` to win
* `/chall1/flag` (GET) get the winning message to sign

# Challenge 2

Alright, our previous attempt had a flaw or maybe someone built a quantum computer to break it, we don't know. So we've decided to use post-quantum algorithms now. 
Attackers can't do anything now.

We've setup an API to allow you to authenticate the messages you send us.

This challenge has four endpoints available on the API:
* `/chall2/sign` (POST) with one argument `data`
* `/chall2/verify` (POST) with two arguments `data` and `signature`
* `/chall2/win` (POST) sign the message returned by `/flag` to win
* `/chall2/flag` (GET) get the winning message to sign

# Challenge 3

That's awful, asymmetric crypto is completely broken. All our attempts failed, so we resorted to the safest crypto of all time: symmetric crypto. AES128 should be fine for our needs and since the attacker doesn't know the key, they can't do anything!

We've setup an API to allow you to encrypt the messages you want to send us, that should work. But since we don't trust whitebox crypto, we cannot give you the binaries, sorry. It's just plain AES128, with 16bytes blocks, don't worry.

Ah, and to avoid having problems with these strange faults that occur randomly, we've added a nice countermeasure. This time we did our homework. We give you, the unbreakable.
  
This challenge has two endpoints available on the API:
* `/chall3/encrypt` (POST) with one argument `data`
* `/chall3/flag` (GET) get the encrypted flag

Note that in this case, the challenge is won by decrypting the flag. Good luck! 
