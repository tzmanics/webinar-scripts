# Kinvey Webinar 18Q4
## 0 - 5:30 Introductory Overview (5:30)

Hi everyone, thank you for joining me today. My name is Tara Manicsic and I’m the developer advocate for the Kinvey team. I’m excited to walk you through a quick intro of the benefits Kinvey can bring to your team and your product.

To put it simply, Kinvey is a platform of tools and services that help you rapidly build and update your complex applications with less dev time, less code all while keeping you and your team in control. Kinvey's goal is to help help you deliver robust applications in a shorter amount of time, while still understanding how any why everything works by reducing complexity without sacrificing functionality.

How do we do this?

One way is that Kinvey allows you to use a single language to create a native application across many platforms. Languages and frameworks that you’re familiar with that have large and growing ecosystems like JavaScript, TypeScript, Angular or Vue. Sound familiar? This allows you to create rich applications in a web-based environment that your team is already experienced in, no training or re-staffing required. We have a development studio that lets you build multi-channel application experiences using a template-based approach. Again, giving you ways to cut down the amount of code that you need to write.

Once your app is developed we help you take the stress out of deployment and scaling with our modern serverless backend which auto-scales to the highest levels. Traffic to your application isn't always predictable: get a mention in a popular tweet that brings tons of unexpected visitors? Scaling is flexible so as your traffic fluctuates Kinvey supports the frequent changes. It also integrates easily into systems of record and authentication all using a configuration-based low-code approach. Again, less code equals fewer dev hours spent on maintenance which means your team has more time to grow your product.

We also give control of microservices and functions as a service without complex, low-level development that you would usually require lots of coding and configuring with infrastructure providers. Because, again, we want you to be able to focus on adding app business value not thousands of lines of code just to get your app up there being served to your audiences. Let us take care of that.

Not only do we want you to be able to create rapidly we also want your data to be fast. That’s why we provide sub-second, safe and secure application access. With Kinvey you can rapidly virtualize different types of enterprise systems using no- and low-code microservices to popular systems such as SAP, SQL Server, Salesforce, Oracle, and more plus use identity solutions such as SAML, Open ID, Active Directory, LDAP.

Sounds nice but again, how do we do this?

We're able to give you sub-second data acceleration with our platform’s multi-level cache design. It protects enterprise Systems of Records from all the demands that having a multichannel digital experience comes with.

Kinvey also lets your application become more accessible to more users, more often by providing you with advanced offline data capabilities, allowing connectivity and end-to-end sync to backend systems when network connectivity is re-established. Your application users don't want to stop have access just because they lose connection. Setting up offline cloud caching can be quite cumbersome, dealing with service workers and caching. Let us do the heavy coding for you. 

A lot of power, right, well obviously we should talk about responsibility then. Security, of course! Kinvey makes sure to provide comprehensive end-to-end security giving you automated audits and compliance tracking of users and app usage. So you can actually see and understand what is going on with your application. Your client device data will automatically be encrypted and data in transport is also protected using TLS/SSL.

Kinvey even offers built-in HIPPA compliance. HIPPA compliance is hard and complicated, we make it easy.

With everything that we offer we want to make sure you’re still in control, that you and your team have full understanding of how your app is performing and advancing. For this we have standard and customizable dashboards to help you monitor your applicaitons and help you quickly assess and resolve any problems. Your team can see and report on compliance events with sophisticated filters and correlations for individual apps and users. This will help you make your application even better by helping you pinpoint and optimize performance bottlenecks or high-latency queries.

When it comes down to it, Kinvey’s purpose is to take big chunks of code off your development and infrastructure schedule so you can focus on building out all the features your users want.

## 5:30 - 11:00 High-level Features & Services (5:30)

Now that we have an overview of what Kinvey can help you achieve, let’s look into the features & services that will get you there.

### Frontend flexibility (0:15)
I started up two coding communities here in Cincinnati: Cincy Women Who Code and NodeSchool and one of the biggest requests from businesses I get is to send them developers. It’s hard to to find developers and even harder to find ones skilled in niche languages. Instead of worrying about that, Kinvey lets you and your team code in the very familiar JavaScript.
  
### Mobile app development with NativeScript (0:45)
Not only do a developers JavaScript skills help you build robust web applications but using NativeScript allows you to build out native mobile applications as well. NativeScript is a sibling product to Kinvey here at Progress but unlike most siblings they work really well together.

NativeScript is an opensource framework, no it’s not a new language, don’t fret :) Instead it actually allows you to code using JavaScript, TypeScript, Angular or Vue to build truly native mobile applications. Because of this you are again utilizing the skills you and your team already have. Letting you write and deploy native mobile apps for both iOS and Android from a single codebase. Even sharing code from existing Angular or Vue web-based projects.

### Rapid/Instantaneous environment creation (0:33)
We want you to be able to hit the ground running so we made it easy to get going with your project thanks to the kinvey console. A place where everything is at your fingertips but you’re not bogged down by endless tabs that drag you deeper into a rabbit hole of complicated options. We want you to be able to find your way around.

