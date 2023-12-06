**BUG REPORT**

<hr>BUG1</hr>

**Summary:**

WEB - Two fields Benefits and Work Methods ('Benefiti' i 'Načini rada')
aren\'t visible in the created job ad.

**Precondition:**

Environment is Windows 10/Chrome.

**Steps to reproduce:**

1\.  Log in to <https://company.matchit.rs/>

2\.  Click on button Add job ad ('+Dodaj oglas')

3\.  Fill all fields and click on Create ('Kreiraj)

4\.  Go to link <https://company.matchit.rs/job-offers> and find newly reated job ad

5\.  Click on created job ad

**Expected result:**

Benefits and Work Methods ('Benefiti' i 'Načini rada') should be visible
in created job ad same as in edit mode.

**Actual result:**

Sections Benefits and Work Methods are missing in created job ad.

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/00911ec2-62cf-47ed-bb78-3a784429367b)
![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/01dcee80-e785-40b1-bc8a-006b3b4d53d5)

<hr>BUG2</hr>

**Summary:**

WEB - Some words are misspelled.

**Precondition:**

Environment is Windows 10/Chrome.

HR/Company user is logged in.

**Expected result:**

Serbian letters are used in the whole application.

**Actual result:**

-   WEB - **'Oglasi'** - In created job ad, letter c (instead of serbian letter č) was used in \'Nacin razvoja\' and \'Broj clanova\' options

-   WEB - **'Deck kandidata'** - In the message appeared after HR/Company user finished choosing all candidates, was used letter dj (instead of serbian letter đ) in word \'medjuvremenu\'.

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/7b92718e-4594-485c-b5bc-f3e0d98b7007)
![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/61263fa1-4c55-48b0-b4cc-839b2606ec56)

<hr>BUG3</hr>

**Summary:**

MOB - Word is misspelled.

**Precondition:**

Environment is Android/Blackview A80 Pro.

Candidate is logged in.

**Expected result:**

Serbian letters are used in the whole application.

**Actual result:**

-   MOB - **'Profil'** - Letter z (instead of serbian letter ž) was used in 'Veštine i bedzevi'

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/4d95bc0e-e96e-435e-89c9-eb60e989f78d)

<hr>BUG4</hr>

**Summary:**

WEB - Created job ad text doesn\'t display Enter to separate new row.

**Precondition:**

Environment is Windows 10/Chrome.

**Steps to reproduce:**

1\. Log in to <https://company.matchit.rs/>

2\. Click on button Add job ad ('+Dodaj oglas')

3\. Fill all fields

4\. In field About project ('O projektu') use Enter to put text in new
row.

5\. Click button Create ('Kreiraj')

6\. Go to link <https://company.matchit.rs/job-offers> and find newly
created job ad

7\. Pay attention to field About project ('O projektu')

**Expected result:**

When HR/Company writes a job ad, text should looks identical in made job
ad. If text is divided into two paragraphs, text should be two
paragraphs.

**Actual result:**

In created job ad, text in section About project ('O projektu) is one
paragraph, although text was edited in two paragraphs.

**Screenshoot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/14e3da69-2b60-49df-b9fa-9edc9d8ccb3a)

<hr>BUG5</hr>

**Summary:**

MOB - The counter shows the number of technologies over the limit when
the user logs in for the first time.

**Precondition:**

Environment is Android/Blackview A80 Pro.

**Steps to reproduce:**

1\.  Log in to application for the first time.

2\.  Fill in Name and Surname.

3\.  Choose maximum allowed random technologies.

4\.  Pay attention how many technologies counter shows.

**Expected result:**

When user Log In for the 1st time on Mobile app. the maximum allowed
number of technologies which user can choose is 20.

**Actual result:**

The user selected 21 technologies.

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/93917fa1-2e51-42ba-bc00-0a4555248eb8)

<hr>BUG6</hr>

**Summary:**

MOB - The counter shows less selected technologies when user unselect
and select technologies again.

**Precondition:**

Environment is Android/Blackview A80 Pro.

**Steps to reproduce:**

