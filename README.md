# Dissertation

Question:
 "What impact does integrating a neuroevolution network into a behaviour
 tree have on perceived difficulty and player enjoyment?"
 
 Hypothesis:
 
 1)
 AI with neuro network is more enjoyable and challenges the player more.
 
 2)
 The players who like harder games will prefer neuroevolution AI and players who prefer easier games will prefer a predefined behaviour AI which is easier to predict.
 
 
 References:
 1) https://dl.acm.org/doi/pdf/10.1145/3067695.3076016
 A Deep Learning / Neuroevolution Hybrid for Visual Control - By Andreas Precht Poulsen, Mark Thorhauge, Mikkel Hvilshj Funch, Sebastian Risi
 Notes:
 - This paper does research on combining Neuroevolution with deep learning, this is an interesting approach and will 
 provide a good reference for my dissertation as I'm combining Neuroevolution with a behaviour tree, the hypothesis
 that they've presented is that the deep learning will help the neuroevolution network learn quicker than if it was on it's own.
 
 - The experiment taken in this paper was random bots are spawned in the scene and the AI gets the position and shoots at them (the bots are stationary as is the AI).
 
 - The training of the AI was performed with Unity's UnityNEAT, they used this instead of the DCNN as input as it's computionally expensive so they used the game engine itself to train the AI.
 
 2)
 https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7307180
 Neuroevolution in Games: State of the Art
and Open Challenges - By Sebastian Risi and Julian Togelius

Notes: 

 - This paper has done research on applying neuroevolution to strategy games to try and solve problems, applying machine learning to strategy games would be beneficial
 as the AI will learn from the players move turn by turn, but in my research I plan to apply neuroevolution on a greater scale. (Page 1)
 
 - In section II neuroevolution it goes into detail about neuroevolution and the most straightforward way to encode an ANN is with a fixed topology that is based
  on the interactions the player takes in the game. (Page 2)
  
  - This paper has a section where it asks why it should use neuroevolution, one of the reasons was to combat problems at a record beating performance, this is one
  of the reasons I am using neuroevolution as I want to challenge the player more than a pre defined AI behaviour would. (Page 2)
  
  - Neuroevolution method convincingly beat all other methods for most problems and it found a solution to the problems in encounter in fewer attempts than any other algorithm 
  which is why it performs better. (Page 2)
  
  - Neuroevolution seems to handle large action/state spaces very well therefore on an fps game there will be a large amount of actions for the neuroevolution to take in and because it handles 
  it well, it won't be an issue. (Page 3)
  
  - Neuroevolution can draw on the rich family of diverysity-preservation methos such as niching, and multi-objective methods that have been developed, this enables neuroevolution methods to achieve 
  several forms of diversity among its results and it can deliver various strategies to combat the player, this takes away the predictability of the AI and makes it a harder target for the player 
  which goes on the difficulty of the AI again which is what I'm trying to achieve. (Page 3)
  
  - The paper talks about the role of neuroevolution and how it can be used in one of two ways, the way I plan on using it is to evaluate the state and actions of the player and learn behaviours off of 
  those actions and define the behaviours the AI will take within a behaviour tree, which is where the neuroevolution is intergrated into my behaviour tree. (Page 3)
  
  - The neuroevolution can predict the experience or preferences the player takes when trying to combat the AI this will make the AI hard for the player which is perceived as more difficult. (Page 3)
  
  - The FPS game Unreal Tournament evolved layered controllers consisting of several neural netowrks that implemented different components of good game-playing behaviour, path following exploration 
  and shooting, these networks output direct control signals and they were able to override eachother according to a fixed hierachy. (Page 5)
  
  
  3)  A. Agapitos, J. Togelius, S. M. Lucas, J. Schmidhuber, and A. Konstantinidis, “Generating diverse opponents with multiobjective evolution,”
in Proc. IEEE Symp. Computational Intell. and Games 2008 (CIG'08),
2008, pp. 135–142.

Notes:

- This paper discusses how different AI behaviours can affect how the game is pereceived whether the behaviours are fun to play against or not.

- Predictable AI is one of the most common complaits found under the I heading in reviews of commericial games, so the fact that the AI in my project will learn from the player
makes it less predictable and the player should enjoy playing against it more.

- If all the AI act the same way it can also be boring for the player, so you want your AI to act differently, more human-like.


4) B. D. Bryant, “Evolving visibly intelligent behavior for embedded
game agents,” Ph.D. dissertation, Department of Computer Sciences,
University of Texas, Austin, TX, 2006.

Notes:


5) C. A. C. Coello, D. A. Van Veldhuizen, and G. B. Lamont, Evolutionary Algorithms for Solving Multi-Objective Problems. New
York: Springer, 2002, vol. 242.

Notes:

6) M. Parker and B. D. Bryant, “Neuro-visual control in the Quake II
game engine,” in Proc. IEEE Int. Joint Conf. Comput. Intell. Neural
Networks 2008 (IJCNN 2008), 2008, pp. 3828–3833.

Notes:


7)
 M. Parker and B. D. Bryant, “Neurovisual control in the Quake II environment,” IEEE Trans. Comput. Intell. AI in Games, vol. 4, no. 1, pp.
44–54, 2012

Notes:

8) J. Schrum and R. Miikkulainen, “Constructing complex NPC behavior
via multi-objective neuroevolution,” Proc. Artific. Intell. and Interact.
Dig. Ent. Conf. (AIIDE), vol. 8, pp. 108–113, 2008.

