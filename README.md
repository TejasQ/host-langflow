# Host Langflow

This repo contains a Dockerfile to help you host Langflow with any hosting provider that supports Docker.

## Usage

The directory structure here helps you deploy to specific targets. Follow this guidance:

- The `bm` directory is for bare metal deployments where you have root access to an actual machine.
- The root is a typical Dockerfile for any standard hosting provider like [Flightcontrol](https://flightcontrol.dev), [Fly.io](https://fly.io), or [Render](https://render.com).
