### Hi, I'm Ellie 👋

I run demand generation, and I build the tooling that makes it run -
automating the parts of campaign ops (list enrichment, outbound campaign
builds, creative production, reporting) that would otherwise eat a team's
week every time a campaign ships.

**What I do:** demand gen strategy end to end - paid social, outbound, ABM,
nurture, and the pipeline reporting that closes the loop - plus the scripts
and automation that let a small team run a lot of campaigns without a lot
of manual work.

#### Demand gen automation

| Repo | What it does |
|---|---|
| [lead-enrichment-pipeline](https://github.com/elliegdickinson/lead-enrichment-pipeline) | Fills gaps in outbound lists via an enrichment API and grades every match by confidence, instead of trusting the API blindly |
| [cold-outreach-campaign-builder](https://github.com/elliegdickinson/cold-outreach-campaign-builder) | Segments target accounts into tiers and builds deliverability-safe email campaigns via the Smartlead API |
| [creative-asset-automation](https://github.com/elliegdickinson/creative-asset-automation) | Turns campaign stats into finished, on-brand social carousel slides in seconds, no design tool round-trip |
| [campaign-performance-report](https://github.com/elliegdickinson/campaign-performance-report) | Joins ad spend and CRM lead data, flags off-target campaigns, and outputs a formatted report with charts |
| [kinetic-video-ad-pipeline](https://github.com/elliegdickinson/kinetic-video-ad-pipeline) | Renders silent, caption-first product ad videos for paid social from a Python config - Pillow frames + ffmpeg, no editor queue |
| [marketing-intel-daily-brief](https://github.com/elliegdickinson/marketing-intel-daily-brief) | Runs standing searches, synthesises a locked-format brief, emails it daily - so staying current is a report, not a recurring chore |
| [lead-routing-automation](https://github.com/elliegdickinson/lead-routing-automation) | n8n workflow: sector-based lead routing and nurture enrolment that fails loud instead of dropping leads silently |

Each repo is a generalised rebuild of a pipeline I actually run day to day -
real logic and patterns, sample data, nothing client-identifying.

#### Side project: Gaffer (a pub-finder app for football fixtures)

| Repo | What it does |
|---|---|
| [gaffer-x-post-generator](https://github.com/elliegdickinson/gaffer-x-post-generator) | Turns live fixture data into on-brand X posts: copy, rendered fixture cards, Buffer-ready CSV |
| [gaffer-seo-brief](https://github.com/elliegdickinson/gaffer-seo-brief) | Daily Search Console brief: near-miss queries, low-CTR pages, coverage gaps |
| [fixtures-ical-feed](https://github.com/elliegdickinson/fixtures-ical-feed) | Scrapes a bot-protected fixtures page into a subscribable calendar feed, built for my own grassroots football team |

These are code I run for real, not rebuilds - no client data involved, so
nothing to sanitise.

**Stack:** Python, REST APIs (Smartlead, Apollo, Meta/Google Ads, Google
Search Console), n8n, openpyxl, Pillow, ffmpeg, Playwright.
