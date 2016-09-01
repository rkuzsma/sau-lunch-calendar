# sau-lunch-calendar

SAU school lunch menu calendar JSON file.

## Why?
I'm experimenting with an Amazon Echo skill to speak what's for lunch on a given day.
I had to store the lunch calendar somewhere, and it only updates monthly, so it's not entirely unreasonable to store it as an NPM module.

## When is the calendar updated?
For now, I manually run a utility to parse the latest lunch menu PDF and update the calendar JSON file.
Then, I rebuild the Echo app using the latest version of this module. This way the Echo app has the latest version available locally.
