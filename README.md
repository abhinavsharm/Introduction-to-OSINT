
Search
Write

Abhinavsharma.exe
Get unlimited access to the best of Medium for less than $1/week.
Become a member



Shreyanka A R

Introduction to OSINT
Abhinavsharma.exe
Abhinavsharma.exe

28 min read
·
Jul 22, 2024
33







What is OSINT?
OSINT, short for Open-Source Intelligence, is data that has been obtained from publicly available sources. OSINT is widely used within law enforcement work, cybercrime activities such as planning an attack, or for business operation purposes, such as checking out the competition. This course will primarily be focusing on the application of OSINT tools and techniques for both red (offensive) and blue (defensive) teams. Let’s explore some examples of OSINT data:

A company that has a public web page that introduces some/all of their employees (think a “meet the team!” page). An attacker could use this to very easily gather a list of targets for social engineering attacks. Some sites may even include contact email addresses or phone numbers, which can aid the social engineering process dramatically.
Job Descriptions that leak information about a company’s internal systems (example: a system administrator role requiring experience with Windows Server 2016 and Solaris). An attacker can use this to plan internal attacks, lateral movement, and privilege escalation once they have gained a foothold in the network.
Photos on social media that are geotagged and contain device information in the metadata(example: that nice photo you shared on holiday? we can find where that is, usually in a matter of seconds — and the device you took it on).
Reading a user’s social media profile to build up a profile of them (information such as date of birth, locations, friends, interests, family). This can be used to learn more about an individual, which is commonly done pre-interview so that employees can get a sense of how the person will act in the workplace.
Exposing Cyber Criminals. Whilst this begins to move into the Threat Intelligence domain, it is possible to use OSINT sources and social-engineering skills to identify the true identity of cybercriminals and pass the details to law enforcement. Whilst this is out of scope for this entry-level course, it shows how powerful OSINT can be in the right hands.
As you can see, the above can be useful to both attackers and defenders. Attackers can build up a good picture of their target without directly interacting with their systems, whilst defenders can get a sense of the publicly available information that is present on the internet, and work to reduce this or mitigate it using security controls such as user awareness training and social-media policies.

Intelligence Cycle
It doesn’t matter if you are a member of a law enforcement agency or a security analyst for a company, either way when you are in an intelligence scenario you will likely be facing the same landscape. On one hand, you will have a huge amount of data that must be analyzed, and on the other, you will have a problem that must be solved.

When dealing with this scenario you need to take advantage of the massive amount of data at your disposal and use it to create an intelligence report that provides a clear explanation of the solutions you are looking for.

The only issue here is that intelligence reports do not grow on trees. So, you must not only identify all this data but also classify and organize it in such a way that all this data can be converted into information.

For these situations, there has always been a process of knowledge creation called The Intelligence Cycle. This iterative model describes a series of stages and procedures that a researcher has to perform to convert the collected data and information into intelligence products capable of bringing solutions to the organization.

This process is carried out in 5 fundamental steps, which you can see in the below image:


1) Planning and Direction

This first stage is the crucial element of the research process, it is the moment when you define which horizon will your investigation take. This is where you determine the purpose of your research and what kind of information you are looking for.

2) Collection (gathering of data and information)

In this second phase your objective will be the identification of which kind of processes you will use to carry out the collection of such information, and then, using all the techniques you know, obtain the data that will help you carry out your intelligence operation.

3) Processing of data and information

In this phase, you will take care of all that was obtained in the previous process. Here your objective is not only the visualization of the information but also the application of decoding, decryption, validation, and evaluation techniques that will allow you to filter the huge amount of information you obtained, to identify useful data for your research.

4) Analysis to produce meaningful intelligence

This is where analysts can show what they really are. Here you must compile all the information you filtered in the previous step to obtain the solutions to your initial problem, as well as the creation of a coherent intelligence product (report, conference, etc.) that allows you to clearly explain the process you recently carried out

5) Dissemination of intelligence to the clients

And finally, we have the final step. Here you must deliver the product you developed throughout the process to the stakeholders (individuals or groups) that requested it. This will help these people make informed and appropriate decisions when tackling the original problem. That is all about the intelligence cycle, now you know everything you have to know to carry out an intelligence process and succeed in the process.

