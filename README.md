# KARYANVISUALS — Cinematic Composition Lab

Open `index.html` in a modern browser. No build step, Node.js, or database is required.

## New Smart Field Coach
- Upload a photo and get related composition grid suggestions.
- Browser-side colour/brightness heuristics suggest a possible scene; this is not AI object/face recognition and may be wrong. Confirm/change the scene dropdown for better recommendations.
- Apply grid controls to the uploaded image, with opacity and colour settings.
- Location shot planner provides six angle/grid/scene-specific shot ideas for markets, forest, streets, stations, cafes, monuments, rooftops, rivers, gyms, villages, and beach/ghat scenes.
- Existing 300 lesson records and filters remain included.

## Important limitation
This is a self-contained client-side app. True semantic recognition of any uploaded photo (e.g. identifying a human eye precisely) requires a vision model/API or an on-device ML model; this version does not pretend that colour heuristics can do that. The composition overlays are guides, not automatic subject/eye tracking. Lesson photo URLs are seeded prototype URLs and are not verified as 300 unique, scene-matched photographs.
