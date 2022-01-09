# Email-Bomber
Email-Bombing Python Script will send any number of emails on single email address using this Script. You can Also Add Attachment with email-bombing Script. This script work on both Windows and Linux Operating System. This script only works on Python3 version So, you must be Install Python3 Version.

## Requirement
You must be Install Python3 Version-<br/>
You can Download the Python3 from this link-
https://www.python.org/downloads/

### Allow less secure app
Before Run this Script Make Sure you have enable the Less Secure App Accees.<br/>
Link- https://myaccount.google.com/u/1/lesssecureapps
![alt text](https://github.com/av3sk77/Email-Bomber/blob/master/less-secure-app.png?raw=true)

## Before Run the Script
Create a text files which contain the Body part Like-

### body.txt
```bash
Hello Sir/Madam,

This is Python Script.
Which is Send Any Number Of Emails Using this Script.

Made By-
Aves Ahmed Khan

Thanks For Using this Script
```

## How To Work
### Help Menu
```bash
# python3 email-bomber.py -h

usage: email-bomber.py [-h] [--attach ATTACH] --name NAME --email EMAIL --sendto SENDTO --number NUMBER --subject SUBJECT --body BODY

optional arguments:
  -h, --help           show this help message and exit
  --attach ATTACH      Add Attachment [Ex. --attach "/root/Desktop/mail.csv"]

Required Arguments:
  --name NAME          Email Sender_Name [Ex. --name "firstname lastname"]
  --email EMAIL        Sender Email Address [Ex. --email sender@example.com]
  --sendto SENDTO      Send To Email Address [Ex. --sendto sendto@example.com]
  --number NUMBER      Number of times [Ex. --number 100]
  --subject SUBJECT    Subject Content [Ex. --subject "Enter Subject Here"]
  --body BODY          Body Content Location [Ex. --body "/root/Desktop/BodyContent.txt"]

```

### Usage
#### Send Email Without Attachment
```bash
# python3 email-bomber.py --name "Your Name" --email senderemail@example.com --sendto sendto@example.com --number 3 --subject "Email Subject Here" --body /root/Desktop/body.txt
```

#### Send Email With Attachment
```bash
# python3 email-bomber.py --name "Your Name" --email senderemail@example.com --sendto sendto@example.com --number 3 --subject "Email Subject Here" --body /root/Desktop/body.txt --attach /root/Desktop/mail.csv
```