Securing Yourself Online
Online Tracking
A common thought that exists in the security community is that OSINT operations are completely invisible and at no time will the individual or organization you are investigating realize who you are. This is why this kind of investigation is called a “passive operation”.

However, something you should know at this point is that nothing is private on the Internet; and since the moment you enter into your trusted search engine, your browser is giving your information to the websites you visit. After all, every time you interact with your browser (either by accessing a website or downloading a file), it delivers a small amount of information about itself, data that not only allows the website to know what type of configuration it should use to display well on your screen but also data that can be used to identify you.

Fingerprinting

Do you remember that first moment when, after visiting an article in a web store, you surfed to your social networks and found an ad that displayed it again on the screen?

Well, this didn’t happen simply because the Internet is omniscient. It happened because, as you will understand, there are programs that can identify “little traces” that you leave behind with your internet browsing, and they are usually used to follow you through the websites you visit hoping to generate a model that helps identify your interests and give you recommendations (they practically know who you are, what you like and where you have been all along).

These “little traces” are usually not a problem if you are not very skeptical, but imagine how they can impact your work as an OSINT researcher while trying to stay hidden from your targets… It would be a disaster!

It not only would allow the targets to know of your existence but could also let them use those “little traces” to find out who you are, putting you at risk.

Without further ado, let’s start with our list of “little traces” that you may know as Fingerprints.

IP Addresses

Yup, what allows us to communicate is also what betrays us.

As you know, every time you use the Internet, your public IP address is sent through your router. This not only allows you to communicate with a website, but also tells it who to contact back, who to send X resource to, and how long it will take to reach that address.

And yes, we know that you know that the IP address is the most public thing that can exist and many websites don’t even bother to store this data. But, even so, you should always remember that this small element can be the first one that reveals who you are.

Cookies

“Would you like a cookie, my dear?” This is practically the question you always find while surfing the Internet, and the reason is that, nowadays, practically all websites use these elements to operate in an “optimal and user-friendly” way.

Cookies store your login information, your personalized settings, and even help you remember what was in your shopping cart. But some of these items are the main reason why websites know more about you. These are the “Third-party persistent cookies” (also known as “tracking cookies”)

These elements are stored on your computer’s Hard Drive and seek to obtain information about your activity, providing data to the website they come from and helping them to identify your likings, making them able to give you a “better user experience”.

Some of the websites that use this kind of cookies are the following:

Note: (These links will redirect you to “TheGuardian.com” website)

Doubleclick
Facebook
Google
and more…
On the following websites, you can learn more about the different cookie varieties and how they allow websites to track you:

https://www.theguardian.com/technology/2012/apr/23/cookies-and-web-tracking-intro
https://privacy.net/stop-cookies-tracking/
https://www.cookieyes.com/how-cookies-track-you-on-the-web-and-what-to-do-about-it/
Browser Fingerprinting

And finally, we have digitally generated fingerprints through the browser. This is actually the most dangerous and intrusive element we can find.

These are logs created by the browser, which use a variety of data available on your computer providing information to websites about the settings you are using, the machine you are on, etc.
This results in the creation of a unique identifier that allows your computer to be recognized from the rest.

This identifier contains information about the version of the browser you use, the operating system from which you are currently browsing, your screen resolution, the font type you have active at this time, among many other things. Making it practically impossible for your navigation to be private.

In fact, there are several pages that you can use to check out the information provided by your web browser. Here we will provide you 2 of them so that you can evaluate how “anonymous” you are while surfing on the Internet.


https://coveryourtracks.eff.org


https://browserleaks.com

Anonymization
After what you have just read you must be asking yourself: “but, if every time I use the Internet, I have to give information to the website I access, how can you talk to me about anonymity?”

And it’s true, we can’t talk to you about anonymity, because you can never really be 100% anonymous while using the internet. However, this does not mean that you cannot make use of some techniques and tools that allow you to look like someone else so that neither social networks nor big brother (Google, please don’t hate us </3) can know who you are while using the internet.

To do this, you just need to be aware of the elements mentioned earlier and install a few tools that will help you to be a little more protected than the rest of your fellow mortals.

Add Extra Layers

