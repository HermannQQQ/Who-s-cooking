# Where is the Chef From?
In this project we aim to predict the category of a dish's cuisine given a list of its ingredients.  Food is such a large part of the daily human experience.  Our strongest geographic and cultural associations are tied to a region’s local foods.  Linking recipes to the country of origin is valuable, especially under multiclass classification conditions. 

‘’If you're in Northern California, you'll be walking past the inevitable bushels of leafy greens, spiked with dark purple kale and the bright pinks and yellows of chard. Across the world in South Korea, mounds of bright red kimchi greet you, while the smell of the sea draws your attention to squids squirming nearby. India’s market is perhaps the most colorful, awash in the rich hues and aromas of dozens of spices: turmeric, star anise, poppy seeds, and garam masala as far as the eye can see. Some of our strongest geographic and cultural associations are tied to a region's local foods.’’

# Setup


pre-requisites: 
---------------

Make sure you have installed: 
1. python 3.6.x
2. pipenv (if not installed, run `pip install pipenv`).

clone:
-----
run `git clone https://github.com/manishpandit/chef.git` in a dir of your choice. 

* cd to chef
cd chef
* sync pipenv: this will install required packages.
pipenv sync

pipenv:
------

* run `cd chef`
* run `pipenv --python 3.6` to create a virtual env.
* run `pipenv shell` to start shell.
* run `pipenv sync` to install required packages.
* run `jupyter notebook`
* In the browser, open the chef notebook and run.

Note:
----
* If you run into to SSL cert error during importing the json file. Open finder--applications--python3.6 and run install cert and retry.
