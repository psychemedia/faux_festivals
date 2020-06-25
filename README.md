# *Faux Festivals* template repository

Faux festivals are real time and "as-if" time streaming video  festivals based around one or more stages programmed using [`Clashfinder.com`](https://clashfinder.com).

Festival acts are programmed on a particular date and stage at a particular time. Associated with each act is a link to a Youtube duration of approximately the same length as a the stage slot time.

Visiting a *Faux Festival* site allows a user to watch acts on stages as scheduled to appear either in real time (at the date and time scheduled) or *faux time*, selecting the festival *day* ans then wathcing the act that particular time.


## Creating a *faux festival* site

In the current iteration, *faux festival* sites are published via Github pages. Custom sites can be created by cloning this repo and updating a simple configuration file. Saving the file triggers and automatic *faux festival* publication process that pulls festival scheduling data down from a specified *Clashfinder* page and construct the *faux festival* website.

There is no limit to the number of people who can visit a *faux festival* site at any one time. The *faux festival* site is a single, simple HTML webpage; video scheduling is based on the local time of each site visitor or the current time in festival locale, and video streaming all handled via embedded Youtube videos.
