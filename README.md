# Ang2-Quickstart
Angular2 tutorial quickstart. 

Note: had to change the package.json property of start.
- From:  "start": "tsc && concurrently \"npm run tsc:w\" \"npm run lite\" ",
- To:  "start": "concurrent \"npm run tsc:w\" \"npm run lite\" ",
