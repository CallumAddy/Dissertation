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



4) K. Chellapilla and D. B. Fogel, “Evolution, neural networks, games,
and intelligence,” Proc. IEEE, vol. 87, no. 9, pp. 1471–1496, Sep. 1999.

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