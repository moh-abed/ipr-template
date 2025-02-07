# Architecture Council Review Name

This template provides standard sections we imagine are relevant to all ACRs, references to supporting assets to help with discovery, and pointers to help you along the way. We’d appreciate you trying it out and iterating on the format as the use of a templated layout will make data discovery easier to automate.

Delete all informational parts when issuing your ACR.

---
### Date - e.g. 2pm 21st July, 2018 

- Complete this before you hold the ACR so that interested parties can attend or request an invite.
- Remember to announce in slack - #architecture-council

---
### Summary

Provide a few paragraphs summarising the ACR including a summary of the context, problem, and constraints. This should allow someone familiar with the space to understand what the decision is about.

Whilst it's crucial to provide the business context and use cases in this section, as well as highlighting constraints, this is a scene setting exercise and detailed explanations are provided below. 

---
### Outcome

Once the ACR has concluded update this summary to include the outcome.

This section should be brief – no more than 3-4 paragraphs (150 – 300 words).

---
### Decision Maker

The individual or individual(s) who will decide the ACR outcome. A team is NOT a Decision Maker.

The Decision Maker might not be the ACR author but is one of the Interested Parties and will be present at the final meeting.

The Decision Maker is responsible for ensuring that the Interested Parties (Consulted) and Informed sections of the ACR are filled out and are exercised.

---
### Interested Parties

List of interested parties. These are the people Consulted to ensure the proper supporting data exist.

At a minimum this should include the teams but prefer a list of individuals.

---
### Domains

Highlights of the ACR decision from 20,000 feet e.g. PII, CI, Platform, Tradie, Subscriptions, etc. Think about hipages domains and how your solution touches any of these. You should consult any owners of domains that aren't owned by the decision maker's team. 

---
### Informed

Who needs to hear about this decision as it progresses and once it's made? People listed here are optional in the room.

Consider:

- Guilds
- People in other teams that do similar things
- Platform Product teams - especially if you believe that the existing product doesn't match the ACR needs

---
## Context

Describe why you are solving the problem and what the problem is. This should take into account the customer/user problem being solved, the business context, and the like. It should also talk about the technical context the solution space exists within.

This is usually where you talk about the particular project and value being added as well as describe any current systems that are relevant. Defining goals in measurable terms will greatly aid future review of the ACR outcome.

As you consult various interested parties include any insights gained. It might benefit those reading to note when the conversation occurred, who was present, and what was discussed. If any options are no starters, then briefly describe these (rather than cluttering the options section with non-genuine options).

Provide references to any related documents.

---
## Constraints, Assumptions, Risks

Describe any constraints, assumptions, or risks influencing the decision. Consider impacts of risks in both a technical (Access, Availability, Agility, Accuracy) and operational (Financial, People, Suppliers/External) context. Use a single list of separate subsections as you see fit. These could include things like:

- A competitor has shipped a similar product and time to market is key to avoid consumer migration and lock in;
- The team has no experience with technology xyz before;
- A data migration must occur without any operational systems experiencing downtime;
- Highly sensitive data is being transmitted therefore security oversight is critical.

During the review be prepared to challenge the constraints and/or consider risk mitigation approaches through the options.

---
## Plan / Options

Outline a number of available options and provide an assessment of the relevant trade-offs. Consider operational factors, privacy, SLAs, cost to build and maintain, disaster recovery, failure modes.

Diagrams are great in this section.

This is traditionally provided as a list of pros and cons but can take any format that works. Ensure option consideration includes identification of risk. 
Note that you might be conducting an ACR to endorse a particular plan or approach - i.e. validating one path forward rather than choosing between options. In this case you would outline research that has led to this point.  The constraints etc section would also support that choice.

---
## Outcome

Attendees: List of those at the meeting including who they represent.
Apologies: List of those who could not make it.

Once the ACR has concluded, in addition to updating the summary with the decision, outline which decision was chosen and why.

Include any acknowledge consequences and/or risk mitigation steps. This should include an assessment of impact on system health.

