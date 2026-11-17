# NL PR waiting times

How long the IND takes to decide on Dutch permanent residence applications, based on dates people shared in an r/Netherlands Reddit thread.

- `index.html` is the page (English/Turkish).
- `data.json` holds the rows. Dates are `YYYY-MM-DD`, or `YYYY-MM` when only the month was given.

Entry fields: `submitted`, `timing` (`before`/`after` the 5-year mark), `timingAmount` + `timingUnit` (`day`/`week`/`month`/`year`, optional), `decided` (null while waiting), `success` (true/false/null), `source` (comment link, optional), `author` (optional).

Reddit closed its public API to new apps on 31 October 2026, so the data is updated by hand, not scraped.
