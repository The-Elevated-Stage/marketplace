# The Elevated Stage — Plugin Marketplace

Claude Code plugin marketplace for **The Elevated Stage** multi-agent orchestration suite.

## Installation

```bash
claude plugin add --marketplace The-Elevated-Stage/marketplace
```

Then enable individual skills:

```bash
claude plugin enable arranger@the-elevated-stage
claude plugin enable conductor@the-elevated-stage
claude plugin enable copyist@the-elevated-stage
claude plugin enable dramaturg@the-elevated-stage
claude plugin enable musician@the-elevated-stage
claude plugin enable repetiteur@the-elevated-stage
claude plugin enable souffleur@the-elevated-stage
```

## Skills

| Skill | Description |
|-------|-------------|
| **Arranger** | Converts designs into phased implementation plans |
| **Conductor** | Multi-task coordination and orchestration |
| **Copyist** | Task instruction generation from plans |
| **Dramaturg** | Research-driven design exploration |
| **Musician** | Autonomous task execution in external sessions |
| **Repetiteur** | Mid-implementation consultation and re-planning |
| **Souffleur** | Conductor liveness watchdog and recovery |

## Pipeline

```
Dramaturg → Arranger → Conductor → Musician
(design)    (plan)     (orchestrate) (implement)
```

## License

MIT
