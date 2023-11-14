# Reputation Systems

#### Track karma stats, earn reputation points in communities, and weight the ranking of wall results

<img src="/images/rep-systems.jpg" style="width: 150px">

One of the challenges of designing a scalable democratic decision making system is working out how to engage as many participants as possible without each decision simply becoming an average of the entire populations vote. In many cases you want the most skilled minds and ideas sifted to the surface to tackle the challenges they are most adapted for in service to the collective, in a more dynamic and flexible fashion.

This problem also applies to the social news domain. Every community has a spectrum of users; on the one end being authentic and experienced users who contribute high quality content relevant to the community and on the other end being fake accounts or those who would seek to damage the community for their own interests. The current 'one user, one vote' system used on Reddit and most other social media platforms treats the votes of every account equally, which has a number of important advantages. It works well to distribute decision making power and protects the system from bias, but it can also, at times, squash out some of the best talent and leave communities open to manipulation from [Sybil attacks](https://en.wikipedia.org/wiki/Sybil_attack) where fake accounts with no prior history are used to sway group results.

<img src="/images/hands.jpg" style="width: 300px">

In society, the process of deciding how to distribute different amounts of power to different individuals has traditionally been achieved through the gradual filtering of social reputation, passing examinations, a portfolio of prior work experience, and finance. In order to reach a position of power in a large company or branch of government, for example, an individual will have to pass through a range of checks and balances over time that demonstrate they have a high level of competence in that field. These mechanisms can't easily be translated into online social networks like Reddit or Facebook, though, so there is yet to emerge an effective equivalent means of tracking and applying reputation in general online communities.

<img src="/images/hand.jpg" style="width: 300px">

The feature we are considering here is one approach to solving part of this problem. By keeping track of the location of every up and down vote in the system and storing this data in an efficiently organised index, it would be possible to provide detailed karma stats to users and communities. It would also then be possible to use those stats to integrate a new reputation system as an optional overlay on top of the current design. 

Users would be able to see a breakdown on their profiles of where their karma points had come from: 

<img src="/images/karma-breakdown.jpg" style="width: 800px">

It would be possible to calculate a leader board of the top voted commenters and posters in each community:

<img src="/images/leaderboard.jpg" style="width: 800px">

These branch points could then be used to work out reputation scores for participating users in each community. A user's reputation score would be based on the percentage of up votes they had gained within the community versus the total up votes received within that community to date.

*(100 / Total Branch Points) x Users Points Gained in Branch = Users Reputation Score in Branch*

These reputation scores could then further be used to generate an alternative ranking mode that users could toggle On or Off on the wall. When switched On, it would weigh every up-vote made in the community in proportion to that voters reputation score. If you had a reputation score of 50, for example, every up vote you made would be multiplied by 50, giving you 5x the voting power of another user with a reputation score of 10, and 500x the voting power of a user with a reputation score of 0.1. New users to the branch would initially have no voting power in this mode until they had received at least 1 up vote from another user on something they had posted to the branch or one of its child branches.

Because the reputation system could be toggled on or off and wouldn't affect the underlying up/down vote mechanism, users or communities who didn't like this feature wouldn't need to use it. Reputation scores would also be recorded separately for every branch so no one could use this system to take control of uninterested communities.

As well as providing an effective mechanism for measuring users reputations and rewarding influence to the top contributors in each community, this design would also help to protect communities from Sybil attacks where fake accounts with little or no prior history are used to influence voting results.

Another interesting possibility is that users could apply reputation scores from different, even seemingly unrelated, branches to the wall they are browsing. A user browsing the wall of a Politics branch, for example, might choose to weight the ranking of posts on the wall by users reputation scores in the Science branch, or any other community whose reputation they trusted or were interested in. This would greatly expand user's ability to customise the way the content they are browsing is sifted and would no doubt reveal many interesting insights into different user demographics.