With the Kinvey console you’re able to rapidly create your application environment and start connecting services immediately. As soon as your app is created you can create, monitor and manipulate your data, identities, business logic, analytics and settings.

### Users & Databases (1:00)
Without delving into code Kinvey allows you to create or load a list of users, customize their information, create and assign roles all from one location. From that same dashboard you have control over connecting, viewing and customizing the data for your application. Here you can pull in data from a Kinvey Data Store or other services including:

- RapidData which lets you integrate with common backend systems and REST APIs like: Salesforce, SAP, Sharepoint, Microsoft SQL Server and more. All with no-code.
- RapidAuth, a no-code authentication service to ingrate common backend identity systems.
- FlexServices which are low-code node.js microservices for integratting with any backend data or auth services or implementing business logic.
- And even a custom option for web services written in any language that you use to integrate data and auth services.

### MIC - Mobile Identity Connect (0:30)
Kinvey comes with Mobile Identity Connect or MIC for short. This service bridges applications with existing enterprise identity and single sign-on solutions using SAML, OAuth2, Facebook Auth, OpenID Connect and more. We do this with a single OAuth2-based interface. This means you can offer your users secure, authenticated access to resources but your application developers do not have to deal with the complecity of integrating these protocols. Yet, they still have full control over a mobile user’s identity.
  
### Serverless Services (1:30)
- Microservice architecture lets you build out modular parts of your applications that can easily be updated and scaled without worrying about breaking the entire applicaiton. This lends itself to less problems when modernizing a project. Our Mobile Microservices Framework let’s you build, deploy and maintain targeted, scalable microservices for your applications. Allowing you to create both no-code and low-code microservices by offering our RapidServies and FlexServices to support Data, Auth and Functions.
  - RapidServices consist of out RapidData integration services for SAP, Salesforce, Sharepoint, NoSQL and REST
  - Flex Services are made up of FlexData which are data integration functions for any data source, utilizing the vast library of modules from the npm ecosystem. FlexServices also include FlexFunctions which are event-based, serverless function for extending your app’s logic to the cloud.

- Business Logic allows you to do things like trigger messages like push notifications and emails on developer-defined changes in a data store. Join multiple data collections to optimize data exchange with your application. Host platform agnostic code to save development time on multi-platform apps. You can trigger this business logic with collections hooks, custom endpoints or scheduled code.

### Security (0:45)
Security is a complex and very important issue and it is taken very seriously at Kinvey. Kinvey ensures security at the application level by design. Application-level security is critical and Kinvey provides the following security features at the application level.
- User Authentication
- Application Connectivity to Enterprise Data & Networks
- User Authorization
- User Revocation
- Data Security & Encryption
- Sensitive Data Protection
- Application Communications
- Data Access Controls
- Audit Trail
- Access to Enterprise Data
- Application Security Testing

Not only does the Kinvey application delivery platform provide enterprise security and HIPAA compliance, it also handles every part of the security infrastructure.

### Built-in Monitoring & Scaling (0:15)
When something goes wrond you don't want to have to spend time creating and running scripts to debug you application. Kinvey comes with built-in monitoring basically looking into the diagnostics of yout application for you. You also won't have to worry about making sure you application can handle an unexpected influx of people using your applicaiton becuase Kinvey takes care by auto-scaling your application. Just a few other ways to help take the load off your team and let Kinvey do the work for you.

## 11:00  - 20:00 Features & Services Breakdown (9:00)

- We’ve honestly just skimmed the surface of what these different features of Kinvey can do for your applications. Let’s dive a little deeper into some of the ways Kinvey can quickly and easily advance your applications.

- Mobile Development
  - Many people are accessing your applications from their mobile phones but we don’t always have the resources to create a web app, Android app AND iOS app. Kinvey and NativeScript (our free, opensource mobile framework that lets you build nativeiOS and Android mobile application with one code base using JavaScript, TypeScript, Angular or Vue).

- Rapid Data
  - Our applications use a ton of data these days, how do you make all this data available without developing and deploying complex APIs? This is where Kinvey’s RapidData comes in to help you make your applications mobile-ready connecting them to Kinvey without your team having to write any code. The Kinvey console will lead you step-by-step thru the process of choosing your RapidData Service. You can see your options here include: a REST API, DataDirect Hybrid Data Pipeline, Salesforce, SAP, Sharepoint, ProgressData, or Microsoft SQL Server.

- Cloud Caching
  - We have many users who have data they need to securely access on legacy systems which can be super slow, sometimes taking tens of seconds to fetch. Your application users don’t want to and, more than likely won’t, wait that long for you to dsplay their data; especially frustrated mobile users. For this reason we created Cloud Caching where we can automiatically maintain a chaced version of your data once it’s enabled. You can enable Cloud Caching any of your collections backed by a Custom or Rapid Service by simply clicking a box in your collection’s settings..

