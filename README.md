# County Index

Interactive U.S. county atlas (GOP share, education, turnout, RESI).

## Host on AWS Amplify

1. Open the [Amplify console](https://console.aws.amazon.com/amplify/).
2. **Create new app** → **Host web app** (GitHub).
3. Authorize GitHub and select **astro-telemetry/county-index**, branch **main**.
4. Confirm build settings (`amplify.yml`: no compile, artifacts from `.`).
5. **Save and deploy**.

Do not use “Deploy without Git” / zip upload for this repo.
