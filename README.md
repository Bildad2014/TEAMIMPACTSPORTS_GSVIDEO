TEAMIMPACTSPORTS_GSVIDEO
========================

GS VIDEO CREDENTIALS AND SYSTEM ACCESS 
Global Sport: Server:

1. Please click on this link: https://my.rackspace.com/registration/1385154192373

Username: TeamImpactAdmin
PW: Crush2013

Account Number:842818


I've use the "yaa@globalsports.net" account via ssh with my public key as in:
ssh -i ~/.ssh/id_sek -p 40782 yaa@globalsports.net
---

So if you or your team currently have sufficient access to SSH in, that yaa@globalsports.net is the account to use.

As far as mysql creds, neither dev has them directly, but they should be in the code. Our former rails dev said to look in database.yml for the production app. Note that the creds may not have been published to github, so your guys will probably have to actually look on the live/production app on the Rackspace box itself.


If you don't have what you need already to SSH in, let me know and I can take care of that. 

Hopefully this'll do it; if not, again, let me know. 

---------------------------------  LIVE SITE CRM /CMS CREDENTIALS: 
GS REGISTRATION PLATFORM: SUPER ADMIN CREDENTIALS:  
http://www.globalsports.net/YAA/prepareLogin.do?organizationId=25 

user: abooma
pass: aso5111


GSVIDEO:  SUPERADMIN CREDENTIALS: 
www.globalsports.net 
As far as admin access, here are the credentials for our app-level admin panel:
URL: www.globalsports.net 
UN: admin@globalsports.net
PW: gsadmin123


Additionally, here're the credentials for the Opentext/Vidavee video CMS: ( These credentials aren't working and also noticed the homepage video stopped playing so it may be an account level issue.    I will do further research. 
URL: http://tribeca.vidavee.com/hsstv
UN: hsstv@hsstv
PW: hsstvUser





GS Home Page Rebranding demo - (http://teamimpactnetwork.com/complete/  )  Goal is to simply swap out home page and replace with the above homepage design with simple login and sign up access to the dashboard.   



Profile Page/ Community  Reskin:
 The Profile Page/Community Site for teams and individual athletes is can be found here:  http://teamimpactnetwork.com/profile/profile.html     ( The goal here is to replace the current template (http://www.globalsports.net/YAA/community2.do?organizationId=62) for abooma sites as well as leverage the template design for GS video profile pages in which we can pull specific fields from the database would integrated.    

I'd Like to integrate profile page template reskin into the following demo accounts with limited functionality with login access to the admin dashboard/league portal which will remain "AS IS": 

Alliance Youth Sports: 
http://www.globalsports.net/YAA/prepareLogin.do?organizationId=13  

Team Profile Highlight Page:   
http://www.globalsports.net/teams/1    




OVERVIEW OF PLATFORM FUNCTION: 

1.) The GS Video platform will be sold into the sports niche with packages targeted towards coaches so they can sell recruitment video packages to their athletes.   The GS video platform will be where the coaches upload and edit game videos and upon completion will have the ability to export the video file for dvd (hardcopy) creation.

2.) The GS Video platform will become a personalized web driven (eventually mobile) video hub where organizations can have there own web driven TV station. 


Development related prerequisites to client onboarding:

In order for us to capitalize on this goal we need to:

1.) Reskin the backend system (Where users will create and edit their videos)
2.) Reskin the frontend system (Where viewers will view showcased videos)
3. Front -end Home Page - FB Sign In and Email Sign In
4.) We need to build a Sign Up Registration Form for Leagues, Team, Players and Coaches to easily sign up for our basic service offering as well as provide us with marketing assets and information we need to effectively create a profile page for them within the scope of our product offering.   PLEASE USE THIS AS A GUIDE -  https://leagueathletics.com/guest/trial.asp?
5. The attached branding assets should be on each page.   Once we finish the first profile landing for "GLOBAL SPORTS FOR YOUTH LEAGUES' GS For Youth Sports Leagues we will then build indiviual landing pages as follows - 

Team Impact Network & New Covenant Partners:

Global Sports: For Youth Leagues: (Abooma Registration, TIN Mobile App Platform,  Processing & Merchant Services, Rainedout)

Global Local Causes(TM) : Solution for Faith Based & Non- Profit Organizations:  ( Abooma Registration, Mobile Cause(Giving Platform), TIN Mobile App Platform,  Processing & Merchant Services)

Global Sports Pro(TM): Pro(TM) For Local Athletes & Professional Organizations powered by Players Authority (  Global Sports: For Youth Leagues: (Abooma Registration, TIN Mobile App Platform,  Processing & Merchant Services, GS Video Recruiting & Highlight Platfrom), Ecommerce)


 
PHASE 1.2: VIDEO PLATFORM INTEGRATION: 


WISITA VIDEO PLATFORM: 
http://teamimpactnetwork.wistia.com/projects
username:  bildad@teamimpactnetwork.com
password: crush2013


ASSESS OPEN TEXT & PIVOT SHARE;  



The re skinning aspect will have 2 primary objectives:

Layer in TIN Branding -The platform per our intended use case will be white labeled and we can't showcase or sell it until it's under our brand name.

UI and layout enhancements - The platform in it's current state is not up to industry standards from an aesthetic and UI stand point.  We will modify it so it's visually appealing and easier to navigate.


3.) Make appropriate system advancements so it's optimized for the video "recruitment package".

- This primarily speaks to the ability to export videos from the GS sports servers.


4.) Test the stability of the system (load and stress testing) 

This is a key perquisite to market penetration (Especially for use case 2).  We need to be 100% confident that the system can handle high levels of user views at any given time.

Much off that will be attributed towards assessing and optimizing 3rd party video streaming API's and hosting Server configuration.





