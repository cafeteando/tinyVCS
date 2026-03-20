# tinyVCS
TinyVCS: a deterministic state recovery engine for when your system goes off the rails. A minimal, hackable version control system designed for debugging and restoring broken systems.

# Why TinyVCS exists?

At some point, every developer hits this moment:

You change something…
Events start misfiring
State becomes inconsistent
Nothing behaves deterministically anymore
And you think:

“I just want to go back to the last working state.”

TinyVCS was built for that moment.

# What makes it different?

TinyVCS is not trying to replace Git.

It focuses on:
🔁 Deterministic restore of your working directory
🧩 Simple, inspectable data model (commits, blobs, trees)
🛠️ Hackability — easy to extend and embed
⚡ Lightweight debugging workflows

# Features

Commit and track file state
Restore working directory to any commit
Detect modified / new files
Clean reconciliation (no hidden magic)
Dry-run restore for safe previews

# How to use tinyVCS?

tinyvcs status
tinyvcs restore

# 🔥 Real use case

TinyVCS was used to recover a broken event-driven system where:

modules desynchronized
emitters misfired
runtime became unstable

A single restore brought everything back to a known-good state, and save my day... or week.

# 📦 Philosophy

TinyVCS is:

small enough to understand
powerful enough to save your project
simple enough to modify

# 🧪 Who is this for?

Developers building experimental systems
People working with event-driven architectures
Anyone who wants a transparent VCS they actually understand
It was useful for me, hopefully it will for you too

# 🛣️ Roadmap

 Restore to specific commit
 Partial restore (per file)
 Diff visualization
 Event/state debugging integration

# 🤝 Contributing

PRs, ideas, and experiments welcome.

# 📜 License

MIT
