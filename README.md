# YelpCrawler

> Crawl multiple company details from Yelp with this python program and store the data in a csv file.

With this Jupyter notebook, a predefined number of companies (multiple of 10) on the rating platform Yelp can be crawled by iterating through
the pages of the rankings and extracting and then saving the relevant information in a data frame. The data frame will then
be exported to a csv file at the end of the program that comntains all of the information in table format.

## Implementation

Enter a search term on Yelp and copy the code of the first page of the results to the code (Cell 2, line 4) as follows:

```sh
url_cur = https://www.yelp.com/search?find_desc=**your search term**find_loc=**Zip code of your search**&start= + str(**Number of pages you want to crawl***i)
```
## Usage example

A few motivating and useful examples of how your product can be used. Spice this up with code blocks and potentially more screenshots.

_For more examples and usage, please refer to the [Wiki][wiki]._

## Development setup

Describe how to install all development dependencies and how to run an automated test-suite of some kind. Potentially do this for multiple platforms.

```sh
make install
npm test
```

## Release History

* 0.2.1
    * CHANGE: Update docs (module code remains unchanged)
* 0.2.0
    * CHANGE: Remove `setDefaultXYZ()`
    * ADD: Add `init()`
* 0.1.1
    * FIX: Crash when calling `baz()` (Thanks @GenerousContributorName!)
* 0.1.0
    * The first proper release
    * CHANGE: Rename `foo()` to `bar()`
* 0.0.1
    * Work in progress

## Meta

Your Name – [@YourTwitter](https://twitter.com/dbader_org) – YourEmail@example.com

Distributed under the XYZ license. See ``LICENSE`` for more information.

[https://github.com/yourname/github-link](https://github.com/dbader/)

## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request
