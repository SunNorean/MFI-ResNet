# MeanFlow

Minimal GitHub version of the project.

## Main scripts

- `scripts/train_meanflow.py`: train the MeanFlow compression model
- `scripts/train_meanflow_twostep.py`: train the 2-step Stage4 version
- `scripts/incubate_stage1.py`
- `scripts/incubate_stage2.py`
- `scripts/incubate_stage3.py`
- `scripts/incubate_stage4.py`
- `scripts/finetune_hybrid.py`: final assembly and finetuning

## Quick start

```bash
python scripts/train_meanflow.py --help
python scripts/train_meanflow_twostep.py --help
python scripts/incubate_stage1.py --help
python scripts/finetune_hybrid.py --help
```

Datasets, checkpoints and experiment outputs are not included.