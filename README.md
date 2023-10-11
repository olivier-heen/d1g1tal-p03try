# d1g1tal-p03try

## Base64
Here are terms that, once encoded in base64, mean something (in leet speak).  
``echo -n " :'OAw4CB81>mK~Xq' :5N.B,@+LLm" | base64``  
``echo -n 'h+bV+&!*hy4X' | base64``  

## Crypt
Here are password hashes that contain identifiable text parts  
``$1$tarzan$bGSmOkedY3nxnPq66FVV51``    # This is a hash for "poetry" with salt "tarzan" and containing "SmOked".

## Sed
Here are somehow readable ``sed`` command and input  
``sed sahara <<< photon``               # sahara turns photon into proton.  
``sed secrete <<< crop``                # secret crop top.  
``sed severe <<< visible``              # sever visible risible.  
These one also lead to command execution  
``sed starlette <<< parles``            # One way to execute 'ps'.  
``sed stilette <<< piles``              # Yet antoher way to execute 'ps'.  
Poor man's command interpreter  
``sed s#.*#\&#ew# #we#&/#*.#s des``     # Oh wait, is this also a palindrom?!  

## Encoding
``$(ls -d)``                            # One way among many to get a "." when it is forbidden.  
ping 127$(ls -d)1                       # One example of using encoded "."  
