+++
title = "A Quick Introduction to the WELLBY"
date = "2025-02-19T01:44:58-08:00" 
+++

I was an intern at the Effective Institutions Project this past summer. A large part of my work was building a framework to evaluate institution decision-making. The blog post that follows is an exploration of quantitative measures of subjective wellbeing, and the problems that ensue.

All opinions are mine and do not reflect the opinions of past/present/future employers. I preface this post by saying that I’m a second-year undergrad, I’m still learning introductory econometrics, etcetera, so all mistakes should be ignored while all correct analyses should be taken as proof of my budding genius. 

## Introduction of the WELLBY
Charities and governments want to create good and reduce bads. But “good” is difficult: what is good for me may be bad for you, and vice versa. Moreover, resources are limited: which bads are most important to reduce? Altruistically inclined institutions lack a standard unit measure for good and bad, harming decision making and evaluation. (Compare this to businesses, which have the simple dollar as a performance indicator.)

Commonly used measurements of “good” include GDP and QALYs (quality-adjusted life-years).  These are insufficient: income and health aren’t good in and of themselves; they are good because they improve personal wellbeing. GDP and QALY measures ignore the assortment of benefits people gain from non-health and non-income determinants. For example, one’s friendships, romantic partner, and career satisfaction are all deeply important to one’s life.

The organization I interned with used subjective wellbeing measured through the WELLBY, a wellbeing-adjusted life-year. Subjective wellbeing captures more than happiness; it contains the broad scope of how one feels about one’s life. We looked at wellbeing determinants, interventions done by institutions and then evaluated the potential impact of each institution’s decisions. 

### Why subjective wellbeing?
There are three main theories of wellbeing: hedonism, desire fulfillment, and objective list. Hedonism evaluates the balance of pleasure and pain. What is good for someone is what is good to someone. Desire theory evaluates the fulfillment of one’s aims. The path to achieving a goal is often unpleasurable or irrelevant. For instance, I desire to bench one plate, not to have the experience of benching one plate. Objective list theory provides a list of items that constitute well-being or the good life. This list consists of experiences that are not simply pleasurable or desirable, but good nonetheless: things like knowledge, moral accountability, and the like. 

There are numerous critiques and responses to each of these theories. I’ll leave those for the reader to explore. What’s relevant for this piece is that subjective wellbeing surveys leave understandings of wellbeing to the individual: it captures subjective preferences and aggregates these to some understandable mean. 

### Why institutions?
There are many levels at which wellbeing interventions can be evaluated. At the policy level: are direct cash transfers actually useful? At the operational level: are these cash transfers being done efficiently? Lastly, at the institutional level: are the right institutions taking on cash transfer projects?

I find evaluating institutions most interesting. Institutions mobilize massive amounts of capital and labour each day. Altruism is not knowledge constrained— it is more often power constrained. We know that Vitamin A deficiencies kill; the question is whether the right global actors are taking micronutrient supplementation seriously, and whether outside actors have the power to influence these major global actors. 

I think this is a more complete approach to charity evaluations and philanthropy research. 

## Finding data

The Gallup World Poll provides the most comprehensive source of wellbeing data. Its main life evaluation question is as follows: 
> Please imagine a ladder, with steps numbered from 0 at the bottom to 10 at the top. The top of the ladder represents the best possible life for you, and the bottom of the ladder represents the worst possible life for you. On which step of the ladder would you say you personally feel you stand at this time? 

This is also known as the Cantril scale. Anyone taking ECO220 at the University of Toronto is probably familiar with this self-reported happiness scale. 

Self-reported wellbeing scores are valuable because they capture valence and preference differences. For instance, my lived experience of a skinned knee is different from yours, and my theory of wellbeing is also likely different from yours. We live in epistemic and moral uncertainty: this necessitates giving weight to others’ experiences and preferences, including those we think are incorrect.

One drawback is that respondents must be able to communicate their life satisfaction to have their wellbeing captured. This can exclude a large audience– animals, young children, extremely disabled people, etcetera– from this evaluative wellbeing method. This doesn’t mean we should ignore WELLBYs as a metric, just that we should be aware of its constraints. Bob Fischer at Rethink Priorities has lots of work on animal welfare ranges and moral weights; there is lots of active research here.

Another thing to note is that the Likert scale is ordinal; response categories definitely have a rank order, but it’s unclear whether the scale is cardinal or linear. In other words, it’s unclear if eg. an increase in subjective wellbeing ratings from 2 to 3 worth the same as an increase from 7-8. Still, many organizations treat life satisfaction measures as if they were interval data. For example, summing WELLBYs incurred from a natural disaster by multiplying the number of people injured by the WELLBYs associated with said injuries. This bodes problematic if the scale is non-linear. 

### Defining parameters for evaluation
There are a couple different ways of calculating WELLBY impacts from an institution’s decisions. We can look at the expected value, the difference between the best and worst case scenarios, the regret minimizing scenario... there are many decision-making models.

I'll walk through the best-worst case situation to demonstrate some of the difficulties making a WELLBY model. First, how do we define our best and worst case– is the best and worst case something that the institution does, or avoids doing? In other words: is there an act-omission distinction? Weakly I think the answer is sometimes. For instance, the FDA has a special obligation to the health of Americans. Not circulating warnings about E. coli in cabbage is a clear violation of their mandate which they ought to maintain, ergo their worst case harms should include harms from inaction. But its less clear in most case. Take the Bretton Woods institutions– should the World Bank be held responsible for not investing in climate finance 20 years ago? Its mandate is to reduce global poverty and climate change has clearly accelerated global poverty. But there are dozens of other institutions that serve similar enough purposes: does the World Bank then have a unique special obligation? When responsibilities are diffuse, its hard to define best and worst cases. 

Even further: how do we define harm? Should we consider harms on future populations, for instance future children displaced by climate-change related flooding? This is a manifestation of the non-identity problem. If we define harm as something that makes another materially worse off than they were before, the affected needs to have some sort of state before, and we need to see a continuity of self. But if we define harm this way, it seems that climate change is perfectly fine for those born in 200 years to regular natural disasters, because they did not exist before. That seems obviously wrong; the future is path dependent and surely 

Defining harm to be something that makes a potentially existent being worse off than their potential counterfactual is also dubious. We’d conclude that legalizing abortion results in near-infinite harms. Surely there must be a time horizon for harm and being? I don't know; I am not a philosopher; I would appreciate direction here. I simply propose that anyone using WELLBYs should clearly define their parameters and stay consistent with them. This is insufficient but it is what I have so far. 

## Concluding note
I am a fan of WELLBYs as a non-financial KPIs. Like all models, WELLBYs are a flawed model of wellbeing, but all models are wrong; some are useful. I think WELLBYs can be very useful for quantitatively answering questions related to philanthropy. 

And I am very grateful for all the EIPeople I worked with and learned from this summer. I’d like to stay up to date on wellbeing economics research, so please share articles you find interesting!