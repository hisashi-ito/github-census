# A census of one million random GitHub accounts

**Read it here: https://hisashi-ito.github.io/github-census/**

One million GitHub accounts drawn uniformly at random from the account-ID
space — stratified by signup era, conditioned on nothing — with avatars,
trailing-year activity, repositories and dependency manifests collected for
each. Twenty-nine days, one token, inside the free API tier.

A few of the findings:

- Six in seven live accounts have never set a profile picture.
- Of GitHub's stated 180M developers, about 33M do anything in public and
  **6.7M commit in a given week**.
- National public holidays are visible in the contribution calendar,
  country by country.
- The median repository's last push is the day it was created.
- LLM SDKs appear in 12.6% of repositories created in 2026, against 0.4% of
  those created in 2022.

This repository holds the published article and its figures. The collection
and analysis pipeline is not public — it is built around identified
per-account records — but the method is specified in the article in enough
detail to rebuild.

*Written with Claude Code as a working partner; the research questions, the
design decisions and the corrections are the author's. See the disclosure at
the top of the article.*
