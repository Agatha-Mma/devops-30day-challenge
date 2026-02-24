# Day 9 – “It Works on My Machine” Explained

I explored why the statement “It works on my machine” can be dangerous.

If an application only works in one environment,
it means the setup is fragile.

Different dependency versions.
Different configurations.
Undocumented steps.

This is called environment drift.

Tools like Docker aim to reduce these inconsistencies.

Key Insight:
Reproducibility is more important than isolated success.
