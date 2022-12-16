# <img src="./img/ywhlogo.png" alt="YWH Logo" width="40px" height="40px"> Vulnerable Code Snippets

![Vulnerable snippet banner YesWeHack Github repo](./img/VsnippetBanner.gif)

[YesWeHack](https://www.yeswehack.com/) present code snippets containing several different vulnerabilities to practice your code analysis. The code snippets are beginner friendly but suitable for all levels!

~ New **vulnerable code snippet** at Twitter [@yeswehack](https://twitter.com/yeswehack) **every Friday**! 🗒

---

⚠️ **Be aware**
> Be sure to run this in a secure environment, as the code is vulnerable and is intended to be used for learning code analysis!

## Twitter posts 🔖
A Collection of all vulnerable code snippets posted on our Twitter 📂    
📜[#1](https://twitter.com/yeswehack/status/1570757831468679169) - SQLi & XSS | Backslash filter collide  
📜[#2](https://twitter.com/yeswehack/status/1573303741310271490) - Improper file access & XSS | Invalid char and regex verificaion  
📜[#3](https://twitter.com/yeswehack/status/1575839882269818881) - Log Forging injection, Path traversal & Code injection | Poor filter and improper include() handling  
📜[#4](https://twitter.com/yeswehack/status/1578370258230194177) - XSS | Invalid user input filter   
📜[#5](https://twitter.com/yeswehack/status/1580911299382296576) - SSRF & Broken authorization | Trusted user input and client IP from header.  
📜[#6](https://twitter.com/yeswehack/status/1583445497687130114) - SSTI | Mixed input format  
📜[#7](https://twitter.com/yeswehack/status/1585979707522134017) - SQLi | Use of invalid variable within statement  
📜[#8](https://twitter.com/yeswehack/status/1588531516665171969) - CSRF | No CSRF token included  
📜[#9](https://twitter.com/yeswehack/status/1591068243439009798) - Open Redirect | Invalid regex handler  
📜[#10](https://twitter.com/yeswehack/status/1593604941897236485) - DOM XSS | Backend filter collide with client side JavaScript  
📜[#11](https://twitter.com/yeswehack/status/1596141663075926017) - CORS | Misconfigured Access-Control-Allow header  
📜[#12](https://twitter.com/yeswehack/status/1598678380072902660) - CSRF/ClickJacking | GET request CSRF with insecure delete process / ClickJacking - X-Frame-Options set in HTML meta tag.  
📜[#13](https://twitter.com/yeswehack/status/1601230194035105797) - Path Traversal/Unrestricted File Upload | Poor Path Traversal and file upload protection results in a code injection.  
📜[#14](https://twitter.com/yeswehack/status/1603751408678969347) - *censored* | *NEW*




## Vulnerabilities 💀
- [Broken access control](https://owasp.org/www-community/Broken_Access_Control) - CWE-284
- [Code injection](https://owasp.org/www-community/attacks/Code_Injection) - CWE-94
- [Cross Site Request Forgery (CSRF)](https://owasp.org/www-community/attacks/csrf) - CWE-352
- [SQL injection (SQLi)](https://owasp.org/www-community/attacks/SQL_Injection) - CWE-89
- [Cross Site Scripting (XSS)](https://owasp.org/www-community/attacks/xss/) - CWE-79
- [Open Redirect](https://cheatsheetseries.owasp.org/cheatsheets/Unvalidated_Redirects_and_Forwards_Cheat_Sheet.html) - CWE-601
- [Server-side template injection (SSTI)](https://owasp.org/www-project-web-security-testing-guide/v41/4-Web_Application_Security_Testing/07-Input_Validation_Testing/18-Testing_for_Server_Side_Template_Injection) - CWE-1336
- [Server Side Request Forgery (SSRF)](https://owasp.org/www-community/attacks/Server_Side_Request_Forgery) - CWE-918
- [Cross Origin Resource Sharing (CORS)](https://owasp.org/www-community/attacks/CORS_OriginHeaderScrutiny) - CWE-942
- [Clickjacking](https://owasp.org/www-community/attacks/Clickjacking) - CWE-1021  
- [Unrestricted File Upload](https://owasp.org/www-community/vulnerabilities/Unrestricted_File_Upload) - CWE-434
- [Path Traversal](https://owasp.org/www-community/attacks/Path_Traversal) - CWE-22  


## Programming Language 💻
- [PHP](https://www.php.net/)
- [Python](https://www.python.org/)
- [Golang](https://go.dev/)
- [JavaScript](https://www.javascript.com/)

__Also included__
- SQL ([MySQL](https://www.mysql.com/))
- HTML
- CSS

---

## Installation 🏁
This will create a new MySQL user and a database for the vulnerable code snippet to use.  
(*You should not move code snippets or any other file within repo*)

```bash
mkdir VsnippetYWH && cd VsnippetYWH;
git clone https://github.com/yeswehack/vulnerable-code-snippets.git
```

> ⚠️ Replace `'<USERNAME>'` `'<PASSWORD>'` `'<DATABASE>'` and remove the `#`. This will be your *new* MySQL vulnerable snippet **user**, **password** and **Database**!  
*Make sure your in the correct folder when running this commands.*  

```bash
sudo apt update;
sudo systemctl start mysql;
cd db/;
chmod +x setupVsnippet.sh;
./setupVsnippet.sh # '<USERNAME>' '<PASSWORD>' '<DATABASE>';
sudo systemctl restart mysql;
```

### Update 
Inside the vulnerable snippet *folder* use: (*Get newest snippets*)
```bash
git pull
```
  
For questions, help or if you have discovered a problem with the code. Contact us on Twitter: [@yeswehack](https://twitter.com/yeswehack) 📬
