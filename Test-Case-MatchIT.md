# ﻿**TEST CASE**
### Test cases with State transition technique
 
<hr>Test case 1 </hr>

**Test case name:** Verify that Pop-up notification will appear on mobile when user got matched with a job.

**Description:** User swipes right a job ad on Start page (‘Početna’) of Mobile app. Next day user appeared in Candidate’s deck (‘Deck Kandidata’) which is visible to HR/Company user. HR/Company user ✔ (tick) the user, and that mean user got a matched job.

Verify that user got the Pop-up notification when became matched with a job. Via pop-up notification user will find out that has a matched job.

**Precondition:** User must like (swipe right) *Medior Android developer* job ad.

|No.|Test Steps|Test Data|Expected Results|
| :-: | :-: | :-: | :-: |
|1|User open MatchIT app.|MatchIT app on Android mobile|The app is open.|
|2|Click on Start page (‘Početna’).||Different job offers appeared on the page.|
|3|Swipe right for a job *Medior Android developer* job ad.||After midnight user will appear in Candidate’s Deck for HR/Company user.|
|4|Next day, in Web app, HR/Company user visit matchIT website.|<https://company.matchit.rs/job-offers>|Website is open with full list of job’s offers.|
|5|HR/Company user click on Candidate’s deck (‘Deck Kandidata’) for *Medior Android developer* job ad.|<https://company.matchit.rs/job-offers/19/deck>|Candidates appeared on the page.|
|6|HR/Company user decline/approve candidates unless candidate’s profile from Precondition appear.||Candidate from Precondition appears.|
|7|HR/Company user ✔ (tick) that candidate.||Candidate is matched with a job. |
|8|User checks notifications on the mobile phone.|User’s mobile|<p>Pop-up notification “ # It’s Match </p><p>Čestitamo na uspešnom povezivanju kompanije Match IT  za poziciju Medior Android developer sa kandidatom Tijana B.</p><p>&NewLine;</p><p>## Poklapanja</p><p>- 50% po tehnologiji</p><p>- 100% po plati</p><p>- 100 % po benefitima</p><p>… “</p><p>appeared on user’s mobile display screen. User find out that got matched with a liked job.</p>|

<hr>Test case 2</hr>

**Test case name:** Verify that user receive a Pop-up notification for new messages on mobile phone.

**Description:** User swipes right a job ad on Start page of a Mobile app (‘Početna’). Next day user appeared in Candidate’s deck (‘Deck Kandidata’) which is visible to HR/Company user on Web app. HR/Company user ✔ the user. That mean user got a matched job, so HR/Company can start a conversation with user on chat.

Verify that user received a Pop-up notifications when got a message from HR/Company user.

**Precondition:** User is matched with a job and has chat.

|No.|Test Steps|Test Data|Expected Results|
| :-: | :-: | :-: | :-: |
|1|User open MatchIT app.|MatchIT app on mobile phone|The app is open.|
|2|Click on Start page (‘Početna’).||Different job offers appeared on the page.|
|3|Swipe right for a job ad *Medior Android developer*.||After midnight user will appear in Candidate’s Deck for HR/Company user.|
|4|Next day, HR/Company user visit matchIT website from Web App.|<https://company.matchit.rs/job-offers>|Website is open with full list of job’s offers.|
|5|HR/Company user click on Candidate’s deck (‘Deck Kandidata’) for *Medior Android developer* job ad.|<https://company.matchit.rs/job-offers/19/deck>|Candidates appeared on the page.|
|6|HR/Company user decline/approve candidates unless candidate’s profile from Precondition appear.||Candidate from Precondition appears.|
|7|HR/Company user ✔ (tick) that candidate. ||Candidate became matched with a job. |
|8|HR/Company user go to Job’s offer page.|<https://company.matchit.rs/job-offers>|Job’s offer page has been opened.|
|9|HR/Company user click on Matches for *Medior Android developer* job ad.|<https://company.matchit.rs/job-offers/19/matches>|Matches candidates has been appeared.|
|10|HR/Company user click MatChat button for wanted matched candidate.||Chat with matched candidate has been opened. |
|11|HR/Company user write a text message and click arrow for sending.|Hello|The message has been sent to matched candidate.|
|12|Candidate checks the notifications on his phone.|User’s mobile phone|Pop-up notification appeared on user’s mobile display screen. User find out that got a message on MatChat.|

### <hr>Test cases with Boundary value analysis</hr>
<hr>Test case 3</hr>

**Test case name:** Verify that user can’t send empty message via MatChat on a Mobile app.

**Description:** Verify when user open MatChat on his mobile and start chat with matched job, if user wants to send empty message to potential employer, app will not allow that. Arrow for sending messages will be frozen if there is no character in message.

**Precondition:** User must be matched with job.

|No.|Test Steps|Test Data|Expected Results|
| :-: | :-: | :-: | :-: |
|1|User open MatchIT app.|MatchIT app on mobile phone|The app is open.|
|2|Click on Matches (‘Mečevi)’.||Matches tab is open.|
|3|Click on matched job.||MatChat is open.|
|4|Click down right arrow for sending to send empty message.||It’s not allowed to send empty message. Arrow for sending is disabled.|

<hr>Test case 4</hr>

**Test case name:** Verify that min. number of character which user can send to matched job in MatChat, on mobile app, is 1.

**Description:** Verify when user open MatChat on his mobile and start chat with matched job, if user wants to send only one character in message to potential employer, the message will be sent successfully.

**Precondition**: User must be matched with job.

|No.|Test Steps|Test Data|Expected Results|
| :-: | :-: | :-: | :-: |
|1|User open MatchIT app.|MatchIT app onAndroid mobile|The app is open.|
|2|Click on Matches (‘Mečevi)’.||Matches tab is open.|
|3|Click on matched job.||MatChat is open.|
|4|Fill bottom field where is text ‘Write something here’ with only one character.|1|Mesage ‘1’ has been sent to matched job.|

<hr>Test case 5</hr>

**Test case name:** Verify that Error message will appear if user send a message with 5001 characters to matched job in MatChat.

**Description:** Verify when user open MatChat on his mobile and start chat with matched job, if user wants to send 5001 characters to potential employer, the Error message ‘Max. message length (5000) exceeded.’ will appear in chat. 

**Precondition**: User must be matched with job.

|No.|Test Steps|Test Data|Expected Results|
| :-: | :-: | :-: | :-: |
|1|User open MatchIT app.|MatchIT app on Android mobile|The app is open.|
|2|Click on Matches (‘Mečevi)’.||Matches tab is open.|
|3|Click on matched job.||MatChat is open.|
|4|Fill bottom field where is text ‘Write something here’ with 5001 characters and click right arrow for sending.|Random string with 5001 characters|Error message ‘Max. message length (5000) exceeded.’ appears in chat.|

<hr>Test case 6</hr>

**Test case name:** Verify that user can send 5000 characters to matched job in MatChat.

**Description:** Verify when user open MatChat on his mobile and start chat with matched job, If user wants to send the message with 5000 characters, the message will be send successfully.

**Precondition**: User must be matched with job.

|No.|Test Steps|Test Data|Expected Results|
| :-: | :-: | :-: | :-: |
|1|User open MatchIT app.|MatchIT app on Android mobile|The app is open.|
|2|Click on Matches (‘Mečevi)’.||Matches tab is open.|
|3|Click on matched job.||MatChat is open.|
|4|Fill bottom field where is text ‘Write something here’ with 5000 characters and click right arrow for sending.|Random string with 5000 characters|Message has been sent to matched job.|

