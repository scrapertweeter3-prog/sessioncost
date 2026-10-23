# sessioncost

LaTeX macros for typesetting cost-per-session comparison tables: one row per
option, with the up-front setup cost, the running cost per session, and the
number of sessions it takes for the bought option to break even against the
pay-per-use alternative.

The `sessioncost` environment sets a compact four-column table: a bold title
line, an assumptions line in small italics, one row per option, and a
small-print note under the table. Macros:

* `sessioncost` environment: the table itself, with a title argument.
* `\scassum`: the assumptions line (utility rates, usage frequency, what the
  pay-per-use alternative charges).
* `\scrow`: one option, as setup cost, cost per session, sessions to
  break even.
* `\scnote`: a small-print note under the table (caveats, what was left out).

The package depends only on the standard `array` package.

## License

MIT