- Flex Services
  - One of the most beneficial resources we have for building robust applications these days are handy and powerful APIs but they don’t always have the easiest process for connecting to your application. Kinvey’s FlexServices allows you to create functions that contain business logic and third-[arty API integrations, tie into authentication systems or data integrations. These FlexFunctions can be reused and triggered in many ways including custom endpoints you can call directly or collections hooks called when data is updated or retrieved. You can use the FlexServices Runtime which is a Node.js serverless runtime environment or External Flex Services. 
  - The FlexService Runtime lets you  deploy your FlexData, FlexFunctions, or FlexAuth services in the cloud, on Kinvey-managed infrastructure as well as incorporate whatever modules you may need utilizing the npm ecosystem.
  - As well as running in the FlexService Runtime, FlexServices can be deployed on any PaaS, local server, or hosting provider.

- API Console
  - All these features are great but actually testing and debugging working with all these different APIs can be a pain. We wanted to give you a resources, built into your application console to be able to check debug your work easily. Kinvey's API Console allows you to send real API requests to your backend, set options for the requests and even save requests that you commonly make.

- Business Logic
  - At Kinvey we wanted you to be able to add more functionality to you application without you having to take a lot of time or write a lot of code. Kinvey Business Logic enables developers to focus on the unique functional business logic of a mobile application, while Kinvey handles the work of receiving, parsing, and routing requests, connecting to and querying data stores, and enabling mobile-specific functionality.
  - You can invoke business logic as part of a request to a Kinvey connection, a custom endpoint to execute an arbitraty function, as common code created and shared among business logic function or as a scheduled task.
  - We mostly see business logic used to trigger messages like emails and pushnotifications upon changes in the data store, joining multiple data collections to optimize data exchange, validating app user actions to enforce business rules and ro provide a means to host platform agnostic code, saving dev time on multi-platform apps.
  - We have extensive documentation to help guide you through all the things you can create using Kinvey Business Logic. 

- Security
  - Making sure your application has reliable security to pass along data is a complicated process. Writing the code and configurations to handle tokens, encryption, decryption across different devices and environments can be very time consuming. Yet, this is extrememly important in application development, and we know that here at Kinvey.  We've created a secure, enterprise-grade serverless cloud platform solution to alleviate security and privacy risks by isolating and protecting enterprise data sources and networks from client applications running on untrusted devices and their networks. We provide end-to-end security with automated audit and compliance tracking of users and access.
  - At the application level, Kinvey secures user authentication, connection to data & networks, user auth & revocation, data security and encryption, sensitive data protection, app communication, audit trails, app security testing and more.
  - We have made it so all access to Kinvey services is abstracted and authenticated with Kinvey tokens & the enterprise token is never passed to the application. Since the application may be running on untrusted, unmanaged devices, this provides a critical level of protection against the threat of enterprise tokens being compromised on the device.
  - Users can be identified through Kinvey Mobile Connect with no-code enterprise identity connections to: PING Identity, CA, Active Directory, Oracle Identity Management, IBM Secure Identity Manager, ForgeRock and more, including custom identity sources.
  - For secure application connectivty mobile applications delivered with Kinvey do not directly connect to enterprise networks or data. Instead we've created a Kinvey Mobile Data Connect between connections secured with a site-to-site IPSEC VPN tunnel with configurations and vendors decided upon by your security requirments.
  - We also know how important sensitive data is so Passwords, PINs, shared secrets and other sensitive information are hashed using bcrypt, SHA-1, SHA-2 or SHA-3 based on the type of data. All passwords are “salted” and hashed when stored.
  - We also have dedicated security focused on out multi-tenant and dedicated cloud instances including an intrustion detection system deployed on the bastion host and inside the VPN, storing Kinvey services behind a VPN, automatic weekly virus scans, monitoring and patching Common Vulnerabilities Exposure, audits on out cloud service and more. All this to say, we make sure your applications are safe and secure on every level.


## 20:00 - 30:40 Demos (10:40)
- Sub-second Data Acceleration & Orchestration (3:00)
- Decoupled Architecture (2:30)
- Connecting to Enterprise Data (3:00)
- Infrastructure & Operation (2:10)

## 30:40 - 35:00 Closing Remarks & Resource List (4:20)(:50)
With many platforms, you are made to rely on aging hybrid technology. Kinvey, on the other hand, is truly native interacting directly with mobile APIs using JavaScript— so no native code is required.

Progress takes your existing web developers and turns them into multichannel experts without expensive retraining or re-staffing. Like we talked about, your team will be using the very well-known, still growing lanuage of JavaScript or TypeScript along with the JS frameworks your team already knows.

Unlike traditional low-code solution that have monolithic architectures which can easily lead to modernization issues, the Kinvey platform is a patented serverless, microservice architecture that gets rid of the complexity of having to to build from scratch.
