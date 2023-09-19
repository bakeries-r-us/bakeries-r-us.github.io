---
layout: post
title: Bakery Supply Chains
---

I want to make a game that lets you explore a supply chain. When I asked my daughter what type of supply chain game I should make, she said one with bakeries, so she could learn more about bakeries. I thought that was a good idea. Everyone has a pretty good concept of what bread is. Supply chains can be a little hazier for some, so I thought it'd be fun to create a game that uses the supply chain of something very familiar, like bread to teach about the complexity of the supply chain.

Since the way the entities interact with each other in a supply chain is complex, I want to make the interface of the game as simple as possible. The goal will be to run control the entire supply chain for a bakery from the wheat to the loaves.

Below is the simplest supply chain I could think of:

```
Wheat ---> Flour ---+
                    |
           Yeast ---+
                    |
           Salt  ---+
                    |
           Water ---+---> Bread ---+
                                   +---> Store shelves
               Paper Bread Bags ---+
```

