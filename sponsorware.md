# Sponsorware 

> This document is an exploration of how a sponsorware model could work for Hivemind, it is not final and might not happen at all if I change my mind

Implement a community funding system where users can donate directly to the project in exchange for:

- Special badges or recognition
- Early access to new features
- One-on-one consultations with developers
- Influence project's direction
- Priority bug fixes

## Terms

- Public/Main branch of the project (the `main project`) under a permissive license (the `permissive license`)
- "Insiders Edition" of main project (`I.E.`) under a strong copyleft license like AGPL (the `copyleft license`)

## Licensing

- the `permissive license` - the `main project` is licensed under a permissive license such as Apache or BSD-3
- the `copyleft license` - the `I.E.` is licensed under strong copyleft such as AGPL or other FOSS but restrictive license (from a commercial POV)
- once code from `I.E.` is merged into the `main project` it changes from the `copyleft license` to the `permissive license` 
- BSD-0 clause license (or other that doesnt even require attribution) can be requested via sales@email.com
- We kindly asked that source code from `I.E.` is not released to the public, the `copyleft license` allows it and this is nothing more than a gentlemans agreement.
- If you are caught leaking source code access to `I.E.` will be terminated and you will no longer have access to future updates (you remain able to exercise the freedoms granted by the `copyleft license`)


## Funding Goals

the `I.E.` defines various funding goals

- Goal to start working on a feature:
  - A funding target is defined, once reached the feature will start being worked on
  - This ensures the developer can allocate time to work on the feature  
- Goal to move from `I.E.` to `main project`:
  - Once features are mature and fully implemented a funding target is defined to make them fully permissive
  - This allows the developer to monetize the feature before losing the business edge of dual licensing
- Stretch Goals:
  - Offer stretch goals once the primary funding target is reached. 
  - These could be additional enhancements or improvements to the feature being worked on.

## Voting Benefits

- Feature requests should be done by the regular channels in the `main project`:
  - members of the `I.E.` can request and then vote for a feature request to be added to the current or next funding goal 
  - this allows members to influence what gets prioritized and worked on
  - Make voting transparent by displaying the number of votes each feature request has received. This encourages healthy competition and helps prioritize features democratically.
- Exclusive features:
  - the `I.E.` may also include exclusive features in the form of plugins or companion apps,
  - members can request and then vote for an exclusive feature to be added to the `main project` funding goal
  - exclusive features should **never** be core to the functionality of the `main project`


## Sponsor Tiers

- To ensure fairness, consider implementing a reputation system where users earn points or badges based on their contributions which then determines their voting power.
- Allow users/developers to earn points by contributing in non finantial ways (e.g., bug reports, translations, documentation updates, code reviews)
- Sponsors can donate monthly any amount they want, this should translate into earning points proportionally to the donation value
- A maximum ceiling for points is needed to ensure throwing more money at the project doesn't allow you to take over the development direction

