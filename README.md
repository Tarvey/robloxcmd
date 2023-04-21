# robloxcmd

Launch roblox from the cmd!

## How to use

### You will need:

Python (3.9+)

Insomnia

requests library for python

A browser (Firefox recommendedd)

### Steps:

1. Go to roblox.com and login 

2. Select a game

3. Open Devtools > requests

4. Click play

5. Look in the requests, look for /v1/authentication-ticket/

6. Copy as cURL (Posix)

7. In Insomnia, paste that cURL.

8. you will see in the headers tab, "Cookie" < Paste that into the python file at headers.Cookie

9. Go back in Insomnia, see X-CSRF-TOKEN, Copy that into the python file at headers.X-CSRF-TOKEN

10. 
