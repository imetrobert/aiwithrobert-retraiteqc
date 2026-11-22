# aiwithrobert-retraiteqc (French address for the Quebec planner)

`https://retraiteqc.aiwithrobert.com` only forwards to `https://retireqc.aiwithrobert.com/?lang=fr`, which opens the
Quebec Retirement Planner in French (the planner reads `?lang=fr` once and remembers it). No planner code lives here;
the planner is in the repo `aiwithrobert-retireqc`. People sign in there with the same account (app id `retire-qc`).

Hosting: GitHub Pages, branch `main`, folder `/ (root)`, custom domain from `CNAME`, then Enforce HTTPS.
DNS: `CNAME  retraiteqc  ->  imetrobert.github.io`.
Change where it forwards: edit the three copies of the address in `index.html` (meta refresh, canonical link, script).
