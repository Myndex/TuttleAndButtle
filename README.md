# TuttleAndButtle
_Canonical rebuttals to sponsored rumors._

## Rebuttal to Yatil's "WCAG 3 is not ready yet"

Early December of 2021, Eric Eggert (Yatil) continued his derisive commentary regarding new contrast methods proposed in WCAG 3. This opinion piece has been re-used and re-posted over the last few years by others of a small group of individuals that have been actively obstructing the improvement of readability and visual accessibility standards. We refer to them collectively as _"the obstructionists"_.

The piece itself is of little value, but it has come to our attention that it is being used as a reference, cited to obstruct the progress of actual accessibility research. As such, it needs to be challenged. It does not contain facts, but rather is a string of provocative logical fallacies, as discussed below, on a line by line basis.

------------
> _<sub>Yatil:</sub>_    
> ### _WCAG 3 is not ready yet_

No one said it was, but parts are/were certainly ready for testing, and actively undergoing tests. APCA was brought to the public view and published as an npm package December 2021 to enable the larger public beta period for testing and evaluation. Mr. Eggert's opinion piece, along with actions by other obstructionists, had a chilling effect, including the disruption of the beta program, and causing some beta testers and early adopters to drop out of the beta test program.

> _<sub>Yatil:</sub>_    
> _And it won’t be for quite some time._

**Logical fallacies:** _reciting **facts not in evidence**, false premise, appeal to ignorance, and uninformed rhetoric._

At the time this was stated, WCAG&nbsp;3 was expected to evolve within a few years. However, as a result of the obstructionists, WCAG&nbsp;3 was brought down and restarted nearly from scratch, and as a result, now does not have any clear release date.

