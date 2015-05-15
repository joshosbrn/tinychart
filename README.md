# tinychart ![pre-release badge](https://img.shields.io/badge/extension-pre--release-green.svg)
TinyChart is a tiny analytics dashboard via Chrome extension built using the Chartbeat API.

## Usage
You can get set up with TinyChart in 3 easy steps:

1. Get a Chartbeat API Key [here](https://chartbeat.com/docs/api/)

2. Add API Key & Host URL to popup.js

        $.jChartbeat({apikey: 'xxxxxxxYOURAPIKEYxxxxxxx', host: 'example.org'});

3. Package the extension & enjoy!

## Issues
You can [report a bug or request a feature here](https://github.com/joshosbrn/tinychart/issues)

## Plans
While TinyChart was a [hack-day project](http://www.niemanlab.org/2011/08/npr-tries-something-new-a-day-to-let-managers-step-away-and-developers-play/), I have plans to extend this plugin in the future. An example of some things I would like to accomplish: adding the ability to add credentials (API key & hostname) via the options page, or bringing in more data from the Chartbeat API & figuring out an elegant way to deal with that much data in the extension interface.

## Collaboration
Please feel free to fork this project, extend the functionality, and submit a pull request.


![tinychart-logo](https://cloud.githubusercontent.com/assets/5692127/7657913/eda2150c-fb03-11e4-860f-683d98f83f23.png)