Before mentioning that the best thing you can do when surfing is to use a VPN or use TOR, we think it is good that you know the benefits of Virtual Machines, and that you know that they not only help you virtualize operating systems but also allow you to add an extra layer of privacy to your activities.

One of the best exponents of OSINT (Michael Bazzell) mentions in his book “Open-Source Intelligence Techniques” that the best practice that an OSINT researcher can do is: Use a Linux operating system (either by USB as a Live ISO or using a VM), do your research and finally erase all trace of you by simply rebooting the system (either by using a Snapshot, or the USB live).

With this, you not only did your research and were able to get all the information you needed, but you also deleted your trace, since any records that might have existed on the system were immediately removed by rebooting the system.

For this purpose, you can use some existing OSINT specialized machines like Trace Lab Osint VM, or you can create your own OSINT Linux Distribution (you will find an excellent guide for DIY Machines in one of the following links).

TL OSINT VM: https://www.tracelabs.org/initiatives/osint-vm
DIY OSINT VM Guide: https://nixintel.info/tag/diy-buscador/
Hide Your Public IP Address

As you well know your IP is the “face” that you present to the Internet world, making this the first thing that computers receive when they communicate with you. For this reason, being able to use a tool that changes your IP will be a decision that will not only help you keep your online identity protected, but will also allow you to navigate the Internet a little more privately. For this, you can use tools such as TOR Browser (covered in our Introduction To Dark Web Operations course), or a VPN.

Virtual Private Networks (VPN)
VPNs are an essential tool for anyone who wants to conduct an investigation. Not only does it allow you to hide your IP address from strangers, but it also adds a layer of encryption to all your communications, which helps a lot to maintain your privacy.

To give you a better insight into the VPN selection process, here is an excellent guide for choosing your own VPN provider:

https://www.secjuice.com/how-to-choose-a-virtual-private-network-vpn-provider/
Extensions For The Win!

Another tip you can use to reduce the amount of information that websites obtain about you is to install extensions that block this activity. That will practically close the possibility that websites can track you or run unwanted scripts on your computer.

Some of the most recommended extensions for this purpose are the following:


User-Agent Switcher and Manager

“spoof your browser “user-agent” string to a custom designation.”


No Script

“Allows JavaScript, Java, Flash, and other plugins to be executed only by trusted web sites of your choice”


Privacy Badger

“Stops advertisers and other third-party trackers from secretly tracking where you go and what pages you look at on the web”


Ublock Origin

“Filters requests to display adverts and prevents your browser from retrieving and displaying marketing content.”


Cookie AutoDelete

“Automatically delete unwanted cookies from your closed tabs while keeping the ones you want.”

Sock Puppetry

And finally, the best way to keep your real person separate from your digital person is by using Sock Puppets. These tools are practically the best friend of the intelligence team.

Give or take a word or two, sock puppets are alter-egos created specifically to carry out various types of projects or research. The purpose of these accounts is nothing more than being a false identity that can come into contact with research subjects, or simply to conduct OSINT research without directly linking your social networks.

Below, you will find some of the best guides on the Internet to build your own Sock Puppet and the best advice on how to NOT build one.

“Welcome to the (Sock) Jungle”: https://youtu.be/v8EP6xOcB8M
“The Art of The Sock”: https://www.secjuice.com/the-art-of-the-sock-osint-humint/
“Creating an Effective Sock Puppet for OSINT Investigations”: https://web.archive.org/web/20210125191016/https://jakecreps.com/2018/11/02/sock-puppets/
“Sock puppet Account Creation — My Process”: https://garrettmickley.com/sockpuppet-account-creation/
“The World’s Best Sock Puppet…Not!”: https://keyfindings.blog/2019/01/21/the-worlds-best-sock-puppet-not/
Tools and Services
The Harvester
The Harvester is a command-line information-gathering tool that utilizes OSINT sources to gather information about the target domain and retrieves information such as hostnames, IP addresses, employees (and their positions), email addresses, and much more. In the below screenshot, I am performing simple reconnaissance on the domain Google.com, using Google as the data source:

theharvester -d google.com -l 100 -b google
(tool) (target domain = google.com) (list 100 results max) (source = google)


