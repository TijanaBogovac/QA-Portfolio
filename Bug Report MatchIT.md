**BUG REPORT**

<hr>BUG1</hr>

**Summary:**

WEB - Two fields Benefits and Work Methods (‘Benefiti’ i ‘Načini rada’)
aren't visible in the created job ad.

**Precondition:**

Environment is Windows 10/Chrome.

**Steps to reproduce:**

1.  Log in to <https://company.matchit.rs/>

2.  Click on button Add job ad (‘+Dodaj oglas’)

3.  Fill all fields and click on Create (‘Kreiraj)

4.  Go to link <https://company.matchit.rs/job-offers> and find newly
    created job ad

5.  Click on created job ad

**Expected result:**

Benefits and Work Methods (‘Benefiti’ i ‘Načini rada’) should be visible
in created job ad same as in edit mode.

**Actual result:**

Sections Benefits and Work Methods are missing in created job ad.

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/c19642dd-e2ca-4dc4-97f4-2c5c2496b7ae)

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/f4f130df-3a98-4fbe-a014-4e384eef09cb)


<hr>BUG2</hr>

**Summary:**

WEB - Some words are misspelled.

**Precondition:**

Environment is Windows 10/Chrome.

HR/Company user is logged in. 

**Expected result: **

Serbian letters are used in the whole application.

**Actual result:**

-   WEB - **‘Oglasi’** - In created job ad, letter c (instead of serbian
    letter č) was used in 'Nacin razvoja' and 'Broj clanova' options

-   WEB - **‘Deck kandidata’** - In the message appeared after
    HR/Company user finished choosing all candidates, was used letter dj
    (instead of serbian letter đ) in word 'medjuvremenu'.

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/a8f29a6b-c119-4a49-a0f8-3ab5128c9da8)


![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/e5aea7d3-6b5a-4260-a9e1-6eaf6b34d777)


<hr>BUG3</hr>

**Summary:**

MOB - Word is misspelled.

**Precondition:**

Environment is Android/Blackview A80 Pro.

Candidate is logged in.

**Expected result: **

Serbian letters are used in the whole application.

**Actual result:**

-   MOB - **‘Profil’** - Letter z (instead of serbian letter ž) was used
    in ‘Veštine i bedzevi’

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/1e18649b-dff9-4545-9752-8dc16b2a8cc2)


<hr>BUG4</hr>

**Summary:**

WEB - Created job ad text doesn't display Enter to separate new row.

**Precondition**:

Environment is Windows 10/Chrome.

**Steps to reproduce:**

1\. Log in to <https://company.matchit.rs/>

2\. Click on button Add job ad (‘+Dodaj oglas’)

3\. Fill all fields 

4\. In field About project (‘O projektu’) use Enter to put text in new
row.

5\. Click button Create (‘Kreiraj’)

6\. Go to link <https://company.matchit.rs/job-offers> and find newly
created job ad

7\. Pay attention to field About project (‘O projektu’)

**Expected result:**

When HR/Company writes a job ad, text should looks identical in made job
ad. If text is divided into two paragraphs, text should be two
paragraphs.

**Actual result:**

In created job ad, text in section About project (‘O projektu) is one
paragraph, although text was edited in two paragraphs.

**Screenshoot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/112a7b88-ac12-4280-b6c6-c8878f9d8b03)


<hr>BUG5</hr>

**Summary:**

MOB - The counter shows the number of technologies over the limit when
the user logs in for the first time.

**Precondition:**

Environment is Android/Blackview A80 Pro.

**Steps to reproduce:**

1.  Log in to application for the first time.

2.  Fill in Name and Surname.

3.  Choose maximum allowed random technologies.

4.  Pay attention how many technologies counter shows.

**Expected result:**

When user Log In for the 1st time on Mobile app. the maximum allowed
number of technologies which user can choose is 20.

**Actual result:**

The user selected 21 technologies.

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/0af83387-b838-44f3-b56d-630e3b2008ed)


<hr>BUG6</hr>

**Summary:**

MOB - The counter shows less selected technologies when user unselect
and select technologies again.

**Precondition:**

Environment is Android/Blackview A80 Pro.

**Steps to reproduce:**

1.  Log in to application for the first time.

2.  Fill in Name and Surname.

3.  Choose maximum allowed random technologies (20).

4.  Uncheck few technologies.

5.  Check random technologies to be maximum allowed (20).

**Expected result:**

When user Log In for the 1st time on Mobile app. the maximum allowed
number of technologies which user can choose is 20.

**Actual result:**

After user deselected few technologies and selected few more, the
counter shows number of maximum allowed technologies less then 20. And
every time when repeating actions check/uncheck, number of allowed
technologies is less and less.

<hr>BUG7</hr>

**Summary:**

MOB - The sections are cut off on the particular tabs in the Profile
tab.

**Precondition:**

Use mobile with bigger display screen. 

Environment is Android/Blackview A80 Pro with  **6.49 inch** display
screen.

**Steps to reproduce:**

1.  Log in Mobile App and choose Profile (‘Profil’).

2.  Choose Certificates (‘Sertifikati’) 

3.  Click button Add certificate (‘Dodaj sertifikat’).

4.  Fill in all fields and click Save (‘Sačuvaj’).

5.  Repeat 3 more times Steps 3, 4.

**Expected result:**

Section should be displayed as a whole.

**Actual result:**

If mobile device has bigger screen size display, then section
Certificates (‘Sertifikati’) is cut off.

