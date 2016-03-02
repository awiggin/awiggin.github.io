---
layout: post
title: "When to use a Hash vs. Array"
date: 2016-2-16 16:39:18
comments: true
description: "Hash vs. Array"
keywords: ""
categories:
- welcome
tags:
- welcome
---



It is important to preface these functions are collections of data and arrays are best for making raw, ordered lists while hashes are best with connecting pieces of information to each other. Arrays are like indexes and the way to reference each piece of information is by referencing the number in the array sequence. Arrays are simple given that a user knows each number of the indexed collection.

Hashes are great for categorizing information and the chipotle order is a great example. Within the chipotle order assembly, you can choose the style of food, the meat, the toppings, and even the drinks. Rather than having an array that lists everything that is in styling, meats, toppings, and drinks, we, as programmers, can provide the information categorically so that the user better understands their order. Hypothetically, a chipotle order could limit the order to one style, one meat, three toppings, and one drink. That totals to six choices. With an array, the user could put this as an order and still meet the maximum order: burrito, tacos, salad, burrito bowl, cheese, and a drink. That right there is six choices. But, it does not make a real order because there was no structure to it. Of course, this is an exaggeration. No one wants a burrito, tacos, salad, and a burrito bowl with just cheese. But, that order is still a possibility if an array is used. Hashes fix the problem with the exaggerated order; they can enforce limits. Hashes can enforce the one style, one meat, three topping, one drink limit because the order becomes categorical.

Arrays and hashes are both functional organization tools for a program. Though hashes are specific and can enforce limits, arrays are useful when working with speed. If chipotle created a dozen fixed orders that could not be changed, a hash would be unneeded. The most important distinction a programmer has to make is when information is categorical. If it is not, then a programmer should use an array. If it is categorical, hashes will better structure the information. The programmer must make sure to be aware of their intent and if they are, both arrays and hashes will serve them well.

https://www.codecademy.com/forum_questions/52a69117282ae3085d000d63

http://www.linuxtopia.org/online_books/programming_books/ruby_tutorial/Ruby.new_Arrays_and_Hashes.html

https://teamtreehouse.com/community/when-do-you-use-an-array-versus-a-hash-in-ruby

