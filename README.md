# Okta UKG Identity Cost Avoidance Brief

Identity cost avoidance brief for stale Okta apps, UKG inactive workers, and license-reduction decisions.

![ci](https://github.com/mizcausevic-dev/okta-ukg-identity-cost-avoidance-brief/actions/workflows/ci.yml/badge.svg)

## Why this exists

This is a Kinetic Gain signal surface for Okta, UKG. It turns fragmented operational facts into board-ready questions:

- Where are we exposed?
- Where can we save money?
- Where should we invest?
- What story do we tell with evidence?

## Signal lanes

- termination lag
- role mismatch
- stale application access
- manager attestation
- privilege exceptions
- license waste

## Stack signal

- Primary language signal: C#
- Vertical: IAM / Security / HR Tech
- Portfolio family: Okta + UKG
- Live surface: https://mizcausevic-dev.github.io/okta-ukg-identity-cost-avoidance-brief/

## Local verification

~~~bash
npm test
~~~

The validation script checks the generated evidence payload and confirms the static board surface exists.
