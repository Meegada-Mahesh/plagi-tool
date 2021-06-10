# plagi-tool
This is a plagiarism detection tool used for text, image, video and audio formats written in Golang

Step 1:- 
Create a Portal which accepts different formats of content

Step 2:-
Detect for Plagiarism


There are four formats for this tool.

1) Text
2) Audio
3) Image
4) Video

Plagiarised content will be categorised and given percent between 0 - 100 %

1) Fully Plagiarised (100 %)
2) Partial Plagiarised (0-100%)

**User can select below modes:-**

1) Instant Mode (while posting a content it will be checked), original owner who posted will have an option to check
2) Relaxed Mode (Can request portal after some time for check), search using timestamps for original owners
3) Claim Mode (Can raise issue, after owner detects plagiarism). Its more of an action based on results from above two modes

**Key Terminologies:-**

1) Front (Initial 5% of content)
2) Back (Last 5% of content)
3) Middle (5< X < 95) of content

**Cases to check plagiarism:-**

**Removed cases:-**

1) Content removed from front
2) Content removed from back
3) Content removed from front & back

**Insert Cases:-**

1) Inserted in middle with no deletion
2) Inserted in front with no deletion
3) Inserted in back with no deletion

**Mixed Cases:-**

1) Inserted from middle & removed from middle
2) Inserted from front & removed from middle
3) Inserted from back & removed in middle
4) Inserted from middle & removed from back
5) Inserted from front & removed from back
6) Inserted from back & removed from front
7) Inserted from middle & remooved from front
8) Insert from front & remove from front
9) Insert from back & remove from back

**Challenges/Tasks to be Completed:-**

1) Dividing content into multiple chunks and hashing
2) Db design
3) Folder and Architecture setup
4) Detecting insertion/deletion from FRONT, BACK and MIDDLE
5) Implementing instant mode
6) Implementnig relaxed mode
7) Implementing claim mode
8) Detecting Fully plagiarised content 
9) Detecting Partial plagiarised content
10) Calculating approx percentage of plagiarised content
11) Alert system for original owner if plagiarised content percent exceeds 51%
12) Reporting system and Content deletion if match detected
13) Optimizing Mixed cases
14) If video/ image/ audio ... implement system for multiple formats and resolutions
15) Encoding/ Decoding/ Compression techniques from uploaded content (except text)
16) Implementing search feature for text content
17) Implement UI
18) Exploring algos for compression, search, hashing, randomization, encoding, decoding, sorting
19) Setting up debug env
20) Track for content changes from original owner/ figuring out where the content is modified by plagiarist
21) Rewarding cryptos/ coins for original content creators

