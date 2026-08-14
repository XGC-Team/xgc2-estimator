# xgc2-estimator

Public XGC-Team aggregator for state-estimation products. Each estimator stays
in its own repository; this tree only pins the checkouts used by the product
catalog.

| Path | Repository | Branch |
| --- | --- | --- |
| `hover-thrust` | [xgc2-estimator-hover-thrust](https://github.com/XGC-Team/xgc2-estimator-hover-thrust) | `noetic` |
| `rigid-state` | [xgc2-estimator-rigid-state](https://github.com/XGC-Team/xgc2-estimator-rigid-state) | `noetic` |

Clone recursively:

```bash
git clone --recurse-submodules git@github.com:XGC-Team/xgc2-estimator.git
```

The main catalog mounts this repository at
`products/ros1/perception/estimator`.
