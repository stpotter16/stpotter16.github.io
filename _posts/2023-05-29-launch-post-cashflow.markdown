---
layout: post
title:  "Project Launch: Cashflow"
date:   Mon 29 May 2023 02:22:00 PM CDT
categories: projects, launch, cashflow
---
# TL;DR
Cashflow is a web app for budgeting and tracking your spending habits.

# The what
Cashflow is not much different than more polished and popular choices, e.g. [You need a budget](https://www.ynab.com/)
or [EveryDollar](everydollar.com).

A core difference is that Cashflow tries to give you tools for reasoning about your budget over the course of the month,
not just a point in time at the beginning of the month.

From an implementation standpoint, I'll likely keep it pretty simple: HTML/Flask/SQL(ite) on a VPS (maybe behind nginx)

# Definition of (MVP) done
Cashflow is MVP complete when a user can create a budget, add transactions, and see their projected spend over a month.

# The why
We currently use EveryDollar for our household budgeting and it works, but there have been a few things I wish it did differently.

More importantly, I'm itching for a chance to do a "greenfield" project that involves the whole stack.
Often much of the "nitty-gritty" is hidden away by libraries and layers of abstraction at work and it'll be nice to get a chance to work with less abstraction.

# Kill criteria
- If I'm not to the MVP state by September 1, walk away
- If I spend more than 100 dollars on hosting, etc., walk away

