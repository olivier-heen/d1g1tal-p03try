# d1g1tal-p03try

## Base64
Here are terms that, once encoded in base64, mean something (in leet speak).  
``echo -n " :'OAw4CB81>mK~Xq' :5N.B,@+LLm" | base64``  
``echo -n 'h+bV+&!*hy4X' | base64``  

## Crypt
Here are password hashes that contain identifiable text parts:  
``$1$tarzan$bGSmOkedY3nxnPq66FVV51``    # This is a hash for "poetry" with salt "tarzan" and containing "SmOked".

## Sed
Here are somehow readable ``sed`` command and input:  
``sed sahara <<< photon``               # sahara turns photon into proton.  
``sed secrete <<< crop``                # secret crop top.  
``sed severe <<< visible``              # sever visible risible.  
These one also lead to command execution:  
``sed starlette <<< parles``            # One way to execute 'ps'.  
``sed stilette <<< piles``              # Yet antoher way to execute 'ps'.  
Poor man's command interpreter:  
``sed s#.*#\&#ew# #we#&/#*.#s des``     # Oh wait, is this also a palindrom?!  

## Catastrophic RegEx
``grep '\(.*\)\(.*\)\(\1\|\2*\)*'``     # Just launch and wait, no input needed.
``grep '\(\(stack\)*\)\(\(overflow\)*\)\(\1*\|\3*\)*'``            # Variant.
``for I in {0..63}; do (grep '\(.*\)\(.*\)\(\1\|\2*\)*' &) done``  # Burn CPU and RAM.

## Encoding
``$(ls -d)``                            # One way among many to get a "." when it is forbidden.  
``ping 127$(ls -d)1``                   # One example of using encoded "."  

## How to ping yourself?
<pre>
ping 127.1  
ping 0x7f.1  
ping 127.0.1  
ping 0177.0.1  
ping 127.0.0.1  
ping 2147483646  
ping 0x7f.066.42  
ping 017701770177  
ping 0177.0x0FF1CE  
ping 0177.0x7f.0777  
ping 0177.17.017.177  
ping 0x7F.127.0127001  
ping 0177.070.070.0177  
ping 0x7F.01000010.0xF7  
ping 0177.0177.0177.0177  
</pre>

## How to ping yourself with palindroms?
<pre>
ping 127.721  
ping 127.1.721  
ping 127.0x0.721  
ping 017710017710  
ping 0177.171.7710  
ping 0177.0110.7710  
</pre>
