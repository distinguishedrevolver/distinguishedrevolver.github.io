---
layout: post
title: "The Killer Bee Project: Dry Run"
date: 2025-07-25
tags: [killer-bee-project]
chronology_order: 2
---
![Expanding Confidence Ellipses by Group](/assets/kbeesscatter.gif)

No matter how a project starts, one can expect there to be some number of remaining open questions and conflicting conclusions as you cross the finish line. No one, outside of mathematics, gets certainty in knowledge, so do not expect such here. The best that can be done in this case, for this particular kind of knowledge, is careful running of an experiment multiple times; refining techniques, and iterating as needed.

<!--more-->

<h3>The Problem Set</h3>

If you have to start somewhere, and you do, you'd be hard pressed to do better than a couple of dry runs. They help guide future plans and tests, which seemed wise, if only to help learn how to conserve either time, or ammunition, for future testing. While not completely equipped for this experiment, the opportunity to start collecting data presented itself in early summer, so I got to work.

There are multiple challenges in attempting to get all three cases up to the test velocity. So, let's dive in:

1. The powder selected, Winchester 231 (W231), has been around many decades now. It meters well and works in a wide variety of cartridges. Its wide spectrum of utility is the reason for its selection- W231 works in 38SC, 38LC, and 38SPL. It is a bulky powder. However, like many ball powders, it is difficult to ignite and can be position sensitive when case fill is reduced. The primers used, Winchester Small Pistol (WSP), are designed to work with this powder, which hopefully will mitigate this issue.

2. Selecting a single bullet with published data for all three cases was impossible- there wasn't the needed bullet weight overlap by cartridge that would return results to help start the process of determining initial powder charges for all three.

3. What velocity data I had already collected for both 38SPL and 38SC using one of the test bullets (CBS100SWC) was shot from a revolver, which meant my test through a 1911 pattern barrel would no doubt return different velocity numbers due to the velocity loss from traversing the barrel/cylinder gap. This also means that much of the velocity data that is available and tested with a vented barrel would also certainly be different.

4. And then, the question of what test velocity should be initially selected for all three cartridges, other than simply "slower, you know, target speed," would be a good starting point?

5. Last, there is the question of hypothesis. Here's mine: there is no statistical difference in group size between cases of various and significant length. While some, like Brian Pearce in <i>Handloader</i> No. 357 (August 2025) would clearly take the opposite view, as he says,
>"My testing has included using the same bullet in special and magnum cases, with the same >powder, but the charge adjusted so that bullets exist the muzzle at more or less the same >velocity.
>
>Space will not allow a great amount of detail, but in essence, the bullet jump from the >case to the rifling is increased when fired from special cases, ***which has proven many >times to decrease accuracy."*** (emphasis mine)

