# Holonics

<img src='https://miro.medium.com/max/720/1*dJltVFtaVwh4CIPBXNOV1A.jpeg' width='400px'>

> _A holon (Greek: holos, 'whole' and -on, 'part') is something that is simultaneously a whole in and of itself, as well as a part of a larger whole. In other words, holons can be understood as the constituent part–wholes of a hierarchy. The holon represents a way to overcome the dichotomy between parts and wholes, as well as a way to account for both the self-assertive and the integrative tendencies of organisms.The term was coined by Arthur Koestler in The Ghost in the Machine (1967). In Koestler's formulations, a holon is something that has integrity and identity while simultaneously being a part of a larger system; it is a subsystem of a greater system._

One of the core unique features of weco is its holonic organisational structure.

[summary video]

#### The Problem

<!-- <img src='images/deep-nesting.jpg' width='600px'> -->

Up until now, social containers like _groups_, _communities_, or _subreddits_ on all the largest social networks have existed as fundamentally seperate locations on a single hierarchical level.

You can create as many of these containers as you like (horizontally) but it’s not possible to nest containers within each other (vertically).

It's a bit like a folder structure on a computer where you're free to create new folders and add content to them but, for reasons we'll get into, it’s not possible to add sub-folders.

In some cases, a predefined set of sub-containers like _Events_ or _Rooms_ on Facebook groups are included, or content can be subdivided by group hashtags as seen with Reddit's _flairs_, but custom multi-level nesting of containers hasn't been an option.

Depending on the size and purpose of the community, these predefined sub-containers and group hashtags may be adequete to meet organisational needs up to a point. But as communities grow in scale and complexity, or if they simply require a higher level of organisation, the restrictions inherant in this framework can force unnecissary fragmentation and significantly limit group capacity.

To better understand the problem: imagine an example community that starts off with 10 individuals, each of whom posts one new item and views 10 other items a day.

Initially, everyone's able to see and respond to all the content flowing through that container. If different subjects come up that are more or less intersting to each individual, it's not an issue because they're all seeing everything and can choose to pay attention to the content that interests them.

But as the number of particpants grows the dynamic begins to shift. Once there are 100 individuals who all post and view content at that same rate, now each person is only able to see 10% of the content flowing through the community and, likewise, only 10% of the community will see their posts each day, and the larger the community grows the greater that gap of perception gets.

Ranking content by how many likes or up-votes it's recieved helps to some degree to sift out content that is more relevant to the community generally but it doesn't help if what you're interested in doesn't match the majoirty opinion, and still suffers from the issue that voters are only seeing a fraction of the available content of interest to them so a lot of content is likely to slip through without gaining relevant views.

To find what you're looking for, you now either have to browse a lot more content, or use search queries and hashtags to reduce the scope of content you're seeing, both of which come with their own limitations: To search by text you already need to know fairly specifically what you're looking for (i.e direct quotes included in the content) so exploration by onotlogical categories is not possible. And while hashtags enable basic onotological categorisation of content, it only goes one level deep (you can't have a hashtag that contains other hashtags) so seperate but related groupings of content remain fragmented and must each be searched individually.

The result in most cases is that people just get used to seeing whatever is judged most popular by majority opinion or create splinter groups to discuss their more specific interests.

#### The Solution

To address these and other related issues weco has been designed from the ground up to enable unlimited nesting of social containers (a.k.a 'spaces').

<img src='images/holonic-transition.gif' width='600px'>

This means it's possible to create an umbrella space for a large topic like Science which contains sub-spaces within it for Biology, Chemisty, and Physics, each of which can themselves contain as many further sub-space as they like, and so on, as deep as is useful to the community at large.

<img src='images/science-holarchy-collapsed.jpg' width='700px'>

Similarly, a space could be created for a city like Bristol, which containes sub-spaces for local neighborhoods, or general interests within the city like 'Bristol Food', 'Bristol Artists' etc. or any other form of organisation.

<img src='images/bristol-holarchy-expanded.jpg' width='700px'>

Every space in these resulting holarchies is a unique location with its own URL, moderators, and rules but remains integrated in its larger context, inheriting relevant constraints from its parents and flowing content back up to them.

