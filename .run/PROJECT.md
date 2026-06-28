---
name: claude-code-101
migrated: true
vision: The hands-on terminal lab of the Claude Code for Business course — a non-dev business owner installs Claude Code and ships one real automation for their business.

milestone: claude-code-for-business
milestone_blueprint: docs/blueprint/PLAN.md

stack:
  framework: markdown-curriculum + bash-installer + static-web-portal
  language: markdown + bash + javascript
  database: supabase
  package_manager: npm

deploy:
  target: none
  config_file: null
  production_url: null
  health_endpoint: null
  auto_deploy: false
  cdn: null

error_monitor: none

analytics:
  tool: none
  project_id: null
  success_metric: capstone_shipped
  funnel_stages: [installed, first_conversation, capstone_shipped]
  # note: no analytics wired for the new effort yet; the question/learning-intelligence
  # loop (D8) gets built in a later phase, which will set this.

required_env: []

tooling:
  type_checker: null
  test_runner: null
  formatter: null
  dead_code: null

git:
  main_branch: main
  commit_style: conventional
  merge_style: squash
  remote: github.com/bradydward/claude-code-101

announce: false
social_scheduler: none
newsletter_drafts_path: null
feature_flags: none
---

# Claude Code 101 / Claude Code for Business — Terminal Lab

## Vision
The hands-on terminal lab of the Claude Code for Business course. A non-technical
business owner installs Claude Code and, guided interactively, ships one real
automation for their own business. This repo is the *delivery surface* (where the
work happens); the Academy (separate phase) is the hosted layer that wraps it.

This repo today is a 16-module RPG-styled tutorial (`claude-code-101`). The
active milestone reworks it into the professional business lab — curated 7-module
spine + capstone, RPG gated/optional, current install/auth/MCP. The new-repo vs
re-architect-in-place decision is being made through a J-bucket planning phase
grounded in repo review + ecosystem research, NOT pre-decided.

## Target Customer
Non-technical local-business owners / operators who want to actually *use* Claude
Code to automate their business — not developers. Warm list / Brady's network
first.

## Pricing / Monetization
Not priced standalone. It is the hands-on delivery surface of the $997–1497
"Claude Code for Business" high-ticket offer (course + community + 1:1).

## Distribution Channels
1. Warm direct outreach (Brady's network) + one live workshop — launch channel.
2. Idea Validator score card = organic share / referral artifact (later phase).
3. Free validator lead-magnet → tripwire → cold ads (scale layer, later).

## Scope Note
This repo = TERMINAL LAB ONLY. Academy portal, Stripe/checkout, sales page,
workshop deck, referral loop are separate milestone phases — out of scope here.
