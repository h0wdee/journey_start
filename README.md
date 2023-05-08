# Useful resources to help you start your hacker journery
Designing this workshop mostly to talk about Bug Bounty Hunting because it sounds flashy and cool,
and honestly kind of is. I also think back to when I was first getting into hacking, this seemed to 
be the most feasible way I could think of making money while having lots of freedom. Turns out there
were and are many other ways, but this way is still really cool.


## Intro
I remember when I was starting out and my head was swimming with questions.
I was fortunate enough to be introduced to a little binary exploitation in
an Operating Systems class in college, but I had little to no exposure at all
to other exploits / where to even look to learn. 

I found that reaching out to people on social media that were hacking things /
making things that I thought were cool was the best way to get my start on discovering
the specifics of my own interests, but there definitely were some "fundementals"
that I found really helpful.

---

#### Without going too in depth, I found the following to be really helpful (in no particular order):
- the ability to read code (you don't really have to know how to write code, just reading it is enough! However, 
you may find further down the line that you want to automate / build your own tooling, and programming will come in handy then).

- having a general understanding of how the internet works
	- Helpful project to learn this: make a website from scratch
		- boot a server via a service like linode, install nginx, and have it serve a basic http page. 
		- you can try hacking yourself!
	- I found just taking a look at a [packet encapsulation diagram](https://docs.oracle.com/cd/E19455-01/806-0916/ipov-32/index.html), and stepping through the TCP/IP stack to be really helpful

- having a general understanding of how operating systems work

*NOTE*: this all really depends on what you want to mess around with too, and what your specific interests are!

--- 

#### Where can I learn these things without breaking the law?
* Some helpful computer fundementals: [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/)

* [INE eJPT (Junior Penetration Tester) Course](https://my.ine.com/CyberSecurity/learning-paths/61f88d91-79ff-4d8f-af68-873883dbbd8c/penetration-testing-student)
	- ngl, never finished this, but this was SO helpful! I learned a lot from this.

* [Hack The Box (HTB)](https://app.hackthebox.com/starting-point)
	- has a bunch of intro challenges that walk you through common exploits against things like SMB, telnet, etc., etc.
	- also just a bunch of CTF (capture the flag), and different challenges to sharpen your hacking skills
		- I've definitely heard of people using there HTB experience on resumes

* [Try Hack Me](https://tryhackme.com/) 
	- similar to hackthebox! 
	- I honestly haven't used this one much, but I've heard great things!

* [Black Hat Python](https://nostarch.com/black-hat-python2E)
	- highly recommend any nostarch book btw.
	- they have a plethora of books on hacking stuffs.

* [Hacker101](https://www.hacker101.com/)
	- I didn't know about this until recently, but it's honestly pretty gr8.
	- They also have [there own set of CTFs](https://ctf.hacker101.com/), and [resources](https://www.hacker101.com/resources) to get you warmed up and into the world of Bug Bounty Hunting :]

* twitter / mastodon (infosec)
	- if you start following other infosec professionals / hackers on twitter and mastodon
	that alone will start leveling you up. many of them are constantly proliferating tooling,
	articles, and general knowledge on a daily basis. It's honestly a tidal wave of information
	and can be kind of exhausting.

##### Other Notable Resources (ongoing list)
* zines
	- some one's that I love / find inspriing:
		- [phrack](http://phrack.org/)
		- [tmpout](https://tmpout.sh/)

* other github repos
	- there are a lot of github repos where people will compile super helpful lists of resources (like this one except better)!
		- [here's one on bug bountying!](https://github.com/nahamsec/Resources-for-Beginner-Bug-Bounty-Hunters)


* blogs
	- there are just.... so many...

**OKEEEEE GLHF!** (=^ ◡ ^=)

##### General question answers:
* What is a vulnerability? What are common vulnerabilities?:
	- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
	- CVEs
		- [What is a CVE](https://cve.mitre.org/docs/cve-intro-handout.pdf)
		- [nvd](https://nvd.nist.gov/)
		- [cvetrends](https://cvetrends.com/)

#### Practice:
[XSS](https://xss.challenge.training.hacq.me/)
	- [preliminary reading](https://owasp.org/www-community/attacks/xss/)
