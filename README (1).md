---
language: en
license: apache-2.0
library_name: diffusers
tags: []
datasets: imagefolder
metrics: []
---

<!-- This model card has been generated automatically according to the information the training script had access to. You
should probably proofread and complete it, then remove this comment. -->

# ddpm-osteosarcoma-256

## Model description

This diffusion model is trained with the [🤗 Diffusers](https://github.com/huggingface/diffusers) library 
on the `imagefolder` dataset.

## Intended uses & limitations

#### How to use

```python
# TODO: add an example code snippet for running this diffusion pipeline
```

#### Limitations and bias

[TODO: provide examples of latent issues and potential remediations]

## Training data

[TODO: describe the data used to train the model]

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 0.0001
- train_batch_size: 16
- eval_batch_size: 16
- gradient_accumulation_steps: 1
- optimizer: AdamW with betas=(None, None), weight_decay=None and epsilon=None
- lr_scheduler: None
- lr_warmup_steps: 500
- ema_inv_gamma: None
- ema_inv_gamma: None
- ema_inv_gamma: None
- mixed_precision: fp16

### Training results

📈 [TensorBoard logs](https://huggingface.co/logannyeMD/ddpm-osteosarcoma-256/tensorboard?#scalars)

