# Jewish Heritage Map

**KoHack 2025 · SAR High School · 2nd place**

A team hackathon prototype for exploring Jewish heritage through community members' stories and traditional recipes. People appear as markers on an interactive map; selecting a marker opens a profile with story, recipe, and contact tabs. A search interface helps visitors find people, while a submission form collects new profiles.

The project connects geography with personal history: the map gives visitors an entry point into the experiences and traditions shared by individual community members. The original page title identifies the entry as **KoHack 2025 - SAR High School**, and the development history dates to March 2025.

## My contributions

I worked on the connection between profile data and the map, the presentation of profile information, and the early form interface. The original commit history records my work on:

- [Populating map markers from stored profile coordinates](https://github.com/pknapp-kyhs/KoHack25-SAR/commit/a913c2064ca25a2ffc93111086633a14741b538e).
- [Styling the profile information sections](https://github.com/pknapp-kyhs/KoHack25-SAR/commit/276f0453f4fa3f399aca11235d4e44a191f479fc).
- [Building the initial multi-step submission form and its layout](https://github.com/pknapp-kyhs/KoHack25-SAR/commit/3dea32d72096fd6cf6d83c79dfce117d2e0fd4a3).

This was a collaborative SAR High School project. The map foundation, server, search, profile features, and completed form reflect contributions across the team, documented in the [full commit history](https://github.com/pknapp-kyhs/KoHack25-SAR/commits/main/).

## Implementation

The frontend uses vanilla **HTML, CSS, and JavaScript** with the **Google Maps API**. A **Node.js / Express** server serves the interface and exposes endpoints for reading and updating a **JSON** data store. The browser creates markers from profile coordinates, matches a selected marker to its record, and renders the associated information.

The source also includes a form that steps through profile details, a heritage story, and a traditional recipe. It converts a submitted location into geographic coordinates for the map.

## Original source

The [archived team repository](https://github.com/pknapp-kyhs/KoHack25-SAR) preserves the hackathon implementation. Useful entry points are the [page structure](https://github.com/pknapp-kyhs/KoHack25-SAR/blob/main/views/index.html), [map and profile logic](https://github.com/pknapp-kyhs/KoHack25-SAR/blob/main/views/script.js), and [Express server](https://github.com/pknapp-kyhs/KoHack25-SAR/blob/main/server.js).

[GitHub profile](https://github.com/ilaygibor)
