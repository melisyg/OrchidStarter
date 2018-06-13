
This is a quickstart repo for Orchid to get you up and running as soon as possible. The only system dependency 
necessary to run Orchid is a valid Java 8 JDK and git. 

```bash
git clone https://github.com/JavaEden/OrchidStarter.git
cd OrchidStarter
./gradlew orchidServe

# View your generated site at http://localhost:8080/
```
Hello!

Rank your 5 favorite, and 5 least favorite, activities from this list: https://gist.github.com/fool/b0f254ff8c72a5765b6a9138249789d6
Favorite
1 Debug a customer's build using a programming language and framework that you've never seen before
2 Write and maintain documentation for our software and blog posts for our website.
3 Respond to 50+ support requests via email or chat most days
4 Work with the development team to help design a new feature based on feedback from customers
5 Suggest and champion improvements to the product and workflow to your colleagues in and out of support

Least Favorite (Only because I had to choose 5, was a difficult task!)
1 Engage multiple users at once via chat to answer their questions and troubleshoot problems. (1 Customer should have your undivided attention :)
2 Create video tutorials to help teach users a specific feature or use case
3 Find and recruit teammates for the Support team
4 Deliver a talk to many people you don't know at a conference or meetup
5 Help manage communications during a service outage


What is your favorite thing about providing technical support? My favorite thing about providing Technical Support is helping the customer fix the issues they are experiencing and feeling the clients’ relief of the issue resolution. 


What did you think of our service during the time you used it?  Provide either some constructive criticism or some points that impressed you.  Be honest!  “It sucked” isn’t a wrong answer unless you don’t elaborate and provide some constructive criticism ;)
I liked everythng about Netlify, it's quite easy to use. 


Talk about how you made your site and why you chose the tools you did.  Briefly explain a challenge you experienced in setting up this site and how you solved it. 
I chose Orchid because of the features which are secure, fast, flexible, scalable, open source, the Netlify option, supports a variety of plugins, and high compatibility with many existing static site generators. Also, it’s Unique and I like orchids of course :)

The biggest challenge for me was I have not used github before.


Provide a link to documentation for a technical/developer-focused product, which you think are well done, and briefly explain why you think they are well done.


Why do you think SSL/HTTPS is important? 
SSL/HTTPS is important to have a secure encrypted connection between a host and a client. As the internet has outgrown its original expectations and now within the newest technology of the internet there are new threats of the man in the middle or per se, physical hacker and it is important to have an SSL certificate for site owners and end-users should routinely use HTTPS connections. If a site has not created and released an SSL Certificate for public use I personally would prefer not to connect to the site. A great free browser extension I use is HTTPS Everywhere. If a site has not created and released an SSL Certificate I would take into consideration and caution, the site may not be safe.


Explain, in a couple of paragraphs, what you think 2 major challenges around DNS configuration are for less-technical internet end-users.
1.	DNS Server Routing/Configurability has been a challenge in the IT industry. Users should be directed to the closest server as a best practice. DNS solutions can be setup and with the up/down measurements into their decision-making process, enabling and maintenance of these functions requires lots of time spent within an IT department and developers which can be very costly.
2.	DNS Server Security
Originally, DNS was created and used for a naming service with IP addressing for computers to work on the internet. Security vulnerabilities come with the territory of running applications on the modern internet. When DNS was first used, security was not a concern. Until recently in the last few years of the physical hacker, DNS security has become a risk for all DNS servers and companies worldwide.  


A customer writes in saying their “site won’t build”.  Compose:
your best short (2-paragraph) customer-facing answer, 
without any additional data, 
that could be useful in the generic case, 
but would also lead to a customer providing a more actionable response.

Hello Customer,
I am sorry to hear you are having issues with your site not building. To better assist you, can you provide any additional details if any are available by providing the following information? 
Have you received any other messages other than "site won't build"? 
Have you received any emails about going over the size limit of 100GB?
Was the site created on your local computer?
Was your Source setting changed after the initial creation? If you change this setting in your _config.yml file, your page may not build.

Kind regards,
Netlify Support - Melissa


(optional/bonus) Can you set up a redirect from “/netlify/anything” to https://www.google.com/search?q=anything ?
 /netlify/anything/*  https://www.google.com/search?q=:anything


(optional/bonus) Could you give us a suggestion to improve this test or the job posting?


Alternatively, you can click the button below to automatically clone this repo and deploy it to Netlify. This starter 
repo includes the [Netlify CMS](https://www.netlifycms.org/), so you will be up and publishing content as soon as 
possible. You will need to set the Github user/repo in `src/orchid/resources/data/netlifyCms.yml`, but the rest of the 
CMS config is automatically generated based on your current Orchid plugins and configurations.  

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/JavaEden/OrchidStarter)

### Example Orchid Sites

* [Official Orchid documentation](https://javaeden.github.io/Orchid/latest/OrchidCore/)
* [Clog documentation](https://javaeden.github.io/Clog/)
* [Krow documentation](https://javaeden.github.io/Krow/)
* [caseyjbrooks.com](https://www.caseyjbrooks.com/)
