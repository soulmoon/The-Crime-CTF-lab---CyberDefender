# The Crime - CyberDefenders CTF Writeup

**Category:** Endpoint Forensics  
**Tools Used:** ALEAPP 

---

## Scenario

We’re in the middle of a murder investigation. The victim’s phone has been obtained as a key piece of evidence.  
Through forensic analysis, we aim to reconstruct the sequence of events and uncover critical details leading up to the incident.

---

## Questions & Answers

### **Q1** - Based on the accounts of the witnesses and individuals close to the victim, it has become clear that the victim was interested in trading. This has led him to invest all of his money and acquire debt. Can you identify the SHA256 of the trading application the victim primarily used on his phone?
 
 <img width="940" height="401" alt="image" src="https://github.com/user-attachments/assets/1070fe05-5216-47a2-a6fb-261e1a5c2f76" />
 **Answer:**  
  4f168a772350f283a1c49e78c1548d7c2c6c05106d8b9feb825fdc3466e9df3c

 ### **Q2** - According to the testimony of the victim's best friend, he said, "While we were together, my friend got several calls he avoided. He said he owed the caller a lot of money but couldn't repay now". How much does the victim owe this person?
 
<img width="940" height="394" alt="image" src="https://github.com/user-attachments/assets/165c0e5f-463f-4ac1-8b66-0822a5db59dd" />

 **Answer:**  
   250000

 ### **Q3** - What is the name of the person to whom the victim owes money?
<img width="940" height="359" alt="image" src="https://github.com/user-attachments/assets/2b4cf22d-3495-4557-b1bc-d7cb506c37df" />

 **Answer:**  
   Shady Wahab

 ### **Q4** - Based on the statement from the victim's family, they said that on September 20, 2023, he departed from his residence without informing anyone of his destination. Where was the victim located at that moment?
<img width="940" height="608" alt="image" src="https://github.com/user-attachments/assets/b53232f7-100a-4238-8405-b48947974ea0" />

 **Answer:**  
The Nile Ritz-Carlton

 ### **Q5** - The detective continued his investigation by questioning the hotel lobby. She informed him that the victim had reserved the room for 10 days and had a flight scheduled thereafter. The investigator believes that the victim may have stored his ticket information on his phone. Look for where the victim intended to travel.
<img width="940" height="458" alt="image" src="https://github.com/user-attachments/assets/42924195-461d-401f-be35-e71ee424ba66" />

 **Answer:**  
Las Vegas

 ### **Q6** - After examining the victim's Discord conversations, we discovered he had arranged to meet a friend at a specific location. Can you determine where this meeting was supposed to occur?
<img width="940" height="457" alt="image" src="https://github.com/user-attachments/assets/2d4c4593-3cb8-42fb-b239-435e12a3a13b" />

 **Answer:**  
The Mob Museum

## **Key Learning Points**
- **ALEAPP** is powerful for Android app data parsing.
- Combining SMS, GPS, media files, and app logs helps establish timelines.
- Cross-referencing between datasets is essential for context.

## **References**
- [ALEAPP GitHub](https://github.com/abrignoni/ALEAPP)
- [DB Browser for SQLite](https://sqlitebrowser.org/)
- [CyberDefenders CTF: The Crime](https://cyberdefenders.org/blueteam-ctf-challenges/)

## **Writeup by**
[Dipak Pakhrin](https://github.com/soulmoon)  
*Forensic Analyst & Blue Team Enthusiast*

