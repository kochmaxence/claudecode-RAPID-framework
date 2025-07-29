# RAPID: Autonomous AI Development Framework

**R**esearch → **A**nalyze → **P**rototype → **I**terate → **D**eploy

RAPID is an autonomous AI development workflow that transforms project descriptions into working software through iterative, evidence-based cycles.

## Framework Overview

RAPID uses 5 specialized AI agents that coordinate through standardized file communication:

### Agents

- **🔍 Research Agent** - Project analysis and technical research
- **🧠 Analyze Agent** - Implementation decisions and specifications  
- **🔨 Prototype Agent** - Working code implementation
- **🔬 Iterate Agent** - Testing and quality validation
- **🚀 Deploy Agent** - Deployment and operational verification

### Workflow

1. **Research** analyzes project requirements, creates feature roadmap
2. **Analyze** makes technical decisions for current feature
3. **Prototype** builds working implementation with evidence
4. **Iterate** tests thoroughly, identifies critical issues
5. **Deploy** makes functionality available and verifies operation

Each cycle produces deployable functionality for a single feature.

## Key Principles

- **Evidence-based progression** - No advancement without concrete proof
- **Anti-optimism enforcement** - Claims must be verified with evidence
- **Real-time progress tracking** - Timestamped updates from all agents
- **Incremental delivery** - Working software every cycle
- **Quality gates** - Strict requirements between phases

## Communication Structure

```
docs/rapid/
├── progress/                    # Real-time agent status updates
├── project-status.md           # Overall project dashboard
├── feature-backlog.md          # Prioritized feature list
├── cycle-brief.md              # Current cycle objectives
└── [agent]-output.md          # Agent deliverables
```

## Agent Files

- `CLAUDE.md` - RAPID Orchestrator
- `rapid-research.md` - Research Agent
- `rapid-analyze.md` - Analyze Agent  
- `rapid-prototype.md` - Prototype Agent
- `rapid-iterate.md` - Iterate Agent
- `rapid-deploy.md` - Deploy Agent

## Usage

Input: Project description  
Output: Working software delivered incrementally through feature cycles

The framework handles project breakdown, technical decisions, implementation, testing, and deployment autonomously while maintaining full transparency through progress tracking files.
