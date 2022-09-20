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


- [Bash Scripting Notes](https://github.com/shreyaschavhan/bash-scripting-cheatsheet/)
- [RegEx Notes](https://github.com/shreyaschavhan/regex-notes)
- [SQL Notes](https://github.com/shreyaschavhan/sql-cheatsheet)


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


## 𝐃𝐚𝐢𝐥𝐲 𝐋𝐨𝐠

```
16th to 18th Sept 2022: Log not maintained
```
```
19th Sept 2022 : 

- Studied https://youtu.be/sa-TUpSx1JA
- Took notes from the video
- Completed interactive tutorial from regexone.com
- Practiced a lil' bit of regex on RegEx Golf, RegEx Crossword, etc
```
