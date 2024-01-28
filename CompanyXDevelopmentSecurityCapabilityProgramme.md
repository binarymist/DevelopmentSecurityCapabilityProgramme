Propagate to Security Champions before submitting.

# CompanyX Development Security Capability Programme

## Definitions

| Key | Value |
|-----|-------|
| Security Champion | An individual who has volunteered to act as the ‘voice’ of security for a Team or teams at CompanyX |
| Developer | Person responsible for developing solutions |
| Titan | Security Champion that has passed the CompanyX Security Titan assessment |
| Warrior | Developer that has passed the CompanyX Security Warrior assessment |

## The Problem

CompanyX is looking for a market differentiator, something to be known as, a specialisation that we don't currently have.

* The software we have created and are creating has many security defects, many of which are vectors for attack. The Security Champions have already found and documented MANY SECURITY DEFECTS
* The majority of our Developers have very little idea of what it means to create secure software
* The Developers (Security Champions) that do have an idea and have received some sort of commission from Kim have been struggling to obtain support in regards to a time investment from the Delivery Leaders and Executives. This may be starting to change
* Customers are starting to demand higher security and protection of their data, but in most cases don't expect to pay more for it
* We need to be able to produce quality products (baking security in upfront) and services faster
* Fixing defects at the end of the project are many times more expensive than if they were found and fixed as they were introduced


## The Dream

What if we could reduce the amount we spend on traditional security reviews, and penetration testing, and at the same time reduce the defects being introduced, and significantly improve your security stature, while reducing total project cost?

What if we could get our products to market faster, with fewer security defects, and for our products already in use, ensure that they will withstand the attacks of our and our customer's adversaries?

What if we had the visibility we need to make good judgement calls on the direction of our products and customers' security?

What if we could PROVE to our customers that we are taking the security of their data seriously, which is often a great marketing point as well, and that our products and services are a much safer investment than our competitors?

What if we could do all of the above, and without charging our customers extra for security?

## The Solution

* Set of lightweight Processes and Practises, Tools and Techniques required to take ownership of our security
* Find and fix defects as they are being introduced (cheapest place), rather than late in the development life-cycle (dearest place). This is a large part of how we offer security for no additional cost
* Provide immediate and continuous visibility and measurability of each project's security stature

### [Cheapest place](https://f0.holisticinfosecforwebdevelopers.com/chap06.html#leanpub-auto-cheapest-place-to-deal-with-defects) to deal with defects

There have been many studies specifically looking at the costs of finding and fixing defects early, as opposed to the planning of how to fix defects once the product is delivered, or not planning at all.

The following table shows the average cost of fixing defects based on when they were introduced versus when they were detected. Putting these practises in the right order can reduce the costs of fixing security defects by up to 100 times.

