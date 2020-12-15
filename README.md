
## Rosie  Resume Website
![Project Image](/img/orgrosie.jpg)

--------

### Table of Content

-  [Description](#description)
 - [User-stories](#user-stories)
 - [User-Acceptance-Testing](#User-Acceptance-Testing)
 - [Technologies](#technologies)
 - [Deployment](#Deployment)
 - [References](#refernces)
 - [Licenses](#licenses)
 - [Author](#author)

------------------------
 ## Description

 The inspiration for developing this website was to start to lay the foundations for a bitcoin/crypto currency wallet and trading platform, this
 is purley educational at this juncture and part of my first project for the Canadian Business college as a full stack developer, i intend to 
 build on this application as my skills evolve throughout my learning process, the website will slowly develop into a fully functional website 
 with the first application "crypto wallet" becoming fully funtional in the coming few months, the second stage devlopment will be a crypto 
 currency platform and the final stage development will be the AI trading bots. These two attributes will be added as my skill become more 
 discerniable, I would also like to collaborate with anyone on github to accomplish these set objectives. I hope to develop this project to 
 become ubiquitous with users around the world.

 ### Wireframes & Mock-ups
 Wireframes file bqwireframe saved in PDF  ,UX Design file saved in PDF, Sitemap file saved in pdf and Mock-ups file MTD_view saved in PDf.
 1.  [wireframes](/wireframe-img/bqwireframe.pdf)
 2.  [UX Design](/wireframe-img/bq_ux.pdf)
 3.  [Sitemap](/wireframe-img/smap.pdf)
 4.  [Mock-ups](/wireframe-img/MTD_view.pdf)
 5.  [README file img](/wireframe-img/bqimg.png)
 
----------------------------
 ## User-stories

 ### Requirement Gathering
 
 The table below will breifly describe the user stories for the functional and non-functional requirements, the user stories decribed in
 **Table 1.0 Requirement Traceability Catalog** will be Independent, Negotiable, Valuable, Estimable, Smart and Testable, **INVEST** in nature and composition.

 *Table 1.0 Requirement Traceability Catalog*

HLR   |  HLR Ref# |    HLR Description    |                              User Stories                                                    |                                                      Acceptance criteria                                                                                        |                                MoSCoW                                                                                                                |
------|---------- |-----------------------|----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------| 
Home  | H-1.0     | Gain access to home section    | **As a** user **I want** to access the home section of Bitquest **so that** I can gain access to the site content.| **Given** that the user is on the Bitquest platform, **When** they click on the Home Nav link **then** the system  will scroll to the home section. |     M   |
Services |  S-2.0   | Gain access to Services section  |  **As a** user **I want** to access the Services section of Bitquest **so that** I can gain access to the site content.| **Given** that the user is on the Bitquest platform, **When** they click on the services Nav link **then** the system  will scroll to the services section. |    M   |
All Services | S-2.1 | Gain accessto All Services section| **As a** user **I want** to access the All services section of Bitquest **so that** I can gain access to the site content.| **Given** that the user is on the Bitquest platform, **When** they click on the All services button **then** the system  will take the user to the second page for all services. |    M   |
All Services | S-2.2 | Gain accessto All Services section| **As a** user **I want** to access the All services section of Bitquest **so that** I can gain access to the site content.| **Given** that the user is on the Bitquest platform, **When** they click on the All services Nav link **then** the system  will take the user to the second page for all services. |    M   |
Testimonials | T-3.0 | Gain access to Testimonials section| **As a** user **I want** to access the Testimonials section of Bitquest **so that** I can gain access to the site content.| **Given** that the user is on the Bitquest platform, **When** they click on the Testimonials Nav link **then** the system  will scroll to the Testimonials section. |    M   |
Contact | C-4.0 | Gain access to section | **As a** user **I want** to access the Contact section of Bitquest **so that** I can gain access to the site content.| **Given** that the user is on the Bitquest platform, **When** they click on the Contact Nav link **then** the system  will scroll to the Contact section. |    M   |
Subscribe email input | C-4.1| Gain access to the subscribe email input| **As a** user **I want** to fill in my email input for subscription on Bitquest **so that** I can subscribe to their News letter.| **Given** that the user is on the Bitquest platform, **When** they input their email **then** the system will accept the user's input and validate .|    S  |
Subscribe button | C-4.2| Gain access to the subscribe button| **As a** user **I want** to click on the subscribe button on Bitquest **so that** I can subscribe to their News letter.| **Given** that the user is on the Bitquest platform, **When** they click on the subscribe button **then** the system will accept the user's input and register them .|    S  |
About Us | A-5.0 | Gain access to About us section | **As a** user **I want** to access the About us section of Bitquest **so that** I can gain access to the site content.| **Given** that the user is on the Bitquest platform, **When** they click on the About us Nav link **then** the system  will scroll to the About section. |    M   |
Login form | L-6.0 | Gain access to login section| **As a** user **I want** to access the Login Modal form for Bitquest **so that** I can gain access to the Login information.| **Given** that the user is on the Bitquest platform, **When** they click on the Login nav link **then** the system  will scroll to the login button.|    M   |
Login form btn| L-6.1 | Gain access to login button| **As a** user **I want** to access the Login Modal btn for Bitquest **so that** I can gain access to the Login form.| **Given** that the user is on the Bitquest platform, **When** they click on the Login button **then** the system  will display the Modal login form and accept/ validte the users input .|    M   |
Login submit btn| L-6.2 | Gain access to submit button| **As a** user **I want** to access the Login Modal submit btn for Bitquest **so that** I can submit my login credentials.| **Given** that the user is on the Bitquest platform, **When** they click on the submit button **then** the system will validte the users input .|    M   |
Login cancel btn| L-6.3 | Gain access to cancel button| **As a** user **I want** to access the Login cancel btn for Bitquest **so that** I can cancel my login.| **Given** that the user is on the Bitquest platform, **When** they click on the login cancel button **then** the system will close the modal form .|    M   |
Login close btn | L-6.4 | Gain access to close button| **As a** user **I want** to access the Login close btn for Bitquest **so that** I can close my login form.| **Given** that the user is on the Bitquest platform, **When** they click on the login close button **then** the system will close the modal form .|    M   |
Login close outside modal form| L-6.5 | Gain access to close the modal form| **As a** user **I want** to click outside the modal form on Bitquest **so that** I can close my login form.| **Given** that the user is on the Bitquest platform, **When** they click outside the modal login form **then** the system will close the modal form .|    M   |
Login form forget Password Link| L-6.6 | Gain access the forget password link| **As a** user **I want** to click on the forget password link on Bitquest **so that** I can change my password.| **Given** that the user is on the Bitquest platform, **When** they click on the forget password link **then** the system will prompt the user to update their new password input .|    M  |
Login form Remember check box| LCB-6.7 | Gain access remember me check box| **As a** user **I want** to check the remember me checkbox on Bitquest **so that** the login form will remember my login credentials.| **Given** that the user is on the Bitquest platform, **When** they check the remember me checkbox **then** the system will prompt the user to store their credentials on google chrome.|    M  |
Signup form | SF-7.0 | Gain access to signup section| **As a** user **I want** to access the signup section of Bitquest **so that** I can gain access to the signup form.| **Given** that the user is on the Bitquest platform, **When** they click on the signup Nav link **then** the system  will go to the signup section, dispaly the form, the form will accept/ validate the users information |    M   |
Signup form btn | SF-7.1 | Gain access to signup button| **As a** user **I want** to access the signup btn form for Bitquest **so that** I can gain access to the signup form.| **Given** that the user is on the Bitquest platform, **When** they click on the signup btn **then** the system will go to the signup section, dispaly the form, the form will accept/ validate the users information. |    M   |
Signup submit btn| SF-7.2 | Gain access to submit button| **As a** user **I want** to access the signup submit btn for Bitquest **so that** I can submit my signup credentials.| **Given** that the user is on the Bitquest platform, **When** they click on the submit button **then** the system will validte the users input .|    M   |
Signup Form Social Media buttons | SF-7.3 | Gain access to signup social media button| **As a** user **I want** to access the signup form social media buttons on Bitquest **so that** I can gain access to the signup form' and register via social media.| **Given** that the user is on the Bitquest platform, **When** they click on the social media btn of their choice on the signup form **then** the system will allow the user to register with their social media credentials. |    M   |
Play btn| PLB-8.0 | Gain access to play button| **As a** user **I want** to access the play video btn on Bitquest **so that** I can watch the video.| **Given** that the user is on the Bitquest platform, **When** they click on the play button **then** the system should play the video .|    M   |
Play Close btn| PLB-8.1 | Gain access to the video| **As a** user **I want** to access the close play video icon on Bitquest **so that** I can close the video.| **Given** that the user is on the Bitquest platform, **When** they click on the close button **then** the system should close the video .|    M   |



## User-Acceptance-Testing

The UAT will define the criteria by which the website is considered to be "working",high, medium or low defects will be identified and cataloged for further improvements or regression Testing.
The UAT critreria and results will confirm if the website can handle required task in a real-world scenarios, according to the Requirements Traceability Catalog Table 1.0.

*Table 2.0 User Acceptance Testing (UAT)*


 Test#    | User stories Ref# |        Description of task        |               Steps to evaluate    |                        Expected Result                                                                                                                                                                                                                             |            Pass / Fail / Comments                             |  
--------  |-------------------|-----------------------------------|------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------| 
APT-H-1.0  | H-1.0             | Home nav link                     | APT-H-1.1: Click home Nav link      | The button should be funtional and scroll to the home section of the website                                                                                                                                                                                     |                     Pass                                      |
APT-S-2.0  | S-2.0             | Services nav link                 | APT-S-2.1: Click services Nav link  | The button should be funtional and scroll to the services section of the website                                                                                                                                                                                 |                     Pass                                      |                                                                         
APT-S-2.1  | S-2.1             | All Services button               | APT-S-2.1.1: Click All services button| The button should be funtional and load the second page of the the website, once correponding nav-link is click it will scroll down to all services section                                                                                                    |                     Pass                                      |
APT-S-2.1  | S-2.2             | All Services nav link              | APT-S-2.2.1: Click All services nav link| The button should be funtional and load the second page of the the website, once correponding nav-link is click it will scroll down to all services section                                                                                                 |                     Pass                                      |                                                                   
APT-T-3.0  | T-3.0             | Testimonials nav link             | APT-T-3.1: Click Testimonials Nav link| The button should be funtional and scroll to the testimonials section of the website                                                                                                                                                                           |                     Pass                                      |                                                        
APT-C-4.0  | C-4.0             | Contact nav link                  | APT-C-4.0.1: Click Contact Nav link|The button should be funtional and scroll to the contact section of the website                                                                                                                                                                                    |                     Pass                                      |                                                                                     
APT-C-4.1  | C-4.1            | Subscribe input feilds             | APT-C-4.1.1: insert Subscribe input email|The input feild should be funtional accept the input and validte the correct email pattern before allowing the user to submit                                                                                                                                |                     Pass: Only submits to code institute server. |                                                                                     
APT-SCB-4.2 | C-4.2            | Subscribe button                  | APT-SCB-4.2.1: Click Subscribe buttom| The button should be funtional and allow the user to Subscribe                                                                                                                                                                                                  |                     Fail: Low defect should be functional in phase 2 development |
APT-A-5.0  | A-5.0             | Testimonials nav link             | APT-T-5.1: Click Testimonials Nav link| The button should be funtional and scroll to the Testimonials section of the website                                                                                                                                                                           |                     Pass                                      |                                                                        
APT-L-6.0  | L-6.0             | Login nav link                    | APT-L-6.1: Click login Nav link| The button should be funtional and load second page of the website, once it is clicked a second time it should scroll to the login button                                                                                                                             |                     Pass                                      |
APT-L-6.1  | L-6.1             | Login form button                 | APT-L-6.1.1: Click login button | The button should be funtional and display the modal form.                                                                                                                                                                                                           |                     Pass                                      |                                                                
APT-L-6.2  | L-6.2             | Login submit button               | APT-L-6.2.1: Click submit button | The button should be funtional, the system should submit the user inputs to the server.                                                                                                                                                                             |                     Pass                                      |
APT-L-6.3  | L-6.3             | Login cancel button               | APT-L-6.3.1: Click cancel  button | The button should be funtional, the system should cancel the login process and exit the modal form.                                                                                                                                                                |                     Pass                                      |
APT-L-6.4  | L-6.4             | Login close icon                  | APT-L-6.4.1: Click close icon | The icon should be funtional, the system should close the login process and exit the modal form.                                                                                                                                                                       |                     Pass                                      |
APT-L-6.5  | L-6.5             | Close modal form outside mondal   | APT-L-6.5.1: Click outside the modal | on-click the event should be funtional, the system should cancel the login process and exit the modal form.                                                                                                                                                     |                     Pass                                       |
APT-LFV-6.6 |L-6.1             | Login form accept inputs & validation | APT-L-6.6.1: Input login credentials | The form should accept the user inputs, the system should validate the form input,check the required patterns for all feilds, the system either accepts and confirms the inputs or rejects the inputs and prompt the user to insert the correct pattern.    |                     Pass:Only submits to code institute server. System does not login into Bitquest user account, it only confirms users have submitted the correct inputs |                                                                                         
APT-LFR-6.7 |L-6.1            | Responsive Modal form                | APT-L-6.7.1: when screen is in mobile view | The modal form should fit all mobile screen height, width and be functional.                                                                                                                                                                            |                     Pass                                       |      
APT-LFP-6.8 |L-6.6           | Forget Password Link                 | APT-LFP-6.8.1: Click forget password link| The link should be funtional and allow the user to change password                                                                                                                                                                                         |                     Fail: low defect should be functional in phase 2 development |
APT-LFCB-6.9|LCB-6.7          | Remember me check box                | APT-LFP-6.9.1: Check the remember me checkbox| The option should be funtional, once a valid submission is accepted by the system the system will open the users chrome password remember box for user to proceed to store their credentials.If the box is uncheck the system will not give the user the option to save their credentials|                     Pass                      |
APT-SF-7.0 |SF-7.0             | Signup nav link                       | APT-L-7.1: Click signup Nav link| The button should be funtional and load the signup form page.                                                                                                                                                                                                    |                     Pass                                       | 
APT-SF-7.1 |SF-7.1             | Signup form button                    | APT-L-7.1.1: Click signup form button| The button should be funtional and load the signup form page.                                                                                                                                                                                               |                     Pass                                       | 
APT-SF-7.2 |SF-7.2             | Signup form submit button             | APT-L-7.2.1: Click signup up form submit button | The button should be funtional and submit the users input to the server.                                                                                                                                                                         |                     Pass                                       |                            
APT-SFV-7.3 |SF-7.0            | Login form accept inputs & validation | APT-L-7.3.1: Input signup credentials | The form should accept the user inputs, the system should validate the form input,check the required patterns for all feilds, the system either accepts and confirms the inputs or rejects the inputs and prompt the user to insert the correct pattern.   |                     Pass                                        | 
APT-SFR-7.4 |SF-7.0            | Responsive Signup form                | APT-L-7.4.1: When screen is in mobile view | The signup form should fit all mobile screen height, width and be functional.                                                                                                                                                                         |                     Pass: Only submits to code institute server. System does not register user with Bitquest ,it only confirms users have submitted the correct inputs|
APT-SFM-7.5|SFM-7.3            | Signup with social media              | APT-L-7.4.1: When the social media button is clicked | The buttons should be funtional and allow the user to register with their social media credentials                                                                                                                                          |                     Fail: Low defect should be functional in phase 2 development |
APT-PLB-8.0 |PLB-8.0           | Play button                            | APT-L-8.1: Click the play button | The button should be functional, and display a pop-up modal static video.                                                                                                                                                                                      |                     Pass                                       |
APT-PLB-8.1 |PLB-8.0           | Play video button to play video        | APT-L-8.1.1: Click the play button | The button should be functional, play the video, the video should be fully responsive to the users needs (volume +/- and large screen capability ).                                                                                                          |                     Pass                                       |
APT-PLB-8.2 |PLB-8.1            |  Close video Icon                     | APT-L-8.2.1: Click the close button | The button should be functional, and close the modal video on click                                                                                                                                                                                         |                     Pass                                       |
APT-PLB-8.3 |PLB-8.0            | Responsive Modal video                | APT-L-8.3.1: when screen is in mobile view | The modal video should fit all mobile screen height, width, be able to play its content and be functional.                                                                                                                                           |                     Pass                                       |      
APT-WSR-9.0 |H-1.0,S-2.0,T-3.0,C-4.0 & A-5.0 | Responsive Website    | APT-L-6.7.1: when screen is in mobile view | The various web pages should fit all mobile screen height, width and be functional.                                                                                                                                                                     |                     Pass                                       |


## Technologies 

The technologies employed to develop this web application was based on the principles of Design for X (DFX) also know as Design for excellence, the basis of this methodology is based
on cost to quality, making effective use of resources to minimize cost and relay more on innovation and technical knowledge to meet the users expectations.The software's used are free 
and meet the **Requirements Traceability Catalog Table 1.0** to develop this website, innovation and technical knowledge was based on my recently aquired skills based on my journey so 
far with Code institute and the Canadian Business College.

Technologies deployed on this project:

 1. For Wire frames, sitemap and UX design draw.io [draw.io](https://app.diagrams.net/)
 2. For Mock-ups Micrisoft Visio professional [Microsoft](https://www.microsoft.com/en-ca/microsoft-365/visio/free-visio-viewer)
 3. For README.md file image Canva software [Canva](https://www.canva.com/)
 4. For coding enviroment /IDE github [GitHub](http://github.com)
 5. HTML 5 code sequence and syntax deployed for index.html, signup.html and services.html
 6. CSS code sequence and syntax deployed for style.css and style1.css
 7. Java script code sequence and syntax deployed for index.html, services.html and smooth-scroll.js
 8. Bootstrap cnd 4.4.1 [Bootstrap](https://getbootstrap.com/)
 9. Bootstrap Jquery 3.4.1 [Bootstrap](https://getbootstrap.com/)
 10. Bootstrap cnd font awesome [Bootstrap](https://www.bootstrapcdn.com/fontawesome/)
 11. Smooth Scroll plug in V16.1.4 [GitHub](http://github.com/cferdinandi/smooth-scroll)
 12. Font Google Poppins [Fontgoogle](https://fonts.google.com/)

---------------------------------------------

 ## Deployment
 After my User Acceptance Testing (UAT) I pushed the final version of my code to git hub , in my commit message I cataloged each change before my final push, the steps I took 
 can be seen below, my project is now live on [GitHub](https://peristratus.github.io/bitcoin-wallet/)

 1. Complete the User UAT evaluation and made sure that all phase 1 codes are funtional and operational.
 2. Used git commit -m to catalog all my changes in line with UAT requirement.
 3. Used git push to push my final version to my git hub repository. 
 4. Clicked on settings on my Peristratus/bitcoin-wallet repository and scrolled down to github pages.
 5. Clicked on select branch drop down menu and then selected master.

-----------------------------------------------

## References

I would like to make references to cetain educational Youtube tutorials and certain articles that have helped with my webdesign develop my skills as a Fullstack developer.


1. Easy tutorials youtube video on responsive landing pages,websites, scroll plugins and login forms [easytutorial](https://www.youtube.com/c/EasyTutorialsVideo?sub_confirmation=1)
2. Dev Ed Youtube tutorials on responsive web design and login forms [DevED](https://www.youtube.com/channel/UClb90NQQcskPUGDIXsQEz5Q)
3. HTML/CSS security by sqreen online article [sqreen](https://www.sqreen.com/checklists/html-css-security-checklist)
4. Input patterns online article [HTML.com](https://html.com/attributes/input-pattern/)
5. W3 schools tutorials on Modal forms, HTML patterns and querry for HTML forms.
6. Tutorial Republic on Modal video pop-ups tutorials.

-----------------------------------------------

## Licenses

All icons,logos and videos used on my website are only for educational purposes and will not be used for the commercial version:

1. Social medial icons free version from icon8 [icon8](https://icons8.com/icons/set/youtube-icon)
2. Hero image p.1 from free png tree [pngtree](https://icons8.com/icons/set/youtube-icon)
3. Footer icons [fontawesome](https://fontawesome.com/v4.7.0/icons/)
4. Bitcoin images and gif image free online images.
5. Testimonial images free online model(s) smiling images.
6. Hero image p.2 from free png tree [pngtree](https://icons8.com/icons/set/youtube-icon)
7. Youtube BBC bitcoin video [BBC](www.youtube.com/embed/SzAuB2FG79A)
8. Youtube Bitcoin wallet [Youtube](www.youtube.com/embed/cSy2ms0hHLs)

-----------------------------------------------

## Author 

*Name: Olaorebikan Roy Abdallah*\
*Institute: Canadaian Business College (code Institute).*\
*Designation: Student.*\
*Course: Fullstack Developer.*

