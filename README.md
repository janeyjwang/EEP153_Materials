
# Table of Contents

1.  [Overview](#org0e55e7e)
2.  [Administrivia](#org9d66f05)
    1.  [Prerequisites](#org074c1a7)
    2.  [Schedule](#org70dc0d2)
    3.  [People](#orgc7f788d)
        1.  [Office Hours](#orga894486)
    4.  [Evaluation (Grading)](#org6cad73b)
        1.  [Team evaluations](#orgd6262ae)
        2.  [Teammate evaluations](#orgc148948)
        3.  [Quality of evaluation](#orgda91631)
3.  [Projects](#orgff8c6a0)
    1.  [Introduction & Collaboration](#orgf9d70cc)
    2.  [Population & Food Supply](#orge99ab75)
        1.  [Readings](#org5991361)
    3.  [Subsistence Diets](#orgeaaea89)
        1.  [Readings](#org0d12e12)
    4.  [Consumer Food Demand](#org5337ddf)
        1.  [Readings](#org20ea5fc)
    5.  [Estimating Food Demand Systems](#org5762ff4)
    6.  [Hacking Food & Nutrition](#orgf5b1cb9)
        1.  [Readings](#orga769fc5)



<a id="org0e55e7e"></a>

# Overview

This course takes a quantitative, hands-on
approach to understanding the challenges of
feeding the human population of the planet
Earth.  We'll discuss topics of nutrition,
subsistence food consumption, and consumer
demand for food to develop our
understanding of the current situation.
We'll then develop both theories and
computer models of population dynamics
taking into account people's decisions
about child-bearing, changes in mortality,
and changes in food supply in order to
learn something about the future of food.
Focus throughout the course will be on
developing practical tools to work with
real-world data.  Those tools will include
linear programs, globally regular demand
systems, and a variety of
econometric tools.  The course will rely on
a knowledge of the programming language
`python`.


<a id="org9d66f05"></a>

# Administrivia


<a id="org074c1a7"></a>

## Prerequisites

Data8, EEP100 or
equivalents required; Math 54
recommended.


<a id="org70dc0d2"></a>

## Schedule

Meet two times per week; M 2&#x2013;4pm and W 1&#x2013;3pm (Pacific Time). 

We'll have a mix of lectures and discussion (typically on Mondays)
and tutorials and group work (typically on Wednesdays).  

When we're able to meet in person we'll be in Social Sciences 110;
until then we'll meet via zoom at
<https://berkeley.zoom.us/j/91293178788>.  Note that to join you'll
need to sign-in to zoom using your `berkeley.edu` email.


<a id="orgc7f788d"></a>

## People

-   Ethan Ligon (ligon@berkeley.edu)
-   Becky Cardinali
-   Ryan Sandan


<a id="orga894486"></a>

### Office Hours

See announcement on `piazza`


<a id="org6cad73b"></a>

## Evaluation (Grading)

Grading in course depends primarily on *peer evaluation*.  In
particular, every project will lead to you evaluating your
classmates in two main ways, and being evaluated yourself in three.


<a id="orgd6262ae"></a>

### Team evaluations

Everyone will evaluate every team according to several criteria:

1.  Code

    1.  Did code work as intended?
    2.  How elegant was the team's code?
    3.  How ambitious were design goals?
    4.  How completely were design goals met?

2.  Organization

    In the presentation:
    
    1.  How well did team manage its time?
    2.  How well did the team work together?

3.  Style

    1.  How interesting was the presentation?
    2.  How polished was the presentation?

4.  Overall

    1.  If you were in the position of needing to hire a team to do
        population analysis, would you hire this team?
    2.  Other constructive comments & criticisms.

5.  Ranking

    Finally, we'll ask you to rank all teams according to your overall
    impression of their presentation.


<a id="orgc148948"></a>

### Teammate evaluations

Everyone will also evaluate all of the individuals on their team
according to several criteria:

1.  Quality of work
2.  Could be counted on to complete tasks in a timely fashion?
3.  Helpful to others in group?
4.  Contributed to the smooth working of the team?

In addition, we'll ask you to give some additional information
about each of your teammates, indicating:

-   What were each person's main strengths?
-   Would you like to work with this person again?

And finally, we'll ask you to:

-   Rank each person according to their overall contribution to the project.


<a id="orgda91631"></a>

### Quality of evaluation

Your own evaluations are an important individual contribution to
the class, and the quality of your evaluations will affect your
grade.  There are three criteria we'll use in judging the quality
of your evaluations.

1.  Prediction of others' evaluations of you

    You'll provide evaluations not only of **other** teams, but also of
    your own team.  And you'll evaluate not just your teammates'
    contribution to the project, but also your **own** contribution.
    
    Your self-evaluations will affect your grade.  However, the *way*
    in which these will affect your grade will depend **not** on how
    good you say you are, but how accurately you **predict** how others
    evaluate you.  In particular, the closer your guesses about
    others' evaluations are to the *average* of what others give you
    the higher your grade.

2.  Information in your own evaluations of others

    The greater the information provided by your evaluations of others
    the higher your grade.  The amount of information will be measured
    partly according to the variation of your evaluation of others, and
    partly according to a (subjective) measure of the quality of your
    comments.
    
    Observation: if you give everyone the *same* scores (e.g.,
    everyone gets top score) there is *no* variation in your
    evaluation.  This would negatively affect your own grade.

3.  Correlation with evaluations of others

    Your evaluations must be honest, in the sense that they are
    attempts to fairly evaluate the efforts of others and of your own
    efforts.  Ideally there will be broad agreement across different
    people's evaluations.  If your evaluations are \`outliers' then
    this will *negatively* effect your grade.  Further, if upon
    examination it appears that you've used your evaluations
    strategically there may be further repercussions, most
    particularly if the manner in which you've evaluated others
    violates Berkeley's Honor Code (i.e., you must "act with
    integrity, honesty, and respect for others").


<a id="orgff8c6a0"></a>

# Projects

The course revolves around a sequence of
topics, each exploring a substantive
issue involved in "feeding the planet"
and each introducing novel tools.
Students will work in small groups to
complete one structured project for each
topic.


<a id="orgf9d70cc"></a>

## Introduction & Collaboration

Students will review introductory materials about coding 
(Python and Pandas) and potential ways to collaborate 
(Google Colab, Trello, Git, and Agile). See `piazza` post 
for links to the resources


<a id="orge99ab75"></a>

## Population & Food Supply

Students will construct datasets on the
distribution of characteristics in the
world population, including measures of
resources, and the age and sex
composition of the world population.  A
separate dataset allows us to think
about food supply.


<a id="org5991361"></a>

### Readings

-   Malthus [An Essay of the Principle of Population (1798)](https://oll.libertyfund.org/titles/malthus-an-essay-on-the-principle-of-population-1798-1st-ed#lf0195_head_002)
-   de Janvry-Sadoulet (2015), [Chapter 11 of Development Economics](http://www.piazza.com/class_profile/get_resource/jr496uyyc062tz/jrb6yugn22e4gp)
-   Fuglie (2012), <https://www.ers.usda.gov/amber-waves/2012/september/global-agriculture/>


<a id="orgeaaea89"></a>

## Subsistence Diets

Every living human has some minimal, or subsistence, nutritional
requirements; should these not be satisfied health and even life
may be threatened.  People satisfy these needs by eating various
kinds of food, but there may be many different food diets which
satisfy people's subsistence requirements.  One criterion for
choosing among these diets is *cost*. 

In this topic students use contemporary data on different kinds of
foods available to the US population along with prices to
construct estimates of *minimum cost* subsistence diets.  


<a id="org0d12e12"></a>

### Readings

-   [Stigler (1945) "The Cost of Subsistence"](https://www.jstor.org/stable/pdf/1231810.pdf?casa_token=WCKDDMzf7CgAAAAA:B1TsWcgpfQQMSXtChZ_VThlodwilTzVbyk-5yj_1U57Kfmth0tE8qV1kcHXDxX1n8Iun8QsEwxAvmLkEc7UtwJd2LPBnRveEWFdrr5OHbeuTDqKqBrE4)
-   [Ligon's notes on the Minimum Cost Diet Problem](https://piazza-resources.s3.amazonaws.com/jr496uyyc062tz/jsb2e24wylb64e/minimum_cost_diet.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIAR6AWVCBXXTXJNAXC%252F20190424%252Fus-east-1%252Fs3%252Faws4_request&X-Amz-Date=20190424T204202Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Security-Token=AgoJb3JpZ2luX2VjEAMaCXVzLWVhc3QtMSJIMEYCIQCk4zh%252Fx1OmB7zaD1m%252F%252Fun7szwA4icbeOeplvEx%252FkLC5wIhAJ78MWuElE8Cm9n73WNwN%252FUy4NI9dBGCd3qyu5vnDSgMKuMDCNv%252F%252F%252F%252F%252F%252F%252F%252F%252F%252FwEQABoMMTMzMTkxNTAzOTgzIgywQbn9l6mWXqzQCMcqtwO5Erkw270lupUuzD8zc6aCuKtu3wTzFkMcc1N7BGrlFoI9OO6p8Oj9IwrBBIvQTRb17Cpt7TKnXWsAe7RZp4EvAl7d9FMSiIze%252BD0O1sBI4FBag73gKAVvhtI3UiWUfVUkgn6pIlMqiMow0eCSKlUR2Dxv%252FX%252FZytGa45MbZKO6dPZVHDhi0laNvOo6fRxNo%252FKDGbTcmaP8dwSwLXt%252Fxa6Bf10FLCFABKRnAE1sM9hOatwzlrbAiq8lGUpG6UFOP4ny4FU0e0Xa0kGsGzon%252FjEpNuIOUBQqcAE0hM2dA9vjvXqj2UlN723ecTvRqP%252BX0ys%252FU1WORasUum7wrgAY9ZNZQ2b6HBse1L1dCIAM1RGFiyy4s417i5iM%252BH1VlMQTv36aeCxBAV%252FmYBg%252BF0d30DH3PhPjFrvWri4j40GFsDytioWfcJXuQtAX28NoYd1UqfCzClZ8lZJ%252BaN84yg8VVjj8YtVCQAsrovvQTvP9zWkB3JsR9V%252FQaRoar9dCgSUDKoFl0dl6etNVDqbwhEN31ikC7dqtUx5Qb7Y09fdPpV%252FsJUSv7bMeoKjIyZzJlD9JhH4MU9X0nVW4MNfOguYFOrMB2YNnmq2%252Fam2pZHo%252B8i1fuw6PHd8THxZ6pzXq6PvUzk%252F9l3XEv2kSt7RwChbg1PZeYvD1wKzi%252BiB6F98V5evv2CaCzpeXwW2fSunaxE3M3uvRuYVYRP9XEZshjGbga9G1pgM%252F4LneC7hhgyehaADntjACrR%252BG%252BKy%252Bg7MHPMbJwg8hCKdCRd5T%252B1OTHgpV8kQZyIb2AdtePKvmixHRKCJIxLfMhHGrL%252BJj6YtG%252BJzllrtUUbw%253D&X-Amz-Signature=97529f8126a21657cebb8b3d269fde748f5a11088c4dfa12e8e91cd651d1660f)


<a id="org5337ddf"></a>

## Consumer Food Demand

In practice, even very poor people seldom choose their diets on
the basis of minimum costs.  Instead, people balance nutritional
requirements against considerations of cost and what we might call
the gastronomical value of different diets.  Here we explore the
theory of demand as it pertains to these diets&#x2014;how does demand
for food depend on income, prices, and other observables?  How
well (or poorly) do these diets serve nutritional ends?


<a id="org20ea5fc"></a>

### Readings

-   Review basic demand theory (e.g., Chapters 3&#x2013;5 in Nicholson-Snyder)


<a id="org5762ff4"></a>

## Estimating Food Demand Systems

Students will use data on household food expenditures for
populations from different countries to estimate systems of food
demand, and relate these demands to the subsistence diets
calculated in the earlier topic.

With these results in hand you will construct aggregate
demand functions that allow one to make predictions regarding how
aggregate demand for different kinds of foods depends on the
distribution of resources and the demographic composition of the
global population. 


<a id="orgf5b1cb9"></a>

## Hacking Food & Nutrition

This project exploits our work on demand for food and is focused on
evaluating what kinds of **policies** might be effective at improving
nutritional outcomes for particular populations.  Our earlier work
addressed the question of how demand for different kinds of food
depends on prices, budgets, and household characteristics, taking as
given prices, budgets, and so on.

One of the take-aways from our earlier project is that the food people
*choose* to eat may be quite different from the foods that people
*should* eat, from a nutritional perspective.   

But if dietary choices respond to prices and budgets, it may be
possible to manipulate nutritional outcomes by changing either prices
or budgets.  We can assess the costs of this kind of manipulation
(e.g., the deadweight cost of a tax or subsidy); where these costs are
large we can also think about the value of innovation in either the
desirability or nutritional content of food.


<a id="orga769fc5"></a>

### Readings

-   Technical change: [Borlaug (2000)](http://www.plantphysiol.org/content/124/2/487?ijkey=c12c5c79e5b11c10820b21877391b978804dc1c5&keytype2=tf_ipsecsha), [Ars Technica (2019)](https://arstechnica.com/science/2019/06/why-havent-genetically-engineered-crops-made-food-better/)
-   Changes in budget: [Deaton-Dreze (2009)](https://www.jstor.org/stable/40278509)
-   Changes in relative prices: [Falbe et al (2016)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5024386/)

