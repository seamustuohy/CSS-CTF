# CSS-CTF : Civil Society Security - Capture The Flag

## What will it look like?

- New CTF challenges will be released on a daily or semi-daily basis to CTF participants.
- These challenges will take the participants down an investigative or support story that leads them to collect "flags." Sending the flags to the organizers leads to the organizers starting the next part of the days puzzle for those participants. 
- CTF participants who need help will be able to go to a designated space to talk to someone who can help them learn skills they need.
- Trainings on specific topics that are more advanced may also be available. (examining email headers, etc.)
- At the end of [every day the first [X] number of people will be given a reward] or [the week every team who finished X number of challenges willbe given a reward.]
- Possibly a scoreboard of some kind?

## What do we want it to accomplish?

The outcome of the CSS-CTF should be an increase of critical information security skills among civil society members. That said, the goal of the CTF is for the players to learn and have fun! The point of a problem is to be solved, so most problems should be solved by any participant who takes a training and success would mean that every problem is solved by at least one team.


----

# Organizational Taks

## Initial Tasks

* Identify key skills we want civil society to learn
* Get organizers who are willing to take ownership over specific problems
* Get clear description of what it is, why it should be done, who is involved, and what resources it will need
* Get approval to do it from IFF organizers 
* Develop short step-by-steps for all problem topics
* Create any game artifacts that are needed on the internet (VirusTotal, Websites, etc.)
* Get any needed CTF management infrastructure in place

----

## Example Problem: Getting a person to send an email as an attachment

Team gets an email from a "civil society member" that says they think they received a phishing email and they want help. When the team responds that they will take a look the participant first sends a screenshot, unless a forwarded attachment is explicitly asked for they will then send the text of the email copy and pasted to the team. If they are asked to send as an attachment they will ask the team to explain to them how to do it. If the organizers think that the explanation is good enough they will send the email as an attachment. The flag will be found in the headers of the email.


## Problem Themes

- Incident Response Challenges
  - Getting a person (a CTF organizer) to send an email as an attachment
  - Setting up a secure channel to communicate with a user over
  - [Access folks?]
  - Write an effective report on social media (Could we get someone from Facebook, twitter, etc. to allow us to do this, give us the success/failure evaluations of some of the actual graders, and run a training there on writing effective reports).

- Forensic Challenges
  - Email Headers
  - Investigations based on an “Indicator of Compromise” // Identifying a malicious binary
    - Getting the hash of a file
    - Searching for indicators in virus-total (Have to get a member to add a flag to the comments?)
    - Running a Yara Rule
    - Use a free sandbox tool to examine a possibly malicious site
    - find that there are macros in a "malicious" word document

- OSINT Challenges
  - Use a proxy to check for censorship, etc. on the internet from a specific location (google play store, etc.)
  - Whois (is it still worth it?)


- Threat info sharing Challenges
  - Create an email alert with a google inbox search query that allows "other users" to find the "malicious attachment" from a phishing campaign
  - Write an alert/guidance email that provides an accurate understanding of a specific type of attack and correct guidance for how to address it. (Reaching out to experts in the community for help highly encouraged. Bonus points for including links/introductions to real support services in the space)


## Key Skills

- High value skills that no, to low, technically skilled civil society members could learn.
  - Ideally each skill could be learn-able in under 30 minutes
  - .

----

## Questions

**Do we add foils? How do we track them?**

    Most forensic challenges can be tied in with Incident Response and teach the learner to handle things with care - this means running files or being careless could lead to loss of (challenge) data or information essential to solve the challenge. For example, write-blockers are utilized by forensic experts as a way of ensuring the integrity of the data is kept true and valid if used in court. Ensure the challenge leads players on a journey, an investigation of sorts with multiple sources of data leading to the culmination of ultimately one solution. - [suggestions for running a ctf](https://github.com/pwning/docs/blob/master/suggestions-for-running-a-ctf.markdown)



----

![Attribution-ShareAlike 4.0 International](https://licensebuttons.net/l/by-sa/3.0/88x31.png "(CC BY-SA 4.0)")
Licensed under a [Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).

Except where otherwise noted, this content is published under a [CC BY-SA license](https://creativecommons.org/licenses/by-sa/4.0/), which means that you can copy, redistribute, remix, transform and build upon the content for any purpose even commercially as long as you give appropriate credit and provide a link to the license.

Recommended attribution:

> "Civil Society Security - Capture The Flag" by A group of security for civil society actors is licensed under CC BY SA 4.0. Available at
> https://github.com/seamustuohy/CSS-CTF/blob/master/README.md

*Civil Society Security - Capture The Flag has been created as a project of a group of security for civil society actors *

The content in this project are part of the commons; if you find broken links or any other errors  [you can help by reporting them as an issue](https://github.com/seamustuohy/CSS-CTF/issues).
