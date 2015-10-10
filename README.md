# Final Year Project Ideas
Ideas for final year projects that I'd be keen to advise

- Implementing a new AI system for the [Battle for Wesnoth](http://www.wesnoth.org) game, they seem to have a [tutorial for customising the AI](http://wiki.wesnoth.org/Customizing_AI_in_Wesnoth_1.8) (hopefully better than the one from a few years ago).
   * Using reinforcement learning
   * Connecting it to an AgentSpeak(L) interpreter like [Jason](http://jason.sf.net)
   * Using some kind of automated planner
- Implementing an HTN planner (from scractch, in Java or Python) that accepts these formalisms:
   * [JSHOP2](https://sourceforge.net/projects/shop/files/JSHOP2/)
   * [SHOP2](https://www.cs.umd.edu/projects/shop/)
   * [PDDL Tasks](http://ipc.informatik.uni-freiburg.de/PddlExtension) - this is optional but pretty cool
- Implementing an [HGN planner](http://www.aaai.org/ocs/index.php/IJCAI/IJCAI13/paper/view/6839)
- Implementing an [AgentSpeak(L)](http://www.upv.es/sma/teoria/teoria_ag/agentspeakl/agentspeakl-rao.pdf) interpreter in Python
- Reimplementing the core of the [Jason](http://jason.sf.net) interpreter using a micro-kernel architecture that allows network-based debugging
- *Fancy UI for Jason:* Integrate some fancy UI engine into an agent programming platform, for example, the [Mason framework](http://www.cs.gmu.edu/~eclab/projects/mason/)
- *Normative Gold Miners:* Implement and evaluate a variation of the gold miners simulator with a parameterisable norm monitor so that certain norms can be specified as well as a customisable norm detection mechanism
- *Integrating Jason with a Visualisation Tool:* Assuming [DIVAs](http://mavs.utdallas.edu/projects/divas) is open in some way (it does not look like it at this point), integrate the Jason interpreter in it to do norm based behaviour simulation.

## Current and past projects

- [ ] Implementation of mini BDI interpreter in LUA
- [ ] Implementation of [HTN-based planning](http://dl.acm.org/citation.cfm?doid=1558109.1558167) into AgentSpeak
- [x] Application of Reinforcement Learning to a [bomberman implementation](http://bombermaaan.sourceforge.net)
- [x] Implementation of [artifact-based](http://jacamo.sourceforge.net) [components for robot control](https://github.com/lsa-pucrs/jason-ros)
- [x] Implementation of a search-based planner
- [x] Implementation of otimization techniques to the [JavaGP](http://emplan.sf.net) version of Graphplan 


## To do
- [ ] Improve this document with further details for some of these projects
- [ ] Separate some of the projects into different files or folders
