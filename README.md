![visitor badge](https://visitor-badge.glitch.me/badge?page_id=shreyaschavhan.oswe-awae-pre-preperation-plan-and-notes&left_text=Views)

`Notes/Plan for my own personal reference!`

# 𝐎𝐒𝐖𝐄/𝐀𝐖𝐀𝐄 𝐏𝐫𝐞-𝐏𝐫𝐞𝐩𝐞𝐫𝐚𝐭𝐢𝐨𝐧 𝐏𝐥𝐚𝐧 𝐚𝐧𝐝 𝐍𝐨𝐭𝐞𝐬

```
Started  : 16-09-2022
Expected : ?? Donno ??
```
```
Goal :
Make yourself familiar enough with all the concepts required to be able to tackle OSWE Course Material and exam
with ease and clear the examination with one single attempt (even if it's gonna be my first certification in the field of cyber sec)
```
<br>
<br>
<div align=center>
<img src=https://user-images.githubusercontent.com/68887544/190704087-2fdd74f2-f395-458a-9fea-52143561436b.png height=400px alt="Image Credits: https://alaa.blog/wp-content/uploads/2020/08/awae.png">
<br>
<p><code>Image Credits</code> <code> https://alaa.blog/wp-content/uploads/2020/08/awae.png</code></p>
</div>
<br>
<br>

## 𝐌𝐲 𝐨𝐰𝐧 𝐝𝐞𝐭𝐚𝐢𝐥𝐞𝐝 𝐧𝐨𝐭𝐞𝐬 𝐚𝐧𝐝 𝐩𝐫𝐚𝐜𝐭𝐢𝐜𝐞 𝐫𝐞𝐩𝐨𝐬𝐢𝐭𝐨𝐫𝐢𝐞𝐬

- [Linux Notes](https://github.com/shreyaschavhan/linux-commands-cheatsheet)
- [Bash Scripting Notes](https://github.com/shreyaschavhan/bash-scripting-cheatsheet/)
- [RegEx Notes](https://github.com/shreyaschavhan/regex-notes)
- [SQL Notes](https://github.com/shreyaschavhan/sql-cheatsheet)
- [AWAE Notes](https://github.com/shreyaschavhan/awae-notes)
  - `[^ Above Repo is private for obvious reasons. I don't wanna spoon feed anyone. Plus, why I kept it here? => For my own convenience.]`
- [Powershell Notes](https://github.com/shreyaschavhan/powershell-notes)
- [Python Notes](https://github.com/shreyaschavhan/python-for-awae)

## 𝐓𝐚𝐛𝐥𝐞 𝐨𝐟 𝐂𝐨𝐧𝐭𝐞𝐧𝐭

```
- Pre-requisites
- Tools and Methodologies
- ATutor Authentication Bypass and RCE
- ATutor LMS Type Juggling Vulnerability
- ManageEngine Applications Manager AMUserResourceSyncServlet SQL Injection RCE
- Bassmaster NodeJS Arbitrary JavaScript Injection Vulnerability
- DotNetNuke Cookie Deserialization RCE
- ERPNext Authentication Bypass and Server Side Template Injection
- openCRX Authentication Bypass and Remote Code Execution
- openITCOCKPIT XSS and OS Command Injection - Blackbox
- Concord Authentication Bypass to RCE
- Server Side Request Forgery
- Guacamole Lite Prototype Pollution
```


## 𝐏𝐫𝐞-𝐫𝐞𝐪𝐮𝐢𝐬𝐢𝐭𝐞𝐬

> - Comfort reading and writing at least one coding language.
>   - This course is not for you if you can't even write few lines of logic - sorry!
>   - Just in case you can or don't know if you can:
>     - [Practice/Test your skills here with whatever programming language you are familiar with.](https://www.codechef.com/practice?end_rating=999&group=all&hints=0&itm_campaign=practice&itm_medium=navmenu&limit=20&page=0&search=&sort_by=difficulty_rating&sort_order=asc&start_rating=0&tags=&topic=&video_editorial=0&wa_enabled=0)
>     - Or [here](https://www.hackerrank.com/)
> - Familiarity with Linux.
>   - [Linux Cheatsheet](https://github.com/shreyaschavhan/linux-commands-cheatsheet)
>   - Book : [The Linux Command Line](https://g.co/kgs/7gC3DZ)
>   - Practice:
>     - [OverTheWire Bandit](https://overthewire.org/wargames/bandit/)
>     - [cmdchallenge](https://cmdchallenge.com/)
> - Ability to write simple Python / Perl / PHP / Bash scripts.
>   - Bash Scripting:
>     - Practice:
>       - [Bash Scripting Practice on Hackerrank](https://www.hackerrank.com/domains/shell?filters%5Bstatus%5D%5B%5D=unsolved&filters%5Bstatus%5D%5B%5D=solved&filters%5Bsubdomains%5D%5B%5D=bash)
>       - https://www.learnshell.org/
>     - Book
>       - [Shell Scripting: How to Automate Command Line Tasks Using...](https://g.co/kgs/LW4kQy)
> - Experience with web proxies.
> - General understanding of web app attack vectors, theory, and practice.
>   - [The Web Application Hacker's Handbook](https://g.co/kgs/AdcrZt)

---

- Things that ain't mentioned in pre-requisites but is actually required
```
- SQL
- ReGex
```

---

- ReGex
  - Best Reources:
    - [Interactive Regex Tutorial](regexone.com)
    - [Best Youtube Tutorial Video](https://youtu.be/sa-TUpSx1JA)
    - [Learn Regex the easy way](https://github.com/ziishaned/learn-regex)
    - [Best Advice on the Internet](https://www.reddit.com/r/learnprogramming/comments/cduxuu/comment/etwj6hj/?utm_source=share&utm_medium=web2x&context=3)

  - Practice:
    - [Regex Golf](https://alf.nu/RegexGolf)
    - [regexcrossword.com](https://regexcrossword.com/)
    - [regex101.com](https://regex101.com/quiz/1)

```
Quick Notes:
```
```
MetaCharacters (Need to be escaped):
.[{()\^|?*+


For Example:
. - select everything
\. - matches literal dot

- You have to escape \ with \ i.e. \\
```

```
Matches characters
.  - Any Character Except New Line
\d - Digit (0-9)
\D - Not a Digit (0-9)
\w - Word Character (a-z, A-Z, 0-9, _)
\W - Not a Word character
\s - Whitespace (space, tab, newline)
\S - Not Whitespace (space, tab, newline)

```

```
Anchors - matches visible positions between characters
\b - Word Boundary
\B - Not a Word Boundary
^  - Beginning of a String
$  - End of a String
```
```
[]   - Matches Characters in brackets
[^ ] - Matches Characters NOT in bracket
|    - Either Or
( )  - Group
```
```
Quantifiers:
*      - 0 or More
+      - 1 or More
?      - 0 or One
{3}    - Exact Number
{3, 4} - Range of Numbers (Minimum, Maximum)
```

---


- SQL
  - https://sqlbolt.com/
  - https://www.hackerrank.com/domains/sql
  - https://leetcode.com/problemset/database/
  - Others
```
codewars
stratascratch
https://pgexercises.com/questions/basic/
https://app.sixweeksql.com/
https://mystery.knightlab.com/
https://schemaverse.com/
https://mode.com/sql-tutorial/
https://advancedsqlpuzzles.com/
https://www.w3schools.com/sql/exercise.asp
https://bipp.io/sql-tutorial
https://learnsql.com/
https://selectstarsql.com/
http://www.sql-ex.ru/
https://www.sqlservercentral.com/stairways
```   

---

## 𝐓𝐨𝐨𝐥𝐬 𝐚𝐧𝐝 𝐌𝐞𝐭𝐡𝐨𝐝𝐨𝐥𝐨𝐠𝐢𝐞𝐬

- Syllabus:
```
- Web Traffic Inspection
- Interacting with web listeners using python
- Source Code Recovery
==> .NET code
==> Java classes
- Source code analysis methodology
- Debugging
```

---

<table>
    <thead>
        <tr>
            <th>Tools</th>
            <th>Features</th>
        </tr>
    </thead>
    <tbody>
      <tr>
        <td><code>Burp Suite</code></td>
        <td>Web Proxy/Listener</td>
      </tr>
      <tr>
        <td><code>dnSpy</code></td>
        <td rowspan=3>.NET Code decompilers</td>
      </tr>
      <tr>
        <td><code>dotPeek</code></td>
      </tr>
      <tr>
        <td><code>ilSpy</code></td>
      </tr>
      <tr>
        <td><code>JD-GUI</code></td>
        <td>Java decompilers</td>
      </tr>
    </tbody>
</table>

Reference:
```
Best .NET Deompilers: https://www.reddit.com/r/REGames/comments/t6me91/what_best_c_decompiler_that_gives_you_working/
Best Java Classes Decompilers: https://www.reddit.com/r/java/comments/6gyprq/looking_for_a_java_decompiler/
```

---

- Vidoes:
  - Reversing .NET Applications with ILSpy: https://youtu.be/3xPL0vHGKLE
  - dotPeek - .NET decompiler and assembly browser: https://youtu.be/msJVDzrHS2g
  - How to Use dnSpy to Reverse Engineer Unity Games: https://youtu.be/jZnT__DphzE

---

### 𝑽𝒖𝒍𝒏𝒆𝒓𝒂𝒃𝒍𝒆 𝑽𝒆𝒓𝒔𝒊𝒐𝒏𝒔 𝒐𝒇 𝑨𝒑𝒑𝒍𝒊𝒄𝒂𝒕𝒊𝒐𝒏𝒔 𝒅𝒊𝒔𝒄𝒖𝒔𝒔𝒆𝒅 𝒊𝒏 𝒕𝒉𝒆 𝒄𝒐𝒖𝒓𝒔𝒆

Syllabus | Version
---|---
ATutor Authentication Bypass and RCE  | ATutor v2.2.1
ATutor LMS Type Juggling Vulnerability | ATutor v2.2.1
ManageEngine Applications Manager AMUserResourcesSyncServlet SQL Injection RCE | ManageEngine Application Manager v12900
Bassmaster NodeJS Arbitrary JavaScript Injection Vulnerability | Bassmaster v1.5.1
DotNetNuke Cookie Deserialization RCE | DNN v9.1.1
ERPNext Authentication Bypass and Server Side Template Injection | Probably ERPNext <= v12
openCRX Authentication Bypass and Remote Code Execution | Probably OpenCRX version <= 4.30 and 5.0-20200717
openITCOCKPIT XSS and OS Command Injection | Probably openITCOCKPIT < 3.7.3

Reference:
```
ATutor to DotNetNuke: https://github.com/timip/OSWE

ERPNext Authentication Bypass and Server Side Template Injection:

A lot of Google Search based on syllabus pdf +
https://erpnext.com/security/references
https://github.com/frappe/frappe/pull/8044
https://www.cvedetails.com/cve/CVE-2019-14965/
https://infosecwriteups.com/frapp%C3%A9-technologies-erpnext-server-side-template-injection-74e1c95ec872

OpenCRX Authentication Bypass and Remote Code Execution:
https://nvd.nist.gov/vuln/detail/CVE-2020-7378
https://www.rapid7.com/blog/post/2020/11/24/cve-2020-7378-opencrx-unverified-password-change/

openITCOCKPIT XSS and OS Command Injection:
https://openitcockpit.io/security/
https://openitcockpit.io/2020/2020/03/23/openitcockpit-3-7-3-released/
```

---

## 𝐀𝐓𝐮𝐭𝐨𝐫 𝐀𝐮𝐭𝐡𝐞𝐧𝐭𝐢𝐜𝐚𝐭𝐢𝐨𝐧 𝐁𝐲𝐩𝐚𝐬𝐬 𝐚𝐧𝐝 𝐑𝐂𝐄

- 𝑷𝒓𝒆-𝒓𝒆𝒒𝒖𝒊𝒔𝒊𝒕𝒆𝒔:
> - SQL Injection - Specifically Blind Boolean Based
>   - [My Notes](https://github.com/shreyaschavhan/advanced-sql-injection-for-awae)
> - File Upload Vulnerabilities
> - Reverse Shells


- 𝑰𝒏𝒔𝒕𝒂𝒍𝒍𝒂𝒕𝒊𝒐𝒏:
> - Download: https://sourceforge.net/projects/atutor/files/atutor_2_2_1/
> - (Worked for me on my local windows machine) XAMPP v3.2.2 : https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/

> ![image](https://user-images.githubusercontent.com/68887544/192209405-57cfec34-af22-4cc4-ae5f-7e2f520c39e0.png)

> - It's one of these versions:

> ![image](https://user-images.githubusercontent.com/68887544/192209794-3401186b-ecde-416d-9893-b5ef08af5bc8.png)

> - I don't exactly remember which one I installed even if I could see the date modified and compiled date.
> - Even installing this on my local machine was a great exercise for me personally.


- 𝑽𝒖𝒍𝒏𝒆𝒓𝒂𝒃𝒊𝒍𝒊𝒕𝒊𝒆𝒔:
> - https://www.cvedetails.com/cve/CVE-2016-2555/

- 𝑷𝒓𝒂𝒄𝒕𝒊𝒔𝒆:
> - https://www.cvedetails.com/vulnerability-list/vendor_id-7805/Atutor.html
```
I was thinking about something and an Idea popped up in my mind.
Idea:
What if we try finding each and every CVE metioned in the CVE list about an application on our own? Don't you think it would be a great practice exercise?
1. Install the vulnerable version of the application.
2. Deploy it
3. Refer the CVE details and try finding that vulnerability on our own.
Great idea isn't it?
```
