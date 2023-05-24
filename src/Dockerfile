FROM golang:1.20.4-bullseye AS builder

# hadolint ignore=DL3008
RUN apt-get update \
    && apt-get install -y --no-install-recommends \
    tree \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
