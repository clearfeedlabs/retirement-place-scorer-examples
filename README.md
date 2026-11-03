# Retirement Place Scorer: Compare US Counties (Census, NOAA): examples

Rank every US county for retirement with your own weights: home prices, rent, winter warmth, summer heat, rainfall, CMS hospital stars, hospital access, broadband. Official Census, NOAA and CMS data with sources cited.

This repo shows how to call the [Retirement Place Scorer](https://apify.com/clearfeedlabs/retirement-place-scorer) Apify Actor from JavaScript or Python, and what the output looks like.

## What's new
- New: published on the Apify Store Nov 3, 2026.

## Use cases
- Retirees and pre-retirees comparing places to live
- Financial planners and retirement content sites
- 55+ real-estate marketers choosing target counties
- Relocation researchers

## Quick start
1. Create a free Apify account and copy your API token from Settings > Integrations.
2. Set it as an environment variable: `export APIFY_TOKEN=...` (never commit it).
3. Edit `input.json`, then run one of:
   - JavaScript: `npm i apify-client && node run.mjs`
   - Python: `pip install apify-client && python run.py`

## Output fields (first of many)
`rank`, `rowType`, `fips`, `county`, `state`, `score`, `dataCoverage`, `factorScores`, `population`, `medianHomeValue`, `medianGrossRent`, `medianHouseholdIncome`, `broadbandPct`, `janAvgLowF`, `julAvgHighF`, `annualPrecipIn`, `hospitalCount`, `avgHospitalStars`

See `sample-output.json` for one trimmed record.

## Ready-made example tasks
- [Best places to retire southeast](https://apify.com/clearfeedlabs/retirement-place-scorer/examples/best-places-to-retire-southeast)
- [Affordable mild summer retirement counties](https://apify.com/clearfeedlabs/retirement-place-scorer/examples/affordable-mild-summer-retirement-counties)

## Pricing
Pay per result: **$5.00 per 1,000 countys**, with no subscription. The [Store page](https://apify.com/clearfeedlabs/retirement-place-scorer) always shows current prices and every optional add-on event.

## Related Clearfeed Labs Actors
- [Storm & Hail Damage Leads: NOAA Hail Reports by ZIP Code](https://apify.com/clearfeedlabs/storm-roofing-feed): ZIP codes hit by hail, wind and tornado warnings
- [Local Business Leads Finder: Emails & Phones, No Google](https://apify.com/clearfeedlabs/local-business-leads): local business leads with phones and websites
- [311 Complaints by District: Pain-Point & Spike Tracker](https://apify.com/clearfeedlabs/district-pain-point-tracker): 311 complaint spikes by council district
- [All Clearfeed Labs Actors](https://apify.com/clearfeedlabs)

## FAQ
**Is this data official?** Yes. It comes from the public source named above, and each record links back to it.
**Do I need a login or proxy?** No. It uses documented public endpoints only.
**Can I schedule it?** Yes. Use Apify Schedules, the API or integrations (Zapier, Make, webhooks, MCP-compatible AI agents).

## Links
- Actor on the Apify Store: https://apify.com/clearfeedlabs/retirement-place-scorer
- Details & pricing: https://clearfeedlabs.com/actors/retirement-place-scorer/
- Clearfeed Labs: https://clearfeedlabs.com
- Bugs or questions: open an issue on the Actor's Issues tab on Apify.

Data comes from public sources and is provided as-is. Check the original source before relying on it. Not legal, financial or investment advice.

License: MIT
