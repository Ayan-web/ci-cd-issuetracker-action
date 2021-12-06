# ci-cd-issuetracker-action
this my github action which has basic ci-cd and issue message with discord server
A very simple pipeline. Have your project setup with scripts `test` to test app, `build` to build app. the action test on node `v12.x`, `v14.x` and `v16.x`. 
Create a `HEROKU_API_KEY` secret in your repository.
that's set now for the Issue message.
Create a discord web hook for your server then create 2 more secrets `WEBHOOK_ID` the number part after `https://discord.com/api/webhooks/` and `WEBHOOK_TOKEN` the text blob after the `id`
