# Overview
For the computing professional, finding the right job-placement is a challenge. For computing firms, finding the right candidates at the right time is just as difficult. RecruitingGrounds connects employers with future employees and potential interns with mentors, allowing for individuals and organizations to seek one another out based on qualifications and needs in a user-friendly and convenient fashion.

Students and professionals looking for a good fit for their particular skill set can easily create a profile and find matching listings by organizations actively recruiting candidates for that skill, and vice versa. Both individuals and organizations provide information necessary for making the right match. 

Individuals can include personal interests or areas they would like to develop, as well as personal goals and strengths.

Organizations can include company background information, which skills they are currently in need of, salary, and the workplace environment candidates will be placed in.

For job postings or information about an upcoming internship, organizations can create a posting with all of the relevant information, and allow interested candidates to apply or seek further information. Similarly, companies actively seeking out a particular skill set or qualifications can send recruiting information to individual candidates directly.

Current Deployment: <a href="http://recruitinggrounds.meteorapp.com">http://recruitinggrounds.meteorapp.com</a>

# User Guide
To get started, click "Log-in" on the landing page to set up an account, and select "Sign Up":

<a href="http://recruitinggrounds.meteorapp.com"><img src="/images/LandingPage2.jpeg"/></a> 

Enter your email address, choose a password, and select your account type depending on whether you are an individual or an organization:

<a href="link"><img src="/images/SignInPage.jpeg"/></a>

## For Individuals
After creating an account, you will be taken to your account home page:

<a href="link"><img src="/images/StudentHomePage.jpeg"/></a>

To edit your account information, click on your profile icon to access your profile page:

<a href="link"><img src="/images/StudentProfilePage.jpeg"/></a>

Click the "Browse Listings" tab to view current job and internship listings:

<a href="link"><img src="/images/BrowseListings.jpeg"/></a>

## For Organizations
After creating an account, you will be taken to your organization's account home page:

<a href="link"><img src="/images/CompanyHomePage.jpeg"/></a>

To edit your account information, click on your profile icon to access your profile page:

<a href="link"><img src="/images/CompanyProfilePage.jpeg"/></a>

Click the "Browse Profiles" tab to view prospective candidates:

<a href="link"><img src="/images/BrowseProfiles.jpeg"/></a>

# Development Guide
First install <a href="https://www.meteor.com/install">meteor</a>.

Next download a copy of the <a href="https://github.com/twt-connections/recruiting-grounds">recruiting-grounds repo</a>.

Then cd into the app directory and install the libraries using:

`$ meteor npm install`

Once the libraries are installed, you can run the application by invoking:

`$ meteor npm run start`

Note regarding bcrypt warning. You will also get the following message when you run this application:

```
Note: you are using a pure-JavaScript implementation of bcrypt.
While this implementation will work correctly, it is known to be
approximately three times slower than the native implementation.
In order to use the native implementation instead, run

  meteor npm install --save bcrypt

in the root directory of your application.
```

On some operating systems (particularly Windows), installing bcrypt is much more difficult than implied by the above message. Bcrypt is only used in Meteor for password checking, so the performance implications are negligible until your site has very high traffic. You can safely ignore this warning without any problems during initial stages of development.

If all goes well, the template application will appear at http://localhost:3000. You can login using the credentials in settings.development.json, or else register a new account.

Lastly, you can run ESLint over the code in the imports/ directory with:

`$ meteor npm run lint`

# Development Guide
## First Milestone
<a href="https://github.com/twt-connections/recruiting-grounds/projects/1">GitHub Repository</a> 
<br />
To begin our project, we installed a standard Meteor web application template from which to work.
<br />
After this, we made some basic mockup pages for what we thought might appear in the finished app, such as:
<br />
-- a Student Home page
<br />
-- a Student Profile page
<br />
-- a Company Home page
<br />
-- a Company Profile page
<br />
-- an Admin Home page
<br />
At this point, though none of these pages were functional, we were able to link them together internally, as well as a create a basic Landing Page from which to sign in and register new accounts.
<br />
Finally, we deployed this first version of the project to Galaxy.
<br />
## Second Milestone
<a href="https://github.com/twt-connections/recruiting-grounds/projects/2">GitHub Repository<a/>

## Third Milestone
<a href="https://github.com/twt-connections/recruiting-grounds/projects/3">GitHub Repository<a/>

# TWT Connections
Team Members: Willard Peralta, Tre Gelacio, Ty Gwartney
<br/>
Organization Page: <a href="https://github.com/twt-connections">https://github.com/twt-connections</a>
<br/>
