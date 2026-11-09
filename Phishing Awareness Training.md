CodeAlpha Cyber Security - Task 2

# Phishing Awareness Training

By Zainab Batool, BS Business Data Analytics, COMSATS University Islamabad

## 1. Phishing kya hai?

Phishing ek cyber attack hai jisme attacker khud ko kisi trusted jagah (bank, company, boss, courier, government) ka bana kar email, SMS, call ya fake website se aap ki sensitive information (password, OTP, CNIC, card number) chura leta hai.

**Types:**

- **Email phishing:** bulk fake emails.
- **Spear phishing:** kisi ek khaas person/company ko target karna.
- **Smishing:** SMS ke zariye (jaise "Aap ka account block ho jayega").
- **Vishing:** phone call ke zariye (fake bank officer).
- **Fake websites / clone pages:** asli site jaisa login page.

## 2. Phishing email kaise pehchanen

**From:** support@hbl-secure-alerts.com\
**Subject:** URGENT: Aap ka account 24 ghantay mein block ho jayega!\
\
Dear Customer, hum ne suspicious activity detect ki hai. Abhi niche link par click karke apna ATM PIN aur OTP verify karein: http://hbl-verify-login.xyz/login

Is email mein red flags:

- **Sender domain galat:** asli bank ka domain alag hota hai, ye random domain hai.
- **Urgency / dhamki:** "24 ghantay mein block" - jaldi karwane ke liye.
- **Generic greeting:** "Dear Customer", aap ka naam nahi.
- **Suspicious link:** `.xyz` domain, bank ka official domain nahi.
- **Sensitive info mangna:** koi bank email par PIN ya OTP nahi mangta.
- **Spelling/grammar mistakes** aur ajeeb design.

## 3. Fake websites kaise pehchanen

| Check | Asli | Fake |
| --- | --- | --- |
| URL | paypal.com | paypa1.com, paypal-login.net |
| HTTPS lock | Hota hai (lekin sirf lock kaafi nahi) | Fake sites par bhi ho sakta hai |
| Design | Professional | Blurry logo, errors |
| Info | Normal login | PIN, OTP, card sab ek page par |

**Tip:** Link par click karne se pehle us par hover karein (mobile par long press) aur asli URL dekhein.

## 4. Social Engineering tactics

- **Urgency:** "Abhi karo warna nuksan."
- **Fear:** "Account block / legal action."
- **Greed:** "Aap ne Rs. 50,000 ka inaam jeeta hai" (jaise fake BISP / lucky draw messages).
- **Authority:** boss, bank manager, FIA, police ban kar baat karna.
- **Trust / familiarity:** dost ya colleague ki hacked ID se message.
- **Pretexting:** jhooti kahani bana kar info nikalna (fake courier, fake HR).

## 5. Real-world examples

- **Fake easypaisa/JazzCash SMS:** "Aap ke account mein galti se paisay aa gaye, wapas bhejein" ya OTP mangna.
- **Fake courier SMS:** "Parcel delivery fail, link par address update karein."
- **CEO fraud (BEC):** boss ke naam se email ke "jaldi payment transfer karein".
- **2016 Bangladesh Bank heist:** fake payment instructions se approx. 81 million USD chori hue (social engineering + malware ka combination).

## 6. Best practices

- Link par click karne se pehle sender aur URL check karein.
- Bank kabhi OTP/PIN/password email, SMS ya call par nahi mangta.
- Strong, unique passwords + password manager.
- **2FA / MFA** on karein.
- Suspicious attachment (.exe, .zip, macro wali file) na kholen.
- Software aur antivirus update rakhein.
- Shak ho to khud official website/app khol kar ya official helpline par call karke confirm karein.
- Phishing email ko report karein aur delete kar dein. Agar click kar diya to password foran change karein aur bank ko inform karein.

## 7. Interactive Quiz

## 8. Quick Spot-the-Phish

Ye message phishing hai ya legit?

"Aap ka Daraz parcel deliver nahi ho saka. Address update karne ke liye click karein: http://daraz-pk-parcel.top/update"