1\.  Log in to application for the first time.

2\.  Fill in Name and Surname.

3\.  Choose maximum allowed random technologies (20).

4\.  Uncheck few technologies.
   
6\.  Check random technologies to be maximum allowed (20).

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

Environment is Android/Blackview A80 Pro with **6.49 inch** display
screen.

**Steps to reproduce:**

1\.  Log in Mobile App and choose Profile ('Profil').

2\.  Choose Certificates ('Sertifikati')

3\.  Click button Add certificate ('Dodaj sertifikat').

4\.  Fill in all fields and click Save ('Sačuvaj').

5\.  Repeat 3 more times Steps 3, 4.

**Expected result:**

Section should be displayed as a whole.

**Actual result:**

If mobile device has bigger screen size display, then section
Certificates ('Sertifikati') is cut off.

**Note:**

The same applies to sections Education ('Edukacija') and Skills and
Badges ('Veštine i Bedzevi').

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/2bc2792f-0f56-4757-a86d-74efebe19adc)
![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/3c4497ff-6009-4cfc-8821-1c238c74c59a)

<hr>BUG8</hr>

**Summary:**

WEB - Word \'None\' is displayed for candidate with a lot of experience.

**Description:**

In job ad (for example *Junior Python developer*) are listed 2 wanted
technologies. Candidate has high experience in both wanted technologies.

When HR/Company user look at candidate's Profile ('Profil kandidata')
and candidate's experience ('Iskustvo'), word 'None' is visible on the
beginning of candidate's listed experiences.

**Precondition:**

Candidate is matched with a job.

Environment is Windows10/Chrome.

HR/Company user is logged in.

**Steps to reproduce:**

1\. Go to candidate's profile, example for <https://company.matchit.rs/job-offers/24/matches/166/candidate>

2\. Pay attention to Experience (\'Iskustvo\') and the beggining of the
experience's list.

**Expected result:**

If candidate has an experience in listed job ad's technologies, word
'None' isn't visible.

**Actual result:**

Candidate with a lot of experience has word \'None\' in Experience
section ('Iskustvo').

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/182b525e-3d2b-4e59-b1a7-feea51e00a49)

<hr>BUG9</hr>

**Summary:**

MOB/WEB - Candidate can\'t see own text message sent together with GIF
to matched job.

**Description:**

When candidate sent text message with GIF to matched job, only GIF
appeared to candidate in chat, while HR/Company user can see complete
candidate's message (GIF and text message).

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

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/6e3ca755-2fc9-4b16-8e3a-ef28b4bfe35e)
![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/fee1d990-5590-4863-9616-7d7818d388c1)

<hr>BUG10</hr>

**Summary:**

WEB/MOB - Candidate's name is displayed as {{ user }} on HR/Company
user's chat while candidate types a message.

**Precondition:**

Candidate is matched with a job.

Environment is Windows10/Chrome and Android/Blackview A80 Pro.

Candidate is logged in on a mobile app.

HR/Company user is logged in web app,

**Steps to reproduce:**

1\. Open matched job on MOB (for example *Junior Python developer*).

2\. Type a message to matched job.

3\. At the same moment open MatChat on WEB: <https://company.matchit.rs/chat?match_id=166>

3\. Pay attention to the chat's bottom in the moment when candidate
types a message.

**Expected result:**

HR/Company user see the name of candidate while candidate types a
message, in this example is

. . . Tijana B is typing\...

**Actual result:**

Candidate's name while typing isn't displayed in HR/Company user's chat.
Instead of name is displayed

. . . {{ user }} is typing\...

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/0fa96640-8e71-4563-b2ce-d2c5ea669b10)

<hr>BUG11</hr>

**Summary:**

WEB - MatChat - Replied message in the \'Thread\' is displayed
vertically.

**Precondition:**

Candidate is matched with a job.

Environment is Windows10/Chrome.

HR/Company user is logged in.

**Steps to reproduce:**

1\. Go to the MatChat for example <https://company.matchit.rs/chat?match_id=166>

2\. Find message \'Vidimo se onda\' from candidate.