**Note:**

The same applies to sections Education (‘Edukacija’) and Skills and
Badges (‘Veštine i Bedzevi’).

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/1af2bf1a-c082-4671-ba44-a6cdb0305709)
![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/26654c5d-fe9d-4bb4-9e62-f2e470dcb104)


<hr>BUG8</hr>

**Summary:**

WEB - Word 'None' is displayed for candidate with a lot of experience.

**Description: **

In job ad (for example *Junior Python developer*) are listed 2 wanted
technologies. Candidate has high experience in both wanted
technologies. 

When HR/Company user look at candidate’s Profile (‘Profil kandidata’)
and candidate’s experience (‘Iskustvo’), word ‘None’ is visible on the
beginning of candidate’s listed experiences.

**Precondition**:

Candidate is matched with a job.

Environment is Windows10/Chrome.

HR/Company user is logged in.

**Steps to reproduce:**

1\. Go to candidate’s profile, example for
<https://company.matchit.rs/job-offers/24/matches/166/candidate>

2\. Pay attention to Experience ('Iskustvo') and the beggining of the
experience’s list.

**Expected result:**

If candidate has an experience in listed job ad’s technologies, word
‘None’ isn’t visible.

**Actual result:**

Candidate with a lot of experience has word 'None' in Experience section
(‘Iskustvo’).

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/49bfca94-96bf-4260-be3e-b19f1ea23e2d)


<hr>BUG9</hr>

**Summary:**

MOB/WEB - Candidate can't see own text message sent together with GIF to
matched job.

**Description:**

When candidate sent text message with GIF to matched job, only GIF
appeared to candidate in chat, while HR/Company user can see complete
candidate’s message (GIF and text message).

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

Candidate see a complete message (text and GIF) which sent to matched
job same how HR/Company user see It. 

**Actual result:**

Candidate see only a GIF which was sent to matched job along with text. 

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/5b6190ed-a2ad-4a25-8350-5519d3b46c49)
![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/9e2b5841-3ad5-4250-a8ee-312f3165864a)


<hr>BUG10</hr>

**Summary:**

WEB/MOB - Candidate’s name is displayed as {{ user }} on HR/Company
user’s chat while candidate types a message.

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

3\. Pay attention to the chat’s bottom in the moment when candidate types
a message.

**Expected result:**

HR/Company user see the name of candidate while candidate types a
message, in this example is

. . . Tijana B is typing...

**Actual result:**

Candidate’s name while typing  isn’t displayed in HR/Company user’s
chat. Instead of name is displayed

. . . {{ user }} is typing...

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/9c6baf2b-dc71-49af-936d-8bc1366af2f6)


<hr>BUG11</hr>

**Summary:**

WEB - MatChat - Replied message in the 'Thread' is displayed vertically.

**Precondition:**

Candidate is matched with a job. 

Environment is Windows10/Chrome.

HR/Company user is logged in.

**Steps to reproduce:**

1\. Go to the MatChat for example
<https://company.matchit.rs/chat?match_id=166>

2\. Find message 'Vidimo se onda' from candidate.

3\. Place the mouse cursor on the message.

4\. Choose icon Reply in the middle (2 arrows icon).

5\. Pay attention to message 'Vidimo se onda' in Thread.

**Expected result:**

Opened field 'Thread' should be enough expanded, so message can fit in
the field.

**Actual result:**

The replied message is displayed vertically.

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/a9055c4d-1d40-478c-8558-76ae1cc70a8c)
![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/ce65f867-dcfe-4193-9d91-05cfb65108ae)


<hr>BUG12</hr>

**Summary:**

WEB - MatChat - Typing message in the 'Thread' isn’t fully displayed.

**Precondition:**

Candidate is matched with a job. 

Environment is Windows10/Chrome.

HR/Company user is logged in.

**Steps to reproduce:**

1\. Go to the MatChat for example
<https://company.matchit.rs/chat?match_id=166>

2\. Find message 'Vidimo se onda' from candidate.

3\. Place the mouse cursor on the message.

4\. Choose icon Reply in the middle (2 arrows icon).

6\. Type a message 123456 below ‘Thread’ field.

**Expected result:**

Opened field 'Thread' should be enough expanded, so all text message
while typing can be seen.

**Actual result:**

Typed message in field below 'Thread' is partial visible - only first 3
characters are visible.

**Screenshot**:

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/28b1735f-3582-4250-8206-0ddf76513936)
![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/bfc290a9-5cb6-498a-9697-46901e8fb86b)


<hr>BUG13</hr>

**Summary:**

WEB - MatChat - Pinned message looks the same like unpinned.

**Precondition:**

Candidate is matched with a job. 

Environment is Windows10/Chrome.

HR/Company user is logged in.

**Steps to reproduce:**

1\. Go to the MatChat for example
<https://company.matchit.rs/chat?match_id=166>

2\. Find message 'Vidimo se onda' from candidate.

3\. Place the mouse cursor on the message.

4\. Click icon three dots (‘...’).

4\. Choose ‘Pin’.

**Expected result:**

Pinned message change position, become highlihted and isolated from all
messages.

**Actual result:**

Pinned message in the MatChat remains at same position, doesn't isolate
from all messages.

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/cfef8486-4f45-4916-8c5d-628725253c11)
![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/c55d1e7d-b67c-4873-b056-e4884becef24)
![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/917e665d-d7d9-4aa3-b149-af530a9c1f48)