This didn’t give us too much information, but knowing the IPs associated with google subdomains could be useful. Now let’s try something a little bit different. If we wanted to launch social engineering attacks against some Google employees, we can quickly identify potential targets by setting the data source to be ‘Linkedin’ instead of ‘Google’:

theharvester -d google.com -l 100 -b linkedin
(tool) (target domain = google.com) (list 100 results max) (source = linkedin)


Now we have a list of potential targets, along with their job titles. We can do further reconnaissance on them using Linkedin itself and build up a profile on them using a tool like Maltego, then we can launch spear-phishing attacks as part of a threat simulation engagement!

Try using The Harvester with different domains, and different data sources. You can access the help sheet for this tool by using the command theharvester within the command line. This will show you the data sources that are available, and other arguments to retrieve specific data.

Maltego
Following the line of TheHarvester, we will now have a very powerful OSINT tool called Maltego.

Maltego is a high-level data mining and information gathering tool, capable of obtaining real-time data on different types of entities (companies, people, websites, etc.), and representing them graphically through nodes, showing all the connections that the program was able to obtain over the Internet, about the subject under investigation.

Note: For this explanation, we will make use of the Kali Linux Operating System, since this tool is part of its “Information Gathering” collection.

So, first things first, to use Maltego simply type the command “maltego” on the command line, or search for the application through the Kali toolbar, as shown in the gif below.


Once started, you will see that there are 5 different versions of the software. Some are paid versions, while others are not. This time we will use the Community Edition since it is free and should not be a problem for you to use it.


Once you have selected your version, all you have to do is accept the license terms, create an account (you will then receive an API key that will allow you to use Maltego), and select the settings you prefer.

Once all the above is done, select the option “Open a blank graph” and finish the process. This will allow you to visualize a screen similar to the one presented below:


The next thing we should do to perform our first search would be to go to the “Transforms” tab and “Transform Hub”.


This will display the catalog of Transform Tools that can be installed in Maltego


For this example, install the tools “CaseFile Entities”, “HaveIBeenPwned?”, “Social Links CE” and “Shodan” (In the case of Shodan you must enter an API Key. To do this simply create an account on their website www.shodan.io and go to your account)


Once you have installed all the Transfer Tools, go back to the blank tab we created earlier and in the “Entity Palette” select “Domain” (you can use the search bar located in the same section), and drag it to the screen, as you can see in the following gif:


(In this example, we will make a scan of the site “paterva.com”, since they are the creators of Maltego and have given their permission to carry out this kind of scan).

Once you’re done with it, right-click on the entity, and click on the arrow next to “All transforms”, this will start the scan.

(If this is your first time running Maltego, a window will be displayed asking you to accept the disclaimer)


Once the scan is complete, you should obtain a graph similar to the one below, displaying all the information obtained by Maltego during the scan.


And that’s it, you’re ready to use Maltego, now start exploring all its functions and analyze all the information you got. The rest is up to you!

If you want to learn more about how to use this software, click on the following link and check out all the resources available on Maltego’s official site: https://www.maltego.com/categories/tutorial/

Tweetdeck
Twitter’s great, right?

There are approximately 500 million tweets a day. That’s a lot of information to get through, but TweetDeck makes it a lot easier to monitor trends, follow hashtags, and perform live searches. This is a useful tool for security professionals, as it allows us to monitor for events in real-time, such as cyber-attacks, vulnerabilities being released, or even tracking malicious actors’ activity. In this lesson, I’ll explain the basics of setting TweetDeck up, how searches work and provide examples of how it can be useful.

As we’re not actually going to be following or interacting with any accounts we’re monitoring, you can use any Twitter account you want, so there’s no real reason to use a throw-away or dummy account.

This is a section of my TweetDeck that I use at work (at time of writing, Sept 2019). My primary use for this is to monitor for vulnerabilities affecting common software (such as browsers), major operation systems (in this case Windows 10), and threat actors.

From left to right, the columns are monitoring for the following activity:

