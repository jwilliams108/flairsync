Various bots for reddit.

# FlairSync
A python script/bot for [reddit](http://www.reddit.com) to keep flair in sync across related subreddits

## Requirements

FlairSync requires [PRAW 4+](http://praw.readthedocs.org/en/latest/index.html), and also requires that you have correctly setup [OAuth access](https://github.com/reddit/reddit/wiki/OAuth2).

# KarmaFlair
A python script/bot for [reddit](http://www.reddit.com) to award user granted karma

## Requirements

KarmaFlair requires [PRAW 4+](http://praw.readthedocs.org/en/latest/index.html), and also requires that you have correctly setup [OAuth access](https://github.com/reddit/reddit/wiki/OAuth2).

KarmaFlair also requires [psycopg2](http://initd.org/psycopg/) and a PostgreSQL 9.5+ database supporting upserts (see karmaflair.sql for DB schema).
