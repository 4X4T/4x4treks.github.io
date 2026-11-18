# 4x4treks.com.au (old site): instructions for Claude

This repo is the **old Mobirise website**, still live at https://4x4treks.com.au through GitHub Pages. Any change pushed to `main` is live in about a minute. Mobirise is retired: nobody edits this site in Mobirise any more.

**The new website is `4X4T/4x4t-website`.** Do real work there. This repo is frozen apart from urgent fixes until John moves the domain to the new site. Then it's archived.

The owner, **Tony Davys**, is not a developer. Talk to him in plain words, don't show him code unless he asks, and finish by telling him what changed and where to look.

## What you may change here
Only small, urgent text fixes that guests need to see now:
- a tour date or "sold out" / spots-left status;
- a price;
- a typo or a wrong phone number or email.

No new pages, no layout or style changes, no scripts, trackers or embeds, and no changes to the policies or booking terms. Those all wait for the new site.

## How
1. **Never commit to `main`.** Make a branch (`tony/<short-description>`), edit the HTML, commit, push and open a pull request with a title Tony would understand.
2. Change only the words. Don't reformat the HTML around them. Mobirise pages are long and fragile.
3. Check the same fact on every page it appears on (for example, `index.html`, `new_zealand_treks.html` and `australian_treks.html` all list departures).
4. Tell Tony the pull request is ready and that John merges it. When it's merged, the site updates in a minute.
5. **Make the same change in `4X4T/4x4t-website`** (usually `site/src/data/tours.json`), so the new site doesn't bring the old fact back. Tell Tony if you couldn't.

## Never
- Change `CNAME`, DNS, Cloudflare, GitHub Pages settings or email records. Wrong DNS breaks Tony's email and every domain. That's John's job.
- Put a token, password or key in a file, commit or message.
- Delete pages or files. Old pages need redirects, and those are part of the move to the new site.
