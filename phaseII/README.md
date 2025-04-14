# Phase II: Refining interaction and designing wireframes

## Introduction

Our last report established the foundation of our project by outlining core functionalities such as password addition and password strength checking. </br>

The Primary goal for this sprint was to implement general user functions - specifically login, sign-up, and password strength feedback, and to further develop the layout of our site. These elements were visualized through a wireframe and evaluated to assess the overall usability of our current design. <br/>

## Methods

### **Cognitive Walkthrough**<br/>
   Two users independently walked through our [Figma wireframe](https://www.figma.com/design/jhDGKQwlUj8O7kmT1LcQr2/WireFrame_2?node-id=0-1&p=f&t=7lfkEIRinDBzvPLv-0). Each user was assigned one of our existing personas: <br/>
   
   * "_Grandpa Joe_ : A 75 year old man, who lives with his wife, and is retired. His kids want to keep in contact with him, but Joe is scared that he wont be able to remember any of his passwords" <br/>
   * "_Tiffany_ : A 32 year woman  who works in the fashion industry, Tiffany works on the cloud, and many other programs." <br/>
   
For each task (signing up, adding passwords), participants answered: <br/>

   * **Will the user know what to do at this step?** <br/>
   * **If the user does the right think will they know they are making progress?**


   This feedback helped us identify where the interface was intuitive and where users may encounter some confusion.
### **Informal Feature Survey**<br/>
   We also conducted an informal survey of the software class (approximately **n=35**), we asked:<br/>
   -_"What features would you want in an app like this?"_ <br/>
   The insights acquired from this survey were used to guide our wireframe design and ensure that the app aligned with user needs.

## Findings

### **Cognitive Walkthrough** <br/>
**Grandpa Joe**<br/>
   * **Concern over forgetting master password** <br/>
   * **Overwhelm due to complexity of features** <br/>
   * **Lack of confirmation screens** <br/>
**Tiffany**<br/>
   * **Unclear copy feadback** <br/>
   * **Search functionality questions** <br/>
   * **Missing Sign-Up Page** <br/>

### **User Survey** <br/>
An informal survey of approximately 35 students in our software engineering course provided a broader view of desired features and pain points. <br/>
**Requested Features**<br/>
   * **Copy Button** <br/>
     Users want an easy way to copy passwords or usernames. <br/>
   * **Browser Extension** <br/>
     Some users expressed interest in a browser extension for auto-filling and syncing. <br/>
   * **Searchability for a Site's Password** <br/>
     Users want to quickly find credentials using a search bar <br/>
   * **Stay Logged in** <br/>
     Several users noted that having to log in frequently can be annoying <br/>

## Conclusions

From our research methods, we were able to obtain key insights into user behavior, expectations, and interface clarity: <br/>

### **From the Cognitive Walkthrough** <br/>
   * **Missing Sign-Up Page Identified** <br/>
      Both users expected a sign-up option during the Walkthrough but they could not find one. This indicated that there is a critical usability gap, highlighting the assumption that account creation is a standard part of app interaction <br/>
      - _UX Insight_ : Users rely on conventional flows, absence of expected elements can cause uncertainty. <br/>
      - _Design Recommendation_ : Ensure that assumptions are met, especially common assumptions like sigh-up/login. <br/>

### **From Informal User Survey** <br/>
   * **Desire for Quick and Easy Access to Functions** <br/>
      Many respondents emphasized the desire to access the app's features without extra steps or confusion. <br/>
      - _UX Insight_ : Reducing steps in navigation and interactions is essential for user retention and satisfaction. <br/>
      - _Design Recommendation_ : Minimize the number of clicks needed to access key features, and implement shortcuts or streamlined menus. <br/>
   * **Concern Over Forgetting The Master Password** <br/>
      Some users raised worries about losing access to the password manager due to forgetting their password. <br/>
      - _UX Insight_ : Users need to feel secure, but also reassured that recovery is possible. <br/>
      - _Design Recommendation_ : Implement a secure and user-friendly password recovery system that balances accessibility and protection. <br/>
   * **Request for Copt Button Functionality** <br/>
      Users mentioned that copying sensitive information (like passwords) should be quick and seamless. <br/>
      - _UX Insight_ : Small convenience features can have a large impact on perceived usability. <br/>
      - _Design Recommendation_ : Add a clearly visible and accessible "Copy" button for relevant fields <br/>

## Caveats

!!! Considerations and/or limitations to the methods you chose and the findings/conclusions drawn from them. In other words, give warnings if there are limitations to your research such as not being able to find enough users of a particular demographic, the methods not being able to expose certain information, assumptions you made, etc. !!!
