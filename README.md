# Tango: LLM-guided Text-to-Audio Generation and DPO-based Alignment

## 🦒 Colab

| Colab | Info
| --- | --- |
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saravananbcs/tango-demo-colab/blob/master/Tango_2_Google_Colab_demo.ipynb) | Tango_2_Google_Colab_demo.ipynb


[Tango 2 Paper](https://arxiv.org/abs/2404.09956) | [Tango 2](https://huggingface.co/declare-lab/tango2) | [Tango 2 Demo](https://huggingface.co/spaces/declare-lab/tango2) | [Audio-Alpaca](https://huggingface.co/datasets/declare-lab/audio-alpaca) | [Tango 2 Website](https://tango2-web.github.io/) | [Tango Paper](https://arxiv.org/pdf/2304.13731.pdf) | [Tango Model](https://huggingface.co/declare-lab/tango) | [Tango Website](https://tango-web.github.io/) | [Tango Demo](https://huggingface.co/spaces/declare-lab/tango)

</p>




## Tango Model Family

| Model Name                 | Model Path                                       |
|----------------------------|-------------------------------------------------|
| Tango                      | [https://huggingface.co/declare-lab/tango](https://huggingface.co/declare-lab/tango)                               |
| Tango-Full-FT-Audiocaps    | [https://huggingface.co/declare-lab/tango-full-ft-audiocaps](https://huggingface.co/declare-lab/tango-full-ft-audiocaps) |
Tango-Full-FT-Audio-Music-Caps | [https://huggingface.co/declare-lab/tango-full-ft-audio-music-caps](https://huggingface.co/declare-lab/tango-full-ft-audio-music-caps) |
| Mustango | [https://huggingface.co/declare-lab/mustango](https://huggingface.co/declare-lab/mustango) |
| Tango-Full | [https://huggingface.co/declare-lab/tango-full](https://huggingface.co/declare-lab/tango-full) |
| Tango-2    | [https://huggingface.co/declare-lab/tango2](https://huggingface.co/declare-lab/tango2)|
| Tango-2-full| [https://huggingface.co/declare-lab/tango2-full](https://huggingface.co/declare-lab/tango2-full)|

## Description

**TANGO** is a latent diffusion model (LDM) for text-to-audio (TTA) generation. **TANGO** can generate realistic audios including human sounds, animal sounds, natural and artificial sounds and sound effects from textual prompts. We use the frozen instruction-tuned LLM Flan-T5 as the text encoder and train a UNet based diffusion model for audio generation. We perform comparably to current state-of-the-art models for TTA across both objective and subjective metrics, despite training the LDM on a 63 times smaller dataset. We release our model, training, inference code, and pre-trained checkpoints for the research community.

## Credits to authors
```bibtex
@article{ghosal2023tango,
  title={Text-to-Audio Generation using Instruction Tuned LLM and Latent Diffusion Model},
  author={Ghosal, Deepanway and Majumder, Navonil and Mehrish, Ambuj and Poria, Soujanya},
  journal={arXiv preprint arXiv:2304.13731},
  year={2023}
}
```

