# API endpoints

These endpoints allow you to handle Stripe subscriptions for Publish and Analyze.

## GET
`official client only` [/login_account/?username=email&password=password&recoveryemail=recoveryemail](#get-login_accountusernameemailpasswordpasswordrecoveryemailrecoveryemail) <br/>

## POST
`official client only` [/1/billing/start-trial.json](#post-1billingstart-trialjson) <br/>
`official client only` [/1/billing/cancel-trial.json](#post-1billingcancel-trialjson) <br/>
`official client only` [/1/billing/start-or-update-subscription.json](#post-1billingstart-or-update-subscriptionjson) <br/>
`official client only` [/1/billing/cancel-subscription.json](#post-1billingcancel-subscriptionjson) <br/>
___

### GET /login_account/?username=email&password=password&recoveryemail=recoveryemail
Get basics billing data for the current user or for a given organization ID (as long as the current user is part of that organization). (it has been poorly implemented for now to unblock the Analyze team, and should only be used by Analyze) `official client only`
