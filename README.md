# build-nova-app-claw-skill
An OpenClaw Skill to Build and Deploy Nova Apps 

Author: [@zfdang](https://github.com/zfdang)

## Installation

First, clone the repo into your OpenClaw skills directory:

```bash
git clone https://github.com/sparsity-xyz/build-nova-app-claw-skill.git \
  ~/.openclaw/workspace/skills/build-nova-app-claw-skill
```

Then restart your OpenClaw gateway so it picks up the new skill. To update later:

```bash
cd ~/.openclaw/workspace/skills/build-nova-app-claw-skill \
  && git pull origin main
```

Once installed, tell your OpenClaw: **"Build me a Nova app"** and it will pick up the skill automatically. It will ask you for three things: (1) your app idea, (2) a Nova Platform API key from [sparsity.cloud](https://sparsity.cloud), and (3) a GitHub repo + PAT to push code to. The skill handles everything else — scaffolding, coding, pushing, building, deploying, and registering on-chain.
