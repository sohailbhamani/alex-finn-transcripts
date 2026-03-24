# Alex Finn Transcripts

Transcript archive of [Alex Finn (OpenClaw)](https://www.youtube.com/@AlexFinn) YouTube videos.

## Stats

- **Videos Downloaded**: 215
- **Date Range**: Feb 11, 2023 - Mar 13, 2026
- **Sync**: Automated via GitHub Actions (midnight + noon CST)
- **Last Updated**: Mar 24, 2026

## Structure

```
alex-finn-transcripts/
├── README.md
├── index.json                    # Master index of all videos
├── video_ids.txt                 # All video IDs (one per line)
├── .github/
│   ├── CODEOWNERS                # Require owner review on PRs
│   └── workflows/
│       ├── daily-sync.yml        # Automated transcript pipeline (2x daily)
│       └── lint.yml              # Ruff lint check on PRs
├── index/                        # Topic-based index
│   ├── README.md                 # All topics with episode counts
│   ├── ai-tools.md              # Episodes about AI tools
│   ├── claude-code.md           # Episodes about Claude Code
│   ├── cursor.md                # Episodes about Cursor
│   └── ...                      # 90+ more topic files
├── episodes/
│   └── YYYY-MM-DD-video-title/
│       └── transcript.md         # YAML frontmatter + full transcript
└── scripts/
    ├── discover.py               # RSS-based new video discovery
    ├── download.py               # Download transcripts (Supadata API)
    ├── enrich.py                 # AI enrichment (entities, topics, etc.)
    ├── create_index.py           # Generates index.json
    └── build_index.py            # Builds topic index files
```

## Transcript Format

Each `transcript.md` contains:

```yaml
---
title: "Video Title"
video_id: "abc123"
youtube_url: "https://www.youtube.com/watch?v=abc123"
publish_date: "2026-01-14"
duration: "32:18"
duration_seconds: 1938
view_count: 10000
author: "Alex Finn"

yt_tags:
  - "AI"
  - "Claude"

# AI-enriched metadata
content_type: "Tutorial"
primary_topic: "AI Tools"
difficulty: "Intermediate"
audience:
  - "Engineers"
entities:
  companies:
    - "Anthropic"
  people:
    - "Alex Finn"
  products:
    - "Claude Code"
  models:
    - "Claude Opus 4.5"
concepts:
  - "Key insight extracted from transcript"
summary:
  - "First key point"
  - "Second key point"
---

# Video Title

[Full transcript text here]
```

## Topic Index

Browse episodes by topic via the [`index/`](index/) folder:

**Top Topics:**
- [AI Tools](index/ai-tools.md) (166 episodes)
- [Coding](index/coding.md) (159 episodes)
- [Tutorial](index/tutorial.md) (148 episodes)
- [Claude](index/claude.md) (133 episodes)
- [Cursor](index/cursor.md) (126 episodes)
- [AI News](index/ai-news.md) (124 episodes)
- [Claude Code](index/claude-code.md) (107 episodes)

[See all 98 topics →](index/README.md)

## Usage

### Search transcripts
```bash
grep -r "Claude Code" episodes/
```

### Use index.json
```python
import json
with open('index.json') as f:
    data = json.load(f)
for video in data['videos']:
    print(f"{video['publish_date']}: {video['title']}")
```

### Filter by enriched metadata
```python
# Find all tutorials for engineers
tutorials = [v for v in data['videos']
             if v.get('content_type') == 'Tutorial'
             and 'Engineers' in v.get('audience', [])]

# Find videos mentioning Anthropic
anthropic_vids = [v for v in data['videos']
                  if 'Anthropic' in v.get('entities', {}).get('companies', [])]
```

### Download more videos
```bash
# Set your Supadata API key
export SUPADATA_API_KEY="your_key_here"

# Download next batch
python scripts/download.py 100
```

## Credits

- Content by [Alex Finn](https://www.youtube.com/@AlexFinn)
- Transcripts via [Supadata API](https://supadata.ai)
- Metadata via YouTube Data API v3