“bluekeep” OR #bluekeep OR cve-2019–0708
CVE-2019–0708, dubbed ‘BlueKeep’ was a Zero-Day vulnerability in Remote Desktop Protocol (RDP) that could allow an unauthenticated, remote attacker to bypass authentication. I was keeping an eye on this to see how it developed.
#firefox OR #chrome OR #internetexplorer OR #IE
Following vulnerabilities in Firefox, Chrome, and Internet Explorer.
#vulnerability OR #vulnerabilities OR #CVE
Broad search term for vulnerabilities (does bring back a lot of non-security tweets due to common language).
“Windows 10” and “vulnerability”
Monitoring for Windows 10 vulnerabilities.
#0day OR #zeroday
Monitoring for zero-day vulnerabilities that are publicly announced on Twitter.

To add a search column, click on the “+” icon on the left-hand side.


A pop-up will allow us to choose what type of column we want to add to our Deck. In this case, we’re going to be using the “Search” column type, in the top right.


This gives us a blank column, where we can enter in our own search queries. A quick example would be monitoring for tweets using the hashtag “#cybersecurity”.


We can start to build out these searches to look for specific activity. In the example below, I’m looking for the following:

Mention of the string “vulnerability” AND the string “apache”
OR the hashtag “#vulnerability” AND the string “apache”
This will show me tweets such as “Wow — just discovered a new vulnerability in apache, can’t wait to exploit it!“, or “CRITICAL #VULNERABILITY announced in apache v1.5 — Patch your systems now!“


This is what the column will look like once we’ve created it. As we can see, these tweets all have “vulnerability” or “#vulnerability” AND “apache”.


We can then click on these Tweets to see them individually, allowing us to comment, like, or retweet if we wanted to!


We can create our search queries in Twitter’s platform, by using their Advanced Search tools. To get to these, open up Twitter, search for anything in the search bar, click the

icon, and choose “Advanced Search”.


From here, we’re able to create complex search queries. In this example, I’m looking for the strings “cyber” and “attack”, and the tweet must also contain one of the following; “apt28”, “turla”, or “apt32” (well-known threat actors).


As we can see in the first two tweets, they both mention the terms “cyber attack” and “apt28”. We can now copy and paste this search string into our TweetDeck, allowing us to continually monitor for this specific activity.


And there you have it! A quick walkthrough of TweetDeck, and using it as a monitoring platform. It doesn’t just have to be cyber attacks or vulnerabilities, it can also be used to track geopolitical news, terror attacks, specific accounts, and anything else you may want to follow.

Google Dorks
Google is helpful in general, but Google Dorks are search hacks where we can use special arguments in a normal Google query to find specific information. Dorks come in the format operator:keyword, an example of this would be filetype:pdf. Real-world examples of using Dorks include:

Retrieving files from domains.
Finding hidden web pages and login portals.
Subdomain enumeration.
And more!
Finding Files

Let’s start of by seeing what PDFs we can find that are associated with cyber security, using the dork query:
Cyber Security filetype:pdf.


In the above screenshot we can see that the search has in fact brought back any PDF files that contain the strings “cyber” and “security. We can use this to see what files a company is hosting online, and see if any are confidential and should not be publicly accessible. It is also possible to retrieve information about internal systems and users by looking at the metadata of files to see when they were created and who by. Documents can also be used to create custom wordlists for password attacks against specific organizations. Try this yourself with a search term or a domain (such as Facebook.com filetype:pdf).

Subdomain Enumeration

Now let’s see how Dorks can be used to enumerate all subdomains of a domain, for passive reconnaissance purposes. For this, we will use Facebook again as the example, with the following query:
site:Facebook.com -site:www.Facebook.com
(Look for sites that include .Facebook.com) (but NOT www.Facebook.com)


Here we can see the list begins with two subdomains, portal.facebook.com, and code.facebook.com. We have successfully enumerated subdomains using Google Dorks. This is a great method for identifying uncommon web pages that may feature a login portal or valuable information such as development environments, files, and more. Have a go yourself with any domain you want, and see what interesting subdomains they have!

Keyword Searching

Using the Dork inurl: (value) we can look for specific keywords in a much more refined way than normal google searches. Using the query inurl: admin we can see a number of what appears to be admin login portals. This would be great if we were working as an attacker (if in scope, we can brute force or bypass the login portal to access administrator dashboards) or a defender (we can work to secure these portals so they are not compromised).


Conclusion