3\. Place the mouse cursor on the message.

4\. Choose icon Reply in the middle (2 arrows icon).

5\. Pay attention to message \'Vidimo se onda\' in Thread.

**Expected result:**

Opened field \'Thread\' should be enough expanded, so message can fit in
the field.

**Actual result:**

The replied message is displayed vertically.

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/897d01ad-91e9-49f8-8050-2ac6e3040e9b)
![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/da7655f6-2912-401e-8a91-cf15d439ab51)

<hr>BUG12</hr>

**Summary:**

WEB - MatChat - Typing message in the \'Thread\' isn't fully displayed.

**Precondition:**

Candidate is matched with a job.

Environment is Windows10/Chrome.

HR/Company user is logged in.

**Steps to reproduce:**

1\. Go to the MatChat for example <https://company.matchit.rs/chat?match_id=166>

2\. Find message \'Vidimo se onda\' from candidate.

3\. Place the mouse cursor on the message.

4\. Choose icon Reply in the middle (2 arrows icon).

6\. Type a message 123456 below 'Thread' field.

**Expected result:**

Opened field \'Thread\' should be enough expanded, so all text message
while typing can be seen.

**Actual result:**

Typed message in field below \'Thread\' is partial visible - only first
3 characters are visible.

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/cab74ead-4203-4aeb-8b90-a51cfd8b962e)
![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/85aca326-5dcc-475b-be86-cb0f1e86d6c5)

<hr>BUG13</hr>

**Summary:**

WEB - MatChat - Pinned message looks the same like unpinned.

**Precondition:**

Candidate is matched with a job.

Environment is Windows10/Chrome.

HR/Company user is logged in.

**Steps to reproduce:**

1\. Go to the MatChat for example <https://company.matchit.rs/chat?match_id=166>

2\. Find message \'Vidimo se onda\' from candidate.

3\. Place the mouse cursor on the message.

4\. Click icon three dots ('\...').

4\. Choose 'Pin'.

**Expected result:**

Pinned message change position, become highlihted and isolated from all
messages.

**Actual result:**

Pinned message in the MatChat remains at same position, doesn\'t isolate
from all messages.

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/f23a4eae-4c73-448a-9161-a5bc39cfd1e9)
![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/b02db72d-bdaf-4485-8563-83d8fa3f2522)
![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/3b124d26-4b61-480f-87bd-0bf9db39e9dc)

<hr>BUG14</hr>

**Summary:**

WEB - MatChat - List of messages with candidates aren't visible.

**Precondition:**

EnvironmentS are Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the link <https://company.matchit.rs/chat>

3.  Mouse right-click on the page \> Inspect

4.  Ctrl + Shift + M

5.  On top left choose *Dimensions: Galaxy Fold*

6.  Pay attention to chat's tab

**Expected result:**

On the left side are displayed candidate's names with messages.

**Actual result:**

Candidate's names with messages aren't displayed, instead of that is
empty gray background.

**Screenshoot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/592a21e9-6ecf-4333-bbe5-568c58f97fd2)

<hr>BUG15</hr>

**Summary:**

WEB - MatChat - Messages are displayed vertically.

**Precondition:**

Environments are Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to <https://company.matchit.rs/chat>

3.  Mouse right-click on the page \> Inspect

4.  Ctrl + Shift + M

5.  On the top left choose *Dimensions: Galaxy Fold*

6.  Pay attention to chat's tab

**Expected result:**

Display of chat's tab are enough expanded, so messages are displayed
horizontally.

**Actual result:**

Messages in chat are displayed vertically, like letter under letter.

**Screenshoot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/0fbabdee-fd56-476d-9000-0ec38c7b160f)

<hr>BUG16</hr>

**Summary:**

WEB - MatChat - First few letters of candidate's names and messages are
displayed.

**Precondition:**

Environments are Windows 10/Chrome and Samsung Galaxy A51/71 with
display's dimensions 412 x 914.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to <https://company.matchit.rs/chat>

3.  Mouse right-click on the page \> Inspect

4.  Ctrl + Shift + M

