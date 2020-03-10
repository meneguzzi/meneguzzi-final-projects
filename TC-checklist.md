# Checklist for final year projects and integrating course

The following checklist applies to both Computer Science (Ciência da Computação) and Information Systems (Sistemas de Informação). Do not forget to read my [tips on writing good science](http://www.meneguzzi.eu/felipe/writing.shtml), and double check the [rules for writing the final projects](https://moodle.pucrs.br/pluginfile.php/2799621/mod_resource/content/4/Normas%20TCC%20ap181.pdf). 
Since I want all academic documents written in LaTeX, please use this handy [template for final year projects](https://bitbucket.org/mflash/ep-tcc/src/master/). 
If you don't know anything about LaTeX, I suggest you check out this [Quick tutorial on LaTeX](https://github.com/VoLuong/Begin-Latex-in-minutes) available on Github.
Finally, besides the specific points I make in this checklist, be mindful of the following quality items for anything scientific you write:

- [ ] Figures and Tables must always have a numbered caption and be referenced in the text. A Figure may be worth a thousand words, but it must be described in a couple of dozen to make sense in the text. 
- [ ] Level of detail: when talking about multiple subjects in a section, be sure to use a consistent level of detail. It reads very poorly if you describe a certain technique in a three-sentence paragraph while put the code in C for another technique in the same section.
- [ ] Arguments and citations: any objective statement (which ought to be most of your text) you write in your text must be backed either by your own work (self-contained) or by a citation to somebody else's peer-reviewed work. Be very careful about statements of the type '*Algorithm X and Y are the most widely used for frombotzing deterons*'



## Final project proposal

The text you deliver as a proposal at the beginning of the semester must clearly outline what you want to *study* throughout the semester. You do not necessarily need to have a specific problem set out yet, but you must know clearly what is the general area in which you want to solve a problem, and show that you have used the first month to read about it. This is what I expect of the text my students hand in:

- [ ] Abstract: the abstract must answer the following questions
	- [ ] What is the problem your project aims to address?
	- [ ] Why is this problem interesting?
	- [ ] How do you aim to solve the problem?
	- [ ] What follows from your solution?
- [ ] Table of Contents
- [ ] Introduction: check the introduction 
	- [ ] Avoid jargon <br/> Do you avoid jargon that is only explain in the rest of the text?
	- [ ] Clarity <br/> Can anyone from computer science read the introduction and understand what's the objective?
	- [ ] Does it clearly describe the problem?
	- [ ] Does the introduction clearly state the contributions?
- [ ] Literature Review: the literature review is meant to convey your knowledge of the subject matter of the proposal, so check for
	- [ ] Does it provide basic definitions of the area?
	- [ ] Terminology dropping from the sky <br/> new technical terms must be explained before they are used, avoid talk about a deteronic frombotzer if you have not said what this is
	- [ ] Consistency of terminology  <br/> do not use different terms to refer to the same technical entity, once you define something as X always refer to it as X
	- [ ] Are the references up to date <br/> i.e. do you cite work that was published in the last 5-10 years
- [ ] Objectives: this is the objective of your design, it will generally focus on studying something to plan for its implementation
	- [ ] General objective <br/> i.e. a brief statement of what it is you want to accomplish
	- [ ] Specific objectives <br/> i.e. a list of concrete goals (you can think of them as 'deliverables')
- [ ] Work plan: 
	- [ ] Real timeline <br/> Does it contain work for all months of the work? Do not count the month you wrote this.
	- [ ] Realistic plan <br/> Avoid doing too many actions in the same month
	- [ ] Achievable plan <br/> You must be able to deliver what you said you would
	- [ ] Avoid copying specific objectives <br/> but the work to reach them can drive this timeline
- [ ] Bibliography: check the bibliography for the following items
	- [ ] Are all references rendering correctly with BibTex (check for foreign language characters and odd symbols)?
	- [ ] Are all references correct? Remember DBLP, ACM, Google Scholar and other automated databases **do** contain errors
	- [ ] Are any important references missing?
	
## Final project I / Integrating Course III (Project Design)

The text you deliver at the end of TC1 is a much expanded version of your plan, but here, you must have a clearly defined problem you will solve, and concrete plans of how you will spend the following semester solving it. 
The resulting text must include almost all of the following items:

- [ ] Abstract: the abstract must answer the following questions
	- [ ] What is the problem your project aims to address?
	- [ ] Why is this problem interesting?
	- [ ] How do you aim to solve the problem?
	- [ ] What follows from your solution?
- [ ] Table of Contents
- [ ] Glossary/Abbreviations (if your work is acronym heavy)
- [ ] Introduction: check the introduction 
	- [ ] Avoid jargon <br/> Do you avoid jargon that is only explain in the rest of the text?
	- [ ] Clarity <br/> Can anyone from computer science read the introduction and understand what's the objective?
	- [ ] Does it clearly describe the problem?
	- [ ] Does the introduction clearly state the contributions?
- [ ] Literature Review Chapters: are meant to convey your knowledge of the subject matter of the proposal, so check for
	- [ ] Is the literature review substantially improved from the proposal?
	- [ ] Balanced chapters/sections <br/> the review chapter can be divided into multiple chapters, make sure subjects are well balanced in the chapters
	- [ ] Basic definitions <br/> Does it provide basic definitions of the area?
	- [ ] Terminology dropping from the sky <br/> new technical terms must be explained before they are used, avoid talk about a deteronic frombotzer if you have not said what this is
	- [ ] Consistency of terminology  <br/> do not use different terms to refer to the same technical entity, once you define something as X always refer to it as X
	- [ ] Are the references up to date <br/> i.e. do you cite work that was published in the last 5-10 years? It's Ok to cite older work, but if you only do this, everyone will question the novelty of your topic
- [ ] Objectives: now you should know your stuff, so you must be clear about what is it that you will deliver at the end of the next semester
	- [ ] Overall objective <br/> i.e. a brief statement of what it is you want to **deliver**
	- [ ] Specific objectives <br/> i.e. a list of concrete goals as you move towards your overall objective, these are now 'deliverables'

## Final project II / Integrating Course IV (Project Implementation)

The text you deliver at the end of the final project II must show that you are able to apply what you learned throughout your undergrad course to solve a concrete problem. You must convince the reader that you are capable of digging deeper into a CS subject and then use this to solve a problem. The resulting text must contain: 

- [ ] Abstract: the abstract must answer the following questions
	- [ ] What is the problem your project aims to address?
	- [ ] Why is this problem interesting?
	- [ ] How do you aim to solve the problem?
	- [ ] What follows from your solution?
- [ ] Table of Contents
- [ ] Glossary/Abbreviations (if your work is acronym heavy)
- [ ] Introduction: check the introduction 
	- [ ] Avoid jargon <br/> Do you avoid jargon that is only explain in the rest of the text?
	- [ ] Clarity <br/> Can anyone from computer science read the introduction and understand what's the objective?
	- [ ] Does it clearly describe the problem?
	- [ ] Does the introduction clearly state the contributions?
- [ ] Literature Review Chapters: are meant to convey your knowledge of the subject matter of the proposal, so check for
	- [ ] Self-containment <br/> Is the literature review enough to understand how you solve the problem?
	- [ ] To the point <br/> Do you have content that is not really relevant for the work? You may need to remove stuff from the material you wrote before to match the problem you actually solved
	- [ ] Balanced chapters/sections <br/> the review chapter can be divided into multiple chapters, make sure subjects are well balanced in the chapters
	- [ ] Basic definitions <br/> Does it provide basic definitions of the area?
	- [ ] Terminology dropping from the sky <br/> new technical terms must be explained before they are used, avoid talk about a deteronic frombotzer if you have not said what this is
	- [ ] Consistency of terminology  <br/> do not use different terms to refer to the same technical entity, once you define something as X always refer to it as X
- [ ] Implementation/Development: here you should describe the details of your contribution so that others can replicate it. Check for
	- [ ] Replicability: is there enough detail that one of your colleagues can replicate your work **without looking at your code**?
	- [ ] Internal consistency: is the terminology and technical concepts used here consistent with what you defined in the literature review?
- [ ] Evaluation: for works with an empirical evaluation component. Check for
	- [ ] Environment description: do you clearly describe your testing rig? 
	- [ ] Results: do you include an objective description of your results (tables, graphs, et)?
	- [ ] Assessment: do you explain the meaning of the results and the implication of them to the problem?
- [ ] Conclusion: here, you summarize what are your contributions and how you envision them going forward
	- [ ] Contributions: what did you achieve in this work?
	- [ ] Limitations: what are any problems or limitations to your contribution?
	- [ ] Future work: what can be done to improve your work?
	

## Final project proposal (Computer Engineering)
TBD

## Final project (Computer Engineering)
TBD
