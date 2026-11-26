# Card 4.1 Plan story S1

**Agent:** Delivery **Mode:** Plan **Typed by:** Agent Designer

```text
Plan story S1 from docs/backlog.md and nothing else. List the files you will create, the scripts you will load and one browser test for each acceptance criterion. Stop after the plan.
```

# Card 4.2 Build story S1

**Agent:** Delivery **Mode:** Autopilot, or Interactive to approve each step **Typed by:** Agent Designer

```text
Implement the approved plan for S1. When I open app/index.html by double-click, I must see a map of Paris with 12 markers colored by segment, a legend and the map attribution. Keep app.js under 150 lines.
```

**Check:** for another case, keep the first and the last sentence and describe what S1 must show.

# Card 4.3 Fix a failed test

**Agent:** Delivery **Mode:** Interactive **Typed by:** Agent Designer

```text
Test [number] fails. I did: [steps]. I expected: [result]. I see: [result, and any red error from the browser console]. Fix only this and change nothing else.
```

# Card 4.4 Build story S2

**Agent:** Delivery **Mode:** Plan, then Autopilot **Typed by:** Agent Designer

```text
Story S2: clicking a marker opens a card with the name, concept, average menu price in euros, followers per network and rating. Add a side panel with three figures for the competitors shown: count, average menu price and total followers. Add filters for segment and arrondissement and a maximum price slider. The map and the figures update together. A missing value shows "n/a" and is never counted as zero.
```

# Card 4.5 Build story S3, the positioning chart

**Agent:** Delivery **Mode:** Plan, then Autopilot **Typed by:** Agent Designer

```text
Story S3: below the map, draw a positioning chart in plain SVG with no chart library. X axis: average menu price in euros. Y axis: experience score from 1 to 5. Bubble size: total followers. Show our concept from data/our-concept.js as a star. The chart follows the same filters as the map.
```

# Card 4.6 Draft the insights, Hybrid story

**Agent:** Delivery **Mode:** Interactive **Typed by:** Agent Designer, approved by the AI Product Owner

```text
Draft three insights in docs/insights.md from data/competitors.js only: where the white space is, which segment is the most crowded and who leads on social media. Quote the figures you used. Mark each insight "Draft, to be approved by the AI Product Owner".
```

# Card 4.7 After the workshop, use your own figures

**Agent:** Delivery **Mode:** Interactive **Typed by:** Anyone, after the workshop

```text
I collected public figures by hand for [N] competitors in data/raw-notes.md, with a source and a date for each number. Convert them into data/competitors.js using data/data-dictionary.md and set fictional to false. Do not guess any value. If a figure is missing or unclear, write null and list it under "To verify" in your answer.
```