5.  On the top left choose *Dimensions: Samsung Galaxy A51/71*

6.  Pay attention to chat's tab

**Expected result:**

On the left side are completely displayed candidate's names with
messages.

**Actual result:**

On the left side of chat are first few letters of candidate's names
displayed, as well as messages.

**Note:**

Same is applicable for:

-   iPhone SE 375 x 667

-   iPhone XR 414 X 896

-   iPhone 12 Pro 390 x 844

-   iPhone 14 Pro Max 430 x 932

-   Pixel 7 412 x 915

-   Samsung Galaxy S8+ 360 x 740

-   Samsung Galaxy S20 Ultra 412 x 915

**Screenshoot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/a775a60a-0943-4819-a2c9-81815eae3dd2)

<hr>BUG17</hr>

**Summary:**

WEB - Oglasi - A vertical line crosses over words.

**Precondition:**

Environments are Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the any job's ad, example <https://company.matchit.rs/job-offers/18>

3.  Mouse right-click on page \> Inspect

4.  Ctrl + Shift + M

5.  On top left choose *Dimensions: Galaxy Fold*

6.  Go down to 'Projekat MatchIT' and pay attention to vertical grey line

**Expected result:**

Vertical line should stand by words.

**Actual result:**

Words are over vertical line.

**Note:**

Same is applicable for:

-   iPhone SE 375 x 667

-   iPhone XR 414 X 896

-   iPhone 12 Pro 390 x 844

-   iPhone 14 Pro Max 430 x 932

-   Pixel 7 412 x 915

-   Samsung Galaxy S8+ 360 x 740

-   Samsung Galaxy S20 Ultra 412 x 915

**Screenshoot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/896ba2d4-fe82-4109-b1a4-61b410c225ce)

<hr>BUG18</hr>

**Summary:**

WEB - Oglasi - Text about project ('O projektu') isn't beside the
vertical line.

**Precondition:**

Environments are Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the any job's ad, example <https://company.matchit.rs/job-offers/18>

3.  Mouse right-click on page \> Inspect

4.  Ctrl + Shift + M

5.  On top left choose *Dimensions: Galaxy Fold*

6.  Go down to 'Projekat MatchIT' and pay attention to 'O projektu'

**Expected result:**

Text about project ('O projektu') should stand beside the vertical line,
on the right side.

**Actual result:**

Text about project ('O projektu') is below the vertical line.

**Note:**

Same is applicable for:

-   iPhone SE 375 x 667

-   Samsung Galaxy S8+ 360 x 740

**Screenshoot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/199800f1-4625-47b9-af65-68be6a47c56d)

<hr>BUG19</hr>

**Summary:**

WEB - Oglasi - Icons for technologies are displayed small.

**Precondition:**

Environments are Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the any job's ad, example <https://company.matchit.rs/job-offers/18>

3.  Mouse right-click on page \> Inspect

4.  Ctrl + Shift + M

5.  On top left choose *Dimensions: Galaxy Fold*

6.  Go down to 'Tech Stack' and pay attention to 'Tehnologija'

**Expected result:**

Icons for listed technologies should be in size to be visible.

**Actual result:**

Icons for listed technologies have small size.

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/06e7b2c1-60f1-4663-9f8e-09cb9b151f83)

<hr>BUG20</hr>

**Summary:**

WEB - Izmena oglasa - Fields for years of experience are empty.

**Precondition:**

Environments are Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the any job's ad, example [https://company.matchit.rs/job-offers/99](https://company.matchit.rs/job-offers/99/edit)

3.  Click on 'Izmeni oglas'

4.  Mouse right-click on page \> Inspect

5.  Ctrl + Shift + M

6.  On top left choose *Dimensions: Galaxy Fold*

7.  Go down to 'Tech Stack' and pay attention to 'Godine iskustva'

**Expected result:**

Years of experience ('Godine iskustva') should be displayed in fields
for that like numbers.

**Actual result:**

Fields for years of experience ('Godine iskustva') are empty, no numbers
displayed there.

**Note:**

Same is applicable for:

