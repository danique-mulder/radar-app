# JobRadar app

The control page for JobRadar: start job checks, add companies to watch, and review the results.

This repo contains only the page's code. Jobs, CV and statuses live in a separate private repo,
which the page reads through a GitHub access key that you paste once and that stays in your
browser (it is never stored in this repo).

**Open it:** https://danique-mulder.github.io/radar-app/

## Setting it up

1. In this repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**,
   branch `main`, folder `/ (root)`, **Save**. The page is live a minute later at the link above.
2. Create a fine-grained access key at <https://github.com/settings/personal-access-tokens/new>:
   - Repository access: **Only select repositories → radar**
   - Permissions: **Actions: Read and write**, **Contents: Read and write**
3. Open the page, enter your username and the key, press **Connect**.

The key only works on the private radar repo. To revoke it, delete it on GitHub
(or press **Settings → Forget key** on the page to remove it from that browser).
