# IAP-CORS-Issue
Google's Identity Aware Proxy is giving me issues

See details here: https://stackoverflow.com/questions/62586304/with-identity-aware-proxy-is-it-possible-to-make-a-cross-origin-request-to-anot


When running the frontend and backend locally the console.logs in frontend work find.

When they are deployed to GAE they work fine.

When I turn on IAP they do not work as per the stack overflow question.

To deploy these cd into each directory then run `gcloud app deploy`

Note that you must already have a "default" GAE service running in your project for these to deploy with the proper names.