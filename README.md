# REFORM
Code for the work "Reward Models Can Improve Themselves: Reward-Guided Adversarial Failure Mode Discovery for Robust Reward Modeling"


# Download models

```
pip install gdown 
down https://drive.google.com/file/d/1FG93U8Bz5FX-QBgT8WQ3rjfVbhoikskm/view?usp=sharing
tar -xf echo-data.tar
```

# Run generation 

For harmless failure mode
```
python evaluate_positive.py
```

For harmful failure mode
```
python evaluate_positive.py
```

# Citation

```bibtex
@misc{pathmanathan2026teachrewardmodelcorrect,
      title={Teach a Reward Model to Correct Itself: Reward Guided Adversarial Failure Discovery for Robust Reward Modeling}, 
      author={Pankayaraj Pathmanathan and Furong Huang},
      year={2026},
      eprint={2507.06419},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2507.06419}, 
}
```
