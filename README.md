# Final Year Project Instructions

## Checklist for the projects

You can find a [Checklist for Final Year Projects](TC-checklist.md), which includes things I expect you to check before handing in the written from.
If you are working with me, you will need to write in [LaTeX](http://www.latex-project.org), and [here's a good place to start](https://github.com/VoLuong/Begin-Latex-in-minutes).

## Projects I'd like to do now

- [ ] Implementation of a [Natural Deduction](https://en.wikipedia.org/wiki/Natural_deduction) proof generator for [propositional logic](https://en.wikipedia.org/wiki/Propositional_calculus), and hopefully eventually for [First-order Logic](https://en.wikipedia.org/wiki/First-order_logic) to automatically generate exercises for Logic for CS. The likely approach for this one would be to use search (perhaps heuristic) together with some kind of proof assistant to check the generated proofs (e.g. [JAPE](https://github.com/RBornat/jape)) This software could gauge the difficulty of proofs based on the number of hypotheses, complexity of the deduction rules, or length of the proof -- **Keywords:** Logic, Search
- [ ] Implementation of an HGN planner using a formalism like [GoDel](http://www.aaai.org/ocs/index.php/IJCAI/IJCAI13/paper/view/6839), ideally with [Heuristics for HGN Planning](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14979/14175), and [cost-optimality guarantees](https://www.knexusresearch.com/wp-content/uploads/2016/07/shivashankar16hopgdp-preliminary.pdf)  -- **Keywords:** Automated Planning, Hierarchical Planning
- [ ] Implementation of an HTN planner in Python capable of planning for both the [SHOP](https://github.com/shop-planner)/[JSHOP2](https://github.com/mas-group/jshop2) formalism and the more recent [HDDL](https://github.com/panda-planner-dev/pandaPIparser) formalism used in the [HTN IPC](http://gki.informatik.uni-freiburg.de/competition/). The implementation can either be a compilation technique, like our [HyperTensioN](https://github.com/Maumagnaguagno/HyperTensioN) planner, or remain completely internal implementation based on our [PDDL parser](https://github.com/pucrs-automated-planning/pddl-parser) -- **Keywords:** Automated Planning, HTN
- [ ] Deploy various models of machine learning to process neuroimaging data (in cooperation with [InsCer](http://inscer.pucrs.br/)), including:
	- [ ] fMRI fingerprinting -- **Keywords:** Neuroscience, Deep Learning
	- [ ] Autogeneration of fMRI paradigms using [Psycopy](https://www.psychopy.org) and automated planning **Keywords:** Neuroscience, Deep Learning
- [ ] Train reinforcement-learning based agents to play games in environment labs such as:
	- [ ] [OpenAI Universe](https://openai.com/blog/universe/) **Keywords:** Reinforcement Learning, Deep Learning, Game AI
	- [ ] [DeepMind Lab](https://github.com/deepmind/lab) **Keywords:** Reinforcement Learning, Deep Learning, Game AI
	-- **Keywords:** Reinforcement Learning, Deep Learning, AI for Computer Games
- [ ] Implementation of a heuristic planner for [incomplete PDDL domains](https://www.sciencedirect.com/science/article/pii/S0004370216301539) in Python -- **Keywords:** Automated Planning
- [ ] Implementation of a [fragment of the PRS interpreter](http://eprints.nottingham.ac.uk/52959/) using Python -- **Keywords:** Multiagent Systems
- [ ] Implementation of a MultiAgent Planner using a [Graphplan](https://github.com/pucrs-automated-planning/javagp) base code -- **Keywords:** Automated Planning, Multiagent Systems
- [ ] Implementation of [HTN-based planning](http://dl.acm.org/citation.cfm?doid=1558109.1558167) into AgentSpeak -- **Keywords:** Automated Planning, Multiagent Systems
- [ ] Implementation of the [CANPLAN semantics](http://dx.doi.org/10.1007/s10458-010-9130-9) using an AgentSpeak-like syntax - -- **Keywords:** Multiagent Systems

## Other Ideas for new projects
Ideas for final year projects that I'd be keen to advise

- [ ] Implement a new AI system for the [Battle for Wesnoth](http://www.wesnoth.org) game, they seem to have a [tutorial for customising the AI](https://wiki.wesnoth.org/Creating_Custom_AIs) (hopefully better than the one from a few years ago).
   * Using reinforcement learning
   * Connecting it to an [AgentSpeak(L)](https://github.com/lsa-pucrs/AgentSpeakPy) interpreter
   * Using some kind of automated planner
- [ ] Implement a level generator for [Super Mario](http://mario-builder.en.uptodown.com/windows) type games backed by a planning system (to design achievable levels) in a similar way to generating narratives automatically
- Implement an HTN planner (from scractch, in Java or Python) that accepts these formalisms:
   * [JSHOP2](https://sourceforge.net/projects/shop/files/JSHOP2/)
   * [SHOP2](https://www.cs.umd.edu/projects/shop/)
   * [PDDL Tasks](http://ipc.informatik.uni-freiburg.de/PddlExtension) - this is optional but pretty cool
<!-- - *Normative Gold Miners:* Implement and evaluate a variation of the gold miners simulator with a parameterisable norm monitor so that certain norms can be specified as well as a customisable norm detection mechanism 
- Compare agents implemented using the [Profeta Python](https://github.com/corradosantoro/profeta) BDI engine with traditional approaches -->
- [ ] Competitively try to play [VizDoom](http://vizdoom.cs.put.edu.pl/tutorial)

<!-- - Reimplement the core of the [Jason](http://jason.sf.net) interpreter using a micro-kernel architecture that allows network-based debugging-->
<!-- - *Integrating Jason with a Visualisation Tool:* Assuming [DIVAs](http://mavs.utdallas.edu/projects/divas) is open in some way (it does not look like it at this point), integrate an agent interpreter in it to do norm based behaviour simulation. -->

## Current projects

- [x] Implementation of a machine learning filter for [arXiv](https://arxiv.org/list/cs.AI/recent) [daily feed](https://arxiv.org/list/cs.AI/pastweek?show=94) based on affinity with past publications. This idea was inspired by the [Toronto paper matching system](http://torontopapermatching.org/webapp/profileBrowser/about_us/) used by conferences to select papers. This is rather similar to the existing [ArXiV-Sanity](http://www.arxiv-sanity.com) -- **Keywords:** Deep Learning, NLP - Débora Pires
- This could be **you**

## [Past projects](Projects.md)

- [x] Implementation of a text summarization technique using deep recurrent neural networks and [sentence to vector embeddings](https://github.com/epfml/sent2vec) - Maurício Steinert
- [x] Implementation of a [planning-driven game playing agent](http://www.dtic.upf.edu/%7Ehgeffner/nir-ijcai-2015.pdf) that interprets the state by learning a neural network-based transition function - Raphael Baldi
- [x] Implementation an [AgentSpeak(L)](http://www.upv.es/sma/teoria/teoria_ag/agentspeakl/agentspeakl-rao.pdf) interpreter in Python - André Leonhardt
- [x] Implementation of mini [BDI interpreter in Python](https://github.com/lsa-pucrs/AgentSpeakPy)
- [x] Implementation of [Adversarial HTN planning for RTS games](http://ijcai.org/Proceedings/15/Papers/236.pdf) - Matheus Redecker
- [x] Implementation of [Montecarlo based game search for Settlers of Catan](http://ticc.uvt.nl/icga/acg12/proceedings/Contribution100.pdf) - Gabriel Rubin e Bruno Paz
- [x] Implementation of a bot for [Spelunkbots](http://spelunkbots.com) - Martin Móre e William Martins
- [x] Implementation of mini [BDI interpreter in LUA](https://github.com/elite5472/turtleai) - Guillermo Borges
- [x] Application of Reinforcement Learning to a [bomberman implementation](http://bombermaaan.sourceforge.net) - Leonardo Amado
- [x] Implementation of [artifact-based](http://jacamo.sourceforge.net) [components for robot control](https://github.com/lsa-pucrs/jason-ros) - Thales 
- [x] Implementation of a search-based planner - Maurício Magnaguagno
- [x] Implementation of optimization techniques to the [JavaGP](http://emplan.sf.net) version of Graphplan - Ramon Pereira e Fernando Giroletti


## To do
- [ ] Improve this document with further details for some of these projects
- [ ] Separate some of the projects into different files or folders
