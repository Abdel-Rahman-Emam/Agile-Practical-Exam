# Za-Warudo MMORPG Video Game
Agile Practical Exam 18P3602
# Short Description of the Project
Za Warudo is an all new MMORPG game that is set in the spartan age, the game’s all about uniqueness in characters and playstyle, ranging from all new combat abilities that is based on actual fighting moves created from scratch by our engineers, to crafting up weapons that are fully user customizable. The game sets off with a customizable character that is to be upgraded and enhanced working up through the game.


## Team Members
| Name | Role | Expertise |
|-------|------|-------------|
| Abdel Rahman Emam Ali | Software Developer | C++ OpenGL|
| Jack Mohamed | Tester | Unit Testng |
| Mohammed Ali | Tester | Integration Testing |
| Youssef Joe | Graphics Developer | Blender |
| Amr Hammam | Graphics Engineer | Unity |
| Hazem Eldeeb | Software Developer | Rust |
| Youssef Kassab | Software Developer | Ruby |
| Magnus Eissa | UX Designer | Adobe XD |
| Mostafa Younes | GUI Designer | Adobe XD |
| Abdelfattah Abdelnasser | Sound Engineer | Fmod |


## Stakeholders

Gofundme funders
Gamers
Designers
Media
Distributors
Developers

## The Near Vision
   For the first sprint, we should have at least a functioning dev character model with very basic animations.
  
   For the second sprint, we hope to have a mini-map to be able to walk around it.

## The Story Point Estimation Convention Used
   The story point estimation convention used in this story as stated in the README file is the Fibonacci convention which states that the story point estimates should take       values based on the Fibonacci series and those are as follows: 1,2,3,5,8,13,20,40,60,80,100. And as can be seen in the product backlog above is that the stories are given       estimates as such.
  
## The product backlog order and rationale:
As the initial photo for the product backlog has already been ordered, it hasn’t been ordered based on the priority and how much return on investment would it achieve and that was already explained in the README.md but rather it has been ordered based off the importance of it to the core gameplay of them game. Questions that were asked to achieve such order were for example: How much would the game change if this feature isn’t added? How will the gameplay build on if this feature is added? and so on. Based on this simple questionnaire we ordered the product backlog to be as it looks in the screenshot above. Also by going for this type of approach, it will give utmost priority to bugs rather than for new features.

 
## Story Points Estimate per Sprint
   Since we have a relatively large team, it was decided that 40 story points is good achievable metric in our sprint duration (4 weeks), thats also due to the fact that we
   have about 5-6 stories per sprint.
   
## Daily Scrum Document 2 Examples:
![image](https://user-images.githubusercontent.com/77146272/147745367-c4cf8f35-df99-4f47-9cb8-0e4360fca330.png)


## Sprint Document Examples:
### Sprint 1 Documentation:
**Goal:**
   In this sprint we would like to have a fully freely moveable character by the end of the sprint as well as have a few animations added to the character that’s beside initial concepts of the founder skin which is exclusive, furthermore we would like to have some sort of initial concept of how the map would look like.<br/>
**Leftovers of Last Sprint:**<br/>
	Since this is the first sprint in the project, there’s no leftovers.<br/>
**What was done Last Sprint:**<br/>
		Since this is the first sprint in the project, nothing was previously done.<br/>
**Sprint Backlog:**</br>
| **Epic**                                                     | **User Story**                                                                  | **Description**                                                                                                 | **Estimate** |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | ------------ |
| **Have character ragdolls with animations and basic sounds** | As a gamer, I would like the game to have where I can move the character freely | The ragdoll will have more nodes representing joints to extend the freedom of movement                          | 13           |
| **Have character ragdolls with animations and basic sounds** | As a gamer, I want the game to have unique fighting animations                  | The game shall have unique fighting animations                                                                  | 13           |
| **Create character skins and classes**                       | As a gamer, I want the game to feature exclusive skins                          | The game will have exclusive skins that shall show from time to time, it starts out with a base founder skin    | 8            |
| **Create character skins and classes**                       | As a gamer, I would like the game to feature various classes at game start      | The game shall have 4 starter classes to start from with basic designs                                          | 3            |
| **Have character ragdolls with animations and basic sounds** | As a gamer, I want the game to have a damage feedback system                    | The game shall have a reactive damage feedback system that shall distinguish between high damage and low damage | 5            |

### Sprint 2 Documentation:
**Goal:**<br/>
In this sprint we would like to have a a basic design of the map and have a standard look of how POIs will look and start on the gear and inventory system.<br/>
**eftovers of Last Sprint:**</br>
	The 4 initial classes to be made and their skins and abilities.</br>
**What was done Last Sprint:**</br>
	The ragdoll model is finally done all that’s left is to apply a standard skin for it, we also did some sort of initial damage feedback system that’s to be updated after game’s release. Furthermore, we had the map model drawn down on paper and did the founder skin.</br>
   **Sprint Backlog:**</br>
   
| **Epic**                                                     | **User Story**                                                                             | **Description**                                                                          | **Estimate** |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------- | ------------ |
| **Create character skins and classes**                       | As a gamer, I would like the game to feature various classes at game start                 | The game shall have 4 starter classes to start from with basic designs                   | 3            |
| **Have a user-interactive map**                              | As a gamer, I would like the game to have many POIs on the map                             | The map shall have initial design of 6 POIs to be wandered around. All dev-textured.     | 20           |
| **Have a user-interactive map**                              | As a gamer, I would like the game's map to respond to players actions.                     | The game should have puncturable environment with feedback and doors and such.           | 20           |
| **Have a user-interactive map**                              | As a gamer, I want the map to be connected through fields                                  | The map’s POIs will be connected through grass and sand                                  | 13           |
| **Have character ragdolls with animations and basic sounds** | As a gamer, I would like the game to have underwater combat abilities                      | Characters shall have special ways of fighting underwater.                               | 5            |
| **Create inventory and enhancement system**                  | As a gamer, I want the game to have a way to be able to enhance the gear and the inventory | The game shall have multiple ways of enhancing items via different enhancing techniques. | 13           |

**Epics to be Delivered:**</br>
Have character ragdolls with animations and basic sounds</br>



## Explanation for the project workflow and rule rationale:
![image](https://user-images.githubusercontent.com/77146272/147746090-cbb37620-d7cd-4926-8bfb-48bb5a91d055.png) </br>
A story feature will be starting from the IN PROGRESS state in which once its done, it will be sent for code review in order to check for safety of the code, if such code has a problem it will be sent back the in progress state for further updating of the code, however from those 2 points a story can be discarded and hence will be sent to the finishing state DISCARDED in which story points that aren’t going to be continued are sent. If the story code however passes the code review it is then sent to the testers of the teams in which they decide whether the code has bugs or not and the severity of such bugs, once those bugs are found the story is then sent back to progress for the bugs to be fixed, however if there are no bugs found by the testing team the story is hence sent to the DONE state in which it will be shipped. One of the rules that has been included in the project workflow is the check on transition from testing to done, which is to done to be absolutely sure that the story has been gone through the required progress.</br>
