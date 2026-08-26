# GAP analysis of accessibility standards in Gaming

Games require an element of challenge which can be thought of as 'intentional friction'. Accessibility guidance aims to reduce all friction because friction creates inaccessibility for groups of people. Therefore accessibility guidance aimed at gaming needs a different approach to standard accessibility guidance. This gap analysis researches existing accessibility guidance that could apply to gaming and finds that there is no robust mechanism for identifying and preserving 'intentional friction'. It proposes that a Games Accessibility User Requirements (GAUR) document is created to address this unmet need. 

## Characteristics of an ideal candidate 
These are the characteristics of an ideal candidate which current resources will be judged against. This is not to say that a GAUR if created will be able to fulfil all of these but it should aim to.  

### Focus on the user experience
A good candidate will attempt to describe good user experience as a first step towards an accessibility standard. By focusing on the requirements of the user rather than the options available to a developer the candidate can describe 'what good looks like' regardless of how achievable 'good' is with current technologies. This is important to enable a realistic assesment of progress and also to futureproof the work.

### Understand intentional friction in gaming
Any accessibility standard will need to avoid requiring 'fundamental alteration' and gaming requires intentional friction in order to provide a challenge. A good candidate should differentiate between intentional and unintentional friction (signal vs noise) to preserve what makes games engaging while minimising inaccessibility. This should enable it to inform the creation of a workable standard.    

### Cover multiple disabilities
A good candidate should cover as wide a range if disabilities as is practical including sight loss, hearing loss, neurodiversity, cognitive impairments and physical disabilities.

### Comprehensive 
As much as possible a good candidate should attempt to be comprehensive to enable any standards it informs to also be as comprehesive as possible. This may require a high level of abstraction in order to avoid gaps. 

### Collaborative 
A good candidate should invite critique from as wide a range of stakeholders as possible to enable it to be as comprehensive and fit for purpose as possible. 

## Intentional friction
There is a body of work that highlights the need for some friction in gaming. This means that a standard approach to accessibility of trying to remove all friction or barriers would be inappropriate. Not only would it constitute fundamental alteration of the game which may be considered an unreasonable requirement but it could actually break the game experience itself.

