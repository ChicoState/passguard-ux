# Phase II : Refining interaction and designing wireframes

## Introduction

Our last report established the foundation of our project by outlining core functionalities such as password addition and password strength checking. </br>

The primary goal for this sprint was to implement general user functions - specifically login, sign-up, and password strength feedback, and to further develop the layout of our site. These elements were visualized through a wireframe and evaluated to assess the overall usability of our current design. <br/>

## Methods

### **Cognitive Walkthrough**<br/>
   Two users independently walked through our [wireframe](wireframes/). Each user was assigned one of our existing personas : <br/>
   
   * "_Grandpa Joe_ : A 75-year-old man, who lives with his wife, and is retired. His kids want to keep in contact with him, but Joe is scared that he would not be able to remember any of his passwords" <br/>
   * "_Tiffany_ : A 32-year-woman  who works in the fashion industry, Tiffany works on the cloud, and many other programs." <br/>
   
For each task (signing up, adding passwords), participants answered: <br/>

   * **Will the user know what to do at this step?** <br/>
   * **If the user does the right thing will they know they are making progress?**


   This feedback helped us identify where the interface was intuitive and where users may encounter some confusion.
### **Informal Feature Survey**<br/>
   We also conducted an informal survey of the software class (approximately **n=35**), we asked :<br/>
   -_"What features would you want in an app like this?"_ <br/>
   The insights acquired from this survey were used to guide our wireframe design and ensure that the app aligned with user needs.

## Findings

### **Cognitive Walkthrough** <br/>
**Grandpa Joe**<br/>
   * **Concern over forgetting master password** <br/>
      Joe's persona highlighted the potential risk of being locked out if he forgets his master password - recreating the original problem the app was designed to solve. <br/>
   * **Overwhelm due to complexity of features** <br/>
      The interface may be overwhelming for less tech-savvy users like Joe. <br/>
   * **Lack of confirmation screens** <br/>
      Joe's walkthrough also highlighted a concern that overwriting existing passwords could happen accidentally, as no confirmation screens were present. <br/>
   
**Tiffany**<br/>
   * **Unclear copy feedback** <br/>
      The interface provided no visual or audio confirmation that the copy button was pressed, this can lead to uncertainty whether the action succeeded or not. <br/>
   * **Search functionality questions** <br/>
      Tiffany raised the question of how a search bar should work - whether it filters results live, is case-sensitive, or searches by site name or username. <br/
   * **Missing Sign-Up Page** <br/>
      Both Tiffany and Joe's walkthroughs revealed the absence of a sign-up page, a basic but essential part of onboarding <br/>

### **User Survey** <br/>
An informal survey of ~35 students in our software engineering course revealed a broader view of desired features and pain points. <br/>
**Requested Features**<br/>
   * **Copy Button** <br/>
     Users wanted a quick and easy way to copy passwords or usernames. <br/>
   * **Browser Extension** <br/>
     Some users expressed interest in a browser extension for auto-filling and password syncing. <br/>
   * **Searchability for a Site's Password** <br/>
     Users want to be able to quickly find credentials using a search bar <br/>
   * **Stay Logged in** <br/>
     Several users noted that frequent logins can become annoying and wanted an option to remain logged in for longer sessions <br/>

## Conclusions

From our research methods, we were able to obtain key insights into user needs, usability gaps, and expectations : <br/>

### **From the Cognitive Walkthrough** <br/>
   * **Missing Sign-Up Page Identified** <br/>
      Both users expected a sign-up option during the Walkthrough and were confused by its absence. <br/>
      - _UX Insight_ : Users rely on familiar, conventional user flows, absence of expected elements can lead to confidence in the interface decreasing. <br/>
      - _Design Recommendation_ : Include a clearly labeled sign-up page and guide new users through onboarding. <br/>
   * **Concern Over Forgetting The Master Password** <br/>
      Users like Joe were especially anxious about being locked out of the password manager due to forgetting their password. <br/>
      - _UX Insight_ : Users need to feel secure, but also reassured that recovery is possible. <br/>
      - _Design Recommendation_ : Implement a secure and user-friendly password recovery system or backup  method. <br/>

### **From Informal User Survey** <br/>
   * **Desire for Quick and Easy Access to Functions** <br/>
      Many respondents emphasized the desire to access the app's features without extra steps or confusion. <br/>
      - _UX Insight_ : Reducing steps in navigation and interactions is essential for user retention and satisfaction. <br/>
      - _Design Recommendation_ : Minimize the number of clicks needed to access key features, and implement shortcuts or streamlined menus. <br/>
   * **Request for Copy Button Functionality** <br/>
      Users mentioned that copying sensitive information (like passwords) should be quick and seamless. <br/>
      - _UX Insight_ : Small convenience features can have a large impact on perceived usability. <br/>
      - _Design Recommendation_ : Add a clearly visible and accessible "Copy" button for relevant fields <br/>

## Caveats

While our findings provided valuable insights into usability and user needs, there are several limitations to our research methods and sample : <br/>
   * **Limited User Demographics** <br/>
      Since our research participants were primarily drawn from UX and software engineering classes. This creates a blind spot in understanding how average, less tech-savvy users might interact with the application. <br/>
   * **Feedback Filtered Through Prior Knowledge** <br/>
      Participants had prior exposure to concepts such as interface design, coding practices, and usability principles. This results in their feedback being based on technical understanding, which may not reflect the experience of a general user. <br/>
   * **Classroom Context and Informality** <br/>
      Since both the cognitive walkthrough and survey were conducted in academic settings, responses may have lacked the formality that real-world usability testing would've encouraged. Formal usability testing with a broader and more varied user base would offer more representative data
   * **Assumptions in Persona User** <br/>
      Cognitive walkthroughs were conducted using personas rather than real users fitting those profiles. This may introduce assumptions about how such users might behave, rather than observing how they actually interact with the app.<br/>

**Future Direction** : In future testing, we should focus on including a more diverse participant pool outside of technical disciplines, incorporate real users that reflect our personas, and conduct structured usability testing to gain more representative data.
