The Session Tunelist to Tunetable Converter [v.0.2]
===================================================

## Overview

Generate handy tunetables from tunebooks and lists of 
tunes tagged on [thesession.org](https://thesession.org/) using [The Session API](https://thesession.org/api).

## TO DO:

- Make AJAX requests to TSO using Fetch API.
- Fetch multi-page lists via promises.
- See if loading longer lists requires wait dialog.
- Get rid of innerHTML in favour of appendChild.
- Pick colors for light theme, add button.
- Try adding animations for buttons etc.
- Find ways to export custom Tunetable as txt.
- Consider @media requests for mobile devices.

## DONE: 

[v.0.2]

+ Validation of inputted links via RegExp.
+ Some infobox messages added.

[v.0.1]

+ Offline version tested on TSO JSON via local server.
+ Four algorithms for handling articles in tune names added.
+ Scripts for sorting through and reordering JSON tunelist.
+ Script for creating and filling in Tunetable from TSO JSON.
+ Script for radio buttons (NB: btn values are always string).
+ UI elements added: buttons, radio inputs, input form.
+ Basic mobile-friendly layout with flexboxes tested in dev tools.
+ Expanding table behavior via disabling negative margins (hacky!)


