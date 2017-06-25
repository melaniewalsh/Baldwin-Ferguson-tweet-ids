# Baldwin-Ferguson Tweet ids
These are the tweet ids for 3,232 tweets that mentioned "Ferguson" and "James Baldwin" in August and November-December 2014, which were taken from a larger "Ferguson" tweet id dataset created by Ed Summers, et al, which you can find available [here](https://archive.org/details/ferguson-tweet-ids). Using [jq](https://stedolan.github.io/jq/), a filter for reshaping JSON data, and regular expressions, I selected the "Ferguson" tweets that mentioned any variation of “J Baldwin” or “James Baldwin” (for example: #JamesBaldwin; J BALDWIN; james baldwin, etc.).

To "hydrate" these tweet ids into a JSON file, download the desktop application [Hydrator](https://github.com/docnow/hydrator#readme) or use the command-line tool [twarc](https://github.com/docnow/twarc). 
