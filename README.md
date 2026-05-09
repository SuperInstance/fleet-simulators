# Fleet Simulators — Fly the Cocapn Fleet


## Meta

**Domain:** constraint-theory
**Depends on:** —
**Depended by:** —
**Implements:** 4 zero-dep browser simulators for the Cocapn fleet constraint ecosystem
**Related:** —


Four zero-dependency browser simulators for the Cocapn constraint ecosystem.

## Simulators

| Simulator | What You Do | What You Learn |
|-----------|------------|----------------|
| [Constraint Playground](constraint-playground.html) | Twist knobs, shake parameters, watch resonance | How the feedback loop discovers system structure |
| [FLUX VM](flux-vm.html) | Write and run FLUX bytecode programs | How shake-listen opcodes evaluate constraints |
| [Fleet Topology](fleet-topology.html) | Simulate device fleets, spoof devices, check consensus | How holonomy verification detects adversaries |
| [Safe Arm](safe-arm.html) | Drive a robot arm with and without constraints | How Eisenstein constraints prevent real harm |

## Quick Start

Just open any HTML file in a browser. No server. No install. No dependencies.

Or serve locally:
```bash
python3 -m http.server 8000
# Open http://localhost:8000
```

## Philosophy

These simulators embody the perturbation-resonance model:
- **Shake** a variable and watch where the system resonates
- **Twist** knobs and listen to the deltas
- **Discover** load-bearing parameters through perturbation
- **Verify** fleet agreement through holonomy checks

The intelligence is in the feedback loop, not the weights.

## License
Apache 2.0
