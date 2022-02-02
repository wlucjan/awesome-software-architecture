# awesome-software-architecture
Collection of articles, courses, videos etc. on software architecture.

## Documenting architecture

Architecture documentation should effectively communicate what the project is about and what problems does it solve and how. 

### C4 model

C4 Model allows you to build a map of the architecture with various level of zoom on the details, from the bird view to the description of individual containers or even code

- [C4 Model](https://c4model.com/) - Simon Brown's (author of the model) website on the C4 model
- [C4-PlantUML](https://github.com/plantuml-stdlib/C4-PlantUML) - [PlantUML](https://plantuml.com/) assets for recording C4 diagrams as code

### Architecture Decision Records

An architecture decision record (ADR) is a document that captures an important architecture decision made along with its context and consequences.

- [Documenting Architecture Decissions](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions) - article by Michael Nygard, probably first one coining the idea and most popular format
- [ADR github repository from Joel Parker Henderson](https://github.com/joelparkerhenderson/architecture-decision-record) - an indepth collection of thoughts on how to use ADRs and when to use them, plus contains selection of templates and examples of ADRs
- [Architecture Decision Records](https://adr.github.io/) - homepage of [Github adr organization](https://github.com/adr) formed to motivate ADR use and build tooling around ADRs
- [ADR at Spotify](https://engineering.atspotify.com/2020/04/14/when-should-i-write-an-architecture-decision-record/) - article on ADRs as adopted at Spotify with good sections on why should you do ADRs and heuristics for when to write one
- [Communicating and documenting architectural decisions](https://www.youtube.com/watch?v=rwfXkSjFhzc) - witty talk by David Ayers on wha would you use ADRs and how to socialize decisions in the team; also what to do about overarching architectural decisions
## Architecture

### Modular Monolith

Modular Monolith architecture is a monolithic system (deployed as single unit) designed in a modular way (lowly coupled independent modules).

- [Modular Monolith Primer](http://www.kamilgrzybek.com/design/modular-monolith-primer/) - a collection of 5 articles describing reasoning behind modular monolith architecture, when it makes sense and approaches for its implementation with integration styles and domain-centric design