Notes:

9) 
J. Schrum, I. V. Karpov, and R. Miikkulainen, “UT2: Human-like behavior via neuroevolution of combat behavior and replay of human
traces,” in Proc. IEEE Conf. Computational Intell. and Games (CIG
2011): IEEE, Seoul, South Korea, Sep. 2011, pp. 329–336.

Notes:

10) J. Schrum, I. V. Karpov, and R. Miikkulainen, “Human-like combat
behaviour via multiobjective neuroevolution,” in Believable Bots.
New York: Springer, 2012, pp. 119–150

Notes:

11) K. O. Stanley, B. D. Bryant, and R. Miikkulainen, “Real-time neuroevolution in the NERO video game,” IEEE Trans. Evol. Comput.,
vol. 9, no. 6, pp. 653–668, 2005.

Notes:


12) G. N. Yannakakis and J. Hallam, “Evolving opponents for interesting
interactive computer games,” From Animals to Animats, vol. 8, pp.
499–508, 2004.

Notes:

13)

S. Zanetti and A. E. Rhalibi, “Machine learning techniques for FPS
in Q3,” in Proc. 2004 ACM SIGCHI Int. Conf. Advances in Comput.
Entertainment Technol. (ACE '04), New York, 2004, pp. 239–244.

Notes:


14)
K. O. Stanley, B. D. Bryant, and R. Miikkulainen, “Real-time neuroevolution in the NERO video game,” IEEE Trans. Evol. Comput.,
vol. 9, no. 6, pp. 653–668, 2005

Notes: 


15) 
G. N. Yannakakis, “Ai in computer games: Generating interesting
interactive opponents by the use of evolutionary computation,” Ph.D.
dissertation, University of Edinburgh, 2005.

Notes:

16)
Zach Laster, "Evolving Agents using NEAT to Achieve Human-like Play in
FPS Games" Master's Thesis, University of Helsinki, 2014.

Notes:

- In this paper their goal is to make a human-like AI in an FPS game this is because AI's in FPS games are very rarely enjoyable to play against as they are very predictable.

- AI's that behaviour like a human are more enjoyable to play against and are engaging for the player as they can't predict what will happen next.

- This project talks about using NEAT to create a more engaging target for the player in an FPS game.

- If a game is too easy it becomes boring quickly, therefore you have to find the right balance of how hard your AI is.

- You want your AI to evolve with the players skills, it is good to reference the flowchannel [Hunicke and Chapman, 2004].

- There is significant research in applying machine learning to games in order to achieve a dynamic and adaptive difficulty scaling, this makes the game more immersive for the player.

- Dynamic Difficulty Scaling can be used to produce a more balanced game as it will adapt with the players skill level as the players skill level improves as will the AI.

- Dynamic Difficulty Scaling is an online mechanic which means that it is utilised during gameplay, this is often achieved by adjusting difficulty between individuals sessions 
 or rounds of the game, but it can adapt during the session.

- Adaptive AI is the route I want to take with my artefact as I want my AI to adapt based on the players input.

- Offline and Online learning can be used in conjunction to better the AI.

- In addition to the difficulty of an agent, it is important that the agen should be interesting, the actions that the agent should perform should appear to be intelligent and human-like.

- If the agents appear to act in a human-like manner this brings the game to life more than if the AI was predictable this will then proceed to add to player enjoyment.

- Making the agent difficult does not always mean that they are fun to play against, the agent needs to act in a human-like manner so that the player can engage better.

- It is believed that given agents human-like behaviours like running away and charging when angered gives the illusion that the agent is more realistic.

- Uses search based approach to find the best solution for the agents problem.

- NEAT evolves the topology of the network instead of just the weights.

- Mutation in nEAT can generate new connections as well as new topology in the network

- NEAT allows the genomes to grow without any limitations.

- We can use NEAT to produce human-like agents which are interesting to play against, these agents once fully trained could be able to keep a player well within the flowchannel for most of the session.

17)
Andrade et al., 2005 Andrade, G., Ramalho, G., Santana, H., and Corruble, V.
(2005). Challenge-sensitive action selection: an application to game
balancing. In Intelligent Agent Technology, IEEE/WIC/ACM International Conference on, page 194-200. IEEE.

Notes:


18) 
Arrabales et al., 2009 Arrabales, R., Ledezma, A., and Sanchis, A. (2009). Towards
conscious-like behavior in computer game characters. In Computational
Intelligence and Games, 2009. CIG 2009. IEEE Symposium on, page
217-224. IEEE.

Notes:


19) 

Bakkes et al., 2009 Bakkes, S., Spronck, P., and van den Herik, J. (2009). Rapid
and reliable adaptation of video game AI. Computational Intelligence
and AI in Games, IEEE Transactions on, 1(2):93-104.

Notes:

20)
Cole et al., 2004 Cole, N., Louis, S., and Miles, C. (2004). Using a genetic algorithm
to tune first-person shooter bots. In Evolutionary Computation, 2004.
CEC2004. Congress on, volume 1, pages 139-145 Vol.1. IEEE.

Notes:


21)
Hunicke and Chapman, 2004 Hunicke, R. and Chapman, V. (2004). AI for dynamic
difficulty adjustment in games. In Challenges in Game Artificial Intelligence AAAI Workshop, pages 91-96.

Notes:


22)

Westra, 2007 Westra, J. (2007). Evolutionary neural networks applied in first person
shooters. Master's thesis, University Utrecht.

Notes:



