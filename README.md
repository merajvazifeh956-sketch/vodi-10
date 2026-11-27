# VodiWalker Panel - Fly.io (RVG-style)

1) In fly.toml set app = "your-unique-name"
2) In Fly dashboard create a Volume named exactly: data  (region fra, 1GB)
3) Deploy / Retry from latest commit
4) Panel: https://APP.fly.dev  - login admin / 123456 - change password NOW
5) Panel settings: set server IP field to APP.fly.dev

DATA_DIR=/data and PORT=8080 are already set in fly.toml.
Region change: edit primary_region (fra/ams/vie/dxb/arn/iad).
Logs: dashboard Logs tab or: fly logs