### The perception of difficulty
[Ian Hamilton's Difficulty vs Accessibility talk](youtube.com/watch?v=sPehhHZvKE8&feature=youtu.be) at GAConf USA 2021 highlighted that there is no fixed difficulty for a game. Games present barriers and players have capabilities and the level of difficulty that arises comes from trying to overcome the given barriers with a user's unique set of capabilities. Disabled people will have reduced capabilities meaning they will face higher difficulty for the same set of presented barriers. Within the talk he states that "Accessibility = avoiding unnecessary mismatch between capability and barrier". Steve Saylor framed this to say that accessibility is a way to [bring the difficulty back towards the intended level](https://kotaku.com/accessibility-difficulty-easy-mode-explained-1851261475).  

### The need to preserve inaccessibility 
In the [IGDA-GASIG page on how to make games accessible](https://igda-gasig.org/how/) it states:
"All games must contain some degree of inaccessibility in order to be a game. There must be some kind of challenge. This necessary inaccessibility varies from game to game. It makes accessibility an optimisation process – thinking about the barriers your game may present, which of those are a necessary part of what makes it fun, and which are not."

### Game Accessibility Paradox
In the article [Game accessibility course design modules in higher education](https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2024.1182541/full)) Thomas Westin describes this as the Game Accessibility Paradox. The author argues that games can be described by a series of strict rules for playing the game which are normative. They can't be changed without fundamentally altering the game and effectively creating a new, different, game. The player interacts with these through game mechanics which are performative. They conclude that the two main approaches for accessibility are removing barriers that aren't needed for core gameplay or creating special games that use a different modality (such as audiogames). They note that a third option is to make modifications that alter the game rules creating a new game.

These examples highlight the need to retain some inaccessible features to preserve the challenge of a game but make no recommendation of a formal process to identify which features need retaining. 

## Existing resouces 

### Accessibility Guidelines

#### Game Accessibility Guidelines
[Game Accessibility Guidelines](https://gameaccessibilityguidelines.com/)
The Game Accessibility Guidelines provide a fairly comprehensive menu of games accessibility advice organised into Basic, Intermediate and Advanced. 

#### AbleGamers Toolkit
The [Accessible Player Experiences (APX)](https://accessible.games/accessible-player-experiences/) from AbleGamers breaks game accessibility down into a set of design patterns organised about the things a developer should do to create accessibility. These are explained in terms of the accessibility use cases but are not split into groups based on the beneficiary audiences. The guidelines give named examples of the design patterns in existing games to provide illustrative use cases.    

#### RNIB Devkit
[RNIB Best Practice in Accessible Gaming 2025](https://github.com/RNIB-MediaAndCulture/Gaming_Devkit/blob/main/Devkit.md)
The accessible gaming devkit from RNIB (Royal National Institute of Blind People) contains high level advice for games developers. A unique feature is the CAPS test which states that Challenge, Agency, Participation and Story are important in gaming and these need to be preserved to ensure that game is still attractive to gamers with disabilities. Whilst it recognises the need for challenge the Devkit is focussed on accessibility for gamers with sightloss.

#### WCAG
The [Web Content Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/) are currently at version 2.2 and are already being used to assess games accessibility in the case of Section 508 in the USA.  

#### ADP from ACB
Audio Description Project (ADP) Gaming Subcommittee

ACB has produced a [Best Practices for Audio Description in Video Games](https://adp.acb.org/sites/default/files/2025-11/AD%20in%20Gaming%20Best%20Practices%20%281%29.docx) document. This focuses on audio description within a game. This is not comprehensive enough to be used as a GAUR.  

#### Xbox Accessibility Guidelines
The [Xbox Accessibility Guidelines](https://learn.microsoft.com/en-us/gaming/accessibility/guidelines) cover a wide range of disabilities and appear to be fairly comprehensive. They discuss game difficulty and recommend adjustable difficulty levels to allow players to find the level that suits them but don't address situations where the nature of the challenge creates an absolute block.  

### Applicable user requirements documents

#### ISO/IEC 29138-1:2018
ISO/IEC 29138-1:2018 sets out user needs for all audiences. (I haven't been able to access the full document, just Annex B which lists the user needs). 

#### EN 301 549
[EN 301549:2021. Accessibility requirements for ICT products and services](https://accessible-eu-centre.ec.europa.eu/content-corner/digital-library/en-3015492021-accessibility-requirements-ict-products-and-services_en) "defines the requirements that products and services based on information and communication technologies (ICT) should meet to enable their use by persons with disabilities." 

#### XAUR
The [XR Accessibility User Requirements](https://www.w3.org/TR/xaur/) describes user requirements for extended reality including virtual reality (a virtual world a user can explore), augmented reality (virtual elements overlaid on the real world), 360 content (immersive content a user can look around in while it's playing) and similar immersive virtual, or semi-virtual environments. It doesn't cover as broad a scope as gaming and doesn't contain discussion of intentional friction.

#### MAUR
The [Media Accessibility User Requirements](https://www.w3.org/TR/media-accessibility-reqs/) contain user requirements that relate to audio and visual content on the web. There will be crossover with gaming but much of the advice will be most relevent to cutscenes and games trailers. Intentional friction is not a relevent concept for the MAUR.   

#### NAUR
The [Natural Language Interface Accessibility User Requirements](https://www.w3.org/TR/naur/) describes user requirements for natural language applications. This is relevent for a small number of current games. The number of games relying on natural language interfaces may increase with more ubiquitious use of AI but is likely to remain only a subset of the games ecosystem.  Intentional friction is not a relevent concept for the NAUR. 

### Existing work within W3C
#### HTML accessible Taskforce note on gaming
[HTML accessible Taskforce note on gaming](https://www.w3.org/WAI/PF/HTML/wiki/Gaming.html)
This is a short note that says:

"Explore needs for gaming

Some work that was done external to W3C has some interesting best practices for gaming accessibility: [Game accessibility guidelines] won the intellectual and developmental disabilities category of the annual US Federal Communications Commission Chairman's Awards for Advancements in Accessibility"

The existence of the page implies that the HTML group sees the value in work on accessible gaming whilst the incompleteness or brevity of the page likely suggests that progress has been limited.

#### 2018 Workshop
In 2018 the W3C held the [W3C Workshop on Web Games Position Paper: Adaptive Accessibility](https://www.w3.org/2018/12/games-workshop/papers/web-games-adaptive-accessibility.html) to propose an Active Games Accessibility (AGA) framework which would create a bridge between games and access technology such as screenreaders, magnifiers and adaptive I/O devices. This would function similar to ARIA or MSAA on Windows. It was suggested the framework could work at three levels: built into the specific game, built into the game engine and external to both the game and the engine.

The workshop was a proposal for a solution rather than a declaration of user needs.

#### FAST
The [Framework for Accessible Specifications of Technologies](https://w3c.github.io/fast/#checklist) is ongoing work within W3C that attempts to identify user needs and the adaptations that may be needed to make those needs accessible. There is an accompanying checklist to help developers identify where their standards may fail accessibility-wise.

#### Making Content Usable for People with Cognitive and Learning Disabilities
The document [Making Content Usable for People with Cognitive and Learning Disabilities](https://www.w3.org/TR/coga-usable/#background) covers user requirements for people with cognitive and learning disabilities as well as relevent design patterns, a set of use cases and personas and advice on user testing with this audience. It covers a diverse audience but is not pan-disability. Intentional friction is not relevent to this document. 

### Digital Accessibility Framework
The [Digital Accessibility Framework](https://accessiblecommunity.org/daf) extends the idea of FAST to all digital technologies and attempts to create a comprehensive mapping of user needs to ways to address those needs through a diverse range of methods and modalities. A stated aim is to be futureproof and the framework therefore covers a far wider set of user experiences than are currently found in gaming or expected in the near future (such as smell and taste). 

The Digital Accessibility Framework is focused on user needs, it is pan disability and it is very comprehensive. Being a multi-use tool it doesn't include the requirement for challenge in gaming and it is also a very low level tool in that it looks at user experience at a very fine granularity. This makes it helpful to design and test a targeted accessibility user requirements document but it is likely too technical and too broad in scope to be usable as one.    

## Evaluation of existing resources
There is a large corpus of accessibility standards that could apply to gaming. Across the five suggested characteristics of an ideal candidate, existing resources collectively cover four reasonably well. The exception, and the clearest gap, is the treatment of intentional friction.

### Focus on the user experience
Documents such as ISO/IEC 29138-1:2018 cover the full spectrum of user needs from interfaces including the needs of people with and without disabilities. The Accessibility User Requires documents from the RQTF group (the XAUR, MAUR and NAUR) then explicitly identify user needs for disabled audiences as do Content Usable from the COGA taskforce and the AbleGamers Toolkit.

### Cover multiple disabilities
Although many of the standards do not cover the full spectrum of accessibilty, between them they leave no obvious gaps in terms of disabilities covered.

### Comprehensive
The Game Accessibility Guidelines offer a very full list of accessibility features that games could require and ISO/IEC 29138-1:2018 is comprehensive to the point that it isn't restricted to just accessibility user requirements but all user requirements. 

### Collaborative
The Game Accessibility Guidelines have been created by accessibility experts from the gaming industry and content creation within the W3C follows collaborative processes that invite comments from outside the organisation.   

### Understand intentional friction in gaming
This is the characteristic where existing resources fall furthest short, and it is the central gap this analysis identifies.

Several sources establish that intentional friction exists and matters. Hamilton frames accessibility as avoiding unnecessary mismatch between capability and barrier, implying that some mismatch is necessary. The IGDA-GASIG guidance states plainly that games need "some degree of inaccessibility" and frames accessibility work as an optimisation problem. Westin's Game Accessibility Paradox goes further, distinguishing normative game rules (which cannot change without creating a different game) from performative mechanics (which can often be adapted), and notes as an illustrative example that small text size is rarely core to a game's mechanic even where it is frequently presented as a barrier. The RNIB Devkit's CAPS test (Challenge, Agency, Participation, Story) recognises that challenge specifically must be preserved for a game to remain attractive to disabled players.

None of these, however, supplies a method for making the underlying judgement. They assert that a line exists between friction that is essential to a game's identity and friction that is merely an unaddressed barrier, but they do not describe how a developer, tester, or standards body should draw that line for a given game, mechanic, or feature. The general accessibility user requirements documents (XAUR, MAUR, NAUR, COGA) are explicit that intentional friction is not a relevant concept for their domains, so they offer no transferable methodology either. The Digital Accessibility Framework and FAST, despite their comprehensiveness, are generic across all digital technologies and have no mechanism for representing "friction that should be preserved" as distinct from "friction that should be removed."

The result is a body of work that is unanimous on the principle (some friction must stay) but silent on the process (how do you tell which friction that is, consistently and defensibly, across genres and disabilities). This is the gap a GAUR is best placed to fill, since it sits at the intersection of user-needs documentation and games-specific domain knowledge that none of the existing candidates individually possess.

## Proposal
Rather than attempting to be the most comprehensive catalogue of accessibility features, a GAUR should prioritise being the resource that closes this specific gap: a working methodology for distinguishing essential (intentional) friction from unnecessary (unintentional) friction, expressed in terms of user needs rather than developer solutions.

Such a methodology should aim to:

### Provide a decision test. 
Building on Westin's normative/performative distinction and the IGDA-GASIG optimisation framing, a GAUR should offer a repeatable question or set of questions (e.g. "Does removing this barrier fundamentally alter the challenge presented or just one possible implementation of the challenge? Is the intended friction intrinsically linked to a user ability such as sight, hearing, or memory? Does removing this barrier change what the player is being asked to do, or only how they are asked to do it?") that can be applied consistently by people who are not accessibility specialists.

### Consider variation across disability types. 
A barrier that is unnecessary friction for one impairment may be part of the intended challenge for another (e.g. a memory-based puzzle could be a valid challenge for someone with sight loss but create inaccessibility for a player with a cognitive impairment). The methodology needs to consider this per-audience distinction and how to account for it in recommendations.

### Produce a defensible, auditable output. 
For the methodology to usefully inform a formal standard, its outputs need to be consistent enough that two independent assessors would classify the same barrier the same way, and transparent enough that a developer or regulator can see why a given piece of friction was classified as essential or not.

### Be created collaboratively. 
In line with the "collaborative" characteristic, the methodology should invite input from developers, disabled players, and accessibility specialists to check that it produces sensible, workable and non-controversial results. 

Developing and validating this methodology, rather than re-deriving a full accessibility feature catalogue (which the Game Accessibility Guidelines and APX already provide), would be the highest-value contribution a GAUR could make, and the one piece of the puzzle current resources do not supply.
