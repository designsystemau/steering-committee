# December 15, 2021 - Meeting Notes

**Faciliators:**

| Name | Abbreviation |
| - | - | - |
| Dominik Wilkowski | DW |
| Esther Semo | ES |
| Matt Sawkill | MS |
| Elise Chant | EC |

## Resources

- [Slides](assets/slides-steering-committee-2021-December-15.pdf)
- [Survey Summary Results](assets/survey-results.pdf)
- [Survey Full Results](assets/survey-results-full.csv)

## Prior

* Maintainers have read proposed RFCs

## Survey findings

* MS to present

Meeting notes:
* Full findings and results are in GitHub
* 60% of respondents had used the system
* Majority people who had used website were in gov, but some interesting edge cases
* 50% respondents located in Sydney, 20.6% in ACT and
* 47% respondents in design role (UX, UI, Accessibility) and 28.6% in development roles
* Features respondents found most useful: accessibility and components
* Features that could be improved: pattern library and more components
* The support services respondents previously relied on: CoP and Documentation
* Other design systems being used: NSW Gov DS, Bespoke DS +
* Many are using a fork of AuDS - we need this to be fed back to us
* Barriers to using GOLD: Lack of ongoing support, Lack of DTA endorsement

## Prioritisation of actions related to survey findings

* MS to present

Meeting notes:
* Raise awareness of Slack/Slack as our CoP
* Improve Docs (and publicise that work)
* Tools for Designers
* Fix open bugs (evidence of support)
* Roadmap for pattern library
* Roadmap for new components
* Get external work back into main
* Local community meetups?

## Maintainers commitments

* DW to present 
  * Min time spend
  * 4 Steering Committee meetings / year
  * Active engagement with project

Meeting notes:
* **Becoming a Maintainer:**
  * We need to officialise who is a maintainer
  * Being a maintainer means: there is a time commitment inclusive of attendees at quarterly meetings, you'll need to submitting/ commenting on RFCs and Implementing RFCs

* **Maintainers from meeting:**
  * Anthony Dann: Product Owner for Queensland Health Design System (based on the DTA)
  * Simon Victory -React Developer, accessibility
  * Berin Denham - Experience in UX, accessibility, dev,
  * TJ Harrop - Happy to help where it’s needed from:
    - design/dev overlap or process
      - DesignOps``
      - front-end tech
      - design tools
      - UX
      - Also in a good position for any gold/NSW collab so happy to help with that too
  * Elise - dev, tech
  * Liam Fiddler - Dev/design (4/1 split)
  * Catherine Thompson - Chris OC & me: design, narrative
  * Mike Hazell - React developer - API design + systems + tooling
  * Han-Qing Tan - backend, systems, tooling
  * Ross - Accessibility
  * Monica - Design and UX (also happy to help where's needed)
  * Matt - Happy to help where it’s needed from:
    - design/dev overlap or process
      - DesignOps
      - front-end tech
      - design tools
      - UX Also in a good position for any gold/NSW collab so happy to help with that too
  * Mitch - Design/Front end. Am working with Anthony (above) on DS based on AUD

## Creating a skills register

* DW to facilitate 
* Slack: 
  * Maintainers group - #steering-committee 
  * Creation of new Slack channels:
    * Practice group - [#tech](https://govau-guides.slack.com/archives/C02QKDZA0DU)
    * Practice group - [#design](https://govau-guides.slack.com/archives/C02QKE4TA06)
    * Practice group - [#a11y](https://govau-guides.slack.com/archives/C02QS50A9U2)
    * Practice group - [#content](https://govau-guides.slack.com/archives/C4RP1MFK8)
* GitHub:
  * Maintainers GitHub group will now auto-assign PR's

## RFC approvals

* [Remove pancake](https://github.com/designsystemau/RFCs/pull/1)
  * Issue: Liam getting value out of SaaS variations
  * Accessibility test tokens?
  * TJ - so few people use NSW DS as SaaS, they moved to CSS variables - good uptake. Created a colour palette.
  * Elise suggests building out th CSS variables before removing SaaS
  * ACTIONS: another RFC will be written up with CSS variables with a testing utility, Dom and Elise to reach out to RJ to hear about the NSW DS work done.

* [Simplify monorepo](https://github.com/designsystemau/RFCs/pull/2)
  * Issue: Very complex because it needs to install packages in specific order
  * Proposal is to go to MPM workspaces
  * It will make things move faster and remove complexity, component output doesn't change
  * ACTION: implement

* [Separate framework entry points](https://github.com/designsystemau/RFCs/pull/3)
  * Issue: Compromises have been made to allow for usability for different variant frameworks
  * Proposal is to remove the 3 proponents that have javascript
  * Matt believes it's worth the hassle as it will ease adoption for majority of people
  * ACTION: implement

* [Docs site improvements](https://github.com/designsystemau/RFCs/pull/4)
  * Co-locate documentation with components, no changes for users. Will be easier to add documentation.
  * ACTION: implement

* [Create STANDARDISED-ACCESSIBILITY-TESTING.md](https://github.com/designsystemau/RFCs/pull/6)
  * A way to ensure that when we're testing accessibility it's all a common language
  * ACTION: implement

* [Update Grid 12](https://github.com/designsystemau/RFCs/pull/11)
  * Update internals of Grid 12 which won't vertically align
  * Grid is based on Bootstrap which has been updated with the ability to use Flex.
  * Some have suggested using a CSS grid
  * Some concern about IE11 support. Simon V says IE11 EoL is June 15
  * Simon V: suggests we got for CSS Grid style implementation on basis that "we are in a position to show our dev peers what implementation is best, so +1 for CSS grid"
  * ACTION: not necessary for now, if we do update grid 12, let's see if we can use CSS. We're pausing it.

* [Distribute unminified and unprefixed CSS](https://github.com/designsystemau/RFCs/pull/16)
  * Contingent on whether or not we remove Pancake. Postpone until next meeting.

* **Other notes:**
  * What is our position on supported browsers?
  * Liam would be keen to understand how opinionated we would like the System to be. Dom suggested creating an RFC so we can discuss at next meeting.
  * Look into Slack integration

## Open Discussion (optional, if time permits)
