# Cache lookups in the resolver hot path

The worker now drains in-flight work and closes connections on SIGTERM instead of exiting immediately.

Change #1 of 4 on branch `pr/20260811-121032-1-cache-lookups-in-the-resolver-hot-path`.
