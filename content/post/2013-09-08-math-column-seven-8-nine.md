---
title: 'Math Column: Seven 8 Nine'
author: Joshua Gancher
type: post
date: 2013-09-08T20:47:49+00:00
url: /2013/09/08/math-column-seven-8-nine/
categories:
  - Features
  - Front Page
  - Math Column
tags:
  - Math Column

---
How many numbers are there?

Suppose that I am trying to figure out if I have the same amount of red and blue jellybeans. How should I go about this? I could count them: get the number of red and blue beans, and compare the two numbers. This is easy for a small amount; say, less than a hundred each. After that, counting starts to become the least efficient solution. The problem with counting is mostly that we are collecting far too much information: we care only about if one of the two subsets of beans is larger, not the actual sizes of them.

Instead, let&#8217;s do this: take each red bean, and attempt to match it with a blue bean. If we can do this for every jellybean in both sets, then the two sets have an equal amount of elements. This process is the attempt to form a **one-to-one correspondence** between the sets of red beans and blue beans.

Suppose, now, that we have a set of infinitely many jellybeans. It is impossible to count them, but _it is not impossible to still form one-to-one correspondences_. Let&#8217;s make one:

Take a jellybean, and call it jellybean 0. Take another, and call it jellybean 1. Call the next one jellybean 2, and so on forever. This is a one-to-one correspondence between the set of jellybeans and the set of non-negative whole numbers (also called the **natural numbers**). This correspondence works both ways: given any jellybean, there is only one natural number assigned to it, and given any natural number, there is only one jellybean assigned to it. Therefore, the set of jellybeans can be given a one-to-one correspondence with the natural numbers. The ability to form one-to-one correspondences with the natural numbers is important in mathematics, and is given a name: a set is **countable** if it can be set into a one-to-one correspondence with the natural numbers. (A somewhat finicky note: sets with a finite amount of elements are also sometimes called countable &#8212; finite sets cannot be put into a one-to-one correspondence with the natural numbers.)

While we cannot say exactly how many elements there are in an infinite set, we can compare the &#8216;bigness&#8217; of two sets through one-to-one correspondences. Recall that if two finite sets have a one-to-one correspondence between them, they must have an equal amount of elements. Now, we will _extend this idea to infinite sets_. The bigness of a set is also called its cardinality. Two infinite sets are said to have an equal cardinality if there exists a one-to-one correspondence between them.

What other sets are countable? That is, what other sets have the same cardinality as the natural numbers? Consider the integers: {&#8230;,-2,-1,0,1,2,&#8230;}. How big is this set? At first glance, it looks twice as big as the natural numbers, since there are two copies of the natural numbers: one running positive, one running negative. Let&#8217;s reorganize this set so we don&#8217;t have ellipses on both sides: {0,1,-1,2,-2,3,-3,&#8230;}. Can we form any one-to-one correspondence with the natural numbers and this set? Sure we can! Assign 0 to 0, 1 to 1, 2 to -1, 3 to 2, 4 to -2, and so forth. This is a one-to-one correspondence, and so the integers are seen to be just as big as the natural numbers.

It turns out showing that a set is countable is really easy: if you can unambiguously list every element, that set is countable, since its position in the list is itself a one-to-one correspondence with the naturals.

What sets aren&#8217;t countable? Equivalently, what sets cannot have their elements listed? A dude named Georg Cantor was the first to show that uncountable sets exist, with what is now called the diagonal method. Here&#8217;s what he did:

Consider the real numbers (that is, numbers with decimals that can go on forever.) Suppose that we can put all of them in a list. Then, consider the number where the first digit after the decimal is from the first number on the list, the second digit from the second, and so forth. Now, change all of the digits by one &#8211; say, if it wasn&#8217;t zero then make it zero, and if it was zero then make it one. Because every digit is different than the corresponding digit from every number on the list, the number we have made is _not on the list_. We have not actually listed every number, which is a contradiction from our original premise that we did list every number. Hence, we have proved that the real numbers cannot be listed &#8211; which means they cannot be put into a one-to-one correspondence with the natural numbers &#8211; which means that they are uncountable. This kind of proof happens a lot in math &#8212; where you first assume something and then show that there is a contradiction from that assumption. This form of proof is called a **proof by contradiction**.

Now we know that the reals are uncountable, and hence has a larger cardinality than the natural numbers!

I leave you with a challenge: First, show that the set of possible finite descriptions one can make in english (or in math symbols) is countable. Using this fact, deduce whether it is possible to unambiguously define every real number.