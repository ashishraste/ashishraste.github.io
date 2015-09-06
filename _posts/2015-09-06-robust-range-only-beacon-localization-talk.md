---
layout: post
permalink: /posts/robl-talk
sitemap: true
---
At the recent <a href="http://paperswelove.org/chapter/singapore/" target="_blank">Papers We Love SG Chapter</a>
meetup, which is held monthly here in Singapore, we had a nice discussion on robot localization
techniques for underwater vehicles as written by the authors of <a href="https://people.csail.mit.edu/teller/pubs/robl.pdf" target="_blank">
this paper</a>.

<!--more-->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dXjBX75JQg8" frameborder="0"></iframe>
Firstly I will jot down the feedback that I gathered from my friends and myself after presenting the paper.

1. At least three days must be kept aside for preparing the slides after and they must be 
rehearsed at least three times.
2. For any talk involving robots it shall be taken care, wherever possible, to explain the concepts
and implementations through appropriate simulations and/or real-robot demos.
3. On foreseeing few technical jargons that are going to be introduced in the presentation, it is better 
to add some relevant humor before or after discussing them which usually helps the audience to grasp them quickly. 
4. Finally, one shall never present anything with an empty stomach.

Things that I liked about this paper are:

1. The approach taken by the authors to eliminate noisy range measurements and how they reduced it to 
an eigenvector problem.
2. A nice linear flow in explaining how the beacons are localized, and how their range measurements
are later used to navigate around the beacon-field taking a simple EKF SLAM approach.

The work discussed in this paper will be great to experiment upon to see how well it performs
in presence of noise and other uncertainties.

---
