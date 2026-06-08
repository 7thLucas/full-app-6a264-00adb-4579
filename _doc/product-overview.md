# Video Analyzer — Product Overview

## What It Is

Video Analyzer is a web-based platform that lets users upload or link videos and receive instant, detailed analysis — from technical metadata and quality scores to content breakdowns and actionable insights. It turns raw video files into structured, searchable intelligence.

## Who It's For

- **Content Creators** — YouTubers, streamers, and social-media producers who need to understand video quality, optimize encoding settings, and review content structure before publishing.
- **Marketing Teams** — Brand and campaign managers who analyze video assets at scale, track quality standards across teams, and ensure consistency before distribution.
- **Media Managers** — Post-production leads and digital asset librarians who catalog, tag, and assess large video libraries efficiently.

## Core Capabilities

1. **Video Upload & Ingestion** — Drag-and-drop upload or paste a URL. Supports common formats (MP4, MOV, WebM, AVI). Files are stored securely and associated with the user's workspace.
2. **Technical Metadata Extraction** — Automatically surfaces resolution, frame rate, codec, bitrate, duration, file size, aspect ratio, and color profile.
3. **Quality Analysis** — Computes a quality score based on resolution, bitrate-to-resolution ratio, encoding efficiency, and detected artifacts (blockiness, banding, noise).
4. **Content Breakdown** — Detects scene changes and key moments, generates a timeline overview, and identifies dominant visual themes (color palette, brightness, motion intensity).
5. **Smart Tagging & Search** — Auto-generates descriptive tags from content analysis. Users can add custom tags. Full-text search across all video metadata and tags.
6. **Analysis Dashboard** — Per-video detail view with metadata cards, quality gauge, scene timeline, and tag cloud. Library-wide dashboard with aggregate stats, trends, and filtering.
7. **Export & Reports** — Download analysis reports as PDF or JSON. Share a read-only analysis link with collaborators.

## Positioning & Brand

- **Name:** Video Analyzer
- **Tagline:** "See every satisfying detail."
- **Tone:** Professional, precise, quietly confident. The product speaks through clarity and data, not hype.
- **Primary Color:** #6366F1 (Indigo) — trust, depth, technical sophistication.
- **Secondary Color:** #0EA5E9 (Sky Blue) — clarity, media, openness.
- **Accent Color:** #F59E0B (Amber) — highlights, scores, attention points.

## Scope & Constraints

- Web-only (responsive but desktop-first experience).
- Server-side processing via Express backend; analysis jobs run asynchronously and results are stored in MongoDB.
- Role-based access: Viewers can browse shared analyses; Editors can upload and analyze; Admins manage users, quotas, and system settings.
- MVP focuses on file-upload ingestion and metadata/quality analysis. Platform-API integrations (YouTube, Vimeo) are post-MVP.

## Strategic Principles

1. **Instant value** — upload a video, get meaningful analysis in seconds, not minutes.
2. **Data-rich, not data-noisy** — surface the metrics that matter; hide the rest behind progressive disclosure.
3. **Team-ready from day one** — sharing, roles, and collaboration are first-class, not bolted on.
4. **No lock-in** — open export formats (JSON, PDF) so users own their data.
