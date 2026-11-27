# MEDMIND
Interactive medical study map prototype. Run npm install then npm run dev. Starter educational content links to NIDDK and NHLBI background resources; not clinically reviewed. Personal maps and notes remain in browser storage. No AI, patient data, collaboration, or clinical decision support. Search submits on Enter. Import uses plain-text indented outlines. Export is JSON. 

Version 2: direct + controls, double-click editing, context menu, custom colors/shapes, cross-links (select source then target), undo/redo for structural edits, SVG export. Notes remain locally saved.

## Online explorer
Search locally or use Explore online to query Wikipedia directly. Select an article to import its section hierarchy as an editable map. Explore online subtopics on a node to attach another article. Internet required; no API key. Imported text is attributed to Wikipedia (CC BY-SA; see linked article for authors/history). Medical content is not clinically reviewed. MedlinePlus, PubMed and Commons are external search links, not imported databases. Browser storage remains local. Export JSON for backup (no JSON restore UI yet).

## Version 6
Structured online maps group Wikipedia sections into medical categories and supplement them with NLM Clinical Tables condition search matches and Europe PMC publication citations. Missing categories are explicitly marked as further study, not invented medical facts. Optional inline illustrations use Wikipedia pageimages (free-license filter); follow the original article for attribution. All requests run in the browser; network/CORS and service availability can vary. No LLM or clinical review is included. Existing localStorage maps remain compatible. Wikipedia content is CC BY-SA; see original article for attribution and history.

## Version 7
Save .medmind exports the active map, its notes, visited nodes and connections. Open file imports a native file or previous JSON library as new maps with fresh IDs. Existing browser autosave remains. External images are not embedded. Online search and generation show indeterminate loading indicators, disable duplicate requests and offer retry on failure. Closing the dialog discards late results (requests may finish in the background).
