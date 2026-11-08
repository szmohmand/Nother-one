# UMA iPad dashboard deployment

This repository is intended to host the existing UMA read-only dashboard. The application files must be added under `UMA_BOT/` before deployment.

Configure Render Docker runtime with `UMA_CLOUD=1` and a private `UMA_PASSWORD` secret of at least 20 characters. Do not commit passwords or trading credentials. This dashboard does not place trades. Its predictions are experimental and have not been validated.
