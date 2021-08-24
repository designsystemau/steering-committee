# August 24, 2021 - Hello World - Meeting Notes

**Faciliators:**

| Name | Abbreviation | Organisation |
| - | - | - |
|Elise Chant|EC  | Thinkmill
|Dominik Wilkowski|DW  | Thinkmill
|Matt Sawkill|MS  |Code for Australia

We are only listing facilitators for this meeting as other attendees were prospective TSC members.

## Resources

- [Meeting Slides](https://docs.google.com/presentation/d/1SDMQwlnCbFCcdy2Z-gy7EcVNRuKz0dMoZwj8mpCWluE/edit#slide=id.geaebde68e3_0_22)
- [Meeting Recording](https://vimeo.com/591398381) (passcode shared with attendees)

## Welcome

## Introductions

Async - Invitees introduced themselves ahead of time in the #tsc group in Slack.

EC, DW & MS introduced themselves as initial TSC members and facilitators for this meeting.

We acknowledged the organisations represented by attendees.

## Vision

EC explained the goals of the project and the [TSC charter](https://github.com/designsystemau/TSC/blob/main/CHARTER.md#goals-of-the-project).

## Technical Steering Committee and Governance

MS explained the [roles](https://github.com/designsystemau/TSC/blob/main/ROLES.md) of TSC, Supporting Organisations, Government Agencies and Contributors

DW introduced the [Code of Conduct](https://github.com/designsystemau/TSC/blob/main/CODE-OF-CONDUCT.md), TSC [structure](https://github.com/designsystemau/TSC/) and [RFC process](https://github.com/designsystemau/RFCs/).

DW's notes:
- We have created the Technical Steering Committee
- We have a Charter that outlines how we want to organise the TSC
- We have outlined how we think changes should be implemented to the Design System via the RFC process
- All of those things are starting positions and can be iterated on by the community now
- Everything we do we will do in the open
- The TSC meeting notes will published including for this meeting [Reference](https://raw.githubusercontent.com/tc39/notes/master/meetings/2021-07/july-13.md)
- TSC definition: Monitors and reviews project status, as well as provide oversight of the deliverables. The Technical Steering Committee provides a stabilizing influence so organizational concepts and directions are established and maintained with a visionary view.

## Managing departmental risk

DW explained the risks we're aware of and invited input from participants on any additional concerns.

DW's notes:
- “What it is” and “what it isn’t”
- We will publish the current components in their current version to the new npm scope so that migration is made easy
- With the move to a federated, community owned project the risk of the leading department folding, or mandate changes is much lower
- Changes will have to go through the eyes of the TSC members and be thoroughly discussed before merged and worked on
- We will take the components as is and work on them from there. Breaking changes as well as any changes will be discussed and approved with enough prior notice to everyone.
- We already got a couple RFCs that seek to address some of the shortcomings the community has pointed out about the Design System a while back. But those RFCs are not done and we still want more input before we will approve anything.
- There is no specific branding of the TSC so the multi-brand, theming aspect of the system becomes even more important and the risk of the Design System just being a single brand decreases

## What happens now?

EC lead a conversation about next steps.

EC's notes:
- DTA support ends on 30 September 2021
- We are able to use the @Gov.au handles
- Also, documentation sites will be removed
- We need to act quickly to respond to provide a migration path
  - Publish to npm
  - Publish new docs site
  - Remove DTA’s branding
  - Provide migration support for teams

### Opportunities to contribute
- Backlog - [“Continuing and Stabilising the Design System”](https://www.google.com/url?q=https://github.com/orgs/designsystemau/projects/4?add_cards_query%3Dis%253Aopen&sa=D&source=calendar&usd=2&usg=AOvVaw0pnd9DcTX1uSVSweUZ5bk5)
- Backlog - [New Branding](https://github.com/orgs/designsystemau/projects/3)
- [BAU Issues](https://github.com/designsystemau/design-system-components/issues)

Shared [an example of TSC meeting notes format](https://github.com/tc39/notes/blob/master/meetings/2021-07/july-15.md) from TSC39 (JavaScript)

## What happens next?
TSC to plan this together (note, in the following TSC Meeting)

## Open Discussion
- Current TSC meeting time of 12pm AEST is good for the folks who were able to attend. Good to consider WA and overseas attendees.
- Simon Victory: Are we able to deprecate the old packages and add a note about the new design System
  - Ross Mullen: unlikely, but should be able to update the README (which is also listed on npm)
- Simon Victory: Do we need to maintain a solution for the current DTA [Community of Practice](https://community.digital.gov.au/)
    - Group: Not essential, but good to archive the valuable conversations had there around the DS to date.
    - Suggestion to scrape this content, rely on web.archive.org, etc. Simon will update ticket to capture this work
- Jordan Hatch: Would the DTA be open to pointing designsystem.gov.au at a GitHub Pages site so there could be a placeholder messages after the current site
  - Ross Mullen: unlikely
- Simon Pascal Klein: made a point around Government engagement - risk to the project that without a .gov.au domain or official endorsement, agencies may not adopt the "new" Design System
  - Group discussion followed around the importance of ground up momentum from practitioners and recognising contributions from agencies who use the DS. Facilitators shared our intent to engage with key agencies around Australian Government brand
