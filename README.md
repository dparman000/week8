Time spent: **5** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQLI InJection

Vulnerability #2: Session Hijacking/Fixation


## Green

Vulnerability #1: Username Enumeration

Vulnerability #2: Cross Site Scripting


## Red

Vulnerability #1:Insecure Direct Object Reference

Vulnerability #2: Cross Site Request Forgery


## Details:
## Username Enumeration: Existence of Username can be determined on Green Target by monitoring
web response to login. 
If username exists it uses class failure. 
if username doesn't exist it uses class failed.
<img src="https://i.imgur.com/hX4vlvu.gifv" width="800">



## Insecure Direct Object Reference (IDOR):Salespersons can be viewed with id numberson Red Target.
By giving arbitrary number For example:id=10 user can see salesperson profile that is not public. 
<img src="https://i.imgur.com/j9BGp61.gifv" width="800">




## SQL Injection (SQLi):SQL query can be inputed in Blue Target.
On Salespersons profile url adress SQL query can be inputed.
For example:' OR 1=1 --'.
<img src="https://i.imgur.com/mGtVhYf.gifv" width="800">



## Cross-Site Scripting (XSS):On Green Target XSS can be submitted by Contact Us Form.
Script is trigered when logged in user goes to Feedback site.
<img src="https://i.imgur.com/Jdf2WEm.gifv" width="800">



## Cross-Site Request Forgery (CSRF):Red Target is vulnerable to CSRF.
If logged in user opens malicious web site, malicious web site can change data on Red Target Web site.
For example: Salespersons Firsname, Lastname, Phone Number,etc.
<img src="https://i.imgur.com/wjuAdpg.gifv" width="800">



## Session Hijacking/Fixation:Users Session can be hijacked on Blue Target.
Non priveleged user can hijack session and change its own session to priveleged user session id,
and preform all the operations desired.
<img src="https://i.imgur.com/cdighkM.gifv" width="800">



## Notes

Describe any challenges encountered while doing the work
