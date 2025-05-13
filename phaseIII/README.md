# Phase III: Prototypes and User Testing

## Introduction

In this phase, we transitioned from wireframes to a functional prototype, integrating core user features such as login, sign-up, and password strength feedback. Our primary goal was to observe how users interact with the live website and gather insights into the effectiveness of our current design. Through informal user testing and feedback analysis, we aimed to identify _usability issues_, _refine interactive elements_, and _further interface iterations_.

## Methods

To gather further insights about user behavior and interface usability, we conducted observational testing using a functional prototype based on the software team's web application. The following methods were used: **Task-Based Usability Testing**, **Pre-Test Survey**, **Post-Task Interview**, and **Thematic Observation**.

  During the **Task-Based Usability Testing**, participants were asked to complete specific tasks using our prototype. These tasks included: _adding a new password entry_, _using the password strength checker_, _generating a password_, _deleting a password_, and _copying a password_. We recorded the success or failure of each task and collected self-reported difficulty ratings on a scale from 1(very easy) to 10(very difficult). Participants were also prompted to explain why they found each task easy or difficult, offering qualitative insights into usability barriers.

Before beginning the tasks, participants completed a **Pre-Test Questionnaire**, which gathered background information about their _Prior use of password managers_, _Experiences with password-related security issues_, and _Habits around password diversity_. These responses helped contextualize participant performance and attitudes during testing.

  After each task, we conducted **Post-Task Interviews**. Participants were asked _what parts of the website worked well_, _which features were strengths or weaknesses_, and _what they considered the best and worst parts of the interface_. This qualitative feedback helped identify interface elements that aligned or conflicted with user expectations and conventions

  Additionally, we applied **Thematic Observation** throughout the sessions. We took detailed notes on user behavior, paying special attention to moments when _users hesitated_, _misinterpreted icons_, or _navigated to the wrong area_. Notably, difficulty recognizing the delete icons and understanding the password strength indicators were recurring pain points. These observations were cross-referenced with post-task feedback to confirm and prioritize key usability issues.
  
## Findings

Participants generally completed the **Task-Based Usability Testing** successfully, but several usability issues emerged, particularly in **Tasks 2 and 4**. 

In **Task 1**, we tasked the users with checking one of their passwords. This task had a success rate of 100%, with all participants completing this task with ease, which showed with most participants except one, giving this task a very easy(1) difficulty.

**Task 2** asked the users to check the security of a password. One participant was unable to complete the task. Several users found the password strength icon unclear or ambiguous, highlighting the need for tooltip labels or explanatory UI elements. The participant who was unable to complete the task, citing that the shield was too hard to recognize as the button to check the passwords. Most users still struggled with this task, which shows in most of the users reporting an easy(2) difficulty,

**Task 3** asked the user to generate a new password. This task was completed by all participants, with all of them giving this task a very easy(1) difficulty. Users appreciated how the option was easy to locate and activate, thanks to familiar layout patterns and labeling.

The most challenging task, **Task 4**, tasked the user with deleting a password. One participant could not figure out how to do this, while the users who had cited moderate difficulty(3). The delete icon was often overlooped or misinterpreted, with participants expecting a trash can icon rather than the current visual. Pointing to a need for standard icon conventions.

Finally, in **Task 5**, participants were tasked with copying a password. All users completed this task easily, citing the familiarity of the copy symbol. Reinforcing the value of using widely recognized UI conventions to streamline user interaction. Users gave this task a very easy(1) difficulty.

The **Pre-Test Questionnaire** revealed that participants ranged from password manager novices to daily users of tools like _Dashlane_, or _Google Password Manager_. Experienced users navigated the website more confidently, but even they encountered difficulties with non-standard icons, reinforcing the need for an intuitive and universal design. Several users also reported previous experiences with data breaches or forgotten credentials, emphasizing the importance of clear trust signals and explanations of security features.

In the **Post-Task Interviews**, participants reflected on their experience after each task. Many expressed confusion over icons or commented that certain features felt hidden or hard to locate. One participant described the list of passwords as "a little overwhelming", pointing to a need for clearer visual hierarchy and more descriptive labeling. While users praised the dashboard layout and the simplicity of adding or generating passwords, multiple participants noted there was too much blue, suggesting a need to diversify the color palette to improve visual structure and readability.

Finally, through **Thematic Observation**, we documented user behavior during testing sessions. Users frequently hesitated when interacting with unlabeled icons, and several were drawn to the wrong areas due to the visual emphasis of red alert symbols, which unintentionally distracted them from the correct controls. These findings indicate a need for _improved icon clarity_, _better visual feedback cues_, and potentially an _onboarding tooltip or guide_ to help new users get oriented.

## Conclusions

User testing revealed several usability challenges that led to key design insights and improvements. Participants often struggled with icons related to password strength and deletion. We implemented hover tooltips and recommend continuing to add labels or hints for non-standard icons. Tasks involving familiar symbols (like "copy") were easily completed, reinforcing the importance of standard iconography, such as trash cans for delete, to reduce user confusion.

Some users found the password list visually overwhelming. To address this, we recommend _decluttering the layout, _grouping related functions_, and _improving spacing and labeling_ to enhance clarity. Additionally, several participants noted the overuse of blue, which impacted readability. A more diverse and accessible color palette would improve visual structure and usability.

Participants with prior security concerns expressed a desire for greater transparency around how features like password strength checking and leak detection work. Adding brief explanations or info tooltips can help build user trust and understanding. These insights are directly shaping our next iteration, with a focus on making PassGuard more intuitive, accessible, and user-centered.

## Caveats

While our user testing provided valuable insights, there are several limitations to consider when interpreting the findings. One such limitation is that our test group was small and consisted primarily of fellow classmates, which does not fully represent the broader user base. Most participants had some familiarity with password managers, which may have influenced their ease of use and expectations. As a result, the findings may not reflect the experience of less tech-savvy or novice users. 

The testing was also conducted in a controlled environment, which may not fully capture how users interact with the product in real-world scenarios. The study also lacked diversity in age, background, and technical experience, further limiting the generalizability of the results. Despite these constraints, the study revealed consistent usability trends and actionable design improvements. 
