# Notations Estimator Bench

**Evaluate supplied estimator results against declared references and inspect exchange and replay bindings.**

[Technical reference](DEVELOPMENT_REFERENCE.md) · [Replay contract](docs/replay-binding.md) · [Research profile](#research-profile) · [Licence](LICENSE)

## Notation Systems

**Frontier Tooling and Instrumentation for Digital Futures.** We develop computational instruments and operational tooling connecting scientific methods, specialist computation and human expertise.

[Notations Systems Terminal](https://github.com/giasonpooni/Notations-Systems-Terminal) coordinates supported execution; this repository owns its evaluation/validation contracts. Estimators retain their algorithms and assumptions. Governed evidence and Cartesian Graphics' interactive worlds, simulation and digital IP have separate authority. [Organization profile](https://github.com/giasonpooni/Notations-Systems-Terminal/blob/b41b84922d4963a9206202029afd1e78b9451f9c/PUBLIC_POSITIONING.md).

## Implemented scope

SET / `state_estimation_testbed` contains exchange validators, declared-reference metrics and content-binding verification for native CIW telemetry/calibrated-observable sessions. It contains **no estimator, simulation, fault-injection runner, published benchmark result set or physical-validation certificate**.

| API | Boundary |
| --- | --- |
| `evaluate_samples` | Bias/RMSE with supplied reference values; NEES/NIS only when the covariance declarations support them |
| `verify_replay_bundle` | Binds retained sessions and separately supplied fresh numerical outputs; absent replay outputs yield indeterminate verification |
| `state_estimation_testbed.contracts` | Validates ordered variables, units, frames, covariance eligibility and distinct artifact identities |

Unknown uncertainty is not zero. Singular/unsupported covariance can leave normalized metrics unavailable. Reference data is caller-declared, not authenticated physical truth. A passed content check is not calibration, model validation, source attestation or admission authority.

## Run

Python **3.11+** is required. From an environment with the documented test dependencies installed:

```sh
python -m pytest
```

The package itself remains dependency-free; NumPy is used by optional differential tests. The [preserved reference](DEVELOPMENT_REFERENCE.md) records runtime compatibility, exact covariance validation policy, API 0.2/0.3 behavior and historical qualification. None is rerun or expanded by this documentation.

## Research profile

**Question:** what evidence is sufficient to support an evaluation or replay claim? Separate numerical accuracy, uncertainty calibration, record integrity and physical validity instead of combining them in one success flag.

Use fixed references and negative cases: missing truth, unknown covariance, inconsistent frames, mismatched replay and unauthenticated runtime declarations. Evaluate new reductions or providers without letting the producer's own acceptance stand in for independent verification.

[Research protocol](https://github.com/giasonpooni/Notations-Systems-Terminal/blob/b41b84922d4963a9206202029afd1e78b9451f9c/RESEARCH_PROGRAMME.md). Additional language/CUDA providers and cost telemetry require separate implementation. Benchmarks must retain setup, failures and end-to-end costs, not just successful kernel time.

## Identity and preservation

Current repository: `Notations-Estimator-Bench`. Earlier names include `Containerized-Estimator-Bench` and `State-Estimation-Evaluation-Testbed`; names do not establish container isolation or universal benchmark coverage. Existing `notation.instrument.*.v1`, state coordinates, corpus citations, imports and historical pins remain unchanged. `bench.estimator` remains a proposed discovery family, not a newly installed command.

The complete former README is preserved byte-for-byte as [DEVELOPMENT_REFERENCE.md](DEVELOPMENT_REFERENCE.md), using its original Git blob at the repository root. No source, tests, dependencies, workflow, licence, permissions or release status change. The existing [LICENSE](LICENSE) and notices remain authoritative.
