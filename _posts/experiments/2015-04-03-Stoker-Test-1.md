---
layout: page
title: "Stoker Test 1"
subheadline: "An Experiment"
meta_teaser: "Let us see just how lazy the Stoker Power Draft System will let us be."
teaser: "Let us see just how lazy the Stoker Power Draft System will let us be."
author: tim
categories:
  - experiments
---


* TOC
{:toc}

## Introduction

So I've had a Stoker Power Draft System for about 5 days now, used it for one cook session where I did some Rack of Lamb and Chickens, but today our goal is not to cook, it is to experiment.

## Hypothesis

Given that the Stoker controls "all" of the Oxygen getting into the firebox, I should be able to load up a **bunch** of logs, set a temperature, and then not have to touch it for **hours**.

## Setup

We ran this experiment starting at the wee hours of Friday April 3rd, 2015.  The fire was lit just before 5:00 AM, it was built as follows:

* One [Weber Chimney][weber-chimney] full of [Kingsford Original Charcoal Briquets][charcoal]
	* Started using [Weber FireStarters Lighter Cubes][starter-cubes]
* Seven Logs of seasoned Post Oak from my log pile.

### Firebox Arrangement

In the firebox, from bottom to top, we had the following:

* Fire Grate, providing about 1 in of airflow underneath the stack.
* The lit charcoal, piled slightly to the center
* Two logs running east-west
* Two logs running north south
* Two logs running east-west
* One log placed down the "chimney" created by the other logs.

### Stoker Configuration

We are running the [Stoker II Power Draft System][stoker] setup as so:

* Running software version 11.0.1.11
* 10 cubic feet per minute blower coupled over and completely covering the air vents into the firebox.
* 1 pit probe, set in the middle of my cookbox, set for a desired temperature of 250°F.
* Monitored using the [StokerLog] application
  * Configured a fire alarm range of 0 degrees (I knew we were starting cold), to 290 degrees (because that would be **way** over temp and not good)

### Weather

According to my weather application, we are running approximately 65°F outside as we start the fire with 16mph

### Chimney

As will become relevant later, we started with a 100% open chimney on the smoker.

## Results

### Morning Prayer

The fire was lit, and I was ready to take an hour on this Good Friday to pray.  I had signed up for 1 hour of prayer as part of my church doing 24 hours of prayer, so 5-6am needed to be focused on other things.  And it mostly was.

### The Initial Climb

We had the fire lit and started monitoring the temperature in the cookbox start at 4:54am.  As you can see from the images below, we made rapid progress getting up to 250°F, reach it for the first time right around 5:13am.

### Leveling Out, Or So I Thought

I was completely unaware of what the temps in the cookbox were, as I was still praying, but as it turns out, things were not going so well.  At 5:21am the fan fired for one last time, but the temp did not stop rising.  So at approximately 5:45am, the fire alarm I had set for 290°F went off, interrupting my prayer, and I realized that something needed to be done.  

I cut back the chimney to be 50% covered and by 6:00am it had dropped back to 260°F, but seemed to be levelling there, so I covered the chimney to 75% covered. At 75% covered I quickly realized that the slope of my line was falling way to fast, so at 6:05am I restored the 50% chimney setting. The temp dropped as low as 241°F recovering from my adjustments, but made it back to 250°F by 6:11am.  And now we were locked in.

### Truly Leveled Out

From 6:11am onward, running a 50% covered chimney, we were completely locked in.  Temperature variations were now all in the +/- 5°F range of 250°F.  That is fantastic, it is the [Stoker] doing the job it was intended to do, so now the question is how long can it keep that up?

Ideally we'd like to see it slowly burn down all those logs to nothing but ash, while holding the temperature perfectly solid the entire time.  This ignores some significant factors though.  As those logs burn down, producing more and more ash, they will begin to obstruct the airflow under the fire.  Eventually the ash will exceed the approximately 1 inch of lift our fire rack has, and that will in turn affect how well the fire can burn.  So I would expect to see eventually that the fan will be running nearly constantly, and we'll fall below 240°F despite this.  When that happens, we will need to open the firebox and help it out.  How long did it take to reach this point?

At 9:11am we finally fell below 240°F, so we opened the firebox to take a look.

<iframe width="1280" height="750" src="https://www.youtube.com/embed/wqGOrUvlqaE" frameborder="0" allowfullscreen></iframe>

As you can see in the video, in my rush to setup this morning I had some logs leaning on the edge of the opening to the cookbox, this meant that as the logs below them were consumed, the did not properly fall and get consumed themselves.  So I've rearranged those logs and we'll see how long we can maintain temperature again with those.

## The Results

From first hit at 250°F to our first fall below 240°F, we ran a total of nearly 4 full hours (3 hours 58 minutes to be exact).  If we count only the time that the Stoker was in complete control of the temperature, we still have 3 hours exactly (6:11am to 9:11am).  That is a very good run of not having to worry about a smoker.  You can get a lot of other things done in that time, like leveling up your Destiny characters, or playing Borderlands with your friends.  Or maybe just writing up the notes from your experiment.

## The Graph

<img src="{{ site.urlimg }}stoker-test-1.png" />

{% include markdown-links.md %}
