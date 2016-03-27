I have wanted to convert this story into a book-like format for a very long time -- ever since I read it, honestly.  Many thanks to Lightning-on-the-Wave for writing this story.  Also, thanks to the creators of [pandoc](http://pandoc.org/) and the LaTeX community for building such wonderful tools.

I've done a little cleanup on scene separators (originals were a string of "SSSSS", replaced with horizontal lines), cleaned up typos and some extra words here and there, and removed some author warnings (due to this being a *book* format, instead of a series of livejournal / fanfiction.net postings). 

Please only contribute typos and other corrections. I do not intend to take the more explicit content from the LiveJournal entries and add it to the book.  I would consider including "Slash warnings" or other explicit content markers, though I would like to see a few proofs of concept before doing so.

Downloads available [in the repository downloads section](https://bitbucket.org/tydavis/lightningwavestories/downloads)

## Details ##
Original Author LiveJournal [available here](http://lightningwave.livejournal.com/)

Story content downloaded from [FanFiction.net](https://m.fanfiction.net/u/895946/) (Apologies for the mobile site. Main site is not working at the moment.)

## To Contribute ##

If you wish to submit changes, please fork this repository, add your changes to a [pull request](https://confluence.atlassian.com/bitbucket/work-with-pull-requests-223220593.html), and I will review.  Many thanks in advance!

## To Build ##
To build PDFs run the following:
```
latexmk -cd -e -f -pdf -interaction=nonstopmode -synctex=1 <FILE>
```

Followed by:
```
latexmk -C
```
to clean up ancillary files.