# Personal opinion on:

### Knijnenburg, B., Bostandjiev, S., O'Donovan, J., and Kobsa, A. (2012). Inspectability and control in social recommenders. RecSys'12 - Proceedings of the 6th ACM Conference on Recommender Systems.

In this paper, the authors present an experiment into how control and inspectability affect the perceived effect of the users of the system. They begin discussing the related work, where they quote several other studies performed that show how the likes of inspectability and control have possitive effects on the users. Then they dive into social recommender systems, which differ from collaborative algorithms in that they only consider the user's friends as neighbors when analyzing their likings and searching for recommendations.

The experiment performed is based on a music recommendation system, that uses Facebook friends. 267 users participated, with a demographic similar to the demography of Facebook users. The recommender system utilized is TasteWeights, which allows it's users to explore their connections, and to adjust the control over the system, being able to change weights for their different likings and friends. To further inspect the controls, they employed three control groups, one with "no control", one with "item control" and one with "friends control".

To analyze the results, two questionnaires were used. One before they used the system, and one after. Based on this results, a figure is included where they make relations between the different factors considered in the questionnaires. They also explain some of what they found from the results, based on this figure. As it can be read from the paper, the authors consider the results to be positive, pointing towards the fact that users actually want more control over their recommendations (unless they are inexpert users), and that inspectability has a positive effect as well.

While checking the Figure 3, with the results, I can see some relations that point to fallacies in the expressed results. The main one is: we can see that _Control_ has a positive relation with _undestandability_. This means that, when users have control over the system, they understand it better. Then, _understandability_ has a positive relation with _perceived control_, which makes sense based on the previous relation. But, we can see that _number of known recommendations_ has a positive relation with _perceived control_ too. Here is the problem I find with this: users feel more in control, they understand better the system, and that makes them have a better sense of control. But, they sense of control is also correlated to the number of knows recommendations they got. So, in conclusion, the users are feeling in control, and feeling like they understand the system, when they are getting recommendations they already know.

Now, what is the problem with that? Well, the point of a recommender system is to find new items, but this results display that this _positive_ things about the systems, only mean that the users are finding things they already know and like. So, yes, the perception of the user is better this way, but then again, this doesn't mean the system is better. In my opinion, this just means that the users were not understanding the goal of the system, and were just answering the questions they got thrown at.
