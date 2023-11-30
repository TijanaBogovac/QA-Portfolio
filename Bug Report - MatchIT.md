**BUG REPORT**

BUG1

Summary:

WEB - Two fields Benefits and Work Methods ('Benefiti' i 'Načini rada')
aren\'t visible in the created job ad.

Precondition:

Environment is Windows 10/Chrome.

Steps to reproduce:

1.  Log in to <https://company.matchit.rs/>

2.  Click on button Add job ad ('+Dodaj oglas')

3.  Fill all fields and click on Create ('Kreiraj)

4.  Go to link <https://company.matchit.rs/job-offers> and find newly
    > created job ad

5.  Click on created job ad

Expected result:

Benefits and Work Methods ('Benefiti' i 'Načini rada') should be visible
in created job ad same as in edit mode.

Actual result:

Sections Benefits and Work Methods are missing in created job ad.

Screenshot:

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image12.png){width="6.5in"
height="3.5833333333333335in"}

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image4.png){width="6.5in"
height="4.541666666666667in"}

BUG2

Summary:

WEB - Some words are misspelled.

Precondition:

Environment is Windows 10/Chrome.

HR/Company user is logged in.

Expected result:

Serbian letters are used in the whole application.

Actual result:

-   WEB - **'Oglasi'** - In created job ad, letter c (instead of serbian
    > letter č) was used in \'Nacin razvoja\' and \'Broj clanova\'
    > options

-   WEB - **'Deck kandidata'** - In the message appeared after
    > HR/Company user finished choosing all candidates, was used letter
    > dj (instead of serbian letter đ) in word \'medjuvremenu\'.

Screenshot:

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image35.png){width="6.5in"
height="3.486111111111111in"}

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image8.png){width="6.5in"
height="3.5277777777777777in"}

BUG3

Summary:

MOB - Word is misspelled.

Precondition:

Environment is Android/Blackview A80 Pro.

Candidate is logged in.

Expected result:

Serbian letters are used in the whole application.

Actual result:

-   MOB - **'Profil'** - Letter z (instead of serbian letter ž) was used
    > in 'Veštine i bedzevi'

Screenshot:

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image1.png){width="1.808682195975503in"
height="3.682292213473316in"}

BUG4

Summary:

WEB - Created job ad text doesn\'t display Enter to separate new row.

Precondition:

Environment is Windows 10/Chrome.

Steps to reproduce:

1\. Log in to <https://company.matchit.rs/>

2\. Click on button Add job ad ('+Dodaj oglas')

3\. Fill all fields

4\. In field About project ('O projektu') use Enter to put text in new
row.

5\. Click button Create ('Kreiraj')

6\. Go to link <https://company.matchit.rs/job-offers> and find newly
created job ad

7\. Pay attention to field About project ('O projektu')

Expected result:

When HR/Company writes a job ad, text should looks identical in made job
ad. If text is divided into two paragraphs, text should be two
paragraphs.

Actual result:

In created job ad, text in section About project ('O projektu) is one
paragraph, although text was edited in two paragraphs.

Screenshoot:

**Edit version:**

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image11.png){width="6.5in"
height="0.8472222222222222in"}

**How it looks in created job ad:**

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image13.png){width="5.057292213473316in"
height="0.937587489063867in"}

BUG5

Summary:

MOB - The counter shows the number of technologies over the limit when
the user logs in for the first time.

Precondition:

Environment is Android/Blackview A80 Pro.

Steps to reproduce:

1.  Log in to application for the first time.

2.  Fill in Name and Surname.

3.  Choose maximum allowed random technologies.

4.  Pay attention how many technologies counter shows.

Expected result:

When user Log In for the 1st time on Mobile app. the maximum allowed
number of technologies which user can choose is 20.

Actual result:

The user selected 21 technologies.

Screenshot:

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image32.png){width="2.0881310148731407in"
height="4.328125546806649in"}

BUG6

Summary:

MOB - The counter shows less selected technologies when user unselect
and select technologies again.

Precondition:

Environment is Android/Blackview A80 Pro.

Steps to reproduce:

1.  Log in to application for the first time.

2.  Fill in Name and Surname.

3.  Choose maximum allowed random technologies (20).

4.  Uncheck few technologies.

