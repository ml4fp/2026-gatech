# Day 5: ATLAS Diphoton Hackathon

**Goal.** Build a selection on the `blackbox` dataset that maximizes the signal
significance in the $m_{\gamma\gamma}$ signal region [120, 130] GeV — **without
sculpting** a fake bump in the background (3σ closure threshold). Start from
[`boilerplate.ipynb`](boilerplate.ipynb).

## Setup
Install the kernel for the conda environment, then open the notebook:
```
source setup.sh
```

## Data
In `/pscratch/sd/d/dnoll/projects/ml4fp/atlas`:

| File | What |
|---|---|
| `blackbox.parquet`   | events to classify (signal + background, **no labels**) |
| `pseudodata.parquet` | a second unlabelled mix to explore |
| `signal.root`        | signal MC (labelled) |
| `background.root`    | background MC (labelled) |

The MC is in ROOT format — reading it (TTree `events`) is part of the challenge.

## Submission
Write a CSV of the `event_id`s you keep and send `submission.csv` to me on Slack
(put your team name in the message).

## Schedule
```
2:40PM  Mid evaluation (see how you're doing)
3:15PM  Final evaluation (determines placing)
3:20PM  Final presentations
```
