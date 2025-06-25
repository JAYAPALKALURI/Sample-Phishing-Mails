# – Phishing Email Analysis

## 📧 Sample Email Overview:
- Subject: "Your Account is Suspended – Urgent Action Required"
- Claimed Sender: PayPal (support@paypaI.com)

## STEP 
There are so many mails available in online site like 
  >github - Phishing Email Corpus,PhishTank,OpenPhish,Kaggle.com........etc
here i created my own Fake_mails to identify them

1.[Open Script](https://github.com/JAYAPALKALURI/Sample-Phishing-Mails/blob/9224ed2329e6c9b78d4e2bb18cf61ddaa65b2e43/Phishing_Mail_Dataset/Fake-mail.txt)

2.[Open Script](https://github.com/JAYAPALKALURI/Sample-Phishing-Mails/blob/9224ed2329e6c9b78d4e2bb18cf61ddaa65b2e43/Phishing_Mail_Dataset/Fake_Mail2.txt)

3.[open image](https://github.com/JAYAPALKALURI/Sample-Phishing-Mails/blob/d075fcd7ea27548016d6cd7677d61996f0d3701d/Phishing_Mail_Dataset/mail.png)


## 🔍 Phishing Indicators:
1. *Email Spoofing*: Sender uses a domain resembling PayPal.
2. *Mismatched URL*: Link text says "https://paypal.com" but redirects to "http://scam-link.net".
3. *Urgent Language*: "Your account will be permanently disabled in 24 hours."
4. *Grammar Errors*: Multiple spelling and formatting mistakes.
5. *Suspicious Attachment*: A PDF file claiming to be an invoice.
6. *Header Analysis*: SPF check failed; origin IP does not match PayPal.

## Tools
After throughly analysing the mail and got suspecious on it.we can also use the Online header Analyzer

1. MXToolBox-[view site](https://mxtoolbox.com/)
   
Screenshots:
![image alt](https://github.com/JAYAPALKALURI/Sample-Phishing-Mails/blob/01a4a9eb8939bf1667ebdddf2cf5afb663e34d5c/Phishing_Mail_Dataset/Screenshot_2025-06-25_06_38_36.png)

![image alt](https://github.com/JAYAPALKALURI/Sample-Phishing-Mails/blob/73dec06ca70ff2bec7b5c41698c6a9e014541bfd/Phishing_Mail_Dataset/Screenshot_2025-06-25_06_36_11.png)

These Online Header Analyzer helps to identify

 >Identify suspicious links or attachments.
 
 >Look for urgent or threatening language in the email body.
 
 >Note any mismatched URLs (hover to see real link).

 >Verify presence of spe ling or grammar errors.

 >Summarize phishing traits found in the email.

## ✅ Conclusion:
This email uses common phishing tactics like spoofing, social engineering, and link manipulation to trick users.
