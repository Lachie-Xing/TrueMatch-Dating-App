# TrueMatch
### Discover compatibility through everyday behaviour

An Android dating prototype combining mobile sensing, profile discovery, messaging and date planning. Built by a six-person team for **COMP90018 - Mobile Computing Systems Programming, University of Melbourne (2025)**.

**[Watch the demo](https://youtu.be/wgXt_u9OY0M)** · **[Figma prototype](https://www.figma.com/design/owWAblqoTqFcsr2LUPYHXN/TrueMatch-prototype)** · **[Project Wiki](docs/wiki_snapshot/Home.md)** · **[Technical report](report/truematch_report.pdf)**

## Project overview

TrueMatch explores whether shared daily habits can support partner discovery. Steps, mobility, app/social usage and inferred sleep behaviour inform visible activity categories alongside conventional profile information.

| Area | Highlights |
| --- | --- |
| Core journeys | Register, discover, like, chat, plan a date and QR check-in |
| Mobile development | Android interfaces, background sensing and runtime permissions |
| Cloud services | Firebase Authentication, Cloud Firestore and a separate scoring backend |
| Design | Figma, Material components and bottom navigation |
| My contribution | UI/UX, registration, discovery, likes, data presentation and integration debugging |
| Repository status | Archived APK, report and walkthrough; source code is not included |

## My contribution

I am **Zijun Xing**. My work focused on turning the team's product flows into Android interfaces, including registration, discovery, likes and user-detail data presentation. One practical improvement was distinguishing missing activity values from measured zero values.

See the [contribution case study](docs/wiki_snapshot/Personal-Contribution.md) for implementation examples and historical evidence. The full application was a team effort.

## Technology stack

| Area | Technology / approach |
| --- | --- |
| Android interfaces | Java-based UI work, XML layouts, ConstraintLayout, RecyclerView, Material components |
| Authentication and data | Firebase Authentication, Cloud Firestore, repository abstractions and real-time listeners |
| Sensing | Android step counter, location, usage statistics and camera |
| Matching | Normalised behavioural categories and backend scoring |
| Design | Figma |

The implementation details are documented in the archived report and my project experience. This showcase does not contain the client/backend code needed to reproduce a source build.

## Documentation index

- [Background, features and scope](docs/wiki_snapshot/Project-Overview.md)
- [System architecture and data model](docs/wiki_snapshot/System-Architecture.md)
- [Demonstration and Android build](docs/wiki_snapshot/Demo-and-Installation.md)
- [My contribution and implementation examples](docs/wiki_snapshot/Personal-Contribution.md)
- [Evidence, checks and limitations](docs/wiki_snapshot/Validation-and-Limitations.md)
- [Team and attribution](docs/wiki_snapshot/Project-Team.md)
- [Wiki Home](docs/wiki_snapshot/Home.md)
- [Documentation and Wiki publication guide](docs/README.md)

## Repository structure

| Path | Purpose |
| --- | --- |
| `docs/wiki_snapshot/` | Versioned Wiki pages and sidebar navigation |
| `apk/app-debug.zip` | Archived Android debug APK |
| `report/truematch_report.pdf` | Team report, architecture, data model and archived commit log |
| `video/readme.md` | Original demonstration link |

## Review the project

Start with the video, then read the contribution and architecture pages. For hands-on review, follow the [APK guide](docs/wiki_snapshot/Demo-and-Installation.md). Original Firebase/backend availability has not been checked.

## Team

Zijun Xing · Shasha Wu · Zherui Wang · Yash Arjun Aslekar · Nathan Charles Lopes · Karl Jorge Cleres Andreo.

This is a university prototype. The report's self-evaluation is not an independently confirmed grade, matching-accuracy result or production-readiness assessment.