-   iPhone SE 375 x 667

-   iPhone XR 414 X 896

-   iPhone 12 Pro 390 x 844

-   iPhone 14 Pro Max 430 x 932

-   Pixel 7 412 x 915

-   Samsung Galaxy S8+ 360 x 740

-   Samsung Galaxy S20 Ultra 412 x 915

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/64c18b40-4988-49c8-a407-6380a7b7a1e2)

<hr>BUG21</hr>

**Summary:**

WEB - Izmena oglasa - Words and icons are out of frame for various
fields.

**Precondition:**

Environments are Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the any job's ad, example [https://company.matchit.rs/job-offers/99](https://company.matchit.rs/job-offers/99/edit)

3.  Click on 'Izmeni oglas'

4.  Mouse right-click on page \> Inspect

5.  Ctrl + Shift + M

6.  On top left choose *Dimensions: Galaxy Fold*

7.  Go down below 'O projektu' and pay attention to all fields

**Expected result:**

Every field has own grey frame. Words, icons are inside that frame.

**Actual result:**

Words and icons are partially outside the frame.

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/b89b2445-e438-4f70-a719-0b27b5012e49)

<hr>BUG22</hr>

**Summary:**

WEB - Izmena oglasa - Fields for benefits ('Benefiti') are displayed
empty.

**Precondition:**

Environments are Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the any job's ad, example [https://company.matchit.rs/job-offers/99](https://company.matchit.rs/job-offers/99/edit)

3.  Click on 'Izmeni oglas'

4.  Mouse right-click on page \> Inspect

5.  Ctrl + Shift + M

6.  On top left choose *Dimensions: Galaxy Fold*

7.  Go down below 'O projektu' and pay attention to benefits ('Benefiti')

**Expected result:**

Chosen benefits ('Benefiti') should be displayed in fields for that.

Actual result:

Chosen benefits ('Benefiti') are displayed empty, like nothing choosed.

**Note:**

Same is applicable for:

-   iPhone SE 375 x 667

-   Samsung Galaxy S8+ 360 x 740

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/eb09d26b-3d52-4474-b7c7-1482c369d4bb)

BUG23

**Summary:**

WEB - Izmena oglasa - Fields for Neto salary in € ('Neto plata u €') are
displayed empty.

**Precondition:**

Environments are Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the any job's ad, example [https://company.matchit.rs/job-offers/99](https://company.matchit.rs/job-offers/99/edit)

3.  Click on 'Izmeni oglas'

4.  Mouse right-click on page \> Inspect

5.  Ctrl + Shift + M

6.  On top left choose *Dimensions: Galaxy Fold*

7.  Go down below 'O projektu' and pay attention to Neto salary in € ('Neto plata u €')

**Expected result:**

Chosen Min and Max Neto salary ('Neto plata u €') should be displayed in
fields for that.

**Actual result:**

Chosen Min and Max Neto salary ('Neto plata u €') are displayed empty,
like nothing choosed.

**Note:**

Same is applicable for:

-   iPhone SE 375 x 667

-   Samsung Galaxy S8+ 360 x 740

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/d5185c75-be70-4ffb-8b1b-38c9c29ceeac)

<hr>BUG24</hr>

**Summary:**

WEB - Deck Kandidata - Years of experience ('Iskustvo') can't be seen.

**Precondition:**

Environments are Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the candidate's deck, example <https://company.matchit.rs/job-offers/99/deck>

3.  Mouse right-click on page \> Inspect

4.  Ctrl + Shift + M

5.  On top left choose *Dimensions: Galaxy Fold*

6.  Pay attention to the right side beside technologies

**Expected result:**

Years of experiences are displayed beside technologies.

**Actual result:**

Years of experiences are shrinked and not visible.

**Note:**

Same is applicable for:

-   iPod Mini 768 x 1024

-   iPad Pro 1024 x 1366

-   Nest Hub 1024 x 600

**Screenshot:**

![image](https://github.com/TijanaBogovac/QA-Portfolio/assets/149398561/2fe44317-30a8-4914-b679-39044048b8bf)
