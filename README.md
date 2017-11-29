# Coordinated disclosure

<img src="README.png" alt="Security icon" width="96" height="118"/>

DRAFT 2 - REQUEST FOR COMMENTS - WORK IN PROGRESS - CONSTRUCTIVE CRITICISM WELCOME

Coordinated disclosure is a computer security term. It describes how people can share reports about security issues. Examples are bug reports, intrusion risks, hacking warnings, data leaks, website breaches, etc. 


## What is this document?

This document explains coordinated disclosure in ways that may help people work together.

Document goals:

1. Help people who discover security issues and want to report them.

2. Help companies' representatives understand responsbile disclosure needs, goals, practices, and special cases.

3. Include example coordinated disclosure policies in the repository folder.

We welcome pull requests, or GitHub issues, or email to security@joelparkerhenderson.com.


## What is coordinated disclosure?

Coordinated disclosure describes three steps when someone discovers a security issue (such as a software bug) and wants to report it to the producer (such as the company that makes the softare).

Steps:

1. The discoverer reports the issue privately in good faith to the producer. 

2. The producer tries to protect users in good faith and tries to address the issue.

3. After a given amount of time, then the security issue is made public. 


## What does the discoverer do?

1. Report the issue privately in good faith.

    * Typically good: an email sent to the producer's security contact, such as "security@example.com", with any relevant info, and any relevant questions.

    * Typically not good: posting the report on a public blog, or alerting the media, or threats, or attempts to sell the security issue to hackers, etc.

    * Tip: the discoverer may choose to be anonymous; the producer may also choose to be anonymous.

2. If you want, continue to be aware of the issue. 

    * Typically good: opening lines of communication, or providing followup information, or monitoring the situtation.

    * Typically not good: forgetting about the issue, 

    * Pro tip: the discoverer may choose to help or not, and also may choose to be in communication or not, and also may choose to change the arrangement if circumstances change.

3. If you want, disclose the issue to others.

    * Typically good: waiting the specified amount of time then going public, such as posting the relevant information to a security news site, or contacting relevant third-party security researchers, or announcing the issue on any public social site, etc.

    * Typically not good: not disclosing the issue to others, unless you feel it would cause more than the comparable amount of risk to yourself or others.

    * Tip: if circumstances change, such as discovery of a higher risk or active exploit in the wild, then the discoverer may disclose the issue to others sooner.


## What does the producer do?

1. Respond within the timeline. 

    * If the discoverer does not specify a timeline, then use one business day, because this is industry standard and current industry best practice.

    * If the discoverer asks questions, answer them. This is especially important if the discoverer asks for permission to test. Ensure all all answers are clear and direct.

2. Respond via an authorized security contact and/or authorized security process.

    * For example this is good: a response from a security-specific email address, such as "security@example.com".

    * For example these are bad: a response from a general-purpose email address, such as "help@example.com", or from anyone who is not an authorized security professional.

3. Respond that the issue is recognized as a security report.

    * Typically good: security-specific wording, such as "Our security team has received your reponsible disclosure report".

    * Typically not good: general-purpose wording, such as "We appreciate your business", or pass-the-buck wording such as "We sent your email to another department".


## What do the discover and producer both do?

1. Understand that coordinated disclosure describes a good faith process.

    * The #1 goal is good faith to help users protect themselves from security risks.

    * The #2 goal is good faith to address the security issue.

    * The discoverer and/or producer may choose in good faith to involve other security people, such as contacting other relevant security researchers to help with the issue.

2. Understand that coordinated disclosure does not create any obligation. 

    * The discoverer and/or producer may opt-out at any time, for any reason, with or without warning. It's courteous to keep all the relevant people informed and up to date, yet this isn't always possible, or practical, or desirable.

    * Coordinated disclosure does not create any legal agreement. If the discoverer and the producer already have a legal agreement, then we suggest that everyone involved consult the appropriate lawyers; do not use this document as legal advice.

3. Understand that coordinated disclosure aims to use good communication and aims to reject threats.

    * Coordinated disclosure is best when everyone involved understands that the #1 goal is to help users protect themselves from security risks, and the #2 goal is to address the security issue.

    * Coordinated disclosure rejects any kind of threat of retribution, intimidation, suspension, revocation, extortion, burden to follow up, or victim blaming.

4. Understand that coordinated disclosure may mean different things to different people.

    * The discoverer and producer may have different understanding of coordinated disclosure. These understandings may not align with each other. Good faith includes everyone involved understanding this.

    * Some producers publish coordinated disclosure policies. These can be helpful guidance. If a discoverer chooses to use a different kind of coordinated disclosure, or has a different understanding of responsbility disclosure, this is absolutely fine. 

5. Understand that typically the discoverer is doing a favor for the publisher.

    * Typically the discoverer does not need anyone's permission to publish vulnerabilities.

    * Typically the discoverer's information helps the publisher.


## Guidance

Guidance for coordinated disclosure can come from many areas, such as ethics experts, legal advocates, the general public's reasonable expectations, etc.

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


## Coordinated disclosure vs. responsible disclosure

Coordinated disclosure is the preferred term. 

  * The most important aspect is the coordination between discoverer and producer.

Responsible disclosure is a deprecated term.

  * People have different views of what it means to be responsible. For example, some people advocate that it is responsible for the discoverer to notify the public immediately regardless of any interaction with the producer, and irresponsible to do coordinated disclosure because it hides information from the public.


## Tracking

* Package: coordinated_disclosure
* Version: 2.1.1
* Created: 2017-09-21
* Updated: 2017-11-27
* Contact: Joel Parker Henderson (http://joelparkerhenderson.com)
* License: GPL