Because of the importance of visual accessibility, the APCA and APC-Readability Criterion is now on a fast-track development with the non-profit [Inclusive Reading Technologies, Inc.](https://readtech.org/ARC/) 

> _<sub>Yatil:</sub>_    
> _In the last couple of weeks, more and more people point at the WCAG 3.0 Working Draft and recommend the adoption of aspects from it that suit their needs, despite the draft clearly stating (emphasis theirs):_

The "aspects of it" is the contrast method, APCA. People are using it because the existing WCAG&nbsp;2 simply does not work. Those that had been adopting it in 2021 were part of the wide public beta program, devised to ensure that future contrast methods did not fail, the way WCAG&nbsp;2 contrast has.

> _<sub>Yatil:</sub>_    
> _These are early drafts of guidelines included to serve as initial examples. They are used to illustrate what WCAG 3.0 could look like and to test the process of writing content. These guideline drafts should not be considered as final content of WCAG 3.0. They are included to show how the structure would work._

**Logical fallacies:** _begging the question (circular argument), false dilemma, equivocation (doublespeak), post hoc ergo propter hoc (after this, therefore because of this, i.e. false correlation), straw man argument (unrelated/irrelevant argument)._

They are included as guidelines to test and evaluate the process of creating the guideline, process of using, and of testing the guideline function as part of the public beta test, etc.

In 2021, as well as now, WCAG&nbsp;2 is not "mandated law" in most of the world, though unfortunately it has been added to some rules in some specific cases, despite the known failings and potential for harm. More on this a bit later.

> _<sub>Yatil:</sub>_    
> _W3C Working Groups publish drafts to allow the public and W3C members to give feedback. They are explicitly not meant as a recommendation or even as advice. To quote from the W3C process document (emphasis mine):_

**Logical fallacies:** _begging the question, false dilemma, appeal to ignorance, reciting facts not in evidence._

How is the public to give feedback, if they don't actually try and use something? What benefit would that provide? None. All guidelines need testing and evaluation. APCA was and is undergoing evaluation, in real world circumstances, using real websites and tools developed by and for designers. 

No one ever claimed WCAG&nbsp;3 was a "recommendation", however when it comes to contrast, WCAG 2.x contrast SCs are so poorly conceived and unusable, that many were eager to try out the new and functional APCA method.

And in fact, by December of 2021, the APCA method then (and now) in testing was not the version first shown in the January 2021 WCAG 3 working draft, and had already advanced substantially beyond that. The stable beta version was released February 15th 2021 (version 0.98G-4g). Taking a conservative approach, nearly a year later the 0.98G-4g beta was made available as an npm package, to help assure consistency across early adopters and beta testers.

>> _<sub>W3C Process as quoted by Yatil:</sub>_    
>> _Working Drafts do not necessarily represent a consensus of the Working Group with respect to their content, and do not imply any endorsement by W3C or its members beyond agreement to work on a general area of technology._
>> _[…]_
>> _A Working Draft is suitable for gathering wide review prior to advancing to the next stage of maturity._

Which refutes the statements Mr Eggert made previously, elsewhere he has claimed that _"there is no provision for testing in WCAG"_ and other nonsense. The working draft is ***explicitly for testing and wide review***. So which is it Mr. Eggert? That there is no provision for testing as you stated elsewhere? Or that there _is_ testing?

> _<sub>Yatil:</sub>_    
> ### _What’s the issue with being an early adopter?_
>
> _In general, web technologies are very good citizens to early adopters like me: They usually come with suitable fallbacks that allow you to use, for example, animations and transitions in 2009 with the fallback of no animation for browsers without support._

**Logical fallacies:** _reciting facts not in evidence, setup for an appeal to ignorance._

In other words, this comment is not at all relevant. APCA exceeds the meager requirements of WCAG&nbsp;2, and no "fall back" is specifically needed.

Nevertheless, we also released [Bridge PCA](https://bridgepca.com) which is a simplified version that is a drop in replacement for the unreliable WCAG&nbsp;2 math. Moreover, WebAim's studies show that [86% of websites fail to use WCAG&nbsp;2 contrast](https://uxdesign.cc/better-reading-on-the-web-c943c4cfc91a) (in large part as it does not work), so here Mr. Eggert seems to want to fall back to a spec that is known to be a fail.

> _<sub>Yatil:</sub>_    
> _With guidelines like WCAG 2.1 and 2.2 (to be released later), the same approach is true. If you use WCAG 2.2 Success Criteria now, the Guidelines are built to be backwards compatible. So you will never break a 2.0 or 2.1 audit by using it._
>
> _But WCAG 3 breaks backwards compatibility. This is a conscious move to better adapt the standard to serve different disabilities which WCAG 2 did not sufficiently cover, due to its structure._
>
> _That means that WCAG 3 will probably have a different scoring system that does not necessarily overlap with WCAG 2. As far as I know – and my involvement was some time ago – the current plan is to make sure all WCAG 2 conforming pages conform to WCAG 3, too, in some form. They will not in reverse._

**Logical fallacies:** _reciting facts not in evidence, fallacy of equivocation, false analogy, arguments from analogy, straw man._

These paragraphs are confusing to say the least. And further, forward/reverse conformance had (at that point) not been a key consideration. The consideration at the time was to start with a clean slate with WCAG&nbsp;3, in order to allow a departure from the areas where WCAG&nbsp;2.x makes unsupportable demands.

## SIDEBAR: *Backwards Compatibility in WCAG&nbsp;2.x Terms*
Let's discuss this, as the "backwards compatibility" issue is the core of Mr. Eggert's demurrer.

Just to clarify, the backwards compatibility being referenced here, as stipulated under WCAG&nbsp;2.0, means that if something "fails" under WCAG&nbsp;2.0, that it therefore "must" fail under _all future versions_. But, any future version of WCAG&nbsp;2.x may **add features** that might ***not*** fail under a previous version.

**In other words, the guarantee posited by AGWG and WCAG&nbsp;2 is that if you pass a future version, you automatically pass all of a previous version.**

Thus, the backwards compatibility here as mandated in WCAG&nbsp;2.x is the ultimate hubris, as if to claim that technology does not change and that AGWG and WCAG&nbsp;2 have infinite knowledge of the future.

Such a premise is absurd on the face of it. Moreover, even the AGWG has disregarded the backwards mandate by removing an SC from WCAG&nbsp;2.2

In the case of contrast under WCAG&nbsp;2, it can actually [**make things worse for people with color vision deficiencies**](https://tangledweb.xyz/whats-red-black-also-not-read-573b9c0a97ed). Further, WCAG&nbsp;2 contrast has no peer-review nor empirical studies, and has been widely criticized. In other words, it is wrong, and it is wrong for it to be in any standard.

The claim that it "can't be changed" due to backwards compatibility issues is an untenable, unpersuasive argument.


> _<sub>Yatil:</sub>_    
> ### _So, what about that “new color contrast algorithm”, then?_
>
> _The visual contrast algorithm that is currently referenced in the WCAG 3 Working Draft, named APCA, is a stark departure from the luminosity contrast algorithm used in WCAG 2._

**Logical fallacies:** _hyperbole ("stark departure"), use of unsupported negative phraseology._

Yes, APCA is a bit of a paradigm shift, as is needed to replace the flawed and much maligned WCAG2 contrast methods and guideines. And how "stark" the departure depends on the level of improved accessibility one desires. And this has little to do with APCA the algorithm, and more to do with the more flexible guidelines that a perceptually uniform algorithm permits.

For instance, the ["Bronze Simple Mode"](https://readtech.org/ARC/tests/bronze-simple-mode/?tn=criterion), created in response to statements like this, is a basic and simple guidelines with basic threshold levels—but using correct math and methods. 

But "Stark Departure" is hyperbole. Both the basic APCA and the WCAG2 test a pair of colors, and provide a value. The difference is that the value provided by WCAG2 is not meaningful, and [not at all consistent](https://tangledweb.xyz/hi-lucas-673167805f55) over the visual range, and this requires brute forcing of threshold levels. APCA is consistent, i.e. perceptually uniform, and that allows for a more complete and useable set of guidelines.



> _<sub>Yatil:</sub>_    
> - _WCAG 2 treats front and background color the same, so inverting the color does not change the calculation. This is notably not how color perception works in practice. You can perceive certain colors better or worse, depending on the surrounding color._
>
> - _WCAG 2 does not take font-size and weight into account, the APCA does_.
>
> - _WCAG 2 did not change the required contrast depending on the font, APCA does._

**Logical fallacies:** _FALSE_, false equivocation, misdirection, and omission of facts surrounding WCAG&nbsp;2 to claim it is simpler. 

WCAG 2 _does_ have font-size and weight breakpoints for normal and bold fonts. [Arguably, this is wholly inadequate](https://tangledweb.xyz/please-stop-using-grey-text-3d3e71acfca8). But it is also disingenuous to imply that WCAG&nbsp;2 is better or easier to use because it is claimed to be "simpler", and omitting the fact that WCAG&nbsp;2 has rudimentary font requirements is the basis for Mr. Eggert's argument that APCA is "more complicated". If one has to lie to make a point, then they have no point to make. In this case, it is an easily verifiable lie, as all one has to do is read the WCAG 2.x 1.4.3 SC.

But more to the point, saying "WCAG&nbsp;2 is simpler" falls flat—designers and content developers certainly don't think so, nor do those with color vision issues who are not well served by WCAG&nbsp;2.

The WCAG&nbsp;2 breakpoints have no support in peer reviewed empirical studies, and no effort is made to recognize that "font-size" does not relate to the actual text size as rendered on screen. Further the contrast levels of 4.5:1 and 3:1 can be either completely inadequate, or paradoxically, more than is needed. Thus, being _"simple"_ is useless if it also means being wrong. WCAG&nbsp;2 barely considers spatial aspects, but moreover, the asserted "simplicity" is not a virtue, it is a part of how WCAG&nbsp;2 contrast SCs fail as guidelines.

There is nothing about the APCA algorithm that prevents this simpleton approach. In fact, BridgePCA is a simple drop-in repacement for WCAG&nbsp;2's faulty math and methods. But with the full APC-RC guideline comes both improved accessibility, and improved flexibility. The APC-RC is designed with good design in mind from the get-go.

**Facts:** contrast perception of most text (as well as lines thinner than about 4px) is primarily driven by these _spatial_ characteristics. The font weight, size, or line thickness is the primary driver, as that is directly related to human contrast sensitivity. This is a matter of well developed, peer-reviewed scientific consensus, going back half a century at least (See Stevens et alia). APCA considers these well established aspects of visual perception, and the APC-RC guidelines are all referencing the well established scientific consensus in readability (Legge, Whittacker, Lovie-Kitchin, et alia).

APCA and the APC-RC are a product of years of research and investigation, using well established peer-reviewed science, and with years now of open public testing.

WCAG&nbsp;2 referred to none of that, instead cherry-picking from an [obsolete 1988 standard for monochrome CRTs.](https://tangledweb.xyz/a-contrast-of-errors-373c2665d42a) So we find it curious that Mr. Eggert and friends are demanding that people adhere to the old, and deeply flawed SCs such as 1.4.3, which does not support actual accessibility, and in fact can be harmful to readability.

> _<sub>Yatil:</sub>_    
> - _These are all good arguments to change to a new way of measuring contrast, especially as APCA also promises to give designers more color choice. However:_
>
> _Any color combination with APCA needs to be checked for both font-size and weight, making requirements documents and design systems more complicated._

**Logical fallacies:** _false equivocation, begging the question, false dilemma, appeal to ignorance, reciting facts not in evidence._

As stated, and as listed in the WCAG&nbsp;2 document, font size and weight also must be checked. Thus, the claim that APCA is "more complicated" is unpersuasive.

The APC algorithm, being based on human perception, provides a substantially more accurate prediction of perceived contrast (as mush as a 250% improvement over WCAG 2). Having an accurate model allows for useful guidelines, such as the [APC Readability Criterion](https://readtech.org/ARC/), which provides designers with useful and actionable guidelines for font size and weight. And designers have been very supportive of the sliding scale that permits greater design flexibility using the APC-RC.

In response to Mr. Eggert's negative views, we developed the [_"Bronze Simple Mode"_](https://readtech.org/ARC/tests/bronze-simple-mode/?tn=criterion) guideline, which uses the APCA algorithm, but breaks the guidelines down into a few simple breakpoints, not unlike the 1.4.3 SC. We also developed the BridgePCA, which is a literal drop-in replacement for the flawed WCAG&nbsp;2 contrast math, and is backwards compatible therein.

We developed BridgePCA in part to get a better understanding of the underlying motivations of the obstructionists. BridgePCA is backwards compatible to WCAG 2 contrast, and substantially improves actual accessibility. Yet the obstructionists have completely ignored it. This clearly demonstrates the obstructionists have goals unrelated to improving accessibility. Their negative viewpoints should be weighted with this in mind.

***AS A SIDE NOTE:*** To be clear, there is nothing at all about the APCA *algorithm* that prevents "backwards compatibility" to the old WCAG&nbsp;2. APCA itself is just an algorithm that predicts contrast perception. It is a matter of the development nd writing of the _guidelines_ that answers the question of backwards compatibility.

The area where APC-RC guidelines are intentionally not backwards compatible with WCAG&nbsp;2, is the area where WCAG&nbsp;2 is harmful to readability for color insensitive folks. This is the one area where Mr. Eggert and friends are frequently claiming that _"you have to follow WCAG&nbsp;2 because, laws..."_ which is not supportable, when the failings and bad law that WCAG&nbsp;2 creates have not been proven in a court of law as valid.

### We consider it inappropriate to support backwards compatibility to guidelines that are harmful.

That said, to answer the demurrers Of Mr. Eggert and others in the obstructionist group, we developed Bridge PCA, which uses APCA technology, but is adjusted for backwards compatibility with WCAG&nbsp;2. That the obstructionist group refuses to acknowledge this is further proof that their underlying motivations are not aligned with actual accessibility.

> _<sub>Yatil:</sub>_    
> _Designers compare the used font to the standard, Helvetica-based, APCA lookup table. This feels like an error-prone step to me, considering that this comparison seems to be done on a visual level. It is not only excluding people with visual disabilities from making their own (accessible) font and color choices, but it also brings a certain level of subjectivity into the rating._

**Logical fallacies:** _hasty generalization, false equivocation, red herring, straw man, genetic fallacy, and ableism._

This statement is incomplete, and not accurate. There is a list of pre-qualified fonts that fit the paradigm of actual accessibility.

And there is a well defined procedure for qualifying alternate fonts, and is a task that only need be done once. The level of subjectivity is minimal, being binary in nature, i.e. a font is either heavier or lighter than the reference at a given weight, and determining this value as ±100 in weight is sufficient.

But more importantly, the line claiming _"...excluding people with visual disabilities..."_ is as provocative as it is dishonest, with no basis in fact.

> _<sub>Yatil:</sub>_    
> _How the APCA values convert to WCAG 3 ratings is not 100% clear to me.

And yet Mr. Eggert has refused multiple good faith attempts to discuss the basis of the ratings, and merits of providing different levels of conformance. If it is not clear to him, he is being obtuse, and actively resiting the work, including the updated documentation. We have offered these obstructionists zoom call discussions to answer questions and show the research and basis for the work—that they have ignored these good faith attempts speaks volumes.


> _<sub>Yatil:</sub>_    
> _The rating section in the draft (expand the “Rating for Luminance contrast between background and text” for more info) refers to the lookup table values and how you can not meet a number of them and still get a rating. (WCAG 3 aims to not have clear pass/fail criteria, but looser ratings, that give websites the opportunity to be a bit inaccessible and still conform to WCAG to a certain extent.)_

**Logical fallacies:** _appeal to ignorance, reciting facts not in evidence, hasty generalization, false equivocation, red herring, straw man, direct falsehoods._

Among the problems with WCAG&nbsp;2 is the lack of any guidance regarding minimum font sizes. Under WCAG&nbsp;2 you could have main content text at a size of 6px and still pass, despite being unreadable to most users.

But then Mr. Eggert claims that WCAG&nbsp;3 had "looser ratings", after earlier claiming that WCAG&nbsp;3 was "more complicated" and implying harder to pass. Well, which is it?

This leads into his assertion that _"...be a bit inaccessible and still conform to WCAG..."_ which is patently false. It is a provocative statement that Mr. Eggert has been repeating, but is very simply a lie. And again, conforming to WCAG 2 by the numbers has been shown to create actually inaccessible results. [WCAG&nbsp;2 contrast is weak](https://tangledweb.xyz/please-stop-using-grey-text-3d3e71acfca8), and does not support, much less mandate, actual accessibility. 47% of the color pairs that WCAG&nbsp;2 passes should fail under a properly developed system. A designer could follow WCAG&nbsp;2 and make a site pass by the numbers, yet be actually and factually inaccessible.

APC-RC provides for fewer color pairs in total than WCAG&nbsp;2, but all the color pairs under APC-RC are useable, while this is definately not tha case with WCAG&nbsp;2. Further, 22% or more of the color pairs WCAG&nbsp;2 _rejects_ are perfectly useable with the correct font weight, and provide for a better experience for color insensitive users. 

> _<sub>Yatil:</sub>_    
> _The – admittedly also draft – design and development information for ”Visual contrast of text” has little actually actionable information at this point: How do I choose colors? How do I make sure my design system complies? How do I measure the colors practically? It has some information on display color calibration and the environment, but in my opinion, those should be relevant for determining the contrast using the algorithm._

**Logical fallacies:** _appeal to ignorance, reciting facts not in evidence, Circular Argument, false equivocation, Red Herring, Straw Man_.

Mr. Eggert is directly relating to a very early draft guideline, yet at the time he wrote this opinion piece, the more complete guidelines had been in public beta for nearly a year. We made good-faith efforts to show Mr. Eggert the works in progress, yet Mr. Eggert refused any attempt to discuss the actual facts and guidelines, instead writing opinion pieces such as this that fully disregard the actual working guidelines that were being tested.

> _<sub>Yatil:</sub>_    
> _The APCA algorithm is changed occasionally (last in March 2021). It’s good that it adapts to new research, but it also means that you might use a color that is not sufficient by a later version._

**Logical fallacies:** _appeal to ignorance, reciting facts not in evidence, false equivocation, Red Herring, Straw Man._

The APCA algorithm was last modified February 15th, 2021. This is the version that has been in public beta, and **successfully used for three years** at this point. There are a few features we are going to _add_ in 2024/2025. Otherwise, the APC algorithm is stable and very useable, as it is based on, and references, decades of established, peer reviewed vision science.

> _<sub>Yatil:</sub>_    
> _This reads much more complicated to me, compared to the current way of using colors. It is probably more exact, but it trades off clarity. Designers might get to use orange and white, but there is an additional effort on how complicated it is to evaluate and describe accessible designs._

**Logical fallacies:** _appeal to ignorance, reciting facts not in evidence, false equivocation, Red Herring, Straw Man._

What does this paragraph even mean? How does APCA "trade off clarity" while being "more exact". This is another baseless logical fallacy intended to confuse not illuminate.

Designers can use some values of orange and white because this supports ***actual accessibility***, especially for those with color vision deficiency. WCAG&nbsp;2 does not support actual accessibility, and some of these color pairs it rejects does so [***at the expense of accessible design***](https://tangledweb.xyz/this-is-a-great-article-on-the-use-of-visual-contrasts-in-design-2063abbd66d9).

> _<sub>Yatil:</sub>_    
> _That trade-off might be totally worth it, but there are many questions that need to be answered between now and then._

**Logical fallacies:** _false dilemma, appeal to ignorance, reciting facts not in evidence._

What questions? And what does Mr. Eggert think was the reason we have an extended public beta period? 

**Here's the actual trade-off:** WCAG&nbsp;2 does not work, is harmful to readability, and designers do not use it. APC-RC works and provides substantial improvement to readability, using guidelines that have been tested and that provide useful guidance to designers, in the pursuit of actual accessibility and visual readability.

> _<sub>Yatil:</sub>_    
> _So, should you use APCA?_    
> _The answer is two-fold:_
>
> _For private, non-commercial projects: Sure, go ahead and apply it to the best of your knowledge. There are no restrictions on what you can do, and it might even inform future developments in WCAG._
> _For commercial and public projects: You are probably, through law or policy, required to conform to WCAG 2. That means you cannot rely on APCA for compliance (simply because it does not exist in WCAG 2)._

**Logical fallacies:** _appeal to fear, post hoc ergo propter hoc, appeal to ignorance, reciting facts not in evidence, false equivocation._

Among the canards asserted by Mr. Eggert and others of the obstructionist camp, are those relating to law. [WCAG&nbsp;2 is a voluntary guideline and not law](https://tangledweb.xyz/hi-simon-nice-article-thank-you-for-the-kind-words-2cf04fa5ef03). In 2021 when written, WCAG&nbsp;2 was not law in an absolute sense, there were some rare examples where legislatures copied from the WCAG&nbsp;2 SCs. Even today, many cite the EU's EN&nbsp;301, but this does not come into actual force until 2025, and then, not even full force until 2030.

In the USA, the US Access Board's 508 rules adopted the SCs from WCAG&nbsp;2.0 (but not later versions), but the 508 rules include clear exceptions, importantly, the "equivalent facilitation" rule, which clearly permits the use of improved guidelines such as the APC-RC.

> _<sub>Yatil:</sub>_    
> _WCAG 3 and the consensus process will probably mean that it takes another 3–5 years until WCAG 3 sees any release. And then WCAG 2 will be still enshrined into a lot of laws and policies. After all, WCAG 3 is a huge monolith of a specification, and the structure that the Working Group wants to use is very complex. You can read about it in the WCAG 3 explainer._

**Logical fallacies:** _False Dichotomy, Equivocation, Hasty Generalization, post hoc ergo propter hoc, reciting facts not in evidence._

This comment was part of the force that was used to halt development of WCAG&nbsp;3 and start again from scratch. Today, WCAG&nbsp;3 is an unknown distance in the future.

As a result of the problems that have arisen with WCAG&nbsp;3, the APCA is now being developed independently with the non-profit Inclusive Reading Technologies, Inc., to ensure that useable guidelines supporting actual accessibility are available.

> _<sub>Yatil:</sub>_    
> _In the meantime, WCAG 2 is there for you. Is it perfect? No. Is the luminosity contrast flawed? Pretty sure. But that should encourage us to take the time to make sure that we don’t make similar choices in WCAG 3. As I have outlined previously on this very blog, I don’t think WCAG 3 is necessary the silver bullet that we think it is._

**Logical fallacies:** _False Dichotomy , Equivocation, Hasty Generalization, post hoc ergo propter hoc, reciting facts not in evidence_.

We brought the problems of WCAG&nbsp;2 to the forefront in April of 2019 in GitHub WCAG issue thread #695. And we have been open about our research and development since that time. There is a discussion forum dedicated to contrast, color, and readability at the main APCA repository.


> _<sub>Yatil:</sub>_    
> _What is the way forward?_
>
> _I think exploring APCA and how it works with your particular color needs is a good first step, and the Accessibility Guidelines Working Group probably welcomes that feedback. If you use it, be aware that you might not conform to WCAG 2, and you cannot conform to WCAG 3 (as that does not exist yet)._

**Logical fallacies:** _False Dichotomy, Hasty Generalization_.

We are not presently concerned with WCAG&nbsp;3, but we are concerned with those that have been bullied into using WCAG&nbsp;2, despite the well known problems. This kind of gaslighting should not be accepted. The general tone has permeated this subject, with the take of "WCAG&nbsp;2 is bad but it's the only thing you can use" which is bizarre and not at all in touch with reality.

> _<sub>Yatil:</sub>_    
> _I’m very worried that some designers might think they should or can use the new contrast algorithm, and then accessibility consultants have to push back and clear up those misunderstandings. It takes up a lot of time, while accessibility consultants have their hands full already._

**Logical fallacies:** _equivocation (doublespeak), appeal to authority, false dichotomy (false dilemma), straw man argument, red herring_.


> _<sub>Yatil:</sub>_    
> _Additionally, it gives accessibility a bad reputation: “You can’t even agree on what colors we should use. Accessibility makes everything more complicated!”. This already is a common sentiment, and speculating what the future might be, based on an early working draft, will not help with it._

**Logical fallacies:** _straw man argument, begging the question (circular argument), post hoc "post hoc ergo propter hoc", red herring_.

The fact that WCAG&nbsp;2 promoted a contrast metric that was not peer-reviewed, not tested, and was even objected to back in 2007, is the source of any "bad reputation". The fact that we in the Visual Contrast group spent years developing a stable and useable guideline is not contributing to that bad reputation. Mr. Eggert's claim here is purely for the purpose if disparagement.


> _<sub>Yatil:</sub>_    
> _What if…?_
>
> _In an alternate universe, we would have a modular WCAG (similar to what CSS is doing) where every two years or so we package up new success criteria into a new version. It would have allowed different speeds for different SCs, and in this case, we might have a better understanding on what the way forward would be. And if our rating or evaluation guideline would change, the next version of that Success Criterion could address it._

**Logical fallacies:** _post hoc ergo propter hoc, appeal to ignorance_.

And yet, when that was proposed for WCAG&nbsp;3, it was shot down. This could be a valid concept, yet obstructionists put a stop to it.

> _<sub>Yatil:</sub>_    
> _That said, it is so easy to think in these inconsequential hypotheticals. The W3C consensus is that WCAG 2.2 is published some time next year. WCAG 3 follows when it’s done. It’s a long process, and we need to make sure all our i’s are dotted and the t’s are crossed. Let’s just make sure we don’t get ahead of ourselves and create confusion._

**Logical fallacies:** _bandwagon logical fallacy, slippery slope logical fallacy_.

How about focusing instead on creating sites that are actually accessible? How about that for a change? This "WCAG apologist" stance is untenable, if not actually harmful.

> _<sub>Yatil:</sub>_    
> ### _Addendum 2021-12-14_
>
> _Maybe the article did not make that clear: If you use a color that has enough contrast to the algorithm specified in WCAG 2 and the one that is maybe coming in the future, that is great, and it will give your color combination a certain longevity._
> _Combining both means cutting off obviously hard to read color combinations that are allowed under WCAG 2 while not venturing out of the color space WCAG 2 has inhabited. That means you raise your level of accessibility beyond the minimal requirements of WCAG 2. And that is awesome._

Okay, but the reality is that WCAG&nbsp;2 interferes with accessibility and creates confusion by rejecting useable colors that are preferred for accessibility reasons.

> _<sub>Yatil:</sub>_    
> ### _Update 2023-03-28_
>
> _WCAG 3 is still not ready. In fact, there haven’t been any meaningful updates to the draft since this article was initially published. The proposed charter for the WCAG WG has a completion date of Q2/2026, which is probably unrealistic. (Minor WCAG 2 updates took between 5 and 10 years, but now they want to create an entirely new standard with new testing requirements and documentation in three years?)_

**Logical fallacies:** _hasty generalization, post hoc ergo propter hoc, reciting facts not in evidence_.

First, obstructionists involved with AGWG ***blocked the updates to the WCAG&nbsp;3 draft*** that were presented as a pull request in June of 2022. This despite the fact that the pull request itself was peer reviewed and approved by the W3C technical director. This pull request was for the version and guidelines that were developed through the extended public beta.

The pull request was essentially what is the [APC-Readability Criterion](https://readtech.org/ARC/), and has ben in use as beta for over three years. It is not "entirely new" though it is a slightly different paradigm. And the Bronze Simple mode and BridgePCA modes are remarkably similar to WCAG2 in practice, but are substantially more supportive of actual accessibility.


## SIDEBAR: Organizational Politics
There is a small group of people obstructing the work toward actual accessibility as it pertains to readability. Mr. Eggert has visible ties that associate him with this group. Their underlying motivations are unclear, but there is definitely an element of toxic personalities surrounding this topic. 

The internal politics of the W3C's AGWG are an untenable and ongoing problem. In response, we founded the non-profit Inclusive Reading Technologies, Inc. The [APC-Readability Criterion](https://readtech.org/ARC/) is in public working draft, and provides solid and useful guidance for designers to ensure visual accessibility and improved readability for all users.

**Legislatures should be aware that WCAG&nbsp;2 is not fit for use in law or regulation**; as a voluntary guideline, the potential for harm is reduced, but when elevated to statute law, the potential for harm is exacerbated. The unfortunate part here is that the serious problems of WCAG&nbsp;2's contrast SCs cast a dark shadow on the rest of WCAG&nbsp;2.

### Don't be led astray, WCAG&nbsp;2.x SCs 1.4.3 & 1.4.11 are not fit for purpose.
WCAG 2's contrast math/methods do not support actual accessibility, and in fact can result in conditions that are worse for those with color vision deficiencies. The understanding docs of WCAG 2.x contain false or misleading information, and the premise lacks scientific support. 1.4.3 and 1.4.11 should not be incorporated into any laws nor regulations.

Moreover, a critical view of the actions here and elsewhere, clearly reveal a motivation to obstruct, with a darker purpose. This can not be allowed to stand. Fixing the significant problems of web content readability is one we take seriously, as is evidenced by our continued development of free-to-use guidelines and technologies.

Thank you for reading.

## Resources

For more background on APCA and Readability, you may find these links helpful:

- [Easy Intro to APCA](https://git.apcacontrast.com/documentation/APCAeasyIntro.html) a brief, easy to read intro to user needs for readability of digital content.
- [Myndex Linktree](https://linktr.ee/Myndex) a short curated list of key resources, tools, and documentation.
- [The APCA Discussion Forum](https://github.com/Myndex/SAPC-APCA/discussions) the discussion forum on GitHub, free to join in the conversation.


