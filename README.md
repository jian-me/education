## An Incident Response Tabletop Exercise for High School / Undergraduate Students

![20231211_095457-EDIT_SMALL](https://github.com/jian-me/education/assets/94001429/7dc1c56b-f475-4a33-a7aa-72240ab1588c)

### Objective

This exercise aims to introduce students to the breadth of work that information security professionals do using an interactive, incident response scenario. 

### Why?

Often in structured learning programs, students learn about information security in silos. This exercise aims to break down those silos by giving students insights into how different disciplines collaborate and share information. We use an incident response scenario because it is fun (if you have ever done incident response, you know what I mean!) and forces natural collaboration. 

### A few things to keep in mind before we start:

1. The content below is provided as a guide. Feel free to amend or add content as you see fit for your specific lesson. 
1. If you plan to run a version of this exercise, I encourage you to rehearse the scenario at least once with the teacher or someone else who will be in the room with you. After my first run-through, the hand-offs between me and the teacher were much smoother, which led to a more engaging and educational experience for the students.
1. The content is meant for high school and undergraduate students. Depending on the students’ knowledge and comfort levels, you may need to adjust the content or delivery accordingly.

### The setup

1. Introduce yourself and the exercise 
> e.g., We are here to learn about the different teams in information security and how they work together in an interactive exercise.
2. Introduce the scenario
> e.g., You are all part of the global security team at a fictional company called Apptastic. The company develops a fully immersive VR experience in a futuristic cityscape in the metaverse. It connects players with a proprietary Hololens technology and interacts with each other using social credits. The company’s tech stack is hosted in Amazon Web Services (AWS). As part of the team, you are called upon to respond to a potential security incident. The details will follow.
3. Split the class into 3 separate groups - GRC, Security Engineering, Security Operations
4. The CISO (teacher) is there to help facilitate discussions among the 3 groups. The teacher may need to prompt certain groups to contribute.
5. There are multiple sets of cards (also called “Fact Cards”) labeled `A`, `B`, `C`. The letter corresponds to the phase of the incident scenario (see “Running the Exercise” below). Hold on to the cards until you reach the appropriate phase.

At this point, you should have the following roles and teams defined.

* Group #1 - GRC (students)
* Group #2 - Security Engineering (students)
* Group #3 - Security Operations (students)
* Teacher - CISO. Help prompt and encourage students to participate and share information. Can also help bridge information in the scenario to what the students may have learned in class.
* You - Facilitator. You will be reading information on the slides and working with the teacher to facilitate discussions. You may also write information (i.e., IP addresses) on the board so it is easier for students to see them.

### Running the Exercise

**Phase A**

Hand out all the “A” cards.

**Nov 23, 2023 @ 20:03:00 UTC** - Read the slide. If the students are not familiar with AWS, you may need to explain why and in what situations AWS Support would contact the company. Read the content of the message in Slide 11 out loud. This slide is meant to ease students into the exercise.

**Phase B**

Hand out all the “B” cards.

**Nov 23, 2023 @ 21:15:00 UTC** - Read the slide. Ask the Security Operations team about the alert and have someone on the team read out some relevant info from the card.

The teams may uncover several data points using the Fact Cards they have now. For example:

* IP addresses and where they originate from (TOR) - Explain what TOR is.
* Email address of accounts that received multiple push notifications
* Name of the vendor that provides outsourced IT services
* Names of some applications from the asset inventory along with owners
* Password and other policies
* Risk exceptions or acceptances

Help encourage the discussion. Depending on the students’ level of experience, you may need to guide them in the right direction. Also, feel free to discount some information if you feel students are going down a rabbit hole or if you are running short on time.

**Phase C**

Hand out all the “C” cards.

**Nov 24, 2023 @ 06:02:44 UTC** - Read the slide. What are the applications? What does this mean? What kinds of threats could possibly take systems / applications offline?

**Nov 24, 2023 @ 12:05:30 UTC** - Read the slide. Does the fact that the issue is now trending on social media change the urgency? 

The teams may uncover several data points using the Fact Cards they have now. For example:

* The systems that are offline. How do these systems tie to the asset inventory?

These cards may or may not be relevant to the decision-making process. By now, students will have most of the information they need to recommend actions.

**Nov 24, 2023 @ 12:10:43 UTC** - Explain what this screen could represent. Explain ransomware.

* Important Discussion Points:
  * What are the impacts?
  * How can companies recover from ransomware?
  * When was the last backup taken?
  * What are the options?
    * Restore from backups. This would cause players to lose several days’ worth of progress in the VR game.
    * Pay the ransom. You may get the encryption key to decrypt your files or you may not. Are you willing to take the risk?
    * Try to recover the latest files by yourselves. You may be able to prevent players from losing several days’ worth of progress but how long could it take to purge the ransomware and recover the latest files?
  * Discuss the trade-off among the groups and with the CISO.
  * Encourage the class to recommend an action to the CISO and discuss the aftermath.

**Wrap-up:** Use this time to discuss what happened after the class decision. Also, ask the class what they learned and perhaps what the company could have done to either prevent this type of incident from happening in the future or reduce the impacts.

If you have any feedback 
