BBF Division 5 Stats Dashboard
Project Summary — For continuing development in a new chat

What Was Built
A live stats dashboard for the British Baseball Federation Division 5 2026 season, hosted on GitHub Pages.
Live URL: https://samuelcwilliamsss.github.io/samuelcwilliamsss.github.io/
GitHub repo: samuelcwilliamsss.github.io
Source file: index.html in the repo root (also saved as bbf_sheet_dashboard.html in chat outputs)

Data Source
Google Sheet: https://docs.google.com/spreadsheets/d/1TWwDMyjkimx6Q9jhrK3xkbWOzcPh0CrvPStbk9ktKAs
Published CSV URLs (used by the dashboard)
Base URL:
https://docs.google.com/spreadsheets/d/e/2PACX-1vRfcExy7QI69mNIzKjEe4OLIktSVWYlD4ttC7UqnbWWfTYhQy4rWlsoRX7_ddl27-uiUj3Vo9CV9NpL/pub?output=csv&gid=
•	Player Batting (493 rows): ...&gid=34236868
•	Player Pitching (138 rows): ...&gid=1358930240
•	Team Batting (27 rows): ...&gid=862775525
•	Team Pitching (27 rows): ...&gid=708296682
Refresh Method
A bookmarklet must be run while on the BBF stats page. It fetches the BBF API (same-origin, no CORS issues) and posts the data to Apps Script, which writes to the sheet.
BBF stats page: https://stats.britishbaseball.org.uk/en/events/2026-d5/stats
Bookmarklet code:
javascript:(function(){var s=document.createElement("script");s.src="https://script.google.com/macros/s/AKfycbxb0ItTYNZ65eYynF-ogTwVNEIepA1Rz4zftWdiOHsbJjjquiz9ti3wo3jPyh4XXC9J/exec?mode=bookmarklet&t="+Date.now();document.body.appendChild(s);})();
Apps Script project: https://script.google.com/home/projects/1JFd09Vuaz-MVcpAxqUcxFF4aEI-RaCB4c2L4CI7KBSM2ifGckb8o4yvD/edit
The Apps Script is at Version 6. It has scheduledFetch, writeBatting_, writePitching_, and setupTrigger functions. Note: Google server IPs are blocked by the BBF API so scheduled auto-refresh does not work — the bookmarklet is the only reliable method.

Known Limitations
•	BBF API blocks Google server IPs — Apps Script cannot auto-refresh (returns 403). Confirmed at network level, not a header/rate limit issue.
•	Mobile Chrome — bookmarklets do not work on mobile Chrome. A refresh.html page was partially built but also gets CORS-blocked since it is not on the BBF domain. This is the main unresolved issue.
•	BBF API rate limit: 60 requests per hour.
•	CORS: BBF API has no Access-Control-Allow-Origin header. Only same-origin requests (from within the BBF page itself) work.

Dashboard Features
Batting Tab
•	493 players across 27 teams
•	Click any column header to sort — click again to reverse (arrow indicator shows direction)
•	Columns: G, AB, R, H, 2B, 3B, HR, RBI, SB, BB, SO, BB%, K%, AVG, OBP, SLG, OPS
•	BB% = BB / (AB + BB + HBP) x 100 — higher is better
•	K% = SO / (AB + BB + HBP) x 100 — lower is better
•	Team filter, player search, min 10 AB qualifier toggle
•	Click any player name to open a stat card modal with percentile badges
Pitching Tab
•	138 pitchers
•	All columns sortable — ERA/WHIP/BAA/H/ER/BB default to ascending (lower = better)
•	Click any pitcher name to open a stat card modal with percentile badges
Player/Pitcher Stat Card Modal
•	Opens on clicking a name in either table
•	Shows full stats with percentile badges: P75+ = green, P25-74 = amber, P0-24 = red
•	Strikeouts and K% correctly show green for fewer (lower is better)
•	Includes + Add to compare button
Compare Batters
•	Head-to-head comparison bars for any two batters
•	League average shown as third reference card and marker line on every bar
•	BB% higher = better (blue bar), K% lower = better (orange bar signals negative)
•	Green = winner, Red = loser
Compare Pitchers
•	Same structure as Compare Batters
•	ERA, WHIP, BAA, BB, H, ER bars: larger bar = worse performance
•	League average reference card and marker line on every bar
Compare Teams
•	Select up to 4 teams for side-by-side batting stat bars
•	League average marker line on every stat bar
League Averages Tab
•	Division-wide batting averages including BB% and K%
•	Division-wide pitching averages
•	All teams vs league average — toggleable chart: AVG, OBP, SLG, OPS, R, HR, RBI, SB, BB, SO
•	Green bars = above average, red = below average, sorted best-to-worst
Colour Logic
•	Green = winner / above average
•	Red = loser / below average
•	For lower-is-better stats (ERA, WHIP, SO, K%, BB, H, ER): larger bar = worse, orange bar colour
•	Percentile badges: top 25% = green, middle 50% = amber, bottom 25% = red

Next Steps / Unresolved Issues
Mobile Refresh (Main Pending Issue)
The bookmarklet does not work on mobile Chrome. Options explored:
•	refresh.html hosted on GitHub Pages — gets CORS-blocked, not on BBF domain
•	Apps Script scheduled trigger — Google IPs blocked by BBF server
•	Cloudflare Worker proxy — not yet attempted, most promising option
A partial refresh.html was built and saved in chat outputs. It replicates the fetch logic but cannot overcome the CORS restriction from an external domain.
Potential Future Features
•	Fielding stats tab (if BBF API exposes this data)
•	Historical data / season-over-season comparisons
•	Mobile layout optimisation
•	Cloudflare Worker proxy to enable background auto-refresh

How to Continue Development in a New Chat
Share the following with a new Claude chat:
•	This document — provides all context about data sources, URLs, architecture and features
•	The HTML file — download bbf_sheet_dashboard.html from the chat outputs and upload it or paste its contents
•	Describe the specific change you want to make
Tips:
•	Be specific: "In the batting table, add a column for..." works better than vague requests
•	All Google Sheet URLs, Apps Script URLs and the bookmarklet are in this document
•	The GitHub repo is samuelcwilliamsss.github.io — mention this so Claude knows where to deploy
•	If using the Chrome extension, mention it so Claude can interact with the BBF page directly
