# Homework 2: Design Specification

This document is last edited by Team _Undefined_ [^Undefined] on April 17, 2019.

## Problem

Pentland et al. stressed the importance of relationships and how it is essential to a team’s success. Their research has shown that interpersonal conversations and social interactions have improved engagement, employee experience, and productivity. However, not every team communicates efficiently nor has strong relationships with one another. The problem we will be focusing on is communication and building trust between teams and team members.

Jong et al. states in their article that negative relationships within the team influences team performance. Research has shown that interpersonal relations marked with animosity can reduce team cohesion and induce team conflicts. Moreover, Jong et al. mentions team members who experience negative emotions can influence and produce a native climate. This, in turn, can obstruct communication within the team. For instance, Jong et al. states in this type of environment team members can withhold information or sabotage another colleague.  In contrast, positive interactions have shown to promote a positive and more welcoming environment. The authors state that effective communications within the teams can soften negative experiences experienced by some team members. Similarly, positive interactions can offset negative relationships within teams.

No matter the project the team is working on, whether that be a technical project or theoretical project, team conflict is unavoidable. There is an existing app called [IceBreaker: Have Better Dates](https://itunes.apple.com/us/app/icebreaker-have-better-dates/id1304625074?mt=8) that provides questions for couples on a first date. The problem with this app is that there is no category of questions to pick from, no option to pick what question comes up and no flexibility to edit or add a question. If a user wants to talk about a topic they are comfortable with but random questions they do not want to answer repeatedly appear, it may lead to frustration and cause tension between the pair.

Additionally, [Poll Everywhere][08b905c4] does introduce the ability to present flexible questions. However, the overall design of the application is too complicated for both the participant and poll creator. Moreover, from the participants perspective, there isn’t a motivating factor that promotes interpersonal communication. This, in turn, does not foster relationships between teammates and would not be particularly effective in utilizing for the purpose of building or strengthening relationships.

  [08b905c4]: https://pollev.com/ "Poll Everywhere"

Another existing application that also provides a fun break from work is [Kahoot!](https://kahoot.com/) Kahoot! is a program, in which a teacher in a classroom setting can create questions for the students to answer. There is an option for Kahoot! to participate as teams, and this provides an opportunity for team bonding. However, this program does not give students the opportunity to get to know one another, and bond over shared interests as the program was designed to be a review of students’ knowledge in class.

A new solution is needed in order to address the difficulties team members experience when working on a team project. There is a large gap within current solutions being implemented in terms of its ability to allow members to get to know each other and integrating face-to-face talking. This gap makes it difficult for team members to move past the stage of being “in the same group” to “acquaintances or friends”. Therefore, the solution outlined below revolves around getting team members to know each other and an opportunity to move the relationship past the initial uncomfortableness.  


## Solution

<div style="width:150px; height:100px">
![Figure 1](/img/figure1.png)
</div>

Figure 1 shows the main page of our web application, Dive-In!. It provides the user with two abilities:
- New which creates a new room
- Join an existing room

The “New” feature will provide Organizers the ability to create a new room while “Join” will connect players with a currently open room.

<div style="width:150px; height:100px">
![Figure 2](/img/figure1.png)
</div>

Figure 2 is when the Organizer has created a room upon clicking the “New” button in Figure 1. It provides the ability to begin the ice breaker game after an ample amount of people are participating. They will have twothree different options which are:
Begins the icebreaker game
A knowledge test where all the players are given a series of question on how well they know each other.


Figure 3

When the Organizer presses on the “Start Icebreaker” they will be shown in Figure 3. The Organizer would select a category of questions they would like to go through. Each icon represents a specific genre of questions. The random option will randomly select questions from each category. While the customized option allows the organizer of the room to write their own questions.


Figure 4

The Organizer will be shown in Figure 4 and have the option to begin the icebreaker. The “Discussion Time!” button will automatically show the next display in Figure 5. Similarly, it will display the question on the Organizer’s screen to every player in the room.


Figure 5

Figure 5 will provide the Organizer with the option to move forward to the next question which will display the next question on the Organizer’s display like Figure 4.


Figure 6

Figure 6 would appear after the Organizer selects the “Take Test” button. This feature will test every player’s knowledge of how familiar they are with their team members. The player will be awarded points based on whether they answer correctly or incorrectly.


Figure 7

If the player selects the join button in Figure 1, they will be led to Figure 7. The player will input their name and room number into the corresponding text boxes and select an icon. The “Join Now” button connects the user to the corresponding room number. Once the button is selected, it will check that the room number is correct and try to connect. However, if the player inputs an incorrect room number then, an error message will appear and ask the user to type in the correct information.


Figure 8

Similarly, after the icebreaker is completed, the players will be shown in Figure 8. Players will have three different features:
An analysis where a personal report is generated showing how well the player did.
The player can overview their answers to the questions they answered.
They can see their rank in comparison to their teammates.

The “View Ranking” feature will only appear after the test has been done.  


Figure 9

After the Organizer selects a category and initiates “Discussion Time!” as shown   Figure 4, each player will be shown the same question on their displays. Likewise, they will have two options to choose from.


Figure 10
Figure 10 is presented after the player selects “View Ranking” from Figure 8. It would show the player the rankings of all the players within the same room which is calculated from their test scores.


Figure 11

Figure 11 would be shown to the player after they press on the “View My Analysis” feature from Figure 8. The player will be shown who is the most compatible teammate based on their answers. They will be provided two options:
Next which will present them Figure 11
Done which exits the analysis screen and presents Figure 8

Figure 12

Figure 12 displays how many people enjoy similar activities as the player or has similar commonalities as them. The player is provided three options:
Next which shows another screen similar to Figure 12 with different analysis
Prev which goes back to the previous analysis page
Done which exits the analysis feature




## References
Jong, Jeroen P. De, et al. “When Do Bad Apples Not Spoil the Barrel? Negative Relationships in
Teams, Team Performance, and Buffering Mechanisms.” Journal of Applied Psychology,
vol. 99, no. 3, 2014, pp. 514–522., doi:10.1037/a0036284.

Pentland, Alex "Sandy", et al. “The New Science of Building Great Teams.”Harvard Business Review,
15 July 2015, hbr.org/2012/04/the-new-science-of-building-great-teams.

Windsor, Grace. “How to Tackle Poor Project Communication.” BrightWork.com, 24 May 2018,
www.brightwork.com/blog/tackle-poor-project-communication.

IceBreaker: Have Better Dates: https://itunes.apple.com/us/app/icebreaker-have-better-dates/id1304625074?mt=8

Our high fidelity application is located here:
https://www.figma.com/file/gW7445WDsd8zFo0SUEv2Nyzi/Prototype?node-id=0%3A1
