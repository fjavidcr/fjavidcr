## 2024-05-14 - Interactive Profile Visualizations
**Learning:** Static data visualizations in profiles (like GitHub stats) benefit greatly from interactive links and detailed alternative text. Users naturally try to interact with visual data components, and screen readers need more context than generic titles.
**Action:** When adding or encountering static visual summary components, ensure they are wrapped in meaningful interactive elements (like `<a>` tags linking to the source data) with descriptive `title` and `alt` attributes to improve both affordance and accessibility.

## 2026-03-27 - Theme-Aware Static Visualizations
**Learning:** Hardcoding themes (like `radical` for dark mode) in static data visualizations (e.g., GitHub stats images) leads to a jarring user experience when viewed in a contrasting system theme (like light mode). Users expect visuals to seamlessly blend with the reading environment.
**Action:** Use the HTML `<picture>` element with `<source>` tags specifying `media="(prefers-color-scheme: dark)"` and `media="(prefers-color-scheme: light)"` to serve theme-appropriate image URLs. This provides a responsive visual UX without relying on JavaScript or client-side logic.
