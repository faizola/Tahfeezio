# MY FINAL PROJECT (Web App Track)
## Title: Tahfeezio Quran Memorisation Buddy

### Problem Statement
As part of his religious studies, my son needs to memorise lots of verses within a short period of time and it can be a feat sometimes.
We have a 'system' of learning that has been working for us (through trial and error) but it's really manual and hard to keep track of progress.
What I want to be able to do is create a web app for it to help him track his memorisation and to gamify the process so it makes it more enjoyable and 'sticky'.

### Business Requirements
| BR id | Requirement                                                              | Rationale                                                                                                   |
|-------|--------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| BR1   | Solution to digitise book and its texts                                  | - To make it easier to extract text in whole/parts<br>- To enable access from anywhere online               |
| BR2   | Solution to gamify process of memorisation                               | - To make it more interesting<br>- To make memorisation long-lasting<br>- To allow tracking of progress     |
| BR3   | Solution to allow Teacher role to set challenge<br> and monitor progress | - To allow customisation of challenge set<br>- To allow followup in physical form to complement application |

### User Requirements
| UR id | Requirement                                                                                                                                                | Rationale                                                                               | Parent  |
|-------|------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|--------------------|
| UR1   | List of chapters as a selection displayed by<br>chapter number, title, (number of verses)                                                                  | Teachers to select chapter as 'challenge' for students<br>to focus on                   | BR1                |
| UR2   | List of verses                                                                                                                                             | Students to be shown verses by ascending<br>order for memorisation challenge            | BR1                |
| UR3   | Students to select chapter to focus on                                                                                                                     | Students to be able to focus on one chapter at a time<br>for best results               | BR2                |
| UR4   | `chapter` in focus where students can click on<br>to resume activity                                                                                       | Students know which chapter they are focusing<br>on for their challenge                 | BR3                |
| UR5   | Audio of `verse` can be played manually by clicking<br>on play icon                                                                                        | Students can hear how verse is to be read<br>so they can model the reading              | BR1                |
| UR6   | Single verse is shown for student in an<br>`activity`                                                                                                      | For students to focus on memorising a particular<br>verse                               | BR2                |
| UR7   | Audio recording of verse is played automatically 3 times<br><br>for student to read-along in an activity                                                   | Students to acquaint with how verse is to be read                                       | BR1                |
| UR8   | Activity for students to drag and drop `words`<br>in a verse and arrange it in correct order                                                               | For students to ensure memorisation                                                     | BR2                |
| UR9   | Single verse can be marked as completed <br>(default status is empty circle)                                                                               | Students can denote verse as memorised to progress on<br>to the next verse in challenge | BR2                |
| UR10  | Completed verse is added to a list in another<br>activity                                                                                                  | For students to recall all memorised verses <br>to ensure 'stickability'                | BR2                |
| UR11  | Activity for students to arrange verses in<br>correct order                                                                                                | For students to recall proper order of verses<br>in a chapter                           | BR2                |
| UR12  | Automated flow of activities for each `session`                                                                                                            | Students sit in a session per daily login (or more)                                     | BR2                |
| UR13  | Activity for student to record an audio/video of reading                                                                                                   | To allow teachers to check on reading competency                                        | BR2                |
| UR14  | Teacher can add comment to reading submission                                                                                                              | To allow teachers to give comments for improvements                                     | BR3                |
| UR15  | Teacher can add score to reading submission                                                                                                                | To allow teachers to mark and manage scores for `class`                                 | BR3                |
| UR16  | Log in as a student or a teacher                                                                                                                           | Allow access to different part of the application <br>under a different role            | BR3                |
| UR17  | Sessions are saved at every point                                                                                                                          | To allow students to pause halfway and resume at <br>another time                       | BR2                |
| UR18  | Progress is saved at every point                                                                                                                           | To allow students to continue progress and teachers<br>to monitor and track progress    | BR2                |
| UR19  | Students to have unique Student ID                                                                                                                         | To facilitate user management                                                           | BR3                |
| UR20  | Teachers to have unique Teacher ID                                                                                                                         | To facilitate class management                                                          | BR3                |
| UR21  | Student can add themselves to a `class` by adding<br>Teacher ID                                                                                            | To facilitate class management                                                          | BR3                |
| UR22  | Teacher can remove student(s) from class                                                                                                                   | To facilitate class management                                                          | BR3                |
| UR23  | One student can have only one teacher                                                                                                                      | To facilitate class management                                                          | BR3                |
| UR24  | Teacher can create `challenge` of completing chapter<br>by a fixed date-time with submission in the form of<br>video recording                             | To allow teacher to set pace of learning                                                | BR3                |
| UR25  | Teacher can create challenge of completing verse-from to<br>verse-till of a chapter by a fixed date-time with<br>submission in the form of video recording | To allow teacher to set pace of learning                                                | BR3                |
| UR26  | Teachers can name a challenge                                                                                                                              | To manage challenges                                                                    | BR2                |
| UR27  | List of challenge for students                                                                                                                             | To allow students to participate in challenge                                           | BR2                |




