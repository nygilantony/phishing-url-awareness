──(kali㉿kali)-[~/phishing-url-awareness]
└─$ python3 phishing_checker.py
EWB Phishing URL Awareness Checker
Text checks only - this program does not open URLs.
Enter a sample URL to inspect: https://in.pinterest.com/

Result:
- No listed warning signs found. This does NOT prove safety.

Never enter passwords from unexpected links.
                                                                                                                                                             
┌──(kali㉿kali)-[~/phishing-url-awareness]
└─$ python3 phishing_checker.py
EWB Phishing URL Awareness Checker
Text checks only - this program does not open URLs.
Enter a sample URL to inspect: https://www.example.com/login

Result:
- No listed warning signs found. This does NOT prove safety.

Never enter passwords from unexpected links.
                                                                                                                                                             
┌──(kali㉿kali)-[~/phishing-url-awareness]
└─$ python3 phishing_checker.py
EWB Phishing URL Awareness Checker
Text checks only - this program does not open URLs.
Enter a sample URL to inspect: http://192.0.2.10/account

Result:
- Uses an IP address instead of a familiar domain.
- Uses HTTP. HTTPS alone does not prove trust.

Never enter passwords from unexpected links.
                                                                                                                                                             
┌──(kali㉿kali)-[~/phishing-url-awareness]
└─$ python3 phishing_checker.py
EWB Phishing URL Awareness Checker
Text checks only - this program does not open URLs.
Enter a sample URL to inspect: http://example.com@sample.invalid/login

Result:
- Contains an @ symbol; inspect carefully.
- Uses HTTP. HTTPS alone does not prove trust.

Never enter passwords from unexpected links.
                                                                                                                                                             
┌──(kali㉿kali)-[~/phishing-url-awareness]
└─$ python3 phishing_checker.py
EWB Phishing URL Awareness Checker
Text checks only - this program does not open URLs.
Enter a sample URL to inspect: https://a.b.c.d.e.example.invalid/path

Result:
- Contains many hostname segments/subdomains.

Never enter passwords from unexpected links.
                                                                                                                                                             
┌──(kali㉿kali)-[~/phishing-url-awareness]
└─$ python3 phishing_checker.py
EWB Phishing URL Awareness Checker
Text checks only - this program does not open URLs.
Enter a sample URL to inspect: https://xn--example.invalid/

Result:
- Contains a punycode-style hostname.

Never enter passwords from unexpected links.
                                                                                                                                                             
┌──(kali㉿kali)-[~/phishing-url-awareness]
└─$ 
