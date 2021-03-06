---
layout: post
title: To Drive or Not to Drive
---

<h3><p style="text-align:center;">Using Data Analysis to Decide Whether or Not to Keep My Car Insured While at UBC Vancouver</p></h3>


My big question when moving to Vancouver for school is should I keep my car insured? It's common knowledge in BC that it's expensive to own a car in Vancouver and the alternative transportation options, such as public transit and car share, are fantastic. Plus, I have a nice commuting bike and some (limited) carpool options.

The decision sounds easy, ditch the car! But for me, it's not that simple. I'm also a competitive runner and I train with a team based out of the Langley area. This means that ~3 times per week I meet up with them to run outside Vancouver. These are longer commutes and harder to get to via transit. Now the decision takes more thought.

Let's look at the three factors most important to me:

1.  **Cost.** I am a student currently and have expenses but little to no income. I want to minimize my transportation costs.

2.  **Time.** Between school and running, I have a demanding schedule and want to minimize commute time.

3.  **Convenience.** I want to be able to go where I want, when I want, and have flexibility in my options.


Let's dive into each individually:

## Cost


**Car Cost:**

1.  Insurance - $125 (pleasure use only, maximum discounts)
2.  Gas cost - $8.25 per roundtrip
3.  Maintenance - $180/year (3 oil changes per year at $60 each)

**Transit Cost:** Due to mandatory UBC transit enrolment, I will say this fee is $0.

**Car Share Cost:** I researched Modo, Car2Go, Zipcar, and Evo, and found Modo to be the best option for me. It would cost $30-45 per round trip, so it is too expensive to use for every commute, but can use it occasionally, about 3 times per month.

**Carpool Cost:** My teammate drives to practice regardless, so I would simply pay her half the cost of gas - $4.12 per rountrip.

Graphing the overall monthly car costs and combined alternative transportation (carpool, transit, and car share) costs:

<center><img src="/images/lab4_blogpost_files/figure-markdown_github/price-1.png" alt="Price Graph" height="350"/></center>

## Time

Next we'll look at commute times for weekend morning and weekday evening practices.

*A couple things to note:*

1.  For simplicity, "Car" driving time will apply to both my own car and car share.
2.  The carpool time is based on transit time to teammate's apartment + drive time to run locations from there.
3.  There are no transit options to Surrey Bend or Derby Reach.

<center><img src="/images/lab4_blogpost_files/figure-markdown_github/time-1.png" alt="Weekend Commute Time"/><img src="/images/lab4_blogpost_files/figure-markdown_github/time-2.png" alt="Weekday Commute Time"/></center>

## Convenience

This is a subjective category, but I created a scoring system for the topics. I've scored the travel types with a +1 or -1 to depending on whether it's convenient and flexible within the specified category or not.

<center><img src="/images/lab4_blogpost_files/figure-markdown_github/conveniencetable.png" alt="Convenience Table" /></center>

Other Factors:

* +1: Transit - bus stop close to my house
* +1: Transit - less effected by rush hour than driving
* -1: Transit - unable to take to some locations
* -1: Carpool - depend on teammate's availability
* -1: Car Share - must return car to "home area"
* -1: Car Share - must specify return time in advance

**Scores:**
* Car = +3
* Alternative Transportation = -5

*As you can see, car received a positive convenience score, meaning it is an easy and flexible transportation method, whereas alternative transportation received a negative score, meaning it takes some extra planning and effort and is not as flexible.*

--------------------------------------------

## Putting it All Together

Let's look at the price, time, and convenience factors together:


<center><img src="/images/lab4_blogpost_files/figure-markdown_github/table1.png" alt="Table 1" /></center>

*Keeping my car is an additional $70 per month and has positive convenience. The bus is an additional 2 hours commuting per month and has negative convenience.*

If I turn all factors into dollars:

* Time will be valued at my past wage, $25 per hour.
* 1 convenience point = $1 per week savings ($4 per month)


The table becomes:

<center><img src="/images/lab4_blogpost_files/figure-markdown_github/table2.png" alt="Table 2"/></center>



The total is based on an "added cost" factor, so the lower the score the better. With this calculation, my car reigns supreme (barely).

