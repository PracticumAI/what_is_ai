Practicum program overview notes.

***

#### Videos
[PAI : Program Overview](https://mediasite.video.ufl.edu/Mediasite/Play/0373a4c5094d48b5afd62e23128411521d)

***
#### Applied AI Use-Cases

1. *Artificial Intelligence with Python* -- chapter 2 (Fundamental Use Cases for Artificial Intelligence)
2. *Artificial Intelligence Basics: A Non-Technical Introduction* by Tom Taulli

***
#### Notes
Dear friends,
 
How much math do you need to know to be a machine learning engineer? It’s always nice to know more math! But there’s so much to learn that, realistically, it’s necessary to prioritize. Here are some thoughts about how you might go about strengthening your math background.

To figure out what’s important to know, I find it useful to ask what you need to know to make the decisions required for the work you want to do. At DeepLearning.AI, we frequently ask, “What does someone need to know to accomplish their goals?” The goal might be building a machine learning model, architecting a system, or passing a job interview.

Understanding the math behind algorithms you use is often helpful, since it enables you to debug them. But the depth of knowledge that’s useful changes over time. As machine learning techniques mature and become more reliable and turnkey, they require less debugging, and a shallower understanding of the math involved may be sufficient to make them work. 
 
For instance, in an earlier era of machine learning, linear algebra libraries for solving linear systems of equations (for linear regression) were immature. I had to understand how these libraries worked so I could choose among different libraries and avoid numerical roundoff pitfalls. But this became less important as numerical linear algebra libraries matured. 
 
Deep learning is still an emerging technology, so when you train a neural network and the optimization algorithm struggles to converge, understanding the math behind gradient descent, momentum, and the Adam optimization algorithm will help you make better decisions. Similarly, if your neural network does something funny — say, it makes bad predictions on images of a certain resolution, but not others — understanding the math behind neural network architectures puts you in a better position to figure out what to do.

Sometimes, we’re told that an idea is “foundational.” While there’s a lot to be said for understanding foundations, often this designation is arbitrary and thus not very useful for prioritizing what to study next. For example, computing happens on processors that are packed with transistors. Do you need a deep understanding of how transistors work to write software? It's hard to imagine an AI application where a detailed knowledge of the physics of transistors would affect your decisions.

Andrew Ng