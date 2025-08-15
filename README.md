🛡 Project: Phishing Attack Investigation 

Introduction 

Phishing attacks are a prevalent cybersecurity threat where attackers deceive individuals into providing sensitive information by masquerading as a trustworthy entity. This project aims to equip you with the skills to identify, investigate, and respond to phishing attacks effectively.  

 Phishing Analysis Report 

1. Executive Summary 

On 26, November 2023 a suspicious email was received by phishing@pot appearing to originate from a user named Michelle. The email attempts to initiate a conversation under the pretense of personal connection and includes a call-to-action to view additional messages. This email exhibits clear phishing characteristics and is likely part of a larger social engineering or malicious campaign, potentially aimed at collecting personal information or delivering malware via follow-up interactions. 

    Tools  

    Thunderbird  

    Virustotal  

    MXToolBox.com 

    Ipinfo.io 

2. Email Overview 

Field 
	

Value 

From 
	

Likely spoofed, name shown as Michelle 

To 
	

phishing@pot 

Subject 
	

Laura - Michelle hat dir eine Nachricht geschickt ✉️ 

Date Received 
	

26-11-2023 

Language 
	

German 

Body Language 
	

Informal, flirtatious tone 

Links 
	

At least one (e.g., “Nachrichten anzeigen”, “click here to remove…”) 

Attachments 
	

None detected 

 

3. Email Body (Translated and Analyzed) 

Original Text (German): 

Hey phishing@pot, ich sehe, wir wohnen in der Nähe. Es wäre schön sich kennenzulernen 😄 

 Zwei weitere Nachrichten von Michelle in Ihrem Posteingang. 

 NACHRICHTEN ANZEIGEN 

 click here to remove yourself from our emails list 

English Translation: 

Hey phishing@pot, I see we live nearby. It would be nice to get to know each other 😄 

 Two more messages from Michelle in your inbox. 

 VIEW MESSAGES 

 click here to remove yourself from our emails list 

 

4. Indicators of Compromise (IOCs) 

IOC Type 
	

Indicator 
	

Description 

Link 
	

Nachrichten anzeigen (hyperlinked) 
	

Likely leads to a phishing or scam site 

Link 
	

click here to remove yourself... 
	

Often used in phishing to verify active inboxes 

Language 
	

Overly informal/flirtatious 
	

Typical of romance scams or clickbait 

Identity 
	

Spoofed sender name (Michelle) 
	

Attempt to create false trust 

Target 
	

Generic catch-all or organizational inbox (phishing@pot) 
	

Not a typical target for personal messages 

 

5. Threat Analysis 

    Phishing Intent: High – The email uses emotional/social engineering tactics to lure recipients into clicking links. 

    Potential Goals: 

    Harvesting credentials or personal information 

    Redirecting to malicious sites 

    Establishing contact for scam (e.g., romance scams, financial fraud) 

    Technical sophistication: Low – No attachments, simplistic message, no personalized targeting beyond the email alias. 

 

6. Recommendations 

    Do not click any links or interact with the message 

    Report and block the sender domain/IP (if traceable) 

    Add filters for similar subject lines or message structure 

    Review email security gateway rules for filtering such emails 

    If any user engaged with the email: 

    Run endpoint scan 

    Reset credentials 

    Monitor for suspicious activity 

 

 
