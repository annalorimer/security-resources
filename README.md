# Security Resources 

A list of stuff I've found useful over the course of me teaching myself All Of The Security Things. Constantly a work in progress.

[Not sure where to start?](#where-to-start)

i. [Android](#android)
 - [Vulnerable Android Apps](#vulnerable-android-apps)
 
ii. [ARM](#arm)
 
iii. [Blog Posts](#blog-posts)
 - [Getting Into Security](#getting-into-security)

iv. [C Code Review](#c-code-review)

v. [Course Notes](#course-notes)

vi. [Cryptography](#cryptography)

vii. [CTFs](#ctfs)

viii. [Law and Social Justice](#law-and-social-justice)

ix. [Podcasts](#podcasts)
 - [Notable Episodes](#notable-episodes)
 
x. [Reverse Engineering](#reverse-engineering)

xi. [Security Culture](#security-culture)
 
xii. [Things I've Heard Good Things About But Haven't Read/Listened To/etc](#things-ive-heard-good-things-about-but-havent-readlistened-toetc)

xiii. [Tools](#tools)
 - [Command Line](#command-line)

xiv. [Web Security](#web-security)

## Where To Start

Not gonna lie, I get this question a lot and I never have a good answer for it. So here's some general tips: 

* Start with what you're interested in. If you heard about an exploit, tool, concept, etc what peaked your interest, dive into that first.
  * Here are some places to start in case you're stuck: 
    - [Common Web Exploits](https://stackoverflow.com/questions/23102/what-common-web-exploits-should-i-know-about)
    - [Wikipedia page on Exploits](https://en.wikipedia.org/wiki/Category:Computer_security_exploits)
    - [Security Planner](https://securityplanner.org/#/)

<br>

* If you are reading a blog post, wiki page, book, paper, etc. and you come across something you've never heard of or don't understand, don't continue reading until you understand that thing. (Obviously, this won't work for everyone because everyone learns differently. One of my first year uni prof's gave me this advice and I've found it to be pretty effective.)

<br>

* Be prepared to not understand pretty much everything.
<br>

* Have a decent understanding of programming. If you've never done any sort of programming before, check out [Code Academy](https://www.codecademy.com/) — the Python track is a good place to start.

<br>

* Don't just read about it! Reading about security is all well and good, but coding exploits will solidify your understanding. Check out the [CTFs](#ctfs) section to get started.

<br>

* Get yourself a bookmarking tool such as [Pocket](https://getpocket.com/). There will be lots of things you'll want to save for later and you'll need a way to organize them. (Don't be like me and use Twitter likes as your bookmarking tool)
  * This is actually a good opportunity to check out [Security Planner](https://securityplanner.org/#/) to learn more about how to manage your online privacy!

## Android

[Android Hacker's Handbook](https://www.amazon.co.uk/Android-Hackers-Handbook-Joshua-Drake/dp/111860864X)
 - A little bit dated but the fundamentals are good
 
[Tutorialspoint Android Penetration Testing](https://www.tutorialspoint.com/android_penetration_testing/index.asp)
 - Covers basic architecture, security architecture, and walks through DIVA
 
### Vulnerable Android Apps

[DIVA](https://github.com/payatu/diva-android)
 - [Walkthrough](http://resources.infosecinstitute.com/cracking-damn-insecure-and-vulnerable-apps-diva-part-1/)

## ARM

[Very vulnerable ARM application](https://github.com/bkerler/exploit_me)

## Blog Posts

### Getting Into Security

[So, you want to work in Security? By Parisa Tabriz](https://medium.freecodecamp.org/so-you-want-to-work-in-security-bc6c10157d23)

[So you want to work in security (but are too lazy to read Parisa's excellent essay) by lcamtuf](https://lcamtuf.blogspot.co.uk/2016/08/so-you-want-to-work-in-security-but-are.html)

[So you want to work in security? (and for some reason ended up here rather than reading other people’s posts on the topic) by Ivan Fratric](https://ifsec.blogspot.co.uk/2018/02/so-you-want-to-work-in-security-and-for.html)

[So you want to be a security engineer? by Niru Ragupathy](https://medium.com/@niruragu/so-you-want-to-be-a-security-engineer-d8775976afb7)

## C Code Review

[CERN Computer Security: Common vulnerabilities guide for C programmers](https://security.web.cern.ch/security/recommendations/en/codetools/c.shtml)

[Smashing The Stack For Fun and Profit](http://www-inst.eecs.berkeley.edu/~cs161/fa08/papers/stack_smashing.pdf)

[Format String Vulnerabilities (Syracuse University)](http://www.cis.syr.edu/~wedu/Teaching/cis643/LectureNotes_New/Format_String.pdf)

[C Programming Language 2nd Edition](https://www.amazon.ca/Programming-Language-2nd-Brian-Kernighan/dp/0131103628/ref=redir_mobile_desktop?_encoding=UTF8&keywords=programming%20c&pi=AC_SX236_SY340_FMwebp_QL65&qid=1517593017&ref_=mp_s_a_1_2&sr=8-2
)

[OWASP Buffer Overruns and Overflows Guide](https://www.owasp.org/index.php/Reviewing_Code_for_Buffer_Overruns_and_Overflows)

## Course Notes

[UWaterloo CrySP's CS458](https://crysp.uwaterloo.ca/courses/cs458/W18-material/home.shtml)

## Cryptography 

[A Stick Figure Guide To The Advanced Encryption Standard (AES)](http://www.moserware.com/2009/09/stick-figure-guide-to-advanced.html)

[Classical Cryptography](http://practicalcryptography.com/ciphers/classical-era/)

[Coursera Crypto I (taught by Dan Boneh)](https://www.coursera.org/learn/crypto)

[Cryptopals](https://cryptopals.com/)


## CTFs

[List of permanent CTFs](http://captf.com/practice-ctf/)

[CTFLearn]()

[Hack This Site]()

[Google Gruyere]()

## Law and Social Justice

[The Black Community Needs Encryption](https://motherboard.vice.com/en_us/article/3danqk/the-black-community-needs-encryption) by Adrianne Jeffries for Motherboard

[Encryption is a Human Rights Issue](https://www.eff.org/deeplinks/2016/03/amnesty-international-encryption-human-rights-issue) from the EFF


### CrySP Speaker Series on Privacy

[Lex Gill: Rearranging Power Through Law and Code: Deciphering the Canadian Encryption Debate](https://www.youtube.com/watch?v=atAx24J1pQE&t=255s)

## Podcasts

[Security Now](https://www.grc.com/securitynow.htm)
 - Good technical content but lacks an intersectional approach to societal implications imo

### Notable Episodes 

[Security Now #65: Why is Security So Difficult?](https://www.grc.com/sn/past/2006.htm)

[Security Now #311: Anatomy of a Security Mistake](https://www.grc.com/sn/past/2011.htm)

## Reverse Engineering

[Introduction to Firmware Reversing](https://www.youtube.com/watch?v=GIU4yJn2-2A&t=1s)

[Reverse Engineering Challenges](https://challenges.re/)

[2017 SIT RE Presentation by TobalJackson](https://github.com/TobalJackson/2017-SIT-RE-Presentation)
* Good intro to radare2 (with exercises and a video!)

## Security Culture

[Hackers (film)](https://en.wikipedia.org/wiki/Hackers_(film))

## Things I've Heard Good Things About But Haven't Read/Listened To/etc

[How To Become A Hacker](http://www.catb.org/esr/faqs/hacker-howto.html)

[The Tangled Web: A Guide To Securing Modern Web Applications](https://nostarch.com/tangledweb)

[Queer Privacy by Sarah Jamie Lewis](https://leanpub.com/queerprivacy)

## Tools

[Burp Suite](https://portswigger.net/burp)
 - The free community edition is fine
 
[hexdump](https://en.wikipedia.org/wiki/Hex_dump)

[Hex Fiend](http://ridiculousfish.com/hexfiend/)
 
[John The Ripper](http://www.openwall.com/john/)

[Wireshark](https://www.wireshark.org/)

### Command Line

[A Quick and Practical Reference for tcpdump](http://bencane.com/2014/10/13/quick-and-practical-reference-for-tcpdump/)

## Web Security 

[Google Gruyere](https://google-gruyere.appspot.com/)

[Hack This Site](www.hackthissite.org)

[Web Application Hacker's Handbook](https://www.amazon.ca/Web-Application-Hackers-Handbook-Exploiting/dp/1118026470)

[OWASP XSS Guide](https://www.owasp.org/index.php/Cross-site_Scripting_(XSS))

[OWASP SQL Injection Guide](https://www.owasp.org/index.php/SQL_Injection)

[OWASP Session Hijacking Guide](https://www.owasp.org/index.php/Session_hijacking_attack)

[OWASP Command Injection Guide](https://www.owasp.org/index.php/Command_Injection)

[OWASP Path Traversal Guide](https://www.owasp.org/index.php/Path_Traversal)
