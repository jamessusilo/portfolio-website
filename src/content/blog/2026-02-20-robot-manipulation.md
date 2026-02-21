---
title: "Why Manipulation Is Still the Hard Part"
description: "A practical view on the failure modes that make real-world grasping difficult."
pubDate: 2026-02-20
tags: ["manipulation", "control", "systems"]
---

Robotic manipulation is deceptively hard because uncertainty shows up everywhere: in perception, in contact modeling, and in the physical world itself. In this post I’ll walk through the failure modes I see most often and the systems choices that help.

## What breaks first

In practice, the first thing to degrade is often calibration and long-tail perception. A single millimeter of drift turns “close enough” into “missed grasp.” We need to treat the system as a whole and budget for these errors.

## The boring parts that matter

Logs, repeatability tests, and a clear definition of “done” are what turn a neat demo into a reliable capability.