```{=html}
<!-- -->
```
5.  Check random technologies to be maximum allowed (20).

Expected result:

When user Log In for the 1st time on Mobile app. the maximum allowed
number of technologies which user can choose is 20.

Actual result:

After user deselected few technologies and selected few more, the
counter shows number of maximum allowed technologies less then 20. And
every time when repeating actions check/uncheck, number of allowed
technologies is less and less.

BUG7

Summary:

MOB - The sections are cut off on the particular tabs in the Profile
tab.

Precondition:

Use mobile with bigger display screen.

Environment is Android/Blackview A80 Pro with **6.49 inch** display
screen.

Steps to reproduce:

1.  Log in Mobile App and choose Profile ('Profil').

2.  Choose Certificates ('Sertifikati')

3.  Click button Add certificate ('Dodaj sertifikat').

4.  Fill in all fields and click Save ('Sačuvaj').

5.  Repeat 3 more times Steps 3, 4.

Expected result:

Section should be displayed as a whole.

Actual result:

If mobile device has bigger screen size display, then section
Certificates ('Sertifikati') is cut off.

Note:

The same applies to sections Education ('Edukacija') and Skills and
Badges ('Veštine i Bedzevi').

Screenshot:

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image9.png){width="2.461233595800525in"
height="4.182292213473316in"}![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image34.png){width="2.5156255468066493in"
height="4.211809930008749in"}![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image29.png){width="2.075288713910761in"
height="4.432292213473316in"}

BUG8

Summary:

WEB - Word \'None\' is displayed for candidate with a lot of experience.

Description:

In job ad (for example *Junior Python developer*) are listed 2 wanted
technologies. Candidate has high experience in both wanted technologies.

When HR/Company user look at candidate's Profile ('Profil kandidata')
and candidate's experience ('Iskustvo'), word 'None' is visible on the
beginning of candidate's listed experiences.

Precondition:

Candidate is matched with a job.

Environment is Windows10/Chrome.

HR/Company user is logged in.

Steps to reproduce:

1\. Go to candidate's profile, example for
<https://company.matchit.rs/job-offers/24/matches/166/candidate>

2\. Pay attention to Experience (\'Iskustvo\') and the beggining of the
experience's list.

Expected result:

If candidate has an experience in listed job ad's technologies, word
'None' isn't visible.

Actual result:

Candidate with a lot of experience has word \'None\' in Experience
section ('Iskustvo').

Screenshot:

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image25.png){width="6.5in"
height="3.6805555555555554in"}

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

BUG9

Summary:

MOB/WEB - Candidate can\'t see own text message sent together with GIF
to matched job.

Description:

When candidate sent text message with GIF to matched job, only GIF
appeared to candidate in chat, while HR/Company user can see complete
candidate's message (GIF and text message).

Precondition:

Candidate is matched with a job.

Environment is Android/Blackview A80 Pro and Windows10/Chrome.

Candidate is logged in on a mobile app.

HR/Company user is logged in web app,

Steps to reproduce:

1\. Opet matched job on MOB.

2\. Write text message with GIF animation.

2\. Send a message.

3\. Open MatChat on WEB <https://company.matchit.rs/chat>

4\. Check new message from candidate.

Expected result:

Candidate see a complete message (text and GIF) which sent to matched
job same how HR/Company user see It.

Actual result:

Candidate see only a GIF which was sent to matched job along with text.

Screenshot:

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image33.png){width="2.694837051618548in"
height="5.494792213473316in"}

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image18.png){width="5.119231189851269in"
height="3.151042213473316in"}

BUG10

Summary:

WEB/MOB - Candidate's name is displayed as {{ user }} on HR/Company
user's chat while candidate types a message.

Precondition:

Candidate is matched with a job.

Environment is Windows10/Chrome and Android/Blackview A80 Pro.

Candidate is logged in on a mobile app.

HR/Company user is logged in web app,

Steps to reproduce:

1\. Open matched job on MOB (for example *Junior Python developer*).

2\. Type a message to matched job.

3\. At the same moment open MatChat on WEB:

<https://company.matchit.rs/chat?match_id=166>

3\. Pay attention to the chat's bottom in the moment when candidate
types a message.

Expected result:

