# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This repository contains a single-page HTML travel plan for a family trip to Miyakojima (宮古島旅行プラン 2026 ファミリー4人).

## Structure

`miyako_trip_plan_2026.html` — Self-contained single file with all CSS and content inline. No build step or dependencies.

## Design Tokens

CSS custom properties are defined in `:root` at the top of the `<style>` block:

- `--ocean` / `--ocean-light` / `--sky` — blue palette
- `--coral` — accent color
- `--sand` / `--sand-dark` — background tones
- `--green` — nature accent
- Use these variables when adding or modifying styled elements.

## Viewing

Open `miyako_trip_plan_2026.html` directly in a browser — no server required.