![average cost of fixing defects](https://user-images.githubusercontent.com/2862029/182813326-2a16cf03-532c-4f30-bef2-9f1aa9b62b00.png)

So... by simply shifting the security expenditure from the end of the project to within the Development Team, thus enabling developers to find and fix their defects as they are being introduced, huge cost savings can be enjoyed.

This is not as difficult as you may think.

### How this looks for each Development Team

* Each Development Team needs to build the process of threat modelling into their work-flows, thus:
   1. Creating actionable countermeasure Product Backlog Items
   2. Integrating them into the same Product Backlog that your Development Team has been pulling business focussed items from
   3. Ordering them based on the risk ratings you create for each
   
![countermeasures backlog](https://user-images.githubusercontent.com/2862029/182813816-c87ef6d7-3716-45e7-801b-18a893be960f.png)

* The [Secure Development Policy](https://wiki.companyx.com/MainPage_Developers?action=AttachFile&do=view&target=companyx+Secure+Development+Policy.pdf) and [Secure Development Policy Secure System Engineering](https://wiki.companyx.com/MainPage_Developers?action=AttachFile&do=get&target=companyx+Secure+Development+Policy+-+Secure+System+Engineering+Principles+and+Checklist.pdf) CompanyX documents describe most of this at varying levels.

## Programme

The individual Team's Processes and Practises will be different due to differences in constraints, technologies, levels of expertise, and culture

### Key Members Requiring Support

These are people with skin in the game. If we don't give them the support they need, then the programme fails.

#### Security Champions

Our Security Champions are smart people, but they are not magic. They need to be provided with time during their development cycles to invest and focus their energies on threat modelling and various other individual and Team activities such as upskilling, evangelising and mentoring Developers. Until now this has been a shortcoming. Without this investment, the plan fails.

#### Developers

Our Developers also need to be up-skilled, and given the time to do it. Developers are one of CompanyX's primary assets, if CompanyX wants to be known as the Leading New Zealand company for developing secure solutions, then we must invest in our income generators. Developers are the primary means for creating software solution outcomes that will not only stand up to the types of attacks we are facing today but actively defend against them.

### Events

#### Guild meetings

Security Champions are a core part of a Development Team with security capability. Our Security Champions need to be looked after, honoured, respected, built up and appreciated, this is simple Kaizen. The Security Champion Guild meetings are now being run monthly. These are a great opportunity to cross-pollinate learnings, discuss progress on initiatives, build our Champions up and continuously deploy them into their respective Teams to build the security capability, passion, awareness, and culture amongst their Developers.

#### Workshops

Various workshops for:

* Security Champions: ad-hoc, infrequent as most of this should take place in regular Guild meetings
* Developers: In order to scale, I'd imagine most of this would be done by the Security Champions eventually. Ideally, these would be reasonably regular

#### Secure Coding Tournaments

Although we are running an initial tournament with SCW, Kim has done ample research and has been involved in running these types of tournaments with free and open-source platforms and challenges. We could put together something custom ourselves in the future. These are great for lifting awareness and security capability amongst our Development Teams. Tournaments are also an opportunity for CompanyX to go public, holding public tournaments, and lifting awareness that CompanyX does what they say they do.

#### Application Security Workshops and Conferences

OWASP New Zealand Day is a free one-day conference focussed on upskilling Software Developers. CompanyX should have a reasonably sized contingent going to this every year. CompanyX Security Champions should be encouraged and incentivised to speak at these events. We have regular OWASP Meetups in Christchurch, CompanyX Developers should be encouraged and incentivised to attend these, learn and give talks.

### Assessments

How do we and our customers know that we are as good as we say we are, other than the obvious results?

#### Warrior

To become a Security Warrior, the student must pass the modules included in the Warrior assessment. Certain modules will be swappable depending on the technologies that the student is working with daily. The student must pass the Warrior assessment before sitting the Titan assessment.

Many modules will be specific to the technology they sit under.

Possible modules:

| All Dev | C# Dev | JS Dev |
|-----|----|------|
| Basic | Basic | Basic |
| Injection Flaws | Injection Flaws | Injection Flaws |
| Authentication | Authentication | Authentication |
| Access Control | Access Control | Access Control |
| Website | Website | Website |
| Mobile | Mobile | Mobile |
| IoT | IoT | IoT |
| Desktop | Desktop | Desktop |
| Insecure Cryptographic Storage | Insecure Cryptographic Storage | Insecure Cryptographic Storage |
| Insufficient Transport Layer Protection | Insufficient Transport Layer Protection | Insufficient Transport Layer Protection |
| Session Management | Session Management | Session Management |
| Cross Site Scripting | Cross Site Scripting | Cross Site Scripting |
| Cross-Site Request Forgery | Cross-Site Request Forgery | Cross-Site Request Forgery |
| Insecure Direct Object Reference | Insecure Direct Object Reference | Insecure Direct Object Reference |
| Security Misconfiguration | Security Misconfiguration | Security Misconfiguration |
| Denial Of Service | Denial Of Service | Denial Of Service |
| File Upload | File Upload | File Upload |
| N/A | N/A | N/A |

Fairly comprehensive set [here](https://securecodewarrior.com/supported-vulnerabilities)

Students will graduate as one of the following: All Warrior, C# Warrior, JS Warrior

#### Titan

To become a Security Titan, the student must pass the modules included in the Titan assessment.

* Advanced Threat Modelling
* Leading and Influencing Developers Effectively
* Active Defence Techniques for Applications

### Initiatives

#### DevSecOps

DevSecOps is an initiative that has taken off in most countries, New Zealand is lagging. As the name suggests it's an initiative that brings Development, Security and Operations closer together, breaking the walls down between these departments and disciplines. Establishing strong and regular communications between these disciplines, so much so that in many cases the lines of separation between departments disappear. It's this cross-cultural, cross-pollination attitude that reshapes an organisation's culture and allows a Software Development shop to move much faster than traditional development shops. DevSecOps goes hand-in-hand with [Continuous Delivery](#cd)

* Developers understand security and operations and can function in all disciplines to a degree
* Security Professionals understand software development and operations and can function in all disciplines to a degree
* Operations personnel understand security and software development and can function in all disciplines to a degree

The DevSecOps culture breaks organisational clicks and unites professionals in a common cause.

#### Bug Bounty Programme

Set up a bug bounty programme where Developers are rewarded for finding security defects in any/all CompanyX products.

#### Forming Habits and Sharpening Skills

Most of this comes from a desire to become great at one's profession. This desire alone can drive most Developers to do their own research, learning and practise. There are many things we can do to support the growth of our Developers. Many of which are already listed in this Programme.

### Regular Development Team Work-flow

The following activities (process and practises) are part of the regular Development Team's workflow.

#### Threat modelling

This needs to be performed initially on every project and continuously as projects are maintained and developed, as specified in the Secure Development Policy (SDP).

#### Evil Test Conditions

Many developers are familiar with the test condition workshop that is often used within a Scrum Team immediately before Developers pull a Product Backlog Item (PBI) into work-in-progress (WIP). This is a perfect point to augment this existing process with a security infusion.

#### Pair Programming

This is a great opportunity to identify defects as they're being introduced, this is the absolute cheapest place to fix them. Pair a Developer with more security capability with one of less.

#### Hand-crafted Penetration Testing

Just as our Development Teams perform some manual testing, we add some manual security testing.

#### Security Regression Testing

Utilise automated security testing tools, and integrate security testing into the development process. This is included as part of a nightly build. This also helps to produce faster release cycles with much greater confidence in the built software. A [bug bounty programme](#bug-bounty-programme) can fill the remaining gaps

#### Code Review

Security Focussed Manual Code Reviews, similar to pair programming but a little later in the development workflow, which means defects found here are slightly more costly to fix.

### Artefacts

#### Product Backlog

Kim is seeing lists of security defects being raised by the Security Champions, this will continue. Defects will be raised by Developers and countermeasures will be created and inserted into the Product Backlog ordered based on the risk ratings defined in the threat modelling that is part of the regular workflow. The visibility of these defects and their related countermeasure Product Backlog items are obviously of a sensitive nature to CompanyX Teams, and visibility of them to outside staff members should be consciously decided by the CompanyX Team responsible for each specific Product Backlog. The Security Champions and Kim at least should have visibility of all team's security defects and their related countermeasure Product Backlog items.


### Supporting Tooling Categories

* Security Regression Testing
* Using components with known vulnerabilities
* Test coverage statistics
* Static and dynamic analysis, linting, static type-checking tools
* Penetration Testing tools used manually within Development Teams

DeveloperX (TeamX Security Champion) has made good progress in terms of PoC's for the first three or four items above.  
Kim has experience with all of the items above and has been working on the first point as a SaaS and CLI product for over a year.

### Secure Development Resources

* [OWASP Top 10 Proactive Controls](https://www.owasp.org/images/b/bc/OWASP_Top_10_Proactive_Controls_V3.pdf)
* [OWASP Application Security Verification Standard](https://owasp.org/www-pdf-archive/OWASP_Application_Security_Verification_Standard_4.0-en.pdf)
* [Holistic InfoSec for Web Developers](https://www.holisticinfosecforwebdevelopers.com)

## The Costs

Each Development Team has very different constraints, therefore each Team must work out the processes and practises for themselves with assistance and guidance from Kim.

Establishing a threat modelling approach for each Team costs some time up front and some ongoing investment. This cost breakdown has been performed by the Security Champions with Kim's guidance and passed on to ManagerX. Although once the capability and culture is established, much of the cost is mitigated by smart processes, practises and tooling. As shown above, the processes, practises, tooling, and most importantly the cultural change will save us money, and at the same time make CompanyX a very attractive option in these times of ever-increasing cyber security attacks.

Workshops will take time for the trainer to prepare and time will be required for attendees.

Assessment creation will cost time upfront and time for each student to complete. We could leverage external training modules.

The process and practises in Regular Development Team Work-flow cost time, but end up saving the investment many times over. Kim has seen this happen in many of the development shops he has consulted for.

Some of the Supporting Tooling has licensing costs, some don't. There will be time investment required to set up, configure, and maintain, but again the cost investment will be returned usually many times over.


## Next Steps

<div id="cd"></div>

Continuous Delivery (CD). MentorX started discussions around adding a strong CD capability to CompanyX. This would be well worth continuing once our quality is in better shape. Scope, quality and speed can all improve, and counter to traditional thinking... this can save us money.



