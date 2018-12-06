<ul>
  <li><a href="#overview">Overview</a></li>
  <li><a href="#userguide">User Guide</a></li>
  <li><a href="#devguide">Development Guide</a></li>
  <li><a href="#devhistory">Development History</a></li>
  <li><a href="#feedback">Community Feedback</a></li>
  <li><a href="#contact">Contact</a></li>
</ul>

<h1 id="overview">Overview</h1>
For the computing professional, finding the right job-placement is a challenge. For computing firms, finding the right candidates at the right time is just as difficult. RecruitingGrounds connects employers with future employees and potential interns with mentors, allowing for individuals and organizations to seek one another out based on qualifications and needs in a user-friendly and convenient fashion.

Students and professionals looking for a good fit for their particular skill set can easily create a profile and find matching listings by organizations actively recruiting candidates for that skill, and vice versa. Both individuals and organizations provide information necessary for making the right match. 

Individuals can include personal interests or areas they would like to develop, as well as personal goals and strengths.

Organizations can include company background information, which skills they are currently in need of, salary, and the workplace environment candidates will be placed in.

For job postings or information about an upcoming internship, organizations can create a posting with all of the relevant information, and allow interested candidates to apply or seek further information. Similarly, companies actively seeking out a particular skill set or qualifications can send recruiting information to individual candidates directly.

Current Deployment: <a href="http://recruitinggrounds.meteorapp.com">http://recruitinggrounds.meteorapp.com</a>
<br />
<a href="https://twt-connections.github.io">Back to top</a>

<h1 id="userguide">User Guide</h1>
To get started, click "Log-in" on the landing page to set up an account, and select "Sign Up":

<a href="http://recruitinggrounds.meteorapp.com"><img src="/images/LandingPage2.jpeg"/></a> 

Enter your email address, choose a password, and select your account type depending on whether you are an individual or an organization:

<a href="link"><img src="/images/SignInPage.jpeg"/></a>

<h3>For Individuals</h3>
After creating an account, you will be taken to your account home page:

<a href="link"><img src="/images/StudentHomePage.jpeg"/></a>

To edit your account information, click on your profile icon to access your profile page:

<a href="link"><img src="/images/StudentProfilePage.jpeg"/></a>

Click the "Browse Listings" tab to view current job and internship listings:

<a href="link"><img src="/images/BrowseListings.jpeg"/></a>

<h3>For Organizations</h3>
After creating an account, you will be taken to your organization's account home page:

<a href="link"><img src="/images/CompanyHomePage.jpeg"/></a>

To edit your account information, click on your profile icon to access your profile page:

<a href="link"><img src="/images/CompanyProfilePage.jpeg"/></a>

Click the "Browse Profiles" tab to view prospective candidates:

<a href="link"><img src="/images/BrowseProfiles.jpeg"/></a>

<a href="https://twt-connections.github.io">Back to top</a>

<h1 id="devguide">Development Guide</h1>

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
<br />
<a href="https://twt-connections.github.io">Back to top</a>

<h1 id="devhistory">Development History</h1>

<h3>First Milestone</h3>
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
<a href="https://github.com/twt-connections/recruiting-grounds/projects/1">First Milestone GitHub Repository</a> 

<h3>Second Milestone</h3>
Our second milestone was our most productive and challenging, as it required something of a "reset" to our plans for moving ahead from our first milestone. The overall goal was to improve the page functionality and connectivity, so it would begin to look and feel more like a working application.
<br />
We started as we had before, each working individually on page improvements, but quickly ran into a difficulty: our database system. Without functioning databases, other parts of the site we were working on, such as listing profiles or editing account information, were immensely more difficult. Upon realizing this, we stopped what we were doing, went back and created functioning collections, one for Student profiles and one for Company profiles, along with the pages that would load information from these collections appropriately. This was difficult and required a lot of debugging, and only one of the collections, the Company collection (and it's accompanying page) loaded properly by the end of this Milestone.
<br />
We also were able to implement some other minor adjustments, such as adding background images to different pages, and redesiging the Landing Page.
<br />
<a href="https://github.com/twt-connections/recruiting-grounds/projects/2">Second Milestone GitHub Repository<a/>

<h3>Third Milestone</h3>
For the last Milestone, after finally debugging the Student collection, we were able to successfully implement our Account information pages, where editing of user information would take place. After this, we edited the default account information for Student and Profiles, as well as changed some of the button configurations to fit more in-line with our original conception of the site. We also removed excess code.
<br />
<a href="https://github.com/twt-connections/recruiting-grounds/projects/3">Third Milestone GitHub Repository<a/>
<br/>
<a href="https://twt-connections.github.io">Back to top</a>

<h1 id="feedback">Community Feedback</h1>
<u>Anonymous User 1:</u>
<br />
<em>"...should have a different picture for background because text is hard to see... separate designs for student home and company home... more creative profile names..."</em>
<br/>
<u>Anonymous User 2:</u>
<br />
<em>"...your website is clean, and pretty user friendly. I just wish that more of the buttons worked."</em>
<br />
<u>Anonymous User 3:</u>
<br />
<em>"... "</em>
<br />
<u>Anonymous User 4:</u>
<br />
<em>"..."</em>
<br />
<u>Anonymous User 5:</u>
<br />
<em>"..."</em>
<br />
<a href="https://twt-connections.github.io">Back to top</a>

<h3 id="contact">Contact - TWT Connections</h3>
Team Members: Willard Peralta, Tre Gelacio, Ty Gwartney
<br/>
Organization Page: <a href="https://github.com/twt-connections">https://github.com/twt-connections</a>
<br/>
<a href="https://twt-connections.github.io">Back to top</a>
