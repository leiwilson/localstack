# Personal LocalStack safe local ops

Safety habits for local AWS emulation.

## Before starting

1. Confirm credentials point at LocalStack, not a real account
2. Use a dedicated local profile / endpoint URL
3. Prefer disposable buckets/queues with obvious local names

## During work

- Keep experiments reversible
- Avoid copying production identifiers into local resources
- Record any destructive test in the experiment notes

## After work

1. Tear down local resources created for the session
2. Stop the LocalStack process / container
3. Note anything that leaked state for next time
