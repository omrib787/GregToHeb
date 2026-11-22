# Hebrew Date Converter

A web page that converts a Gregorian date to a Hebrew date using the Hebcal API.

## Features
- Converts a date to the Hebrew date
- After sunset option (a Hebrew day starts at sunset)
- Shows holidays and the weekly Torah portion for the date
- Validation and error messages

## How to run
Open GregToHeb.html in a browser. No installation needed.
https://omrib787.github.io/GregToHeb/GregToHeb.html

## API
Hebcal converter: https://www.hebcal.com/home/219/hebrew-date-converter-rest-api

## What was tricky
The API doesn't reject wrong dates. For example 2026-13-45 becomes a different date
instead of an error, so I added my own check before sending the request.