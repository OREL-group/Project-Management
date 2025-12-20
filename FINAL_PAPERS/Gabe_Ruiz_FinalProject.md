## ShroomGuard

Name: Gabe Ruiz

Semester: FA 25



|![wildmushroomspic](https://github.com/user-attachments/assets/960de31f-22a9-4281-adc8-ce6d02a16dcb)| 

## Introduction   

One of my favorite activities to do when school is off is to go hiking and spend several days in the wilderness. It's fantastic to feel the open air, reconnect with nature, and to detach from the rest of the world. A highlight of hiking for me will always be foraging. Whether it's finding wild berries, small seasonings, and flowers adds a lot of authenticity to the activity. However, an issue I and other hikers have run into before is not knowing which mushrooms are safe to pick. It's difficult to choose to risk a great addition to that night's meal or dangerous poisoning. In the last 25 years, there have been over 130 thousand cases of mushroom poisoning and exposure (Brandenburg, 2018).

This is where ShroomGuard comes in, which is an app that allows users to take pictures of the mushrooms they find, and then a risk factor will be identified and swiftly delivered. It would be similar to apps that scan objects into 3d, but instead of turning them into a model, it looks at all the features of a mushroom and then identifies how likely it is to be poisonous. The app is not going to change the world, but it will save thousands of lives.

The goal of this paper is to explore the architecture and implementation of ShroomGuard; from the motivation to implementation strategy and how its open-source community will work.

#### Objectives & Motivation

My interest in developing ShroomGuard comes from personal experiences and observations on the general hiker's knowledge of mushroom picking. Having experience exploring nature trails and hiking, I have witnessed the tragic consequences of mushroom misidentification through news reports and foraging community discussions. Seeing experienced foragers rely on outdated field guides and new hikers trust unreliable online sources, I see now an opportunity to create meaningful change through technology. The project represents more than just an educational tool, it's a chance to solve a life-threatening problem that affects thousands of foragers, hikers, and nature enthusiasts annually.

This project goes beyond individual hikers avoiding a stomach ache. Studies show that mushroom poisoning leads to thousands of emergency room visits each year, with some cases proving fatal (Northwest Mushroomers Association). Many of these incidents happen because foragers and hikers lack access to reliable and immediate identification resources in the field. As long as people keep confusing mushrooms for their toxic or non-toxic lookalikes, there will be a constant risk. By creating an app that provides instant, accurate identification with clear toxicity warnings, ShroomGuard has the potential to significantly reduce these preventable poisonings and save lives.

The need for such an app is easy to see from there. With increasing interest in hiking and foraging, sustainable food sources, and outdoor recreation, more people are picking mushrooms than ever before. Current solutions mostly boil down to field guides that require prior knowledge to actually use, or mobile apps with limited databases and unreliable image identification. ShroomGuard would address this by combining the latest image recognition technology with a comprehensive, expert and user verified database that prioritizes safety above all else, making reliable mushroom identification accessible to both beginners and experienced foragers alike.

#### Technical Vision & Implementation  

The technical architecture of ShroomGuard is designed for scalability, reliability, and user experience. The project is structured into distinct phases that ensure systematic progress while maintaining flexibility for adaptation based on user feedback and changing requirements.

The backend track is from database design to payment integration which forms the foundation of the platform. Using modern technologies like cloud infrastructure, the system will handle real-time image processing and direct user feedback. The development sprints are carefully planned across 24 weeks, just under 6 months, with clear milestones and deliverables at each stage.

My technical implementation begins with a scalable database design for managing user profiles, their pictures, and the mushrooms they have cataloged. This foundation is very important for handling the relationships between users and the app. Building upon this, we implement user authentication systems that ensure secure access and protect user data while maintaining a seamless experience. 

The frontend track focuses on creating an intuitive user interface that makes taking pictures of the mushrooms as simple as possible. This phase is followed by the implementation of specific user features and mushroom cataloguing which would help ensure that the platform remains user centric while maintaining technical excellence. The frontend development emphasizes responsive design and accessibility while making sure that users can easily access the platform across various devices and screen sizes.

| <img width="2438" height="1410" alt="image" src="https://github.com/user-attachments/assets/be8bd30a-cf2a-41d8-92cc-9ad6a36ee568" />| 
| :--: |
| <b>Figure 1.</b> Project Plan Mapping |

## Project Management

The development of ShroomGuard follows a four-sprint structure, each handling a major phase of research, design and deployment. The diagram above depicts the progression from foundational planning all the way up to initial release. Each sprint iterates from the previous one, meaning all team members working on the project have to communicate and correspond with each other throughout the whole process.

### Sprint 1: Scoping and Project Planning

The first sprint revolves around clearly establishing the issue we're trying to solve and what our software needs to look like in order to solve that issue. The research process would include outreach to hiking communities and experts to get their input into what the most pressing issues are when it comes to mushroom picking as well as academic research into different mushrooms and how to recognize which ones are poisonous. Once that's done, we would create diagrams and graphs that outline the rest of the project so that everything is completed as close to a timeline as possible. THis would also be the time to address upcoming challenges and concerns about the project. 

### Sprint 2: Prototyping and Outreach

This is when all hands are on the deck and the project is officially being made. The development and research teams would be working on developing the back end of the app, designing and developing the architecture of the app, how it will generally look and work, and looking into ways to store the information collected from users. At the same time, the database and cloud management team would be working on the setup for the database and testing its limits. The purpose of this would be to make sure that the information is being properly stored, that it's secure and protected from attacks, and most importantly, to see how much data it can actually handle and at what speeds. If it turns out that the database we're using is not up to the task, we need to pivot and adjust as quickly as possible, as to avoid technical debt and having to scrap large sections of the project trying to catch up. Lastly, the marketing and outreach team would begin their marketing process and fund-raising efforts. These types of projects aren't cheap, and we need as much funding as possible as early as possible. Whether it's crowd-funding or finding private investors, we would need the resources to train all our developers on software they're not familiar with as well as paying them for their work. 

### Sprint 3: Development and Implementation

During this sprint, the app would enter it's final stages of initial development. This would include fully integrating the database into the app, testing to see that everything works as intended, refining the UI so that users don't find themselves frustrated or confused on the app, and making sure all the features work as intended. At this point, the app should be able to scan the mushrooms and give various metrics on its toxicity and usefulness. This sprint is a little larger than the other development ones, since finishing the app always comes with unexpected issues and delays, so giving ourselves extra time just in case can help mitigate the time spent on bug fixing and restructuring of certain parts of the app if they don't work as intended. By the end of this sprint the app should be fully usable and confirmed to be able to handle thousands of users. 

### Sprint 4: Release

The most important part of creating a project is actually releasing it. The final sprint would be everything that comes with the launch of an app, including the actual release and immediate support. During this sprint, we want to see what issues users are dealing with that we didn't catch, immediate issues that require attention, and seeing what the most requested changes are. We also want to monitor the database, making sure it's working as intended and that its as secure as possible. We don't want any users to be doxxed. 

#### Risks & Challenges

ShroomGuard solves a very specific issue. It's going to be difficult to advertise it to broader audiences and to investors if they only see an app with one feature with no room for growth. It also makes it difficult to spread the word because the hiking and foraging communities are not gigantic, getting a casual hiker to find out about our app is going to be a difficult challenge. It's important that we emphasize the open-source aspects of the app, and to show users that the base app can be used in countless other ways. 

The technical debt of this project is going to be quite large. 3D scanning is not a cheap technology, and neither is training developers to use it. There is a great risk of not being able to deliver the product in time if the technical debt for image processing isn't dealt with efficiently. Ensuring that we are focused on what the app is supposed to do and not tinkering with features that will lead nowhere is extremely important. We also want to make sure that developers keep the information they learn, committing the syntax to short memory will be good during the sprints, but if current developers can't document properly or explain to future developers how to use the software, it's useless. 

Lastly, as an open source project, managing it's community will always be a challenge. Whether it's automating the process and training bots to detect harmful contributions and misconduct or hiring moderators for ShroomGuard, keeping tabs on the community is a time and money sink. Hopefully with the revenue collected during the sprints, this issue is taken care of at launch, and not something that has to be done out of pocket or with the time of our development staff. 


#### Future Development

The future development roadmap for ShroomGuard extends beyond its initial implementation as we envision an evolution that adapts to emerging technologies and changing image scanning needs. Our scalability strategy includes both technical expansion and market growth which ensures the platform remains relevant and efficient as demand increases.

Technological advancement stands at the top of our future development plans. Integration of machine learning algorithms will enhance the mycology library and mushroom detection and also analyze geographical data to inform users of what types of mushrooms inhabit their local hiking area. These predictive capabilities will help hikers forage more efficiently while also making sure they aren’t overwhelmed with information or lost on how to find details about their region.

Infrastructure scalability remains a critical focus for future development. Our cloud based architecture will be optimized to work offline, but update when the user is connected to a local network. Database sharding and replication strategies will maintain performance as the user base grows while content delivery networks will ensure consistent service quality across geographic regions.

Community growth initiatives focus on expanding the network effect of our platform. Partnership programs with property developers will integrate ShroomGuard with other hiking and foraging related apps. Having everything located in one place greatly helps user retention and app usage. Proper collaboration with health authorities and mushroom experts will help our credibility and ensure a level of safety for our users so they know they can trust our app to save them from ingesting anything directly dangerous.

### Conclusion      

ShroomGuard represents a meaningful intersection of technology and outdoor safety, addressing a critical need in the hiking and foraging communities. By leveraging modern image recognition technology and comprehensive mushroom databases, the app has the potential to prevent thousands of poisoning incidents annually and provide peace of mind to both novice and experienced foragers alike.
The structured four-sprint development approach ensures systematic progress while maintaining flexibility to address challenges as they arise. From initial scoping and research through prototyping, full-scale development, and release, each phase builds upon the previous one to create a reliable, user-friendly platform. The emphasis on expert verification, secure data management, and comprehensive testing throughout the development process reflects a commitment to safety—the core mission of ShroomGuard.

While challenges exist, particularly in marketing to niche audiences, managing technical debt associated with image processing technology, and maintaining an engaged open-source community, these obstacles are addressable through careful planning and resource allocation. The open-source nature of the project not only encourages community contribution and transparency but also positions ShroomGuard as a foundation for broader applications beyond mushroom identification.

Looking ahead, ShroomGuard's success will be measured not just by download numbers or user engagement, but by its real-world impact: fewer emergency room visits, increased confidence among foragers, and ultimately, lives saved. By making reliable mushroom identification accessible at the moment it matters most—in the field, when a forager encounters an unknown specimen—ShroomGuard fills a critical gap in outdoor safety technology.

The path from concept to launch is challenging, but the potential to create genuine positive impact makes ShroomGuard a project worth pursuing. With proper execution, community support, and ongoing development, this app can become an essential tool for anyone who ventures into the wilderness to explore nature's bounty.

### References     

Brandenburg, W. E., & Ward, K. J. (2018). Mushroom poisoning epidemiology in the United States. Mycologia, 110(4), 637–641. https://doi.org/10.1080/00275514.2018.1479561

Poisoning - Northwest Mushroomers Association. (2023, February 28). Northwest Mushroomers Association. https://www.northwestmushroomers.org/poisoning/


