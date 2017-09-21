# Responsbile disclosure

DRAFT 1 - REQUEST FOR COMMENTS - WORK IN PROGRESS - CONSTRUCTIVE CRITICISM WELCOME

Responsbile disclosure is a computer security term. It describes how people can share reports about security issues. Examples are bug reports, intrusion risks, hacking warnings, etc.


## What is this responsbile disclosure document?

This document explains responsible disclosure in ways that may help people work together.

Document goals:

1. Help people who discover security issues, and want to report them, and want to be able to point here as a reference document. We welcome advice for how to improve this.

2. Help companies understand what they need to do for responsbile disclosure. If you're reading this because someone pointed you to it, and there's anything that you want to know more about, please let us know and we'll do our best to help.

3. Include example responsible disclosure policies in the repository folder.

We welcome pull requests, or GitHub issues, or email to security@joelparkerhenderson.com.


## What is responsible disclosure?

Responsible disclosure describes three steps when someone discovers a security issue (such as a software bug) and wants to report it to the producer (such as the company that makes the softare).

Steps:

1. The discoverer reports the issue privately in good faith to the producer. 

2. The producer tries to protect users in good faith and tries to address the issue.

3. After a given amount of time, then the security issue is made public. 


## What does the discoverer need to do?

1. Report the issue privately in good faith.

    * For example this is good: an email sent to the producer's security contact, such as "security@example.com".

    * For example these are bad: posting the report on a public blog, or alerting the media, or threats, or attempts to sell the security issue to hackers, etc.

    * Pro tip: the discoverer may choose to be anonymous; the producer may also choose to be anonymous.

2. If you want, continue to be aware of the issue. 

    * For example these are good: opening lines of communication, or providing followup information, or 

    * For example these are bad: forgetting about the issue. 

    * Pro tip: the discoverer may choose to help or not, and also may choose to be in communication or not, and also may choose to change the arrangement if circumstances change.

3. If you want, disclose the issue to others.

    * For example these are good: waiting the specified amount of time then going public, such as posting the relevant information to a security news site, or contacting relevant third-party security researchers, or announcing the issue on any public social site, etc.

    * For example these are bad: not disclosing the issue to others, unless you feel it would cause more than the comparable amount of risk to yourself or others.

    * Pro tip: if circumstances change, such as discovery of a higher risk or active exploit in the wild, then the discoverer may disclose the issue to others sooner.


## What does the producer need to do?

1. Respond within the timeline. 

    * If the discoverer does not specify a timeline, then use one business day, because this is industry standard and current industry best practice.

2. Respond via an authorized security contact and/or authorized security process.

    * For example this is good: a response from a security-specific email address, such as "security@example.com".

    * For example these are bad: a response from a general-purpose email address, such as "help@example.com", or from anyone who is not an authorized security professional.

3. Respond that the issue is recognized as a security report.

    * For example this is good: security-specific wording, such as "Our security team has received your reponsible disclosure report".

    * For example this is bad: general-purpose wording, such as "We appreciate your business", or pass-the-buck wording such as "We sent your email to another department".


## What do the discover and producer both need to do?

1. Understand that responsible disclosure describes a good faith process.

    * The #1 goal is good faith to help users protect themsevles from security risks.

    * The #2 goal is good faith to address the security issue.

    * The discoverer and/or producer may choose in good faith to involve other security people, such as contacting other relevant security researchers to help with the issue.

2. Understand that responsible disclosure does not create any obligation. 

    * The discoverer and/or producer may opt-out at any time, for any reason, with or without warning. It's courteous to keep all the relevant people informed and up to date, yet this isn't always possible, or practical, or desirable.

    * Responsible disclosure does not create any legal agreement. If the discoverer and the producer already have a legal agreement, then we suggest that everyone involved consult the appropriate lawyers; do not use this document as legal advice.

3. Understand that responsible disclosure aims to use good communication and aims to reject threats.

    * Responsible disclosure is best when everyone involved understands that the #1 goal is to help users protect themselves from security risks, and the #2 goal is to address the security issue.

    * Responsible disclosure rejects any kind of threat of retribution, intimidation, suspension, revocation, extortion, burden to follow up, or victim blaming.

