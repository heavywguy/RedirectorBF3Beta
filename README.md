Credits to Aim4Kill (https://github.com/Aim4kill) for making the redirector and marcosmpg75 on discord for fixing the redirector.

# How To Use
You will need:
A Blaze server (you can use https://github.com/heavywguy/BlazeServer)
A DNS server, i used technitium dns server. (to redirect gosredirector.ea.com and gos.ea.com)

Edit config.json so the redirector knows the ip of the blaze server (use the local ip address of the computer if the server running the redirector is also running the blaze server)
Run BlazeRedirectorServer.exe
Run the Blaze server.
On the dns server, redirect these 2 domains: gosredirector.ea.com and gos.ea.com to the computers running the redirector and blaze (note: don't use 127.0.0.1 for this one, use ipconfig on the cmd and get the computer's local ip ex: 192.168.1.2)
for example:
gosredirector.ea.com -> 192.168.1.2
gos.ea.com -> 192.168.1.2 
To connect the ps3 to your dns server: get the local ip of the computer running the dns server and put in to the primary dns, secondary should be 1.1.1.1/8.8.8.8
Entering the BF3 Open Beta and entering multiplayer (while signed in) **should** put you into multiplayer.

# But how do i enter a game?
Install the Battlefield 3 Alpha-Beta AIO Repack v3 (https://drive.google.com/file/d/1IW-qG9-7T88Wu6Ykh0XsoP1gaGXGqP4S/view)
Password is nchardcore
go to the Bf3 open beta servers, edit config.ini so the game server knows which ip is the redirector, if everything goes well, the redirector will receive it and will redirected to the blaze server.

# additional info 
gosredirector.ea.com:
client port: 42127
gos.ea.com:
 blaze client: 42129
 game server: 25200
