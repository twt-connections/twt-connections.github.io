## Overview
For the computing professional, finding the right job-placement is a challenge. For computing firms, finding the right candidates at the right time is just as difficult. RecruitingGrounds connects employers with future employees and potential interns with mentors, allowing for individuals and organizations to seek one another out based on qualifications and needs in a user-friendly and convenient fashion.

Students and professionals looking for a good fit for their particular skill set can easily create a profile and find matching listings by organizations actively recruiting candidates for that skill, and vice versa. Both individuals and organizations provide information necessary for making the right match. 

Individuals can include personal interests or areas they would like to develop, as well as personal goals and strengths.

Organizations can include company background information, which skills they are currently in need of, salary, and the workplace environment candidates will be placed in.

For job postings or information about an upcoming internship, organizations can create a posting with all of the relevant information, and allow interested candidates to apply or seek further information. Similarly, companies actively seeking out a particular skill set or qualifications can send recruiting information to individual candidates directly.

## User Guide
To get started, click "Log-in" on the landing page to set up an account, and select "Register":

<a href="link"><img src="/images/LandingPage.png"/></a> 

Enter your email address, choose a password, and select your account type depending on whether you are an individual or an organization:

<a href="link"><img src="/images/SignInPage.png"/></a>

### For Individuals
After creating an account, you will be taken to your account home page:

<a href="link"><img src="/images/StudentHomePageMockup.png"/></a>

To edit your account information, click on your profile icon to access your profile page:

<a href="link"><img src="/images/StudentProfilePageMockup.png"/></a>

Click the "View Listings" tab to view current job and internship listings:

<a href="link"><img src="ViewListingsMockup.png"/></a> - IN PROGRESS

### For Organizations
After creating an account, you will be taken to your organization's account home page:

<a href="link"><img src="/images/CompanyHomePageMockup.png"/></a>

To edit your account information, click on your profile icon to access your profile page:

<a href="link"><img src="CompanyProfilePageMockup.png"/></a>

Click the "Browse Profiles" tab to view prospective candidates:

<a href="link"><img src="BrowseProfilesMockup.png"/></a> - IN PROGRESS

## Development Guide
First install <a href="https://www.meteor.com/install">meteor</a>

Next download a copy of the <a href="https://github.com/twt-connections/recruiting-grounds">recruiting-grounds repo</a>

Then cd into the app directory and install the libraries using:

```$ meteor npm install```

Once the libraries are installed, you can run the application by invoking:

```$ meteor npm run start```

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

```meteor npm run lint```

### TWT Connections
Team Members: Willard Peralta, Tre Gelacio, Ty Gwartney <br/>
Organization Page: <a href="https://github.com/twt-connections">https://github.com/twt-connections</a> <br/>
Current Deployment: <a href="http://recruitinggrounds.meteorapp.com">http://recruitinggrounds.meteorapp.com</a> <br/>
Current Milestone (M2): <a href="https://github.com/twt-connections/recruiting-grounds/projects/2">https://github.com/twt-connections/recruiting-grounds/projects/2<a/>

### Completed Milestones
First Milestone (M1): <a href="https://github.com/twt-connections/connections/projects/1">https://github.com/twt-connections/connections/projects/1</a>
