# Personal LocalStack service matrix

Personal service enablement for local AWS work with this fork.

## Enabled for most projects

| Service | Why I enable it | Smoke check idea |
|---|---|---|
| S3 | Object storage in almost every demo | create bucket / put object |
| DynamoDB | Simple persistence without a real DB | create table / put item |
| SQS | Async job experiments | create queue / send message |
| Lambda | Local function invoke loops | invoke a hello function |

## Usually disabled

- Services I do not need for the current experiment
- Anything that makes startup materially slower without benefit

## How I decide

1. Start minimal
2. Enable one service at a time
3. Keep this matrix updated when a project needs something new
