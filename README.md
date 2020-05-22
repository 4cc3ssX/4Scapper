# 4Scapper
This is a vulnerable scanner using python for LFI, RFI, RCE, SQLi, XSS. Thanks for using and feel free to report issues or bugs.

# Usage
```bash
 python3 4scapper.py
 ```
 Choice a number for vulnerable type.  
 Give custom payload path or use default payload.  
 Give regex or search string that ur payload will output enter if use default.  
 Give target only single support for scanning replace !! where ur payload will gonna replace.
 If METHOD is post your post data would be needed for request to server so write in json format. Example :  
 ```html
 <form action="#" method="get">
  <input type="hidden" name="token" value="1234"/>
  <input type="text" name="username"/>
  <input type="password" name="password"/>
  <input type="submit" name="submit" value="Submit"/> 
 </form>
 ```
 So, look above code you have to convert like this :  
 ```json
 {"token":"1234","username":"admin'OR ''='","password":"fakepsw","submit":"Submit"}
 ```
 Note: you have to write in json format, set values and keys with double quote -> ```json
 "key":"value"
 ``` not single code.
 
 # Disclaimer
 I will not responsible for any misuses or scanning in unauthorized networks or computers. Use at your own risk.
 

