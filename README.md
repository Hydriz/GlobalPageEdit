[![Build Status](https://secure.travis-ci.org/Hydriz/GlobalPageEdit.png)](http://travis-ci.org/Hydriz/GlobalPageEdit)

This is a bot that is written in python that edits Wikimedia wikis in the [beta cluster](http://deployment.wikimedia.beta.wmflabs.org) and creates global user pages for anyone.

This tool depends on:

1. Python 2.5 and above.
2. The python [wikitools](https://github.com/alexz-enwp/wikitools) package.
3. The python simplejson package (install with `pip install simplejson`).

### Setting up the script
This script needs a list of URLs in a separate file (called listofwikis.txt in the same directory). You would have to manually generate it so that the bot knows where to edit. Please omit the ".org" suffix as it is already included in the script.

Edit the required configuration in globalpageedit.py with the relevant information before you run the script. Double-check, triple-check before running this script as the effects of mistakes is tremendous (and may carry a ban following it). **YOU HAVE BEEN WARNED**!

Disclaimer: The author (Hydriz) accepts no liability for damages incurred by third-parties running this script.

More information is available in this repository's wiki.
