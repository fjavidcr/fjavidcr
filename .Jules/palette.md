## 2024-05-14 - Interactive Profile Visualizations
**Learning:** Static data visualizations in profiles (like GitHub stats) benefit greatly from interactive links and detailed alternative text. Users naturally try to interact with visual data components, and screen readers need more context than generic titles.
**Action:** When adding or encountering static visual summary components, ensure they are wrapped in meaningful interactive elements (like `<a>` tags linking to the source data) with descriptive `title` and `alt` attributes to improve both affordance and accessibility.
