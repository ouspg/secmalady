These are persistent notes of the [OUSPG open](https://github.com/ouspg/ouspg-open) review of [Pekka Tetri's secmalady](https://github.com/ouspg/secmalady/blob/master/researchplan) Ph.D. research plan on [etherpad](http://muistio.tieke.fi/p/secmalady) [8 reviewers]

> == Research Plan ==
>
> OUTDATED - see attached file for the latest version.

 * q?

 * meta discussion about the research experiment for the last paper

# Abstract

> just to new few

 * new -> name?

>  some would like to argue they enable them

 * sure? "information security enables them"?

>  We argue that informatn security cannot be fully understood, unless a serious attempt to look at it as an entity is undertaken.

 * Do you mean "information security" as a topic, or rather "the security of information systems"?
 * typo: informatn

> We argue that informatn

 * typo

> we argue it is vital to understand the entirety of how information security is done, so we can analyse it

 * "it is vital to understand the whole implementation - including security controls/measures/...." ?

> We reviewed several different topics and their research and came to a conclusion that lots of the underlying cornerstones go unchallenged. Our aim is to give it a new reading, analysis and further research based on those analyses.

 * This sounds like the beef so should be lazer sharp? Attempt: "After reviewing relevant research, we conclude that lots of the underlying cornerstones go unchallenged. We will ... <not sure I understand rest of the sentence>"


> We argue, that information security should be looked from the view of what it does – which has largely gone unnoticed – and the way increasing complexity might, under certain circumstances, make systems, or data, less secure.

 * Break the complex sentence?
  * :+1
 * Further more "what it does" is rather abstract
  * Maybe: "We argue, that actual impact of the information security should be studied. How the subject to be protected is impacted has largely gone unstudied. Studying the actual impact may expose issues such that the increasing complexity introced by information security measures might, under certain circumstances, make systems, or data, less secure."

>  Essentially, if the target system is complex enough, it is difficult to defend against unauthorized users.

 * The more complex the system is, the more difficult it is to defend against..

> (lisää liite)

 * viite?

> What does normal network traffic look like.

 * questionmark ?

> but the concept of normal/abnormal is a key concept.

 * reduntant use of concept? "key concept is normal vs abnormal" ?

> Our concept has far reaching ramifications; we are excluding users, code, hardware from the space of normalcy, so the power of information security research is far reaching.

 * more redundancy ... _far reaching ... is far reaching_

> Throughout this research, we consider all parts of information security as mere actors, or components of a larger machine that does security.

 * as  a first time reader this strikes a bit off, as in my world security is built-in to processes. There is no separation of a machine which produces
    the value and a machine which does the security (on top of it)
 * Should be stated, I might be just on wrong abstraction level, your sentence could be valid when viewing trough another lense
 * To beat the dead horse: lets think of a table. There is nothing special in it that "does not breaking of the table". It is built the we it is as robust as possible.

> We do not seek to argue against the goal, however, we intend to show its means of achieving the goal to be often paradoxical, and often causing completely new problems that escape, as practitioners and researchers alike seek to create a more secure digital world.

 * Break complex sentence
 * Are you saying: "we intentd to show that attempts of achieving the goal may actually worsen the situation"?  
 * Or alternatively, "the means of achieving one goal jeapordise another" (implementing means to protect confidentiality weaken the availability)?


 > We see this as a good starting point, as it seems to be a popular topic, and yet we know very little about it

  * Does this mean: The world knows or  The author knows ?
  * Based on background conversations i would bet the first. Maybe worth clarifying?

> Starting from ”the human factor” also provides us an opportunity to contribute to the body of knowledge, which is not large at the moment.

 * Answer to the previous point seems to be on the following sentence. I would still clarify the previous sentence.

> If social engineering is the biggest problem in information security

 * Is "human factor" 100% about social engineering? OR is the traditional malicious employees FUD included as well?

> We argue, that adding more information security does not necessarily result into a more secure environment.  
  * "adding more information security is sometimes counterproductive"?

> But, attackers evade controls, dupe users, and simply take advantage of an opportunity, it follows that we need to include people as well.

 * take an opportunity <-> people link weak? How about "...any opportunity, including humans,...." etc?

 > Fourth, we will seek to understand the technology itself; is more security technology always better?

  * This  has been already presented (we argue, that adding more information security...)

>  is it conceivable to go with a single solution for singular view

 * Hmm, depends a bit what you mean with the "view" - but
   * if you refer to technical means to defend a system, the "views" is not the only thing to cover, how about "controls"?
   * if you mean in more high level - "approach" - one approach would be to stack up a number of technical controls and views
   * confusion arises

>"Detecting a possible attacked"

 * Unsure of what this is supposed to be
 * _attack_?

> ...empirical evidence in SE stud- ies and the...

 * -> studies
 * Multitude of copy-n-paste resulting in similar problems

## Security controls as obfuscators for detection (work in progress, help needed!)

 * Some technical metrics from chosen black boxes? "Ports open on box / number of protocols supported",
 * http://www.digitalbond.com/blog/2011/01/18/ms-attack-surface-analyzer-my-first-take-and-why-you-should-know-about-it/
 * Large number of AV bugs from google project zero are a good motivator

## Social Engineering

  * Organization's / society's role ... complex processes are more prone to hacking?