HR/Company user see the name of candidate while candidate types a
message, in this example is

. . . Tijana B is typing\...

Actual result:

Candidate's name while typing isn't displayed in HR/Company user's chat.
Instead of name is displayed

. . . {{ user }} is typing\...

Screenshot:

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image26.png){width="6.5in"
height="3.75in"}

BUG11

Summary:

WEB - MatChat - Replied message in the \'Thread\' is displayed
vertically.

Precondition:

Candidate is matched with a job.

Environment is Windows10/Chrome.

HR/Company user is logged in.

Steps to reproduce:

1\. Go to the MatChat for example
<https://company.matchit.rs/chat?match_id=166>

2\. Find message \'Vidimo se onda\' from candidate.

3\. Place the mouse cursor on the message.

4\. Choose icon Reply in the middle (2 arrows icon).

5\. Pay attention to message \'Vidimo se onda\' in Thread.

Expected result:

Opened field \'Thread\' should be enough expanded, so message can fit in
the field.

Actual result:

The replied message is displayed vertically.

Screenshot:

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image15.png){width="6.5in"
height="3.7916666666666665in"}

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image23.png){width="6.5in"
height="3.986111111111111in"}

BUG12

Summary:

WEB - MatChat - Typing message in the \'Thread\' isn't fully displayed.

Precondition:

Candidate is matched with a job.

Environment is Windows10/Chrome.

HR/Company user is logged in.

Steps to reproduce:

1\. Go to the MatChat for example
<https://company.matchit.rs/chat?match_id=166>

2\. Find message \'Vidimo se onda\' from candidate.

3\. Place the mouse cursor on the message.

4\. Choose icon Reply in the middle (2 arrows icon).

6\. Type a message 123456 below 'Thread' field.

Expected result:

Opened field \'Thread\' should be enough expanded, so all text message
while typing can be seen.

Actual result:

Typed message in field below \'Thread\' is partial visible - only first
3 characters are visible.

Screenshot:

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image15.png){width="6.5in"
height="3.7916666666666665in"}

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image31.png){width="6.5in"
height="3.8194444444444446in"}

BUG13

Summary:

WEB - MatChat - Pinned message looks the same like unpinned.

Precondition:

Candidate is matched with a job.

Environment is Windows10/Chrome.

HR/Company user is logged in.

Steps to reproduce:

1\. Go to the MatChat for example
<https://company.matchit.rs/chat?match_id=166>

2\. Find message \'Vidimo se onda\' from candidate.

3\. Place the mouse cursor on the message.

4\. Click icon three dots ('\...').

4\. Choose 'Pin'.

Expected result:

Pinned message change position, become highlihted and isolated from all
messages.

Actual result:

Pinned message in the MatChat remains at same position, doesn\'t isolate
from all messages.

Screenshot:

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image16.png){width="5.135416666666667in"
height="3.78125in"}

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image21.png){width="5.072916666666667in"
height="4.03125in"}

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image28.png){width="6.5in"
height="3.875in"}

BUG14

**Summary:**

WEB - MatChat - List of messages with candidates aren't visible.

**Precondition:**

Environment is Windows 10/Chrome and Galaxy Fold mobile phone with
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

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image3.png){width="2.8926465441819773in"
height="5.432292213473316in"}

BUG15

**Summary:**

WEB - MatChat - Messages are displayed vertically.

**Precondition:**

Environment is Windows 10/Chrome and Galaxy Fold mobile phone with
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

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image17.png){width="2.9154713473315836in"
height="4.786458880139983in"}![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image5.png){width="2.7041688538932633in"
height="4.161458880139983in"}

BUG16

**Summary:**

WEB - MatChat - First few letters of candidate's names and messages are
displayed.

**Precondition:**

Environment is Windows 10/Chrome and Samsung Galaxy A51/71 with
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

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image7.png){width="3.585883639545057in"
height="4.067708880139983in"}

BUG17

**Summary:**

WEB - Oglasi - A vertical line crosses over words.

**Precondition:**

Environment is Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the any job's ad, example
    > <https://company.matchit.rs/job-offers/18>

3.  Mouse right-click on page \> Inspect

4.  Ctrl + Shift + M

5.  On top left choose *Dimensions: Galaxy Fold*