As you now know, Google Dorks are very useful. Take a look at this extensive list of the different search queries you can use, and play around with a few yourself to really understand how they work, and how they could be used for defensive or offensive security. https://securitytrails.com/blog/google-hacking-techniques

Defending Against Google Dorks
We know that Google Dorks can be incredibly powerful — they can exposure admin login portals, usernames and passwords, IP cameras and webcams, and much more. But how exactly do we protect against them?

Geofencing and IP Whitelisting

There are a number of ways we can use IP-based controls to restrict who can access web content, such as unauthorized users or google’s crawlers (programs that search the internet, indexing every publicly-accessible page they can find).

Geofencing is a method of blocking entire IP ranges associated with countries so that only access from a specific location will be allowed. For example, if a UK business wanted to only allow connections to their site from UK IP addresses, they could do this. Can you see the security flaw in this? If someone from America had a VPN, they could set it to exit from the UK, and now they are able to access the site. Netflix uses IP geofencing as they have different versions of the USA and the UK. VPNs were used to access the American version, but soon after Netflix caught on, and started to disallow VPN connections and proxies to access Netflix (you’ll see an error page asking you to turn off your routed connection before being able to access content).

IP whitelisting works in a similar way, but instead it only allows specified IP addresses to access resources, and blocks everything else. This is great if you have a development environment or site that is present on the internet, but you don’t want anyone accessing it. You can set the whitelisted IPs to the public range of the organization so that only IPs belonging to the company can actually view the site.

Crawler Restrictions

A very effective method of preventing content being present on Google is to block their crawlers from being able to access any of the content present on the internet. This can be achieved by creating a robots.txt file that disallows any crawlers from indexing any part of your website, preventing it from showing on Google’s search engine.


The above file will disallow any (*) user-agents from crawling any directory on the website (such as /images/ or /training/)

Requesting Content Removal

If you run google dorks against your company and find results that could be used by a malicious actor (such as a login portal or sensitive files) you can make a request to Google asking them to temporarily remove the content from their search engine (90 days) or permanently remove it. You must provide sufficient evidence that you own the site in order to have anything removed.

Information about temporary and permanent URL removals can be requested here –https://support.google.com/webmasters/answer/1663419?hl=en

OSINT Framework
This website is a hub for hundreds of OSINT sources and tools, and is easily sorted so you can find the tool that you need quickly. You can access the site here — https://osintframework.com

Use Case: Social Engineering Attacks

Say I wanted to create a fake persona so I could launch some social-engineering attacks during a red team engagement at my company. By opening the OpSec arm, and then Persona Creation, I’m provided with 5 links to online tools that can help me with the task I’m trying to complete. This can help me build a rich and more authentic profile, than if I was just filling out details off the top of my head.


Use Case: Are Target Emails Compromised?

Without diving down the rabbit-hole that is Threat Intelligence, we can quickly get a sense of whether a target email address has been mentioned in a data breach. Why is this useful? Because if we get an indication it has been leaked before, we can then start to explore paths such as finding data breach dumps on the dark web, and seeing if the email address has been linked with any passwords — then we can use these for password or social-engineering attacks. If we visit the Email Address branch, then the Data Breach sub-branch, we are provided with a number of online services that allow us to enter email addresses in, to see if they have been breached.


Use Case: Boosting OSINT Skills And Knowledge

OSINT Framework offers a good selection of OSINT training resources, so if you’re looking to further your skills then check these out. These are available under the Training branch.


We strongly suggest you check out this tool and see what interesting sites and tools you can find from it. https://www.osintframework.com

TinyEye
TinEye is an image search and recognition company, which offers customers the ability to receive alerts when their images are identified on the internet. This could be useful for Security Blue Team, as if people started posting our logo, it could potentially be someone pretending to be us, using our branding to give them more authenticity. This could also be useful for photographers who don’t want their images shared without proper authorization.

Moving away from the Alerts service they offer, anyone can use TinEye to conduct reverse image searches, which is where we upload an image and see where else it is present on the internet. We’ll cover how to use it, and provide a couple of use cases for using this tool.

Using TinEye

Head over to https://tineye.com/ and you’ll see the below search bar at the top of the page. You have the option of uploading an image, or using a URL that takes you to a hosted image. For this example we’ll use the upload feature with the below stock image of a dog. We should expect to see a lot of results for this image, as it will likely be used across the internet due to its nature.