*Now, let's quickly address the limitations of this analysis: I only considered using the transportation methods to get to practices, not for errands, meet ups, etc. I did not factor in any of the environmental benefits of carpooling and transit. The convenience score is arbitrary and different scoring methods could result in a different decision. ALL of my costs and times are estimates and reality may vary.*

That being said, the analysis did slightly favour me keeping my car insured this year and that is what I plan to do!

<center>
<img src="https://media.giphy.com/media/ypJDAUdeiBZDy/giphy.gif"/>
</center>
<center>
<a href="https://giphy.com/gifs/ypJDAUdeiBZDy">SOURCE</a>
</center>


----------------------------------------------------


#### References:

Google Maps data for driving/transit times:  [Surrey Bend](https://www.google.com/maps/dir/W+16th+Ave+%26+Macdonald+St,+Vancouver,+BC+V6K+3C5/Surrey+Bend+Park,+104+Avenue,+Surrey,+BC/@49.2258985,-123.2274779,10z/data=!3m1!4b1!4m14!4m13!1m5!1m1!1s0x548673a866c49329:0xaaa502444c7a42b!2m2!1d-123.1684032!2d49.2577712!1m5!1m1!1s0x5485d6cef33fbd01:0x86930b15b5c4ec4e!2m2!1d-122.7284123!2d49.1941758!3e0),  [Campbell Valley](https://www.google.com/maps/dir/W+16th+Ave+%26+Macdonald+St,+Vancouver,+BC+V6K+3C5/Campbell+Valley+Regional+Park,+16+Avenue,+Langley,+BC/@49.1437448,-123.1948014,10z/data=!3m1!4b1!4m14!4m13!1m5!1m1!1s0x548673a866c49329:0xaaa502444c7a42b!2m2!1d-123.1684032!2d49.2577712!1m5!1m1!1s0x5485c6062b7e792d:0xd51f4184d46485b6!2m2!1d-122.6608212!2d49.0303964!3e0),  [Burnaby Lake](https://www.google.com/maps/dir/W+16th+Ave+%26+Macdonald+St,+Vancouver,+BC+V6K+3C5/Burnaby+Lake,+Burnaby,+BC/@49.2555999,-123.1953396,11z/data=!3m1!4b1!4m14!4m13!1m5!1m1!1s0x548673a866c49329:0xaaa502444c7a42b!2m2!1d-123.1684032!2d49.2577712!1m5!1m1!1s0x5486779ec98481d3:0x4bb40fdefbc73000!2m2!1d-122.9441117!2d49.2420313!3e0),  [Burnaby Mountain](https://www.google.com/maps/dir/W+16th+Ave+%26+Macdonald+St,+Vancouver,+BC+V6K+3C5/Burnaby+Mountain+Park,+Burnaby+Mountain+Pkwy,+Burnaby,+BC/@49.2700849,-123.1908451,11z/data=!3m1!4b1!4m14!4m13!1m5!1m1!1s0x548673a866c49329:0xaaa502444c7a42b!2m2!1d-123.1684032!2d49.2577712!1m5!1m1!1s0x548677a6363c6f03:0x5f34938923afee19!2m2!1d-122.9331187!2d49.2826282!3e0),  [Derby Reach](https://www.google.com/maps/dir/West+16th+Avenue+%26+Macdonald+Street/Derby+Reach+Regional+Park,+21801+Allard+Crescent,+Langley,+BC+V1M+3W1/@49.2028634,-123.160848,10z/data=!3m1!4b1!4m14!4m13!1m5!1m1!1s0x548673a866c49329:0xaaa502444c7a42b!2m2!1d-123.1684032!2d49.2577712!1m5!1m1!1s0x5485d30cadb1a875:0x98951fb4642ac568!2m2!1d-122.5945669!2d49.199814!3e0)

Car Share Rates: [Evo](https://evo.ca/rates),   [Car2Go](https://www.car2go.com/CA/en/vancouver/rates/),   [Modo](https://www.modo.coop/plans/#page-submenu),   [Zipcar](https://www.zipcar.ca/learn-more/vancouver?plan_key=evp-50)

Other: [Calculate Gas Prices per Route](https://www.fueleconomy.gov/trip/),  [Transit schedules](https://www.translink.ca),  [ICBC Info](https://www.icbc.com/Pages/default.aspx)