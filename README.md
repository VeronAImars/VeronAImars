<img src="https://raw.githubusercontent.com/VeronAImars/veronaimars.github.io/main/brand/veronaimars-tile.svg" width="88" alt="veronaimars" align="left">

# veronaimars

Open-source tools for people who run real systems and want their assistants to read what
is true now. Everything here is built in the open under Apache-2.0, maintained by this handle,
and judged by one test: does it run against the real thing, and does it stay current when the
real thing changes.

Code regulates the people who use it as surely as any rule written down. The work here keeps
that in view: the engine is open, the checks run on real artifacts, and nothing is hidden
behind a hosted service that could quietly change.

## Projects

| Project | What it is | Where it stands |
|---|---|---|
| [tided](https://tided.io) | A daemon that keeps an agent's grounding current, on your own machine. Fetches, diffs, bounds and pages what a model reads, so a small model can do what only a large one could. | Design; landing live, engine in progress |
| [cryptographers-core](https://github.com/VeronAImars/cryptographers-core) | The engine behind the cryptographer's terminal: OpenSSL's documentation by release tag, option diffs between versions, pinned release images, checks that run the real binary on real artifacts. | Building; first milestones open as issues |
| [openssl-workshop](https://github.com/VeronAImars/openssl-workshop) | Lessons generated from OpenSSL's own documentation for the version you pick, graded on the artifacts you make, re-tested the night the docs change, published as a site. | Building; lesson issues open, help wanted |
| [k3sm](https://k3sm.io) | Kubernetes on Apple silicon, natively. This handle contributes console and app work, release mechanics, and a [privileged-updater design](https://github.com/VeronAImars/k3sm-updater-poc) backed by working proofs. | Shipping; maintained by its own project |

More is in progress and appears here when it runs.

## How to help

Each repo carries its own contribution guide, a DCO sign-off requirement, and issues labelled
for first contributions. The workshop's `lesson` issues are the easiest place to start: pick an
OpenSSL task, write the steps, and the engine grades them against real releases.

## Elsewhere

- Site: [veronaimars.github.io](https://veronaimars.github.io)
- tided: [tided.io](https://tided.io)
