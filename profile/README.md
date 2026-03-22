# rr-ventures

I build products, internal tools, and automation systems that remove friction from real workflows.

What interests me most is not startup theatre or shipping for the sake of shipping. It is finding a problem that is genuinely annoying, repetitive, expensive, or unclear, then turning it into software that feels obvious once it exists.

Most of the repos here sit somewhere in that space: AI products, local-first tools, desktop apps, workflow systems, and experiments that became real products because they turned out to be useful.

## What I'm Building

- AI products that help people make better decisions faster
- Workflow software that replaces manual, fragmented processes
- Local-first tools that are fast, practical, and easy to live with
- Internal systems that make building and operating multiple products easier

## Selected Products

### [MixingSongFinder](https://github.com/rr-ventures/me-favouritesongsfinder-app)
An Electron desktop app for discovering new music through a scoring pipeline built from multiple signals, not just one recommendation source.

- React, TypeScript, Electron, SQLite
- Onboarding flow, discovery pipeline, library views, and playback tooling
- Built around a real personal workflow for finding genuinely good tracks faster

### [Lightroom Preset Selector](https://github.com/rr-ventures/me-tinderphotomaxxing-app)
A full-stack photo analysis app that helps users review batches of photos, understand what edits will work, and export stronger final images.

- FastAPI backend with a React frontend
- Gemini-powered analysis, preset recommendations, crop suggestions, and enhancement flows
- Built as a product workflow rather than a one-off image script

### [Playlist Saver](https://github.com/rr-ventures/product-playlistsaver-app)
A monitoring product for Spotify and YouTube playlists that snapshots track history and alerts users when songs disappear.

- FastAPI, Next.js, PostgreSQL, Celery
- OAuth flows, scheduled checks, removal detection, notifications, and billing foundations
- Designed like a real SaaS product, not just an API wrapper

### [AI Content Coach](https://github.com/rr-ventures/product-performingcontentfinder-app)
A self-hosted content intelligence dashboard for scraping post history, analysing competitors, transcribing reels, and chatting with the results.

- Node.js orchestration with Apify, Whisper, yt-dlp, and Claude
- Setup wizard, local dashboard, competitor analysis, and AI chat layer
- Built to make content strategy feel more like a system and less like guesswork

### [AU Property Ops Copilot](https://github.com/rr-ventures/product-aiproptech-app)
A property workflow product for running comparative market analysis, due diligence, feasibility, and renovation planning from one operating system.

- Python, FastAPI, Jinja, multi-model AI tooling
- CLI and web interfaces for deal workflows and decision support
- Focused on making complex property work more structured and repeatable

### [MediaDL](https://github.com/rr-ventures/me-mediaDL-app)
A local media operations tool for downloading, converting, transcribing, and processing video, audio, and music from one interface.

- Streamlit-based UI with multiple media pipelines
- Video/audio downloads, bulk music queueing, text-to-audio, audio-to-text, and video-to-text
- Built as a practical utility I would actually use day to day

## Other Active Apps

### [Life Automations](https://github.com/rr-ventures/me-lifeautomations-app)
Recurring automations for planning, coaching, events, and email workflows, tied together with Notion and lightweight Python services.

### [Notion Wardrobe Stylist](https://github.com/rr-ventures/me-wardrobestylist-app)
A Notion + Gemini outfit workflow with a web UI, request pipeline, polling, and webhook handling.

### [Personal AI Chat](https://github.com/rr-ventures/me-personalAIchat-app)
A local-first Ollama chat app with streaming responses, saved chat history, and reusable personas.

## Builder Infrastructure

Some of the most useful things I build are the tools behind the products.

- `App Launcher`: local process manager for starting, stopping, and monitoring all my apps from one dashboard
- Shared dev environments, local automation, and operating tooling that make it easier to run multiple products in parallel

## Philosophy

I like products that earn their place by being useful.

That usually means software that saves time, reduces mental load, improves visibility, or turns a messy process into something much simpler. AI is part of that story, but only when it makes the product genuinely better.
