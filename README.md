# XIV-Marketeer

This is and was a pet project to visualize changes in the global market of the online MMORPG [Final Fantasy XIV](https://de.finalfantasyxiv.com/) using tools like [Garland Tools](https://garlandtools.org/) and [Universalis](https://universalis.app/).
Using this project is potentially against ToS, though it "just visualizes data".

Essentially, what it would do is:
1. Pull various data from APIs (like Garland Tools and Universalis)
2. Process through the data to find specific combinations like "in high demand, but no supply" or "supply overflow"
3. Present the compiled data as easily understandable graphs and text on a GitHub page

Some of the data had to be precompiled in via a CI/CD, which would limit it to daily/hourly runs.

The Jupyter Notebook part of this can be found [here](https://forgejo.sakul-flee.de/SakulFlee/XIV-Marketeer-Jupyter)!

I do not have the time to continue development of this project.
It should still work, though it may need to be updated for future expansions.