6.  Go down to 'Projekat MatchIT' and pay attention to vertical grey
    > line

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

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image30.png){width="2.84375in"
height="5.5in"}

BUG18

**Summary:**

WEB - Oglasi - Text about project ('O projektu') isn't beside the
vertical line.

**Precondition:**

Environment is Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the any job's ad, example
    > <https://company.matchit.rs/job-offers/18>

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

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image14.png){width="3.213542213473316in"
height="5.1246784776902885in"}

BUG19

**Summary:**

WEB - Oglasi - Icons for technologies are displayed small.

**Precondition:**

Environment is Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the any job's ad, example
    > <https://company.matchit.rs/job-offers/18>

3.  Mouse right-click on page \> Inspect

4.  Ctrl + Shift + M

5.  On top left choose *Dimensions: Galaxy Fold*

6.  Go down to 'Tech Stack' and pay attention to 'Tehnologija'

**Expected result:**

Icons for listed technologies should be in size to be visible.

**Actual result:**

Icons for listed technologies have small size.

**Screenshot:**

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image22.png){width="4.260416666666667in"
height="5.6875in"}

BUG20

**Summary:**

WEB - Izmena oglasa - Fields for years of experience are empty.

**Precondition:**

Environment is Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the any job's ad, example
    > [https://company.matchit.rs/job-offers/99](https://company.matchit.rs/job-offers/99/edit)

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

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image20.png){width="2.557292213473316in"
height="4.091666666666667in"}

BUG21

**Summary:**

WEB - Izmena oglasa - Words and icons are out of frame for various
fields.

**Precondition:**

Environment is Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the any job's ad, example
    > [https://company.matchit.rs/job-offers/99](https://company.matchit.rs/job-offers/99/edit)

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

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image24.png){width="2.806427165354331in"
height="5.109375546806649in"}![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image19.png){width="3.2315999562554683in"
height="3.008423009623797in"}

BUG22

**Summary:**

WEB - Izmena oglasa - Fields for benefits ('Benefiti') are displayed
empty.

**Precondition:**

Environment is Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the any job's ad, example
    > [https://company.matchit.rs/job-offers/99](https://company.matchit.rs/job-offers/99/edit)

3.  Click on 'Izmeni oglas'

4.  Mouse right-click on page \> Inspect

5.  Ctrl + Shift + M

6.  On top left choose *Dimensions: Galaxy Fold*

7.  Go down below 'O projektu' and pay attention to benefits
    > ('Benefiti')

**Expected result:**

Chosen benefits ('Benefiti') should be displayed in fields for that.

**Actual result:**

Chosen benefits ('Benefiti') are displayed empty, like nothing choosed.

**Note:**

Same is applicable for:

-   iPhone SE 375 x 667

-   Samsung Galaxy S8+ 360 x 740

**Screenshot:**

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image10.png){width="2.2496139545056866in"
height="4.338542213473316in"}

BUG23

**Summary:**

WEB - Izmena oglasa - Fields for Neto salary in € ('Neto plata u €') are
displayed empty.

**Precondition:**

Environment is Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the any job's ad, example
    > [https://company.matchit.rs/job-offers/99](https://company.matchit.rs/job-offers/99/edit)

3.  Click on 'Izmeni oglas'

4.  Mouse right-click on page \> Inspect

5.  Ctrl + Shift + M

6.  On top left choose *Dimensions: Galaxy Fold*

7.  Go down below 'O projektu' and pay attention to Neto salary in €
    > ('Neto plata u €')

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

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image27.png){width="3.0504713473315834in"
height="3.458938101487314in"}![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image6.png){width="2.4119739720034996in"
height="2.586975065616798in"}

BUG24

**Summary:**

WEB - Deck Kandidata - Years of experience ('Iskustvo') can't be seen.

**Precondition:**

Environment is Windows 10/Chrome and Galaxy Fold mobile phone with
display's dimensions 280 x 653.

**Steps to reproduce:**

1.  Log in to the <https://company.matchit.rs/>

2.  Go to the candidate's deck, example
    > <https://company.matchit.rs/job-offers/99/deck>

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

![](vertopal_21f27a23018d418d878f5639f547aa4d/media/image2.png){width="1.9796751968503936in"
height="2.5364588801399823in"}
