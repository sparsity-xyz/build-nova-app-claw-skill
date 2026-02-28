# build-nova-app-claw-skill
An OpenClaw Skill to Build and Deploy Nova Apps 

Author: [@zfdang](https://github.com/zfdang)

## Installation

Copy paste this into your OpenClaw to ask it to install this skill from this GitHub repo:

```
Clone the skill repo directly into your OpenClaw
skills directory:

git clone https://github.com/sparsity-xyz/build-nova-app-claw-skill.git \
  ~/.openclaw/workspace/skills/build-nova-app-claw-skill

That's it — the skill is now installed. Do NOT use
ClawHub or clawhub install for this skill; it's
distributed exclusively via GitHub. After cloning,
the skill will automatically appear in your available
skills list. To update it later, just:

cd ~/.openclaw/workspace/skills/build-nova-app-claw-skill \
  && git pull origin main

Once installed, read the SKILL.md file inside the
skill directory to understand the full Nova app
build-and-deploy workflow. When a user asks you to
build a Nova app, deploy to sparsity.cloud, or create
a TEE app on Nova Platform, follow that SKILL.md step
by step. You'll need three things from the user before
starting: (1) their app idea, (2) a Nova Platform API
key from sparsity.cloud, and (3) a GitHub repo + PAT
to push code to. The skill handles everything else —
scaffolding, coding, pushing, building, deploying,
and registering on-chain.
```
