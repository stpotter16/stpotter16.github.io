---
layout: post
title:  "Cashflow: Week 2"
date:   Mon 12 Jun 2023 09:24:52 AM CDT
categories: projects, cashflow
---
# Last week's progress
# 1. Finish hypermodern python guide
Sadly, not much progress this week (work, was hectic).

I got really stuck trying to fight nox, pip, and poetry while trying to finish the
"Linting" section of the hypermodern guide. The TL;DR is that poetry includes the extras
when in creates the contraint file for pip, e.g. `coverage[toml]`, but that's not valid
for a contraint file.

I opened a few issues to keep track of where I am / maybe come back to this later
- [Managing nox dependencies with poetry](https://github.com/stpotter16/cashflow/issues/1)
- [Using pre-commit hooks](https://github.com/stpotter16/cashflow/issues/2)

More broadly speaking though, I think I'm getting lulled into the "do this cool thing" vs.
thinking critically about what the project _needs_.

Let me be clear -- I think the hypermodern python guide is useful. I'm just falling into a trap
of following it in a "rote" manner, instead of being more pragmatic.

# 2. Make a decision about supporting multiple python versions
I've decided it's silly to try to support multiple versions of python.
The application is an application (duh), not a library

# Goals for the week
1. Finish the hypermodern python guide, but be more careful about needs vs wants
