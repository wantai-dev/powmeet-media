# powmeet-media

Images for PowMeet Ai's Instagram and Threads posts. Both APIs take an image only by public URL, so the powder
pipeline in powmeet-ai (`publish-meta`) commits each approved card here just before posting and passes its
`raw.githubusercontent.com` address.

- `posts/<runId>/<postId>.jpg`: one card per post, written only after a person approved the run.
- Nothing else belongs here: no data files, no keys.

Forecasts on these cards are guidance only and are not for safety decisions.
