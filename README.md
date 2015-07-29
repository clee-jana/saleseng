Background
===

When an mCent user installs an app and tries it, the app has a mobile
attribution tracking SDK that makes a call to a 3rd party attribution
platform.  In turn, this attribution platform makes a call to the mCent
servers so we can acknowledge the install, and reimburse our members.

We are trying to troubleshoot a discrepancy with the attribution
platform. Our account managers want to know how many callbacks we
received from our partner, and how many we received for a specific
campaign.

Callbacks to our system have the following URL structure:

`/aff/callback/<partner_id>?<campaign_attributes>`

Questions
===

For each problem, please provide an answer, and any scripts/commands
that you used to get to the answer.  If you write any scripts, please
check them in to a public github repo with a codename that does not have
Jana in the name.

Access logs are provided in `elblogs.txt`.

1) How many callbacks did we receive for partner id `nyr8nx`.

2) How many callbacks did we receive for partner `nyr8nx` for campaign id
(cid) `X9KN0`
