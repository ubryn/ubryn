<!--```python
#!/usr/bin/python
# file: ubryn_conn.py

import pwn

p = pwn.process("./ubryn")
resp = p.recv()
print(resp.decode())
p.close()
```-->
```bash
$ python3 ./ubryn_conn.py
[+] Starting local process './ubryn': pid 506

# Hello, I'm                                                                
#    _                  _               _    _        _          _          
#   /\_\               / /\            /\ \ /\ \     /\_\       /\ \     _  
#  / / /         _    / /  \          /  \ \\ \ \   / / /      /  \ \   /\_\
#  \ \ \__      /\_\ / / /\ \        / /\ \ \\ \ \_/ / /      / /\ \ \_/ / /
#   \ \___\    / / // / /\ \ \      / / /\ \_\\ \___/ /      / / /\ \___/ / 
#    \__  /   / / // / /\ \_\ \    / / /_/ / / \ \ \_/      / / /  \/____/  
#    / / /   / / // / /\ \ \___\  / / /__\/ /   \ \ \      / / /    / / /   
#   / / /   / / // / /  \ \ \__/ / / /_____/     \ \ \    / / /    / / /    
#  / / /___/ / // / /____\_\ \  / / /\ \ \        \ \ \  / / /    / / /     
# / / /____\/ // / /__________\/ / /  \ \ \        \ \_\/ / /    / / /      
# \/_________/ \/_____________/\/_/    \_\/         \/_/\/_/     \/_/      .
#                                                                           
# Are you ready to question everything you thought you knew?                

[*] Stopped process './ubryn' (pid 506)
```
