# 4thWaveAI

Future-tech automation & intelligence: **AI • Robotics • Quantum • Biotech • Nanotech**.  
Open-core **Automation OS**, connectors, templates, and real-time feeds.

## Repos
- **feeds** — aggregated research/news feeds (AI/robotics/space, etc.)
- **templates** — starter flows, connectors, actions (coming soon)

## How to use our reusable workflows
```yaml
jobs:
  task:
    uses: 4thWaveAI/.github/workflows/feed-runner.yml@main
    with:
      script: scripts/update_feeds.py
      requirements_path: path/to/your/requirements.txt
