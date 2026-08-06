# Claude Tasks & Automation

A central repository for organizing Claude-related projects, automated tasks, custom skills, and productivity tools.

## Structure

### `/av-monitoring/`
Daily/weekly AV technology updates and brand tracking
- **brands-list.md** — Core list of AV manufacturers and brands to monitor
- **daily-reports/** — Archive of daily AV technology summaries
- **notes.md** — Research notes, emerging brands, market observations

### `/skills/`
Custom Claude skills and prompt templates
- Subdirectory per skill with documentation and examples

### `/automation/`
Scheduled tasks and automated workflows
- **scheduled-tasks.md** — Documentation of all active scheduled tasks
- Configuration and trigger details

### `/docs/`
General documentation and reference materials
- Best practices for Claude workflows
- Integration notes
- Troubleshooting

## Active Automations

### Daily AV Technology Updates
- **Status:** Active
- **Schedule:** Daily at 8:00 AM PT (15:00 UTC)
- **Trigger ID:** `trig_01S47ZwBhWzNeej1vARdaAPE`
- **Description:** Monitors 15+ AV brands for new products, firmware updates, and industry news. Only sends report when substantive news exists.
- **Brands Monitored:** Q-SYS, Biamp, Extron, Sennheiser, Audio Technica, Audinate, Planar, LG, Samsung, Brightsign, Lightware, Inogeni, Heckler, Turtle, CatchBox
- **See:** `/av-monitoring/brands-list.md`

## Quick Reference

- **GitHub:** [your-github-repo-url]
- **Last Updated:** August 5, 2026

## How to Use This Repo

1. Clone locally or sync from GitHub
2. Update brand lists, add new automation documentation as tasks are created
3. Archive completed/historical reports in subdirectories
4. Commit changes regularly to maintain version history

## Contributing

Keep structured, descriptive commit messages for tracking changes over time.
