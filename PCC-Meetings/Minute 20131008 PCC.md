** PCC Project Coordination Meeting Minutes**

* Meeting called by Klaus-Rüdiger Hase
* When: Tuesday, 8th of October, 13:00 - 16:00
* Where: Braunschweig, DLR-Location
* Minutes taken by Bernd Hekele
* Participants: 
  * AEbt: Merlin Pokam
  * All4Tec: Cyril Cornu
  * Alstom: Pierre-Francois Jauquet
  * CEA: Matthieu Perin, Virgile Prevosto
  * DB: Klaus-Rüdiger Hase, Baseliyos Jacob, Bernd Hekele 
  * DLR: Marc Behrens, Bernd Gonska
  * EclipseSource: Jonas Helming 
  * ERSA: Patrick Deutsch
  * ERTMS-Solutions: Stan Pinte
  * FormalMind: Michael Jastram
  * Fraunhofer: Jens Gerlach, Alexander Stante
  * General Electric: Giovanni Zanelli
  * IT-Telecom: Ana Cavalli
  * LAAS-CNRS: Silvano Dal Zilio
  * Lloyds: Jan Welvaarts
  * Mitsubishi Electric MERCE: David Mentré
  * NS-Rail: Jos Holtzer
  * Siemens: Gerhard Assmann, Uwe Steinke
  * SQS: Izaskun de la Torre
  * Systerel: Marielle Petit-Doche
  * TWT: Stefan Rieger
  * TU-Braunschweig: Jan Welte
  * Uni-Bremen: Cecile Braunstein
  * Uni Rostock: Alexander Nitsch

# Topics:
1. Welcome address / Objectives for this PCC Meeting
1. Wrap-up of ITEA2 review and recent activities in WP3 + WP7
1. Proposals for further actions
1. Decisions

# Findings:
Topics 1., 2. and 3. are covered by slides 1 - 13 of the [presentation](https://github.com/openETCS/governance/blob/master/PCC-Meetings/201310081255_openETCS-PCC_as.pdf)

### 4. Decisions
It was intended to vote on the decisions as a whole lot. However, in order to get an view on the acceptance of the individual decisions a walk thru the Decisions 3. - 12. was performed. The result of the decisions is documented in the rear part of this document.

After having seen some objections against parts of the proposal, the following conclusion was agreed on:

1. The document D7.1 was accepted as a document providing a good working base for the next steps. The goal of the document was accepted.

* In order to work on the gaps discussed during the PCC an Action Plan was agreed.
This Action Plan has the target 
 * to start  the openETCS Charta. Participants for the work group: ERTMSSolutions, CEA, NS, EclipseSource, Alstom
 * prepare the toolchain decision 

In the subsequent WP3 meeting(Braunschweg, 9th of October 2013) the start of WP3 owned System Analysis was confirmed. It was agreed to start a task force initiated by Alstom and with participation of all major players committing to contribute to the SysML Analysis with reasonable effort (Alstom, Siemens, DB, NS/LLRE and Systerel). The first workshop is scheduled for October 22nd - 25th)

### Results of walk thru the decisions:
* Decision 1: By vote in Paris on July 4th, 2013, all the partners agree on the use of Eclipse as tool platform.

  * Result: accepted, no objections, no abstentions
 
* Decision 2: By vote in Paris on July 4th, 2013, all the partners agree on the use Papyrus/SysML to cover the highest level of the OpenETCS V-cycle. Later it was clarified that it will be an original or bidirectional synchronized (but not a derived) artifact.

  * Result: accepted, 1 objections, no abstentions

NS/LLRE did not agree to the proposal. The difference in opinion can be seen as a different interpretation of the process.

* Decision 3: With input from WP2 and WP3, a WP7 will develop a validator for Papyrus-based SysML.

  * No objections, Abstention by 5 Partners (ERTMSSolutions, EclipseSource, Alstom, All4Tec, Systerel). Rest agreed.
 
* Decision 4: As the first tool chain release, WP7 will provide at a minimum a Papyrus SysML environment to WP3, under the assumption that this is suficient for WP3 to start modeling, until the final decision has been made (see Decision 5).

  * Result: accepted, no objections, 1 abstention (ERTMSSolutions)

* Decision 5: A final decision on the primary tool chain must be made by the end of January 2014. After this point, WP7 resources must not be spread between competing tools.

  * Discussion: an action plan is currently not visible to prepare for this decision and how we are going to proceed with this decision in January. Foundation of the plan has to be the openETCS Charta which needs to be started now to be available in January. The base for the charta is seen in the Eclips Way of Life.
 
  * Result: accepted, no objections, 2 abstention (ERTMSSolutions, Alstom)

* Decision 6: ERTMSSolutions activities will be coordinated with WP4, to support V&V activities (as these are modeling activities, they still belong in WP3). This issue must be raised and resolved with the PCC. 

  * Discussion: With this shift of resources resource allocation substitution of efforts by other partners is needed. The Doodle initiated with this query showed substantial indication  by DB, Systerel and Siemens to cooperate in WP3. 

However, the approach was not supported by a majority because of the missing charta in openETCS.

  * Result: not accepted, 2 objections, 17 abstention

* Decision 7: Unless new evidence is provided in agreement with Decision 5, SCADE will be considered the foundation for the primary tool chain. In that case, a feasible migration from what had been done with SCADE is essential.
 
  * Discussion: the term "evidence" is seen ambiguous and shall be removed.

  * Result: accepted, no objections, 5 abstention (ERTMSSolutions, EclipsSource, MERCE, Systerel, Alstom).
 
* Decision 8: Work on the tool chain must always take the objective of an OSS migration into account, e.g. by standardizing interfaces between tools. It is acknowledged that such a migration may not be feasible within the timeframe of the openETCS project. However, by the end of the project, feasibility of a migration must be demonstrated (e.g. with a prototype or case study). 

  * Discussion: Rephrasing the text was recommended in order to increase the understanding of the document.

  * Result: accepted, no objections, 2 abstention (ERTMSSolutions, Alstom)

* Decision 9: All openETCS project partners must be made aware of the need for acquiring a SCADE license (depending on their activities). If a partner feels that this is not achievable, this must be escalated to the project office by November 15, 2013. The project office will assist in finding a solution. If no solution has been found by January 31, 2014 for all partners who escalated, then SCADE will be abandoned for anything on the critical path of the tool chain.

  * Result: accepted, no objections, 3 abstention (ERTMSSolutions, AEbt, Alstom)

* Decision 10: According to the spirit of an open proofs project, team members are permitted to continue evaluating B, even with the objective of contradicting Decision 7. However, if unsuccessful by the deadline set by Decision 5, they must refocus either by contributing elsewhere, or by focusing on the transition to OSS, as outlined in Figure 57. The team is strongly encouraged to coordinate with POLARSYS.

  * Discussion: The proposal is seen to special. A more general recommendation is requested. 
  * Result: accepted, 2 objections (LLRE, Alstom) + 5 abstentions.

* Decision 11: WP4 is going to consider the artifacts of "SysML+ SCADE" tool chain for the first round of verification and validation launched in July 2013.

  * Discussion: The proposal is seen to special. A more general recommendation is requested. 
  * Result: accepted, no objections + 1 abstention (ERTMSSolutions).

* Decision 12: For the following rounds, starting in February 2014, WP4 will adapt the verification and validation activities to the models and code provides by WP3.


* Decision on D7.1 as a complete package:
  * Result: accepted, no objections, 5 abstention (ERTMSSolutions, NS, LLRE, Systerel, Alstom).
