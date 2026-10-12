# VRScheduler

A CPM schedule editor and schedule analysis tool that runs in the browser, from VissRad, a Suite of Interactive Smart Tools for Project Delivery.

Open it at https://dwaynepennington.github.io/VRScheduler/

## What it does

- Build a schedule: activities, milestones, WBS, calendars, constraints, predecessors and successors. The critical path is recalculated as you type.
- Load a Primavera P6 schedule (.xer or P6 XML) or a Microsoft Project XML file, with optional resource files.
- Analyse it: cover sheet, S-curve and FTE curve, earned value, critical path, float distribution, milestones, look-ahead plan, WBS summary, CPM check, DCMA 14-point checks, baselines, Monte Carlo risk and resource levelling.
- Work the grid: sort by any column, choose columns, roll up by WBS, zoom from 50 to 200 %, and keep the timescale in view while scrolling.
- Export to P6 XER, Microsoft Project XML or CSV.

## Your data

Files are read in this browser only; nothing is uploaded. A loaded schedule and the editor's plan are kept in this browser's storage so they reopen after a reload. "Start over" removes them and reopens the synthetic sample.

The sample project is synthetic. It does not describe any real project, client or contractor.

## About this repository

This repository holds the built site only. It is published with GitHub Pages from the `main` branch.

For the full suite, see https://vissrad.com

Copyright Pennington Group Associates. All rights reserved.
