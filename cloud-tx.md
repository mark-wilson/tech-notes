# Cloud Transformation
Cloud transformation is about tools and technology. It’s often IT-led (though it should involve business stakeholders too) and so it’s the domain where us techies are most happy. Often, it involves creating new platforms, using cloud services – Azure, Amazon Web Services, Office 365, G-Suite, Dynamics 365, Salesforce. But cloud transformation is just an enabler. In order to deliver value, [business transformation](business-tx.md) is required.

## What do we mean by "Cloud"?
In the early 2010s, everything was trying to be cloudy. If you ran a server in a datacentre and provided services to others (an application service provider), you probably said you were "on the cloud". These were the wild west days of cloud computing. A farm of virtual machines became "a private cloud", regardless of how they were managed and operated. 

Thankfully, the United States National Institute of Standards and Technology (NIST) wrote a short paper, which should be required reading for anyone getting their head around cloud computing. [The NIST Definition of Cloud 
Computing](https://nvlpubs.nist.gov/nistpubs/legacy/sp/nistspecialpublication800-145.pdf) defines the concepts we all settled on:

- The essential characteristics of cloud computing: on-demand self service; broad network access; resource pooling; rapid elasticity; and measured service.
- The service models: infrastructure-; platform-; and software-as-a-service (IaaS, PaaS and SaaS).
- The deployment models: public; private; community; and hybrid clouds.

## Moving to cloud is not the same as cloud transformation
A lot of my views on cloud is based on examples where organisations don't transform. Lift and shift is not cloud transformation. If you want to save money by moving to AWS or Azure, but without changing your working practices, you're in for a shock.

A former colleague, Colin Hughes, and I used to tell our clients that you can either transform as part of the programme, or afterwards. The timing will depend on the motivations - if you have an impending deadline (for example for a datacentre exit), then the temptation is just to lift and shift. But you must have that second phase of funded activity - to transform the estate - otherwise you will be left with big bills and wondering if you did the right thing. In fact, there's a perfect case study in this: in October 2022, [David Heinemeier Hanson wrote about how his company, 37 Signals, was leaving the cloud](https://world.hey.com/dhh/why-we-re-leaving-the-cloud-654b47e0). It seems to me, if they were renting servers for a decade. They never refactored the applications to take advantage of cloud native capablities.

## Does cloud have tangible benefits?
I asked a question of two people I respect a lot in this industry - Chris Weston and Matt Ballantine - on their WB-40 podcast [episode 271](https://wb40podcast.com/2023/09/11/271-ask-wb-40/). The question was not entirely clear in the way it was posed and the answer is a bit of a ramble - I don't even agree with all of it - but it contains some interesting points:

> "Mark: I think that selling cloud transformation on cost savings alone is dangerous, because it often costs more. But what tangible benefits have you seen from organisations making the journey to the cloud, or is it all non-tangible things like burstability?
> 
> Matt: Okay, so first of all I would say that burstability and flexibility, whilst weird language, are very tangible and anybody who has seen their website go down because of their inability to be able to service all of the users at any given time will know absolutely what the tangible result of not being able to burst capacity of what you’re doing might be like. Interestingly, one of my colleagues has just published a blog talking around how, I think, it’s a two second page load time is the limit at which you start to see massive drop-off of people being able to complete transactions on e-commerce sites and that again is a question about burstability being able to get the capacity when you need it as you need it to go to support customers when they’re coming. So there some things there that are quite tangible.
> 
> I think though, that the question about why is it an advantage I have seen and I have implemented plenty of advantage in moving to cloud based services because in medium-sized organisations it's meant that I just haven’t had to have a load of skills that we never really had any way in managing infrastructure. By being able to take out a swathe of risk associated with unpatched and unupdated stuff that was Internet-facing that really we didn’t know what we were doing as we didn’t have the money to be able to properly fund the people that are necessary to do it. That for me in the medium to large, medium organisations is the single most compelling business benefit of all of this stuff. You turn a whole load of things you used to care about worry about into black boxes that you no longer need to care and so not having to care about low-level security concerns, not having to care about management of hardware, and heating, and air conditioning, and power, and... and... and... and back ups, and... and... and - and it just being somebody else’s problem and the people whose other problem it is now having the scale and capability and capacity to be able to do it properly. That is the single biggest cost... and actually when you then think about the cost implications of all of that what you often find is, it’s way cheaper doing a lot of these things in cloud because you never were properly funding how you did it before. Take something like email as an example of that - you just you didn’t have the people to go to manage it properly. Which is why email used to go down regularly.
> 
> Chris: Yeah all of that, completely agree with all of that. I do think removing that destraction of the data centre that one day has to be replaced or created or whatever is definitely a tangible benefit. But I will also say that one of the things that we do a lot in our business is legacy modernisation and what it is currently right now is called digital transformation. People say what's digital transformation, well digital transformation for me is when you realise that your business organisation, needs a certain capability that your current tech stack just can't provide because it hasn't kept up with your competitors, you haven’t made the right decisions for whatever reason along the way and you found yourself in a place where you need to make a leap - a technological leap so that might be a "well we need to rewrite this software", "we need to re-platform", "we need to create...". A bank's a great example, right where suddenly they found that they needed to do the things that the challenger banks were doing like providing apps with instant access to the balances, so you go into your app and you can see what your balance is. In the old banks, for the old technology that the balance sits on a mainframe somewhere and in order to get that balance to a system that can talk to a mobile app that takes quite some engineering at the back end and it comes to a point where so much stuff is then being done in the app that you just can’t maintain this sort of ramshackle kind of mouse trap style technology that gets you from one place to another. 
> 
> The thing about cloud services is and this is different from just doing lift and shift of infrastructure to infrastructure as a service on cloud to more about the development on the cloud using platform as a service etc. is that you are always benefiting from the billions of dollars of research that’s been put in to lots of different products by various vendors and by Microsoft etc. because it’s always being updated and if you want to stay  competitive and again, I think that cloud versus on-prem debate goes back to a time, not so long ago when we used to get a CD with some software in it, put it onto a server and then that that’s your server and the argument about cloud was well "Is it your shit in your data centre or is it your shit in someone elses datacentre?". Well now it’s just it’s not shit anymore it’s it’s the whole thing, it's everything so not just how much do you want to be able to make it that it’s not just going to change when the next CD comes out in a years time or whatever - it’s going to constantly evolve, and if you’re gonna do that you really are going to need to have the latest tech available to you in terms of the platform. 
> 
> So yeah those are for me those are tangible benefits that show and provide capability to a business that they just don’t have on prem and I’m not saying on prem and cloud it’s always cloud and cloud‘s a no brainer. It’s not always the case, but if you ignore those things which are genuine benefits of being in the cloud then you're really not asking the right questions. 
> 
> Matt: interestingly as well, one of the clients I’ve been working with recently - they work in the financial services industry - and they produce software for banks that need to be installed because of security into banks' data centres and it’s really interesting how the skill of developing software to be distributed for installation into a behind firewall data centre is an extremely rare skill - these days people don’t know how to do it anymore. They know how to build a build for cloud, they know how to build a build for app stores. They maybe know how to be able to build to be able to distribute in containerised cloud things which can be implemented into private clouds for the idea of what was the exe installer for server software. There's very few people who know how to do that anymore because nobody does it anymore and that’s been a really interesting revelation for me at just quite how much things have moved on."

## Competition in cloud services
In 2022, the UK's communications regulator, Ofcom, stated its intention to carry out a [market study into the supply of cloud services in the UK](https://www.ofcom.org.uk/consultations-and-statements/category-2/cloud-services-market-study) to explore if these markets are working well and whether any regulatory action is required. [The final report was published in October 2023](https://www.ofcom.org.uk/__data/assets/pdf_file/0027/269127/Cloud-services-market-study-final-report.pdf), and determined that: 

> "there are features of the market that act as barriers to multi-cloud and switching and we have reasonable grounds to suspect that these features prevent, restrict, or distort competition in the UK, and that they merit further detailed assessment by way of a market investigation reference (MIR)."

Ofcom was most concerned about the following features:

> - "Egress fees are the charges that customers pay to transfer their data out of a cloud. The cost of transferring data between rival providers can discourage customers from using more than one cloud provider and in some cases make switching more costly.
> - Technical barriers mean that customers need to put additional effort into reconfiguring their data and applications to work on different clouds. A lack of interoperability and portability can restrict the ability of customers to switch and multi-cloud. 
> - Committed spend discounts can benefit customers by reducing their costs, but the way these discounts are structured can incentivise customers to use a single cloud provider for all or most of their cloud needs. This can make it less attractive to use rival providers as part of a multi-cloud strategy."

The [Cloud Services Market Research](https://www.ofcom.org.uk/__data/assets/pdf_file/0031/256459/context-consulting-cloud-services-market-research-summary-of-findings.pdf) that Ofcom commissioned through [Context+](https://welivecontext.com/) is a fascinating read. It's effectively a "state of the nation" when it comes to UK cloud services and it's a goldmine of information for anyone who wants to understand the sector.

Key findings included that:

- There is a widespread desire among firms to move towards cloud computing, with continued investment likely.
- The cloud supplier landscape is led by the big 3, with many companies not looking at the smaller players.
- Many companies struggle to accurately predict costs of cloud computing, and price increases at renewal can be steep.
- Switching between PaaS/IaaS providers is relatively uncommon, but this is not perceived to be due to restrictions imposed 
by suppliers.
- Diverse views co-exist as to the degree of commercial choice and competitiveness in the cloud computing market."

It then goes on to detail many items from the research including 

- Usage of cloud computing services.
- The supplier landscape.
- Contracts and purchase process.
- Service and supplier switching.
- Customer attitudes to competition in the cloud market.

As I read the research (and I'd recommend it to others too), some points that resonated with me were: 

- > "Support levels were criticised by many respondents, especially among those in smaller firms."

    That's something I've experienced too but the report also flagged that

    > "AWS is also not especially communicative or helpful in terms of supporting customers."

    I have no real experience with AWS, but it struck me how the hyperscalers are offering commodity services and support is a premium service.

- > "Deceptively expensive: make it hard to manage costs, with opaque pricing and billing."

    The billing/cost prediction issue seems real. Whilst there are tools and services that can  help with identifying optimisations after the fact, "bill shock" is a problem. Work can be done with policies and other governance approaches to control deployments and avoid spiraling costs.

- > "Fear of de facto lock-in and inability to switch."

    Egress costs are a big consideration and common across all major players (as the Ofcom investigation found). For PaaS, there's less commonality in the underlying platforms to move things around (which is why containers have become so helpful). Moving IaaS between providers should not be a significant challenge though.

    This is drawn out in another finding:

    > "Those who use both IaaS and PaaS are most likely to have switched. Those only using PaaS are less likely to have considered switching. Also, among barriers to switching are perceived effort, skills issues and dependency on ecosystems, with limited upside anticipated. Secondary barriers to switching are nonetheless significant; nearly all are internally driven rather than being 'created' by vendors."

    So the market is not seen as the problem.

- > "For many interviewed firms, existing investment in, and knowledge of, Microsoft environments makes using Azure a no-brainer."

    If you can build a business around Microsoft cloud services, the future looks bright. So bright in fact that:
    
- > "Those purchasing cloud indirectly are largely highly satisfied by the benefits these intermediaries provide.
  > - Without question, the experience of companies working with MSPs is positive.
  > - They tend to be smaller, more responsive and ‘human’ than the hyperscalers.
  > - Acting as a 'bridge', they are more readily available also.
  > - Specific benefits identified included: 
  >   - Deliver added value expertise, advice and consulting.
  >   - Provide more responsive service and support.
  >   - Can help end-customer to manage costs.
  >   - Can have stronger culture fit with smaller firms.
  >   - Help to deliver scarce, highly qualified resource.
  >   - May provide niche, vertical sector knowledge.
  >   - Can provide invaluable insight across cloud platforms."

    As an employee of an MSP, this was heartening. Especially as we have our own cloud and hybrid offers!

## Additional benefits of being in the cloud

Technology moves quickly. And we're all used to keeping operating systems on current (or n-1) releases, with known support lifecycles and planned upgrades. We are, aren't we? And every business application, whether COTS or bespoke, has an owner, who maintains a roadmap and makes sure that it's not going to become the next item of technical debt. Surely?

Unfortunately, these things are not always as common as they should be. A lot comes down to the perception of IT - is it a cost centre or does it add value to the business?

### Software Assurance and Azure Hybrid Benefit

Microsoft has a scheme for volume licensing customers called [Software Assurance](https://www.microsoft.com/en-gb/licensing/licensing-programs/software-assurance-getting-started). One of the benefits of this scheme is the ability to keep running on the latest versions of software. Other vendors have similar offers. But they all come at a cost.

When planning a move to the cloud, Software Assurance is the key to unlocking other benefits too. [Azure Hybrid Benefit](https://azure.microsoft.com/en-gb/pricing/hybrid-benefit/) is a licensing offer for Windows Server and SQL Server that provides a degree of portability between cloud and on-premises environments. Effectively, the cloud costs are reduced because the on-prem licenses are released and allocated to new cloud resources.

But what if you don't have Software Assurance? As a Windows  operating system comes to the end of its support lifecycle, how are you going to remain compliant when there are no longer any updates available?

### Extended Security Updates (ESUs)

That's where some organisations fall back onto [Extended Security Updates (ESUs)](https://www.microsoft.com/en-gb/windows-server/extended-security-updates). But it is a safety net - even Microsoft describes the ESU programme as: 

> ["a last resort option for customers who need to run certain legacy Microsoft products past the end of support"](https://learn.microsoft.com/en-US/lifecycle/faq/extended-security-updates).

In addition, the ESU scheme: 

> "includes Critical and/or Important security updates for a maximum of three years after the product's End of Extended Support date. Extended Security Updates will be distributed if and when available.
>
> ESUs do not include new features, customer-requested non-security updates, or design change requests."

They're just a way to maintain support whilst you make plans to get off that legacy operating system - which by now will be at least 10 years old.

If your organisation is considering ESUs, The real questions to answer are what are their sticking points that are keeping you from moving away from the legacy operating system? For example:

- Is it because there are applications that won't run on a later operating system? Maybe moving to Azure (or to a hybrid arrangement with Azure Arc) will provide some flexibility to benefit from ESUs at no extra cost whilst the app is modernised? (Windows Server and SQL Server ESUs are automatically delivered to Azure VMs if they’re configured to receive updates).
- Is it a budget concern? In this case, ESUs are unlikely to be a cost-efficient approach. Maybe there's an alternative - again through cloud transformation, software financing, or perhaps a cloud-to-edge platform. 
- Is it a cash-flow concern? Leasing may be an answer.

There may be other reasons, but doing nothing and automatically accepting the risk is an option that a lot of companies choose...  the art (of consulting) is to help them to see that there are risks in doing nothing too.

[Go home](README.md)
