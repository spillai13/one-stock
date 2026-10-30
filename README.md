# One stock: a public experiment

**The live page: https://spillai13.github.io/one-stock/**

A computer picks one stock and puts all the money in it, then sells by rules set before it buys. Every trade stays on the record, losses included. Not investment advice.

## Checking when each trade was made

- [`trades.csv`](trades.csv) (also [`trades.json`](trades.json)) has one line per buy or sell: date, action, stock and price.
- Lines are only ever added. The site will not publish if an earlier line would change or disappear.
- [The file's history](https://github.com/spillai13/one-stock/commits/main/trades.csv) shows the commit that added each line, with its timestamp. Lines from before 2026-10-30 arrived together when the file was created; for those, the [page's daily history](https://github.com/spillai13/one-stock/commits/main/index.html) shows each trade as it appeared.

Everything here is published automatically once a day.
