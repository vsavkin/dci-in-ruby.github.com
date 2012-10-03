---
layout: page
title: "Overview"
description: ""
group: navigation
weight: 2
---
{% include JB/setup %}

Here, I'm going to describe the core functionality of the application.


<h2>Creating New Auction</h2>

<p class="block">
A signed in user can create a new auction by filling in all the required fields. Basic validations (e.g. the end date is in the future, or the buy it now price is a number) are ran when a new auction is being created:
</p>

![Creating a new auction](assets/images/Screenshot_1.png)

<p class="block">
Every user can view the list of all auctions, as well as view detailed information about each individual auction.
</p>

![All auction](assets/images/Screenshot_2.png)


<h2 class="block">Bidding</h2>

<p class="block">
After an auction has been created, other users can bid on it.
</p>

![Making a bid](assets/images/Screenshot_3.png)


<p class="block">
A flash messages pops up after a bid has been accepted.
</p>

![Bid is accecpted](assets/images/Screenshot_4.png)


<p class="block">
Other users don't know who made the bid, they can only see the highest bid's value.
</p>

![Another bid](assets/images/Screenshot_5.png)

<p class="block">
Another bid is accepted.
</p>

![Bid is accepcted](assets/images/Screenshot_6.png)

<p class="block">
While bidders see only the highest bid's value, the seller has access to more detailed information.
</p>

![All bids](assets/images/Screenshot_7.png)


<p class="block">
Besides ensuring that the bid is present and is a number, the application verifies that:

<li>You don't bid against yourself.</li>
<li>The auction is active.</li>
<li>The bid is greater than the last bid.</li>
<li>The bid is smaller than or equal to the Buy It Now price of the auction.</li>
</p>

![Validations](assets/images/Screenshot_8.png)

<p class="block">
An auction gets stopped and its item gets purchased if a user pays the Buy It Now price of the auction.
</p>

![Buying](assets/images/Screenshot_9.png)
