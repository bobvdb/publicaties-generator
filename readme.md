#Publicaties generator
This code was written to quickly automate some manual work. The code is barely tested and far from production ready. Please do not use this in production.

## Getting Started
To start generating your own publicaties, place your own Slack Token in the SlackApi.java file on line 18. Afterwards you can run the program. In the project root a file should be visible after running the program called publicaties.txt. This file will contain the publicaties form the last 7 days.

## TODO
* Handle the scenario where a publicatie contains an new line (currently not picked up by the regex's that are used)
* Fix HtmlUtil to try multiple ways to retrieve the page title instead of just a normal GET request which fails often
* Write more tests
* Write documentation/comments
* Add properly error handling