4. Understand that responible disclosure may mean different things to different people.

    * The discoverer and producer may have different understanding of responsble disclosure. These understandings may not align with each other. Good faith includes everyone involved understanding this.

    * Some producers publish responsible disclosure policies. These can be helpful guidance. If a discoverer chooses to use a different kind of responsible disclosure, or has a different understanding of responsbility disclosure, this is absolutely fine. 


## Guidance

Guidance for responsible disclosure can come from many areas, such as ethics experts, legal advocates, the general public's reasonable expectations, etc.

If you are seeking guidance, then you may be interested in these three areas, all describe below.

  * Good Samaritan
  * Duty to rescue
  * Duty of care


### Good Samaritan

https://en.wikipedia.org/wiki/Good_Samaritan_law

Good Samaritan laws offer legal protection to people who give reasonable assistance to those who are, or who they believe to be, injured, ill, in peril, or otherwise incapacitated. The protection is intended to reduce bystanders' hesitation to assist, for fear of being sued or prosecuted. 



### Duty to rescue

https://en.wikipedia.org/wiki/Duty_to_rescue

A duty to rescue is a concept describing a circumstance in which a party can be held liable for failing to come to the rescue of another party in peril. A duty to rescue may have moral areas and/or legal areas. 



### Duty of care

https://en.wikipedia.org/wiki/Duty_of_care

A duty of care is obligation to a standard of reasonable care while performing any acts that could foreseeably harm others. A duty of care may have moral areas and/or legal areas. Some aspects to consider are: the foreseeability of the harm or injury, the possible magnitude of the potential harm or injury, the importance or social value of the activity engaged in by the defendant, the usefulness of the conduct to the defendant, the feasibility of alternative conduct, the costs and burdens associated with the alternative conduct, the relative usefulness of the alternative conduct, and the relative safety of the alternative conduct.


## Special cases

Our security teams have a seen a wide range of special cases. 

We describe them here to help people understand where there are a wide range of opinions on what may be OK and what may not be OK. We recommend that everyone involved communicate in good faith about these.


### Accessing other users' information

Example: you discover that a URL has your user id in it, and reveals a bug, and you believe you can edit the URL to change your user id to a different user id.

  * Is it OK for the discoverer to do this, such as with the sole goal of discovering if it's affecting other users too?

  * Is it more important to quickly understand the breadth of risk for all users, than it is to protect a couple of users whose information may already be visible to hackers?

  * Is it OK for the discoverer to do with as many users as you want?

  * Is it OK for the discoverer to try to contact users to let them know they are affected? Is it OK to offer suggestions for mitigation?


### Denial of service

Example: you discover a bug that accidentally suspends your account, such as triggering a password lock.

  * Is this considered a denial of service attack?


### Unsolicited email

Example: you try to report a security issue to people in the company who you think are relevant, and whom you discover by researching on LinkedIn, Facebook, etc., or by using naming conventions such as "webmaster@example.com" or "security@example.com".

  * Is this OK?

  * Is this considered unsolicited email? 

  * Is this considered unauthorized email?


### Excluded groups

Example: you're in an excluded group, such as being a minor, or on a santion list, or in a country on a sanction list.

  * Is it OK for you to do a report?

  * Is it OK to report anonymously?

  * Is it OK to deliberately change potentially-identifying information, such as to escape the excluded group, and with the goal to help the disclosure reach the right people?


### Third-party 

Example: you discover that a company's sofware has a bug involving a third-party, such as an integration with another piece of software or another website.

  * Is it OK for you to report all the information you find to both parties?

  * Is it necessary to do two different responsbile disclosures, such as one report to one company, and a different report to the third-party company, with the goal of limiting the information sent to each company?

  * Is it OK for the discover to put the companies in touch with each other?


### Disruptive software

Example: you are skilled enough to be able to write a virus that you believe is likely to help users protect themselves from the security risk, or identify if they are at risk, or to fix the security risk.

  * Is it OK?

  * Is it OK for the discover to point users to software like this, and/or to guides or tutorials that describe how to create this kind of software?


## Tracking

* Package: responsible_disclosure
* Version: 1.0.0-alpha
* Created: 2017-09-21
* Updated: 2017-09-21
* Contact: Joel Parker Henderson (http://joelparkerhenderson.com)
* License: GPL