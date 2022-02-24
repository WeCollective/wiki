# Decision Trees

#### A new tool for collective decision making

<img src="/images/decision-tree-icon.jpg" style="width: 150px">

The polling tools already built into Weco have been designed to help communities make decisions as a group but each decision is still, in a sense, isolated by its poll. The current design doesn't yet make it easy for strings of multiple decisions to be weighed up against each other and then decided on collectively by a community. This becomes particularly relevant when tackling complex multifaceted tasks that involve many related decisions, such as organising a public event or designing a new product. After considering a number of ways in which this might be achieved we eventually came to a new design that we’ve since been calling ‘Decision Trees’.

<img src="/images/decision-tree.jpg" style="width: 200px">

A new decision tree would be initiated when a user creates the first ‘node’, which could be submitted as a new post to any branch on the site. This could be the proposal to accomplish a complex task such as ‘Let’s start a Science festival in Bristol’ or a complex question with many related sub-questions like ‘What would be the best approach to terraforming Mars?’.
Once the initial node has been created and posted, other users could then up or down vote the starting node to indicate their interest in the proposal/question or attach their own new nodes that branch off from the first one. Using the example of starting a Science festival in Bristol, some of the first attached child nodes might be along the lines of ‘What would be the best location?’, ‘Should it involve live music?’, ‘Who would be the best speakers to invite?’ etc.

To make this easy to visualize we’ve decided to order the nodes by popularity in clockwise order around the starting node. The first and most popular child-node would be positioned directly above the starting node and then they would decrease in size proportional to the amount of points they have received as you follow them clockwise to the right. Users browsing the emerging decision tree could up-vote each node once. The positioning of nodes would be constantly updating, just like the wall of a social news community, such that smaller child nodes can move up the list and larger ones can sink in response to user’s live votes, allowing the decision tree to quickly adapt and change shape.

This same process of attaching and voting on child-nodes would then also be allowed on all of those nodes and so on as far as is useful to users, allowing decision ‘trees’ to grow out to any scale; each node shaped proportionally by the votes of participating users. To keep the visual illustration from overlapping, after the initial starting node, all attached child nodes would be limited to a rotation of 180 degrees around their parent node and would alternate sides with each additional layer.

In the diagram above we’ve overlaid red arrows to indicate the direction of the top four decision pathways. Users could therefore arrive at a decision tree of any scale and quickly find the most popular pathways. They could then also easily zoom in to browse all the potential deviations from those routes and visually gauge their relevance by size.

To prevent a decision tree from becoming too cluttered it’s also possible that when a high enough ratio of the users who initially up-voted the first node also then up-vote every node in a chain i.e:

**Topic** --> **Question** --> **Choice** --> **Specification**

it could be banked as a confirmed decision path and hidden from the live tree.
This same dynamic could be used for a wide range of purposes including mapping out and gauging support behind various competing scientific theories or belief systems and weighing up complex political decisions. Because the nodes could scale proportionally to any size, the design could be used by an unlimited number of participants making it useful to communities of all sizes.
