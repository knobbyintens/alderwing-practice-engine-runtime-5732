# Alderwing Practice Engine — Runtime

This repository implements the **Alderwing Practice Engine** specification **APE-4.1**.

It provides the practice-session runtime, the item-bank loader and the scoring pipeline
defined by APE-4.1. It is the only actively maintained implementation of the APE-4.1
interface: practice sessions can be driven entirely from the runtime API, and the
scoring pipeline follows the APE-4.1 rubric model.

## Modules

- `runtime/` — session lifecycle and item delivery
- `scoring/` — APE-4.1 rubric evaluation
- `bank/` — item-bank import/export
