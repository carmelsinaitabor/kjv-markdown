
# King James Version Markdown Bible

## For Bible Study & Margin Notes

> _16 For God so loved the world, that he gave his only begotten Son, that whosoever believeth in him should not perish, but have everlasting life._

This is a repo of the KJV scriptures. This is for non-public use in bible study. Made with care using [Bible Gateway](http://biblegateway.com) one chapter at a time.


### Copyright info

This isn't my content. The King James Version (KJV), also known as the Authorized Version, is an English translation of the Bible begun in 1604 and completed in 1611.

King James Version (KJV). Public Domain. [According to](https://support.biblegateway.com/hc/en-us/articles/228180427) Bible Gateway Public domain Bibles may be used freely, without restriction and without prior permission. Note that these works are in the public domain in the United States. Their copyright status may differ in other countries, so please check your local copyright laws before using them outside the US.

***

## Uses & Notes

I have found it useful and fun to study the bible in my code editor; using project search, file fuzzy search, and even a dash of ASCII art to jump around in translations, journaling, and adding margin-notes in line in an indexable way. 

Using a tool like [Pandoc](http://pandoc.org/) you can convert this into other formats as needed.

I use [sublimetext-markdown-preview](https://github.com/revolunet/sublimetext-markdown-preview) to open text in the browser where it is easy to highlight a passage and have a screen reader read aloud (alt+esc on MacOS).

Each file ends with an end-of-file "eof" tag to indicate its end; it's an intentional marker I find useful to denote the end of the content of the book.

***

#### Thanks! 

[@ArleyM](http://twitter.com/ArleyM)

<!-- BOT_CLI_HELPERS_START -->
## Multi-Repo Bot CLI Helpers

All helpers accept a short repository name (such as `tcm_basics`), a full `owner/repo` path, or no repository argument to default to `carmelsinaitabor/bible_dailydevotional`:

- **Check runs and open issues (`checkpipeline`):**
  - `checkpipeline tcm_basics` — lists recent workflow runs and open issues on `carmelsinaitabor/tcm_basics`
  - `checkpipeline carmelsinaitabor/temp_dump` — accepts full `owner/repo` syntax
  - `checkpipeline` — defaults to `carmelsinaitabor/bible_dailydevotional`
- **Assign a task or trigger Chief (`askchief`):**
  - `askchief tcm_basics "Audit index layout and check broken links"` — opens a `[Chief]` issue on `carmelsinaitabor/tcm_basics`
  - `askchief "Audit daily pipeline logs"` — opens a `[Chief]` issue on `carmelsinaitabor/bible_dailydevotional`
  - `askchief tcm_basics` — triggers `chief.yml` (or falls back to `bot_chief.yml`) directly without opening a new issue
- **Full daily status report (`dailyreport`):**
  - `dailyreport tcm_basics` — displays the latest 10 workflow runs, open issues, and open PRs on `carmelsinaitabor/tcm_basics`
  - `dailyreport` — defaults to `carmelsinaitabor/bible_dailydevotional`
- **Close specific issues (`closeissue`):**
  - `closeissue tcm_basics 1` — closes issue `#1` on `carmelsinaitabor/tcm_basics` (supports multiple issue numbers, e.g. `closeissue tcm_basics 1 2`)
  - `closeissue 12` — closes issue `#12` on `carmelsinaitabor/bible_dailydevotional`
- **Batch-close `bot-triage` issues (`closeissues`):**
  - `closeissues tcm_basics` — closes all open issues labeled `bot-triage` on `carmelsinaitabor/tcm_basics`
  - `closeissues` — batch-closes open `bot-triage` issues on `carmelsinaitabor/bible_dailydevotional`
- **Check scheduled workflows and next-day queue (`tomorrowcheck`):**
  - `tomorrowcheck tcm_basics` — lists active workflows and recent `schedule` runs on `carmelsinaitabor/tcm_basics`
  - `tomorrowcheck` — checks scheduled runs and displays the tail of `source_devotionals.txt` on `carmelsinaitabor/bible_dailydevotional`
<!-- BOT_CLI_HELPERS_END -->
