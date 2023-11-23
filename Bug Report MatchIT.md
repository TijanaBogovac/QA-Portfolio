`				`**BUG REPORT**

**BUG1**

**Summary:** 

WEB - Two fields Benefits and Work Methods (‘Benefiti’ i ‘Načini rada’) aren't visible in the created job ad.

**Precondition:**

Environment is Windows 10/Chrome.

**Steps to reproduce:**

1. Log in to <https://company.matchit.rs/>
1. Click on button Add job ad (‘+Dodaj oglas’)
1. Fill all fields and click on Create (‘Kreiraj)
1. Go to link <https://company.matchit.rs/job-offers> and find newly created job ad
1. Click on created job ad

**Expected result:** 

Benefits and Work Methods (‘Benefiti’ i ‘Načini rada’) should be visible in created job ad same as in edit mode.

**Actual result:**

Sections Benefits and Work Methods are missing in created job ad.

**Screenshot:**

![https://lh7-us.googleusercontent.com/Mr1LOxAvl27-6goFHrgYvzg16DEQhzsGWha9GaG5-ueJeMH_keY3R4r2fiVygCLkO_U6DNjaeWu5kNP8bQZome4N3VgC7b_29wpg66Nn38cl30qcx_c_uwHfLMDRzEN-o2HPpMy5Nd0xBKzsg1ZaDCI](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.001.png)

![https://lh7-us.googleusercontent.com/ywIF4QcswGDPWyHMDODII_EXbvVyiEz35vEitHAdYlDFoNvdrKG9vOjSsLsHSXKbWAMp8S1exq2iST1mIkEZsFJ0Gj1wUacgYa482lBK3vjIMnOFcZe0172jbNSC2MXoYNpa97sTG-Zu-hK9RqSSnVs](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.002.png)

**BUG2**

**Summary:**

WEB - Some words are misspelled.

**Precondition:**

Environment is Windows 10/Chrome.

HR/Company user is logged in. 

**Expected result:** 

Serbian letters are used in the whole application.

**Actual result:**

- WEB - **‘Oglasi’** - In created job ad, letter c (instead of serbian letter č) was used in 'Nacin razvoja' and 'Broj clanova' options
- WEB - **‘Deck kandidata’** - In the message appeared after HR/Company user finished choosing all candidates, was used letter dj (instead of serbian letter đ) in word 'medjuvremenu'.

**Screenshot:**

![https://lh7-us.googleusercontent.com/JH0HwL67PT7mm53gpog4KFRKUzzWLHiJewkXEzP833TA5xeW_bBGgeIJA5KRsnUX3Sw7O5Ep2PbGRiyyN-6ELb15Wu6g-xTTTp1LPBFFg1e6ezgMcJ3BGFdSKTswzHf3qOZgm_wjrOiEKXzr6PjQhUE](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.003.png)

![https://lh7-us.googleusercontent.com/WofrM_yJsbeaGN-l11_C3dJalyw9uYoGWsW6F6vwsCqGHWqzjwSRP8JEW2pcNJCSA0OQzm3TAgpC-MqmGjnr_Ja6OLThEwZ3FQOWspBJZWN0AwVoxWNq_s9oy59LBNhQ6_pMudP7JLJvgadYZAMKEQo](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.004.png)

**BUG3**

**Summary:**

MOB - Word is misspelled.

**Precondition:**

Environment is Android/Blackview A80 Pro.

Candidate is logged in.

**Expected result:** 

Serbian letters are used in the whole application.

**Actual result:**

- MOB - **‘Profil’** - Letter z (instead of serbian letter ž) was used in ‘Veštine i bedzevi’

**Screenshot:**

![https://lh7-us.googleusercontent.com/yepuA9TIKr9IMd8RyvrQ7DOhaq30IlLz07xMG-sUK-0ACzYmvavDJJfeRQvVOUBH1Xvu1pL0WMHAbHNs82KpbCLf6yFRnZb57_S9TrsGmclFKPuedzyG7-Ahedu9Z2J8SkzUlque-IjwpRxFbOjyZfU](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.005.png)

**BUG4**

**Summary:**

WEB - Created job ad text doesn't display Enter to separate new row.

**Precondition**:

Environment is Windows 10/Chrome.

**Steps to reproduce:**

1\. Log in to <https://company.matchit.rs/>

2\. Click on button Add job ad (‘+Dodaj oglas’)

3\. Fill all fields 

4\. In field About project (‘O projektu’) use Enter to put text in new row.

5\. Click button Create (‘Kreiraj’)

6\. Go to link <https://company.matchit.rs/job-offers> and find newly created job ad

7\. Pay attention to field About project (‘O projektu’)

**Expected result:** 

When HR/Company writes a job ad, text should looks identical in made job ad. If text is divided into two paragraphs, text should be two paragraphs.

**Actual result:**

In created job ad, text in section About project (‘O projektu) is one paragraph, although text was edited in two paragraphs.

**Screenshoot:**

**Edit version:**

![https://lh7-us.googleusercontent.com/C0chECUnctU_fm3XPtZeB6GuO4urmzPn21ubz5QNuLwoZj3M9Ns1FRphl2UP9TVz9NZobBW7f-Lta9A3e7sle2K_KkJEk-_vU5R6-IemsL_V3zpRlNbDMxvF_9HcolAmSGoEWb1tbrO28WX67T-OyHU](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.006.png)

**How it looks in created job ad:** 

![https://lh7-us.googleusercontent.com/xyEFuTneiwTQz_g_a0GA_7U4R_MzaWlKiGZHwm9RXODUCpyJ8n9strQMrVeJvxi_IBpxDeUBUMFgbAPblZIcO9k8XtDBtnEFlk3oOiiq8IY1ZC8ouCSlsg3yMZQOY7mI7UuMhiCrlUp9vXpqRE4XrvM](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.007.png)

**BUG5**

**Summary:**

MOB - The counter shows the number of technologies over the limit when the user logs in for the first time.

**Precondition:**

Environment is Android/Blackview A80 Pro.

**Steps to reproduce:**

1. Log in to application for the first time.
1. Fill in Name and Surname.
1. Choose maximum allowed random technologies.
1. Pay attention how many technologies counter shows.

**Expected result:**

When user Log In for the 1st time on Mobile app. the maximum allowed number of technologies which user can choose is 20.

**Actual result:**

The user selected 21 technologies.

**Screenshot:**

![https://lh7-us.googleusercontent.com/LCarBcb-rLmqT8zlAtTZpqbLAu-gsddrCk3__OTU8ErOjdbutrlXi5fLGUwkJrUQ223cTNvLche1NH7nh7x2b4lplHWPhL-g_Byu9yV_nWDCTQ4stwrDkIubujQHn5LLUHUDGuY0aNN8pcSqaY-Cx4o](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.008.png)

**BUG6**

**Summary:**

MOB - The counter shows less selected technologies when user unselect and select technologies again.

**Precondition:**

Environment is Android/Blackview A80 Pro.

**Steps to reproduce:**

1. Log in to application for the first time.
1. Fill in Name and Surname.
1. Choose maximum allowed random technologies (20).
1. Uncheck few technologies.
1. Check random technologies to be maximum allowed (20).

**Expected result:**

When user Log In for the 1st time on Mobile app. the maximum allowed number of technologies which user can choose is 20.

**Actual result:**

After user deselected few technologies and selected few more, the counter shows number of maximum allowed technologies less then 20. And every time when repeating actions check/uncheck, number of allowed technologies is less and less.

**BUG7**

**Summary:**

MOB - The sections are cut off on the particular tabs in the Profile tab.

**Precondition:** 

Use mobile with bigger display screen. 

Environment is Android/Blackview A80 Pro with  **6.49 inch** display screen.

**Steps to reproduce:**

1. Log in Mobile App and choose Profile (‘Profil’).
1. Choose Certificates (‘Sertifikati’) 
1. Click button Add certificate (‘Dodaj sertifikat’).
1. Fill in all fields and click Save (‘Sačuvaj’).
1. Repeat 3 more times Steps 3, 4.

**Expected result:**

Section should be displayed as a whole.

**Actual result:**

If mobile device has bigger screen size display, then section Certificates (‘Sertifikati’) is cut off.

**Note:**

The same applies to sections Education (‘Edukacija’) and Skills and Badges (‘Veštine i Bedzevi’).

**Screenshot:**

![https://lh7-us.googleusercontent.com/fSJCpiCzyg8bqJr5nZyBvxZPiiZ7R_NpwVTptSmiziSmO2ny1xChPwPrpOXvfZCXdhc5vAPw6pR-F1YgJJnIImTiV_R-8RiRetSjUX5mRNdwN5JxXUBoZxWKnLt0VvP7hQGmFTBO-H8cK0zng67geJk](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.009.png)![https://lh7-us.googleusercontent.com/5cKDyW30U8haxj1sdIp04ebQDmfC_x1eLPBRVzcRYw4u3TcwL3Mto7RR1Z435cnO_aUfMa14CFOFQAJmaMkNMx8Rvjz0cX0tcRd4NW2MwXx71tdDBl7Q1ANBe3EmYCGighSIPA_btqc1-1eJ3Mpquo0](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.010.png)![https://lh7-us.googleusercontent.com/_DEVtdq-hDJ-PXfi1XeiOsfN47AiUvPoNe-3wkHZCf36XjMyHw-Ye1BM7LaQqxrC-Zq4TxXs8wnEFu0SQPezGFOApfCBV410hm14MEX3al8EjnQVGoL7U9QRefEWQd5G5mqY9Jk9Xz1TAGCzX4l1dFA](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.011.png)

**BUG8**        

**Summary:**

WEB - Word 'None' is displayed for candidate with a lot of experience.

**Description:** 

In job ad (for example *Junior Python developer*) are listed 2 wanted technologies. Candidate has high experience in both wanted technologies. 

When HR/Company user look at candidate’s Profile (‘Profil kandidata’) and candidate’s experience (‘Iskustvo’), word ‘None’ is visible on the beginning of candidate’s listed experiences.

**Precondition**:

Candidate is matched with a job.

Environment is Windows10/Chrome.

HR/Company user is logged in.

**Steps to reproduce:**

1\. Go to candidate’s profile, example for <https://company.matchit.rs/job-offers/24/matches/166/candidate>

2\. Pay attention to Experience ('Iskustvo') and the beggining of the experience’s list.

**Expected result:**

If candidate has an experience in listed job ad’s technologies, word ‘None’ isn’t visible.

**Actual result:**

Candidate with a lot of experience has word 'None' in Experience section (‘Iskustvo’).

**Screenshot:**

![https://lh7-us.googleusercontent.com/Yrymq--FyDT9alENSrQY-bBBwEz8IlBICtHHW05io5bg5vw5vFDQDYaZMfB5wfhrShfLszhIWIwyN2fbZCSPheiN5pBAlHXZNBg5nVnnzzJMUcijMPDLNooWVoDyZ-M_6CCLmfadY_8ZeO8T99OKcXA](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.012.png)

**BUG9**

**Summary:**

MOB/WEB - Candidate can't see own text message sent together with GIF to matched job.

**Description:** 

When candidate sent text message with GIF to matched job, only GIF appeared to candidate in chat, while HR/Company user can see complete candidate’s message (GIF and text message).

**Precondition:**

Candidate is matched with a job.

Environment is Android/Blackview A80 Pro and Windows10/Chrome.

Candidate is logged in on a mobile app.

HR/Company user is logged in web app,

**Steps to reproduce:**

1\. Opet matched job on MOB.

2\. Write text message with GIF animation.

2\. Send a message.

3\. Open MatChat on WEB <https://company.matchit.rs/chat>

4\. Check new message from candidate.

**Expected result:** 

Candidate see a complete message (text and GIF) which sent to matched job same how HR/Company user see It. 

**Actual result:**

Candidate see only a GIF which was sent to matched job along with text. 

**Screenshot:**

![https://lh7-us.googleusercontent.com/-pvHV71GprMDyufwehsgECU8DH-N_PevTxZBnykiIfMc4GnJtE1Lc2RiwV5jYfyexztE8wCu0PL5TU3cTIeLdehiQ9siwx2QqXyP2oA-x8gvWP1-B_-apgE9hZrqqZV4wqAqVszTkSIfG34wnmnNlxE](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.013.png)

![https://lh7-us.googleusercontent.com/oEcbenOxPVomGvvj8b4kxgyWBtydVvyKbXrJKE5oUVd22S5gb3Szx17NN6L-XHTMs5ULNAXXhElIqffZtXYs-4jYjY_-qA_sBNP8bF_HibwwGN1fNKTgADLbkmkRPQ-pN6iNgujKT3zj0b2Ud7Pu05w](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.014.png)

**BUG10**

**Summary:**

WEB/MOB - Candidate’s name is displayed as {{ user }} on HR/Company user’s chat while candidate types a message.

**Precondition:**

Candidate is matched with a job.

Environment is Windows10/Chrome and Android/Blackview A80 Pro.

Candidate is logged in on a mobile app.

HR/Company user is logged in web app,

**Steps to reproduce:**

1\. Open matched job on MOB (for example *Junior Python developer*).

2\. Type a message to matched job.

3\. At the same moment open MatChat on WEB: 

<https://company.matchit.rs/chat?match_id=166>

3\. Pay attention to the chat’s bottom in the moment when candidate types a message.

**Expected result:**

HR/Company user see the name of candidate while candidate types a message, in this example is

. . . Tijana B is typing...

**Actual result:**

Candidate’s name while typing  isn’t displayed in HR/Company user’s chat. Instead of name is displayed

. . . {{ user }} is typing...

**Screenshot:**

![https://lh7-us.googleusercontent.com/y5hPHKtVgy0PAAKxLaZ6yx2d5_DKt8iJFAhbW8Ji0Dlq19jqtMgRVSqrhxxg5b9tPU4kvxSajJY54HbA6OfPtyK4hJ9sevuZANNwQQM2Rpjn3OC764C9j_Vrh-82HEKWSvpBPXYYKSCJKMk-KOAv_m0](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.015.png)

**BUG11**

**Summary:**

WEB - MatChat - Replied message in the 'Thread' is displayed vertically.

**Precondition:**

Candidate is matched with a job. 

Environment is Windows10/Chrome.

HR/Company user is logged in.

**Steps to reproduce:** 

1\. Go to the MatChat for example <https://company.matchit.rs/chat?match_id=166>

2\. Find message 'Vidimo se onda' from candidate.

3\. Place the mouse cursor on the message.

4\. Choose icon Reply in the middle (2 arrows icon).

5\. Pay attention to message 'Vidimo se onda' in Thread.

**Expected result:**

Opened field 'Thread' should be enough expanded, so message can fit in the field.

**Actual result:**

The replied message is displayed vertically.

**Screenshot:**

![https://lh7-us.googleusercontent.com/2Bb3AuHSW5-mCRfK6lW9jQPbO7-fXEG5oUJvn0J8BJGV_EoPU_1fZG_41VXLs3YjEvT70YRK2NYbJ6y00v-aRxo3WsMbqu15OvzyCGASnDR0uPLl36QOvKpeYJ5bxp8sn9D0eSXSLT5w5qN6wotU0_k]

![https://lh7-us.googleusercontent.com/eADA5Xd8dlRnkhEljERWdTXkpfPAtN2t5FiPPzE6WxsYHp8GKMaHW4xpNY4h3nAbM_t7XTS3j5Xf-0NlQSuII8S9FQz0p4qW7GFLjGb3ZNVZ2NwMJIshrZCYutRb0F0eVnMf039fKFNIoKtW0mV1fP8](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.017.png)

**BUG12**

**Summary:**

WEB - MatChat - Typing message in the 'Thread' isn’t fully displayed.

**Precondition:**

Candidate is matched with a job. 

Environment is Windows10/Chrome.

HR/Company user is logged in.

**Steps to reproduce:** 

1\. Go to the MatChat for example <https://company.matchit.rs/chat?match_id=166>

2\. Find message 'Vidimo se onda' from candidate.

3\. Place the mouse cursor on the message.

4\. Choose icon Reply in the middle (2 arrows icon).

6\. Type a message 123456 below ‘Thread’ field.

**Expected result:**

Opened field 'Thread' should be enough expanded, so all text message while typing can be seen.

**Actual result:**

Typed message in field below 'Thread' is partial visible - only first 3 characters are visible.

**Screenshot**:

![https://lh7-us.googleusercontent.com/2Bb3AuHSW5-mCRfK6lW9jQPbO7-fXEG5oUJvn0J8BJGV_EoPU_1fZG_41VXLs3YjEvT70YRK2NYbJ6y00v-aRxo3WsMbqu15OvzyCGASnDR0uPLl36QOvKpeYJ5bxp8sn9D0eSXSLT5w5qN6wotU0_k]

![https://lh7-us.googleusercontent.com/wOvpozHNS4KWRvwo5eM5435kPGMFwFhPIKn_0kJHIaA3Etoyjvpo-oLib70DIKq9-fPZf-JK-6-1U8_lRjzE9NiabKRuHl1nrq8-QyubOIU_E6hVMWM1em6Y_qiwPIstjfSe90jMNegC8TEHmceiprU](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.018.png)


**BUG13**

**Summary:**

WEB - MatChat - Pinned message looks the same like unpinned.

**Precondition:**

Candidate is matched with a job. 

Environment is Windows10/Chrome.

HR/Company user is logged in.

**Steps to reproduce:**

1\. Go to the MatChat for example <https://company.matchit.rs/chat?match_id=166>

2\. Find message 'Vidimo se onda' from candidate.

3\. Place the mouse cursor on the message.

4\. Click icon three dots (‘...’).

4\. Choose ‘Pin’.

**Expected result:**

Pinned message change position, become highlihted and isolated from all messages.

**Actual result:**

Pinned message in the MatChat remains at same position, doesn't isolate from all messages.

**Screenshot:**

![https://lh7-us.googleusercontent.com/BruObgNQb5xNMh183qhHH3NQH48XhwMAbF-SeWz-7i1Kef-dg3YqvFurwUSm048aNfYRKxT1cdk72lLZdsAJlpQ4-d6SBcGTO_smsa0pOKAn6z-lsTcFaGKBPEFwEG32u63sNWbFLg6B7JzCJDDaK5Y](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.019.png)

![https://lh7-us.googleusercontent.com/QMrhPUntKX8JtyyMHsH5gs7DZ8HgzWPV7u9ipwRmtHiMlkwl37ucrjvvncWslS-GkQwIYqWl0gePqpQSXdjNG9ILYzaVZbyRO4ZId-5HVqYVVE00eVi7Su0LrgDTflvGcrxmuwtx-kdpC-jcTQWmkmU](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.020.png)

![https://lh7-us.googleusercontent.com/MjByjwrgeEDBTln5mGw6_qAVZpCRV_SDfwSb4PiaYrR02lOnrz4yibQWfGlABzwnkXf3jg2MWK3q74efPI-w_iXyof4qpO7g46kXuplVWLXbt_JVVeShNN-SaltvRxp539aOK3wspkG_RMkq7Wr_FEM](Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.021.png)

[https://lh7-us.googleusercontent.com/2Bb3AuHSW5-mCRfK6lW9jQPbO7-fXEG5oUJvn0J8BJGV_EoPU_1fZG_41VXLs3YjEvT70YRK2NYbJ6y00v-aRxo3WsMbqu15OvzyCGASnDR0uPLl36QOvKpeYJ5bxp8sn9D0eSXSLT5w5qN6wotU0_k]: Aspose.Words.36360118-b5e1-4d49-8efe-6f00aeb174f7.016.png