After the search was completed, we were presented with the below screen, which shows that this exact image was found in 512 different places, amongst the total 39.6 billion images that were processed in an incredible 12.1 seconds.


Use Case: Identifying Social-Media Fakes

When people create fake social-media accounts, it’s extremely likely that they’re not using a unique photo. Chances are they’ve google something along the lines of “profile photo generator” and used one of them. These are usually really easy to identify just by looking at them (no one smiles that much), however using TinEye we can quickly identify fakes by seeing how common the profile photo is. We should expect to see anywhere between 0–10 results, depending on how much the photo subject loves using that specific photo. If we reverse search a profile picture and it has hundreds of thousands of hits, this should immediately throw red flags. We can then start to look at the websites the image features on (we can see this on the screenshot above). If we see stock photo sites or similar, we know that it’s pretty likely this is a fake account, using someone else’s photo. This doesn’t just apply to profile pictures — if an account is posting some pretty generic photos, we can also check how common they are. It’s virtually impossible for two people to take the exact some photo unintentionally, so if their images have even a low number of hits, this could be classed as suspicious.

Use Case: Brand Reputation Monitoring

Whilst there are better ways to do this, using the TinEye Alerts service, you can be notified every time one of your images is identified on the internet. This can be useful for monitoring the use of logos, especially trademarked ones.

Google Image SearchGoogle Image Search is very similar to TinEye as they share the core functionality. Simply head over to https://images.google.com and you’re able to search for an image URL, or upload an image manually. Let’s try using the dog stock photo from the TinEye lesson.


In the below screenshots, we can see that Google provided us with some interesting results based on the image we uploaded (above). At the top of the page (first screenshot), we can see the image in the search bar. There is also the phrase “free dog” which was actually generated by Google after analyzing the image, web pages where it is present, and any keywords that are commonly used in an attempt to describe what content the image contains. Google has searched any indexed pages for the image we uploaded, which has returned 2,910,000,000 results. Scrolling down the results page (second screenshot) we can see that Google is showing us any pages that include complete matches of the image we searched for.



Course Capstone
OSINT Challenge Brief
Welcome to the Course Challenge for our Introduction to OSINT course! We hope you have enjoyed the content so far, but now it’s time to put your skills to the test. In this challenge, you will need to complete three objectives:

Identify any social-media accounts or websites used by the person-of-interest
Build up a profile of the person-of-interest
Find any evidence of malicious behaviour
Challenge Scenario

You work for a law enforcement organisation, and you have been assigned to track a person-of-interest, that is believed to be associated with a hacking group that recently compromised a Managed Service Provider (MSP) and are trying to sell the stolen credentials on both the clear net and dark web. Another team is focusing on the dark web lead, so you have been tasked with using OSINT sources to build up a profile on the individual and attempt to locate any evidence that links them to the MSP breach and sale of account details. You have been provided with some information to start your investigation. You should use any of the sources or tools taught in this course, that you deem to be applicable and appropriate. We know that the email address used to register the Twitter account is fake, so do not include this in your report.

This is a fictional scenario. Any affiliation between the scenario individual and any real person is strictly coincidental.

Challenge Resources

Your manager has provided you with the following starting information:

Twitter handle used by actor: @sp1ritfyre
You can download a list of the information you have been asked to retrieve about the subject (.txt file). You should use this to help you find the right information, ready to hand in during the Challenge Submission in the next lesson. This will help to keep you on track, and not gather information that is not relevant to the current investigation. See the “Tips and Advice” section below before starting.

Download Challange Report

Tips and Advice

Read the template “SBT-OSINT-Challenge-Report.txt” properly. This will help you gather the information you actually need, instead of falling down a rabbit-hole.
Do not attempt to gain unauthorized access to any sites or accounts featured in this challenge, as it is illegal. There are potentially password-protected pages that are in scope and can be accessed. Do NOT attack them, try to find credentials.
DNS TXT records can be used to show text strings. Don’t forget to check if the owner has left a comment!
Some information may be encoded in Base64 or Hexadecimal so that it is not immediately human-readable. You can use online sites to decode them! Make sure you understand what B64 and Hexadecimal strings look like, so you can identify and convert them!
If you get stuck, chat with other students in our Discord server, specifically in the #i2-OSINT channel (but remember, no spoilers as they breach our Discord and community rules!).
OSINT Challenge Submissiom
Please ensure you have read the challenge brief in the previous lesson to familiarize you with the challenge scenario and the information you need to collect. Please note the following information regarding the challenge:

You can reattempt the quiz as many times as you like.
As with all final challenges, we do not provide Hints. Engage with fellow students in the Discord server, in the #i2-OSINT channel.
You need at least 80% to pass this quiz — remember you need 100% course progress to earn your certificate of completion.
Have fun, take your time, and apply the skills you have learned in the course!
[1] What is the hacker's first name?
[2] What is the hacker's last name?
[3] What is the hacker's age?
[4] What country does the hacker live in?
[5] What are some of the hacker's interests? (choose 5)
(a)Security  (b)Reading  (c)Photography  (d)Construction  (e)Gaming  (f)Malware Analysis  (g)Camping
[6] What company does the hacker work for?
[7] What is the hacker's position within the company?
[8] What is the full url of the website owned by the hacker?
[9] List any full URLs of websites not owned, but used by the hacker (Blogs only)
[10] What email address has been used by the hacker?
Thankyou For Reading

~Abhinav Sharma

Introduction
Osint
Osint Investigation
Osint Tool
Law Enforcement
33





Abhinavsharma.exe
Written by Abhinavsharma.exe
4 Followers
·
8 Following
Cyber Crime Intervention Officer at ISAC | Founder & CEO of Global Offensive Security | Helping CBI, CID, NCIB, NCB, MP Police, MP Cyber Police HQ | call 1930

Edit profile
No responses yet

Abhinavsharma.exe
Abhinavsharma.exe
﻿

Cancel
Respond
Respond

Also publish to my profile

More from Abhinavsharma.exe
Understanding the Threat of "Digital Arrest": A New Breed of Cyber Fraud
Abhinavsharma.exe
Abhinavsharma.exe

Understanding the Threat of "Digital Arrest": A New Breed of Cyber Fraud
Aug 18


The Truth About The Dark Web: What Is It, And How Can You Access It?
Abhinavsharma.exe
Abhinavsharma.exe

The Truth About The Dark Web: What Is It, And How Can You Access It?
The dark Web is a vast network of websites that aren’t indexed by search engines like Google and Yahoo. This means the sites are…
Oct 30, 2022


See all from Abhinavsharma.exe
Recommended from Medium
How to find webcams using the Google Dorking.
bob218
bob218

How to find webcams using the Google Dorking.
by bob218

Aug 31
14


SAR Use Cases for Geospatial Analysis
Cyber.H0und
Cyber.H0und

SAR Use Cases for Geospatial Analysis

Oct 31
1


Lists



Medium's Huge List of Publications Accepting Submissions
377 stories
·
4130 saves
designs of moka pots through the years
Staff picks
789 stories
·
1506 saves
Hunt down your colleagues with OSINT : 0
OSINT Team
In

OSINT Team

by

Dev Gautam Kumar

Hunt down your colleagues with OSINT : 0
Then, using some basic yet effective OSINT techniques, I shared surprising insights about them. The reactions were priceless — pure…
Nov 22
60
2


Social Links: Maltego As An OSINT Tool.
Investigator515
Investigator515

Social Links: Maltego As An OSINT Tool.
Identify associated accounts and become an A-grade sleuth using Maltego Transforms.

Oct 27
46


Geolocating a Gang Lord Wanted by the FBI: An OSINT Explainer
Benjamin Strick
Benjamin Strick

Geolocating a Gang Lord Wanted by the FBI: An OSINT Explainer
This report shows how OSINT techniques were used to find the ‘home’ of a gang leader.
May 28
380
3


Top 10 OSINT Tools for News Analysis
Vlad Mihet
Vlad Mihet

Top 10 OSINT Tools for News Analysis
Open-source intelligence (OSINT) tools have become indispensable for journalists and news analysts. They offer powerful capabilities for…

Jul 3
136


See more recommendations
Help

Status

About

Careers

Press

Blog

Privacy

Terms

Text to speech

Teams
