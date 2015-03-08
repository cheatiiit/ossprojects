## **Personal Details**

**Name:** Chetna Gupta <br>
**Email:** cheta.gup@gmail.com <br>
**IRC:** chetna on freenode <br>
**Skype:** chetna.gupta3<br>
**Github:** cheatiiit<br>

***
## **Background**
I am a fourth year Computer Science student at International Institute of Information and Technology, Hyderabad, India. I love to take challenges in various fields. I have worked as Google Summer of Code Intern (2013) for Sympy (Python based Computer Algebra System)[1] and have also worked with YouTube Live team as Google Software Engineering Intern (2014) at Cambridge, USA. <br>During my google internship I came to know about GHC and Anita Borg Insitute. I couldn't be a part of the conference last summer because of prior commitments but I became really interested in the kind of work taken up at Systers, specially because of the impact people bring using this platform. 

***
## **Skill Set**
I've done coding in several high-level languages (C, C++, C#, Python, Java); What I like most about Python is the simplicity and readability of the language which allow for what I find to be very elegant programs. I have worked on python based web development softwares like Web2py (MVC Model). I have also started getting the knacks of basics of Django and Ruby on Rails. I got an opportunity to build a website with database support for immigration company in php as part of course project.

I have been using git, because of my involvement in the sympy project. I'm still learning the little tricks for the version control. 

***
## **Solution**
Looking through Ushahidi Project Video[2], I would start with the approach proposed on the lines of Ushahidi Project where PCV onsite will be able to gather data via GPS device or laptop and record information on each location they determine a deaf occupant. This information would be displayed on a web page for PCVs to see and to facilitate the needs of the deaf occupants. Their action would be reported back to Peace Corps.

This solution would then be extended to make the process more user-friendly in the following ways:<br><br>
_1) Pushing periodic map-notifications when a previously attended occupant might be in need of service again.<br> PCV can set timers for such notifications. For example a deaf school might require new sports equipments after an year, PCV in-charge can set the notification accordingly for another PCV to help the occupant after an year.<br><br>_
_2) Letting an onsite PCV know about an already registered deaf occupant who might be in need of service._
_This system can be made more efficient by choosing a PCV nearest to the occupant based on GPS coordinates(Shortest Path) and allocating him/her the job<br><br>_
_3) A global map can be provided where occupants are marked in different color based on the status of service facilitated to them, example an action completed might be indicated by green while different shades of red might be used to represent action in progress.<br>_
_This would not only save time but would make the interface less technical and more informative for the Peace Corps.<br>_

***
## **Details**
Here are some details for the implementation of the idea. They are subject to change as per the discussion. Following might be the main modules for the project:<br>
1) _**Login Module:**_ This module would allow Peace Corps and Peace Corps Volunteers to sign in/sign up. PCV's GPS coordinates would be automatically updated whenever they login/logout.<br>
2) _**Profile Module:**_ This module would support separate profile pages for Peace Corps and the PCVs.<br>   **PCV:** PCVs would be able to see their personal information and the occupants they have served.<br> 
**Peace Corps:** Peace Corps would be able to see their personal information and PCVs under them.<br>
3) _**Action Module:**_ This module would allow PCV to record the details of the deaf occupant and the kind of services to be provided which would be stored in the database.<br>
4) _**Global Module:**_ This module would show various locations with map-pins, indicating deaf occupants, which can be clicked to checkout the progress of the service provided.<br>
5) _**Progress Module**_ This module would provide separate progress pages for PCV and Peace Corps.<br>
**PCV**: Status of service provided to the occupant registered by the volunteer. Also he/she would be able to see the already registered occupants who might be in need of service again.<br>
**Peace Corps**: Occupants to be served by the volunteers under him/her and the occupants already served by his/her volunteers.<br>
6) _**Add/Remove PCVs Module**_: This module would allow Peace Corps to add or remove PCVs under them.<br>

***
##**Timeline**
Timeline for the project would be as follows which is subject to change after initial round of discussion:
<table>
<tr><td width="30%">
19th May  - 25th May</td> <td>    Initial Setup and Configuration. Starts working on the login page.</td></tr><tr><td>
26th June - 1st June     </td><td>Works on login module with advance options such as forgot password, password reset etc.</td></tr><tr><td>
1st June               </td><td>  <b>Project Major Milestone:</b> Fully functional Register/Login mechanism</td></tr><tr><td>
9th June  - 15h June   </td><td>   Works on Setting-up a database with schemas to support PCV and Peace Corps functionality. Also start with PCV Profile Page Layout</td></tr><tr><td>
16th June - 29th June     </td><td>        Gets PCV and Peace Corps Profile Page ready</td></tr><tr><td>
27th June               </td><td>         <b>Mid Evaluation</b> With Login and Profile Module Fully-functional</td></tr><tr><td>
30th June - 6th July     </td><td>         Works on Action module which would update profile page for every action taken by PCV</td></tr><tr><td>
7th July - 13th July     </td><td>         Starts working on Global page layout, using interactive-client-side script, would try to integrate AngularJS.</td></tr><tr><td>
14th July - 20th July  </td><td>           Gets Global page layout working.</td></tr><tr><td>
21st July - 27th July     </td><td>        Completes Progress page for PCV and Peace Corps</td></tr><tr><td>
27th July                </td><td>        <b> Project Major Milestone:</b> Fully functional Action, Global and Progress Module</td></tr><tr><td>
28th July - 3rd Aug      </td><td>         Works on Add and Remove PCV module</td></tr><tr><td>
4th Aug - 10th Aug      </td><td>          Refactor code segments, clean code, solve unexpected issues, bugfixes.</td></tr><tr><td>
11th Aug - 22nd Aug      </td><td>         Write documentation, provide contribution guidelines.</td></tr><tr><td>
22nd Aug             </td><td>            <b>Final Evaluation</b> with all modules working</td></tr></table>


***
##**FrameWork**
I have started working on Kohana PHP but not much support for the framework in terms of tutorials, documentation etc is available online which might limit the scope of the project. It would be great if we can move towards frameworks like Django or Rails. Apart from this Web APIs such as ArcGis which is Javascript API would make the interface more client side dependent hence reducing the reliance on web connections in remote areas. 

***
##**Bibliography**
[1] Sympy GSoC Proposal 2013: https://github.com/sympy/sympy/wiki/GSoC-2013-Application-Chetna-Gupta:-Risch-algorithm-for-symbolic-integration <br>
[2] Ushahidi Project: http://youtu.be/MrRfkQuvoyA?list=PLEHn86nuOrtuSQcSrc57-P5IzCnlD4TcT

***
