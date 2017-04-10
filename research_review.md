#Research Review

##STRIPS
STRIPS(Fikes and Nilsson, 1971) is he first major planning system, illustrates the interaction of these influences.[1] The same name was later used to refer to the formal language of the inputs to this planner. This language is the base for most of the languages for expressing automated planning problem instances in use today; such languages are commonly known as action languages.[2] 

A STRIPS instance is composed of:

* An initial state;
* The specification of the goal states – situations which the planner is trying to reach;
* A set of actions. For each action, the following are included:
	* preconditions (what must be established before the action is performed);
	* postconditions (what is established after the action is performed).

##Partial-Order planning
Partial-order planning is an approach to automated planning that leaves decisions about the ordering of actions as open as possible. It contrasts with total-order planning, which produces an exact ordering of actions. Given a problem in which some sequence of actions is required in order to achieve a goal, a partial-order plan specifies all actions that need to be taken, but specifies an ordering of the actions only where necessary.[3] The idea underlying partial-order planning include the detection of conflicts (Tate, 1975a) and the protection of achieved conditions from interference (Sussman, 1975). The construction of partially ordered plans (then called task networks) was pioneered by the NOAH planner (Sacerdoti, 1975, 1977) and by Tate's (1975b, 1977) NONLINE system.[4]

##Binary Decision Diagram
A binary decision diagram (BDD) or branching program is a data structure that is used to represent a Boolean function. On a more abstract level, BDDs can be considered as a compressed representation of sets or relations.[5] There has been interest in the representation of plans as binary decision diagrams, compact data structures for Boolean expressions widely studied in the hardware verification community (Clarke and Grumberg, 1987; McMillan, 1993). There are techniques for
proving properties of binary decision diagrams, including the property of being a solution to a planning problem. Cimatti et al. (1998) present a planner based on this approach. Other representations have also been used; for example, Vossen et al. (2001) survey the use of integer programming for planning.[6]


##References
[1] Russell, Stuart and Norvig, Peter. Artificial Intelligence: A Modern Approach 3nd Edition, P.393.

[2] https://en.wikipedia.org/wiki/STRIPS

[3] https://en.wikipedia.org/wiki/Partial-order_planning

[4] Russell, Stuart and Norvig, Peter. Artificial Intelligence: A Modern Approach 3nd Edition, P.394.

[5] https://en.wikipedia.org/wiki/Binary_decision_diagram

[6] Russell, Stuart and Norvig, Peter. Artificial Intelligence: A Modern Approach 3nd Edition, P.395-396.