Or, if that didn't describe it, how about this very clear expression of the
[contraposition](https://www.bullseyeforum.net/t5689-talk-to-me-about-case-length) to mine:

![Jerry Keefer on Headspace](/assets/jerryheadspace.png)

The work is cut out for me.

But, then, what reward exists beyond the work itself?

<h3>Load Development</h3>

The trick, it seemed to me, was using the high end of the shorter case(s) velocity as the top end of a speed bracket, while using the lower end of the largest case velocity as the bottom end of the same bracket. If this approach wouldn't work, it is hard to see what kind would.

Using current published data from [Hodgdon](https://hodgdonreloading.com/), the top end of velocity would be approximately 770FPS for a 135 GR LRN from the 38SC. The 38LC is similar, with an upper end cut off at 760 FPS for a 125 GR LRN. That left the 38SPL, and the outlook was not good. The lightest charge for a 125 GR LRN returned 870 FPS, which was basically 100+ FPS too many. And this is for the much more established 125GR LRN than the 100GR SWC.

As an aside, interestingly, when asking Hodgdon about the particular brand of cast bullet they used for both the 38SC and 38LC reloading data, they were unable to give me one; the data had been collected long ago (the CUP figures are a clue to that) and from before at least one ballistic lab move.

There are no listed 100GR loads for either the 38SC (however, there is 93GR load data) or 38LC. The listed 100GR load for 38SPL doesn't have W231 as an option to select, and if you did choose one from the available powder options, they are all going much faster than needed.

Many variables in play. But as a dry run, it seemed best to start using the load data I had already captured since it was on hand and was within the velocity bracket mentioned above, so that's what I did. (Velocity data will be discussed in a future post.)

<h3>Test Setup</h3>

The barrel test fixture was setup and chronograph mounted for velocity measurements.

Fifty each 38SPL (4.0), 38LC (3.1), and 38SC (2.5) cartridges were loaded using W231, WSP, CBS100SWC, and Starline Brass. Crimp (~.376-7") was the same for each and seating depth in all cases was set to approximately .020" SWC shoulder above the case mouth. This exercise also gave me the opportunity to collect powder weight data. I like my UniqueTek [micometer powder bar](https://uniquetek.com/shop/ols/products/micrometer-powder-bar-kit), and getting data for it helps me save time when I want to move from one load to another.

As I am waiting on my [KKM barrel](https://kkmprecision.com/) to be chambered for 38SPC, I used a barrel that is a bit of a mystery- no makers mark. It was picked it up specifically to use it for testing; no idea about the twist rate. I call it the "Mystery Bull Barrel," and I'm indebted to the kind fellow who let me have it for the cost of shipping.

The barrel securing bracket & bolts were torqued to 120 inch pounds, and checked going from case length to case length samples. There were no apparent torque changes between cartridges. After a run of ~50 rounds (SPL->LC->SC), I scrubbed the barrel 10 times back and forth with a copper brush and CLP, then dry patched twice before moving on to the next lot for testing. Sadly, not all shots were recorded for velocity, and I am missing some from the LC and SC groups since I needed to use some of the loaded rounds as sighters. Also, if there was any error, it may have been leaving the 38SPL ammo in the sun on top of the tester- it did become a hot day, and the sun beats down on everything. Once it became apparent, somewhere in the middle of the 38SPC run, I moved the ammo to a shaded bench.

Groups were collected at 10 shot intervals and new targets put up for the next series of 10, continuing until that load was exhausted.

For a dry run, this initial test was very informative.

| ![38 Special](/assets/series_303.svg) |
|:--:|
| 38 Special. Loaded with [4.0 W231 3X Starline](/assets/SR0303Report.csv) |

| ![38 Long Colt](/assets/series_306.svg) |
|:--:|
| 38 Long Colt Loaded with [3.1 W231 New Starline](/assets/SR0306Report.csv)|

| ![38 Short Colt](/assets/series_308.svg) |
|:--:|
| 38 Short Colt [2.5 W231 1X Starline](/assets/SR0308Report.csv) |

<h3>Test Results</h3>

Upon returning home, the targets were scanned and the data plotted. From there, it was time to see if there was any statistical difference between any of the groups. In short, there was none. The R50 values are nearly identical across the cartridges. I ran an ANOVA analysis comparing the groups with one another. Again, there was no difference, as signified by the high p-values (above .05).

|ANOVA Results|38LC vs. 38SC|ANOVA Results|38LC vs. 38SPL|ANOVA Results|38SC vs. 38SPL|
|Coordinate        | p-values|Coordinate       | p-values|Coordinate       | p-values|
|:---|:---|
|X Coordinate:| 0.3958|X Coordinate:| 0.4926|X Coordinate:| 0.7027|
|Y Coordinate:| 0.8211|Y Coordinate:| 0.8062|Y Coordinate:| 0.9503|

And just to be thorough, I compared all three groups together. Based on the results of the Multivariate Analysis of Variance (MANOVA), there is no statistically significant difference between the three groups based on their XY coordinates.

The p-value from the test (using Wilks' lambda) is approximately 0.9136, which is much higher than the typical significance level of 0.05. This indicates that we fail to reject the null hypothesis, meaning the observed differences in the group mean radius' are not statistically significant compared to one another. Or, in other words, the groups are not statistically different from each other in the 2D space based on this analysis.

Of note is the elliptical patterns presented by each cartridge. 38SPL and 38LC appear to be somewhat vertically oriented, where the 38SC appears to be somewhat horizontally oriented. An explanation might be that there was some disturbance of the 38SC bullets traveling further down the chamber itself such that it presented the pattern seen in the scatter plots. But in terms of mean radius, they are all effectively the same.

Another insight into the above results isn't about the groups themselves or the size of the case, but is instead related to how many times the cases have been fired. The 38SPL was 3X, the 38LC is new Starline brass, and the 38SC is 1X. While this test was not created to see if case life has any impact on accuracy, it does give one a little food for thought; according to these results, it may not matter.

| ![Outliers](/assets/outliersdryrun.png) |
|:--:|
| Outliers: 2 in 38SPL, 1 in  38SC|

Last, I plotted out what would be considered outliers, as seen above. This was calculated using Mahalanobis distance, which is a fairly robust method for measuring this kind of data. Something that may prove useful is capturing the shot distribution by velocity and adding that into the calculation to see what, if any, effect may be present that could account for the outliers. Otherwise, the fault of them is either in the creation of the round, or the testing itself.

<h3>Thoughts</h3>

This test, while itself an initial foray into this research, helped me to determine how best to load up the rounds for testing, setup speed, and total time from first round downrange to pack-up and exit. Next steps are to load up some more ammo to see if I can get the velocities to match using the data previously collected and from this batch.
