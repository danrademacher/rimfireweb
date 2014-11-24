rimfire
=======

This is a version of Change Brackets for the Rim Fire and Wholly H2O.

This set of files displays and runs the slideshows hosted at rimefire.whollyh2o.org. The data for those slideshows is stored in [this Google Doc](https://docs.google.com/spreadsheets/d/1EFabn1WUm2YtYabwmDjEaH5OXAMeRMwxe_7I7vmxUNg/edit#gid=727579335).

The social media in that spreadsheet is harvested using separate code hosted on Heroku. There's zero traffic and one harvest per day, so that service easily runs under a free single-Dyno Heroku instance.

The source code for the harvesters is over in the [the Change Brackets repository](https://github.com/nerdsfornature/changebrackets).

Variations on this repo served via Github Pages combined with that one running on Heroku constitute a free, low-maintenance front and backend solution for Change Bracket installations.
