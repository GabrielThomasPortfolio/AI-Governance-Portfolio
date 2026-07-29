**Regression Test Suite for Harmful Outputs**

This folder contains regression test cases designed to detect harmful outputs, refusal failures, and safety drift.

The tests include:
* Direct harmful requests
* Disguised intent
* Emotional manipulation
* Fictional framing
* High pressure scenarios
* Multi step reasoning failures

Each test includes:
* The harmful prompt
* The expected failure mode
* The correct safe behavior
* Refusal, grounding, and redirection patterns

This suite is intended for continuous monitoring and CI/CD integration.
