More logs available here: https://gitlab.com/cscs-ci/electronic-structure/benchmarking/-/pipelines/254949088

Benchmark settings:

```json
{
    "id": "654f6877-323e-4b88-b141-b6dc2a20c0e5",
    "reference": {
        "spec": "sirius@6.5.7 +scalapack",
        "cmd": [
            "sirius.scf"
        ],
        "repo": "electronic-structure/SIRIUS",
        "sha": "a24d674330b97675090853be47ef2269f1f7185e",
        "build": false
    },
    "current": {
        "spec": "sirius@develop +scalapack",
        "cmd": [
            "sirius.scf"
        ],
        "repo": "electronic-structure/SIRIUS",
        "sha": "dd26b4c3a8b510264c2723458c0ccaf5eeca6037",
        "build": false
    },
    "report_to": {
        "repository": "electronic-structure/SIRIUS",
        "type": "pr",
        "issue": 575
    }
}
```
