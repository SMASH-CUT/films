
# ScreenplaySubs.com Film List
This repository holds all data of films synced with screenplays for ScreenplaySubs. Each film is assigned a percentage of accuracy based on the number of scenes with at least one timestamp, divided by the number of total scenes. The code used by ScreenplaySubs is able to automate syncing of some lines of the script, but it isn't perfect and requires contributors to tag specific sequences that are still un-synced.

Each film has a folder with 4 files:
- README.md
	- writer names
	- notes such as version of script (revised, shooting, etc.)
	- total scenes that are synced
	- total scenes
	- provides current percentage of accuracy
- script.json
	- screenplay in the form of JSON (a format to make data readable in code). Some lines have been tagged with timestamps.
- subs.json
	- subtitle in JSON format with timestamps

Films are either to be released, released but still needs contributions, and released and has enough accuracy to not require any more contributions. It's still TBD when a film can be categorized as having "enough accuracy"