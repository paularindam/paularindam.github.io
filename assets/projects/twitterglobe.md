---
layout: default
title: Arindam Paul
---

<div class="post">
	<h1 class="pageTitle">Mining Golden Globe Tweets</h1>
<p align="center">	<img src="{{ '/assets/img/goldenglobe.png' | prepend: site.baseurl }}" alt="" height="155" width="115"></p>

	<!-- <p>Large, deep convolutional neural networks (based on both a self-developed library on theano
	and torch7) are trained to classify ~1 million real-life images from Pinterest, into 1300+
	different classes. Architectures including AlexNet, VGG, GoogLeNet are experimented. We
	employ frequent itemset mining to group labels into superclasses, and embed this information
	into the loss function to improve accuracy.</p> -->
	<p>Users tweet a great deal during award ceremonies. They tweet about who won the awards. They tweet about who should have won instead. Also, they tweet about their own categories: who looked most beautiful/handsome, who was the best dressed etc.</p>

<p>	We built a semantic processing system which looks at all tweets during +/-2 hrs of the Golden Globe awards which use the official hashtag #GoldenGlobe2014. In the first phase, we evaluated who won the awards <i>based on the tweets</i>. This was a trickier problem than it seems at first glance. This is because twitter users often tweet. </p>
<p align="center"><img src="{{ '/assets/img/twitter.jpg' | prepend: site.baseurl }}" alt="" height="280" width="280"></p>

<p>In the second phase, we extended our system to look for tweets which did not use the official hashtag. Many users are not aware of the official hashtag and some make typos. We used regular expressions to look for hashtags after manually checking

<p>In the last phase, we used our system to look for winners in <i>user categories</i> e.g. best dressed. Of course, there is no absolute truth values for these categories other than what some news outlets have

</div>