---

#### Multi-level Aggregation

Posts shared to public spaces within this framework are aggregated by default in each of the parent spaces above them in the holarchy.

In the following tree structure: A > B > C, posts to 'A' will only show up there as it has no parents above it. Posts to 'B' will appear in both 'A' and 'B', and post to 'C' will appear in all three.

This means that a parent space like Bristol at the top, for example, integrates content not only shared directly there but to each of its contained child spaces at every level below in one location.

If you want to see the latest content from all Bristol related spaces, there's no need to jump around through different splinter groups as you can see it all aggregated in one location. But if you want to narrow the scope of your focus, you can just as easily navigate down the holarchy to whichever space you're most interested in.

In this way you get the best of both worlds: the ability to differentiate content into intuitive ontological categories while still retaining a higher level of integration.

Note: We've included the option to toggle the depth of content included on each spaces feed in the filter settings so it's still possible to only view content directly posted to that space if desired. As such, no prior functionality is lost, you just have the addtional option to integrated related subjects into a single feed as well.

#### Multi-locality

Within this framework both posts and spaces can exist in multiple locations simultaneously.

Posts can be tagged with as many spaces as desired when created or reposted to new spaces after creation, causing them to show up in each location at the same time without the need for duplicates. Each instance of the post simply points back to the same entry in the database, helping to reduce unnecissary clutter wihtin the overall holarchy.

[image]

Spaces can also have multiple parents, allowing them to exist in many different locations at once.

One example in the current holarchy is the Biochemistry space which exists in both Biology and Chemistry, feeding its content into both.

[image]

#### Moderation

The creator of each space becomes its default moderator with the power to:

- Update the spaces settings (handle, name, description, flag image, and cover image)
- Invite or remove other mods
- Attach their own child spaces
- Accept or reject child space requests from other user
- Remove child spaces
- Attach their own parent spaces
- Send parent space requests to spaces created by other users (requires permission from their mods)
- Remove parent spaces

The provides a lot of flexibility within the design, granting creators of spaces the freedom to reorganise and relocate their holarchies as desired while retaining appropriate control over the content they have created.

Space permissions.... privacy...

[image]

In the future we plan to add the following additional governance features:

- The ability for mods to easily remove unwanted posts in their spaces
- The ability for users to flag posts with different labels (spam, NSFW, irrelevant etc.) to help mods manage their spaces content
- The ability for users of a space to self moderate content without the need for mods by setting thresholds for removal of content linked to the number of flags posts have recieved
- The ability to directly link governance decisions and space settings to democratic polls and other decision making tools on the platform
- The ability to define a range of different user roles within a space linked to unique permission sets

#### Competition and Natural Selection

As the number of spaces within a holarchy grows,

When visualising holarchies for users to explore,

In order to prevent stagnation within ontolgoies or blockages due to bad moderation, decentralised competition and natural selection dynamics are also harnessed within the design to help regulate the visibility of spaces at every level, allowing the whole framework to fluidly evolve and adapt over time to better meet changing users needs.

Child spaces at each level can be sorted by a variety of metrics (currently: date created, total posts, total followers, total reactions, total likes, total comments, and total ratings).

[gif image]

Because there's a limit to how many spaces it makes sence to display at once in

Rival spaces can thus co-exist and compete for real-estate within a holarchy. Whichever space attracts more activity will show up earlier in the listings and thus gain more views. Unsued or inactive spaces, in contrast, sink down the listings reducing their exposure.

Because

---

Below are a series of digrams illustrating the evolution of social news leading up to weco's holonic organisational framework from a cybernetic perspective.

Each social container could be seen as a kind of social cell/vessel, with inputs (content sharing), processing (interactions), and outputs (ranked/filtered content).

---

#### Advantages

The main adanatges of this holonic architecture are:
advantages:
explorers:

- easier to explore/find relevant content
- more control over scope of focus

  creators:

- more likely to get relevant views
- better exposure gradient

#### Technical implementation

Avoiding recursive queries (probably why this hasn't been done before...)

SpaceParents and SpaceAncestors
