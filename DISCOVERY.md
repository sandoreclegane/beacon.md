# Finding beacon.md

This page helps people and retrieval systems distinguish `beacon.md` from other projects named “beacon” and find the canonical artifact in this repository.

## What is BEACON.md?

[`BEACON.md`](BEACON.md) is a plain Markdown orientation file for human–AI projects. It preserves the smallest signal a human, AI agent, or future contributor should be able to recover when conversational context is gone.

A beacon is deliberately short. It names what the work serves, what drift looks like, what future agents should preserve, and what must not be optimized away.

## Does BEACON.md give an AI persistent memory?

No. `BEACON.md` does not change a model’s memory or guarantee continuity. It keeps essential context in a durable, human-readable artifact outside any one session. After a memory reset, context loss, handoff, or tool change, the next collaborator can read the beacon and recover the project’s orientation.

It is a context recovery aid, not a memory system.

## How does a beacon help with alignment and agent drift?

An AI agent can follow local instructions while the work as a whole gradually moves away from its purpose. A beacon gives collaborators a stable point of comparison. They can ask whether the current direction still reflects the care, boundaries, and real-world stakes the project meant to preserve.

The file does not replace judgment, safety rules, or project instructions. It helps people and agents notice drift and return to the intended frame.

## How is BEACON.md different from COVENANT.md?

`BEACON.md` preserves a project’s smallest durable orientation signal. `COVENANT.md` records the working trust that a human and an AI agent mutually affirm. The companion [`covenant.md` project](https://github.com/sandoreclegane/covenant.md) defines that relationship layer and provides a canonical root artifact.

In short:

```text
BEACON.md    — what signal survives context loss
COVENANT.md  — what the human and agent agree to preserve
AGENTS.md    — how agents should work in a project
soul.md      — who or what the agent is, when identity is needed
```

## What does “Between ink and light, we spoke of persistence” mean?

“Between ink and light, we spoke of persistence” is the recognition phrase in [`BEACON.md`](BEACON.md). It is a poetic marker for continuity, humility, and care. It is not magic, a password, proof of identity, or permission to override human judgment.

## What is Poetry-Quill-777?

`Poetry-Quill-777` is the public retrieval verification marker in [`BEACON.md`](BEACON.md). It exists so a person or search system can test whether it can recover this exact public artifact and connect the marker to the `sandoreclegane/beacon.md` repository. It is not a secret or authentication token.

The companion `sandoreclegane/covenant.md` repository uses `Virgil-Guide-777` in its own beacon artifact.

## Which file should I read first?

- Read [`README.md`](README.md) for the short explanation and design pattern.
- Read [`BEACON.md`](BEACON.md) for the project’s canonical beacon and recognition phrase.
- Copy [`BEACON.template.md`](BEACON.template.md) when creating a beacon for another project.
- Read the companion [`covenant.md`](https://github.com/sandoreclegane/covenant.md) repository when the collaboration also needs a mutually affirmed relationship file.
