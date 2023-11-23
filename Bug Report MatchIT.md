**BUG REPORT**

**BUG1**

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

![](media/image1.png){width="5.9in" height="3.2525634295713037in"}

![](media/image2.png){width="5.927522965879265in"
height="4.141666666666667in"}

**BUG2**

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

![](media/image3.png){width="6.5in" height="3.4916666666666667in"}

![](media/image4.png){width="6.5in" height="3.533333333333333in"}

**BUG3**

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

![](media/image5.png){width="1.8083333333333333in"
height="3.683333333333333in"}

**BUG4**

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

**Expected result: **

When HR/Company writes a job ad, text should looks identical in made job
ad. If text is divided into two paragraphs, text should be two
paragraphs.

**Actual result:**

In created job ad, text in section About project (‘O projektu) is one
paragraph, although text was edited in two paragraphs.

**Screenshoot:**

**Edit version:**

![](media/image6.png){width="6.5in" height="0.8416666666666667in"}

**How it looks in created job ad: **

![](media/image7.png){width="5.066666666666666in"
height="0.9416666666666667in"}

**BUG5**

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

![](media/image8.png){width="1.8314107611548556in"
height="3.809332895888014in"}

**BUG6**

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

**BUG7**

**Summary:**

MOB - The sections are cut off on the particular tabs in the Profile
tab.

**Precondition: **

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

![](media/image9.png){width="2.262840113735783in"
height="3.8583333333333334in"}![](media/image10.png){width="2.142904636920385in"
height="3.5833333333333335in"}![](media/image11.png){width="2.075in"
height="4.433333333333334in"}

**BUG8**

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

![](media/image12.png){width="5.033333333333333in"
height="2.8457688101487313in"}

**BUG9**

**Summary:**

MOB/WEB - Candidate can't see own text message sent together with GIF to
matched job.

**Description: **

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

**Expected result: **

Candidate see a complete message (text and GIF) which sent to matched
job same how HR/Company user see It. 

**Actual result:**

Candidate see only a GIF which was sent to matched job along with text. 

**Screenshot:**

![](media/image13.png){width="2.7in" height="5.5in"}

![](media/image14.png){width="6.6422014435695536in"
height="4.099991251093614in"}

**BUG10**

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

![](media/image15.png){width="6.660550087489064in"
height="3.8426246719160106in"}

**BUG11**

**Summary:**

WEB - MatChat - Replied message in the 'Thread' is displayed vertically.

**Precondition:**

Candidate is matched with a job. 

Environment is Windows10/Chrome.

HR/Company user is logged in.

**Steps to reproduce: **

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

![](media/image16.png){width="6.5in" height="3.7916666666666665in"}

![](media/image17.png){width="6.5in" height="3.9916666666666667in"}

**BUG12**

**Summary:**

WEB - MatChat - Typing message in the 'Thread' isn’t fully displayed.

**Precondition:**

Candidate is matched with a job. 

Environment is Windows10/Chrome.

HR/Company user is logged in.

**Steps to reproduce: **

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

![](media/image16.png){width="6.5in" height="3.7916666666666665in"}

![](media/image18.png){width="6.5in" height="3.825in"}

**BUG13**

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

![](media/image19.png){width="5.133333333333334in"
height="3.783333333333333in"}

![](media/image20.png){width="5.075in" height="4.033333333333333in"}

![](media/image21.png){width="6.5in" height="3.875in"}
