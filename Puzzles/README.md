**NOTE: Please feel free to contribute to and edit this document with your own ideas.**


# Possible Puzzle/Activity Ideas To Flesh Out

### find the reporting contact (hosting provider)

###  find the reporting contact (domain

###  indicator collection (URI)

###  indicator collection (IP)

###  indicator collection (avoiding false positives)
**instructions**: Look through a list of indicators for an incident and find the indicators that are producing false positives.

**Narrative Element**: Someone reaches out to you about some indicators they were sent (by you earlier or by someone else about the same incident) about the incident you are working on. "I'm seeing lots of examples of this incident! But, some of them can't be right. Can you help me figure out what could be going wrong?"

**possible false positive indicators**:
- domain of major free email provider (gmail, yahoo, hotmail, outlook, etc.)
- hash of 1x1 tracking pixel GIF/JPG/PNG

**References**
- [Typical false positive hashes](https://github.com/Neo23x0/ti-falsepositives)
- [misp-warninglist](https://github.com/MISP/misp-warninglists)
- [5 Tips to Create Quality Indicators](https://stixproject.github.io/documentation/concepts/creating-quality-indicators/)

### Send me the email. no not a screenshot. no send it as an attachment. NO NOT AN ATTACHED SCREENSHOT!
**instructions**: Work with a victim to get access to an emails content

**Narrative Element**:
### Indicator collection (EmailAddress)

### Indicators for the masses

**instructions**: Create an indicator that an end user can use to find if they were targeted by the malicious email.

**possible indicators**:
- gmail search string that properly limits to just the one email
- file search string that properly limits to the attachment


### Shortened Link to differentiate untargeted phishing from spear-phishing

**Instructions:** Use click analytics from a shortened link (bitly, googl, etc.) to identify that a "spear phishing" email you were shown

**The types of questions they should be asking**
• How long has the attack lasted for?
• What is the distribution of clicks for the attack, before and after the initial incident date?
• Are there indications of attacks resurfacing after the initial incident date?
• Which top referrers are referring click through traffic to the attack? (Both platforms and UI's in the case of email based phishing.)
• Which top countries are referring click through traffic to the attack?


**references**
- [Using URL Shorteners to Compare Phishing and Malware Attacks](https://docs.apwg.org/ecrimeresearch/2018/5351273.pdf)

### identifying possible email impersonation
**instructions**: Identify possible email address impersonation by looking at email headers

**Narrative Element**:


### Searching others investigations (URL)

**Instructions:** Search through public web scanners to see the results of other peoples scans of urls.


**:**


urlscan.io - Quickly get a screenshot and redirects (run by @heipi)
UrlQuery.net - Get screenshot, analyze for known risks, create public record (run by @urlquery)
phishcheck.me/search - Custom phishing detection engine
VirusTotal - Checks against multiple blacklists


### Searching others investigations (files)

**Instructions:** Search possibly malicious file through public malicious file sources to see the results of other peoples scans without scanning the file yourself.

VirusTotal - Checks against multiple blacklists
MISP instance? - Is this the IFF to attempt this? We should have public infrastructure first.


### Viper: This office document has a Macro
**instructions**: Use viper to see if a office document has macros in it

**Narrative Element**:


### Viper: This office document has linked files
**instructions**: Use viper to see if a office document is linking to external resources

**Narrative Element**:

### Viper: identifying possible email impersonation
**instructions**: Use viper to identify possible email address impersonation

**Narrative Element**:


### Viper: Urls in an email
**instructions**: Use viper to see the urls in an email

**Narrative Element**:

### Viper: getting attachements from emails
**instructions**: Use viper to get attachments from an email

**Narrative Element**:


### Viper: Yara Rules

**instructions**:

**Narrative Element**:

### Referrals to civil society rapid responders (AccessNow)

### Referrals to civil society rapid responders (CDR)

### Referrals to civil society investigators (EFF)

### Referrals to civil society investigators (Amnesty)

### Referrals to civil society investigators (CitizenLab)

### video verification with metadata

## reaching out to original content submitter(s) to track down raw files

## reaching out to original content submitter to get access to deleted footage


## ?Self Care Puzzle?
