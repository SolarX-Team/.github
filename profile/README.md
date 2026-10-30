<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./solarx-lockup-on-dark.svg">
    <img src="./solarx-lockup.svg" alt="SolarX-Team" width="360">
  </picture>
</p>

<p align="center"><b>Worlds, imagined in the open.</b></p>

SolarX is an open research team on world models. We release model weights, datasets, training code and GPU kernels, towards a fully open research ecosystem.

### Models

- **SolarWM**: open data and scalable training for long-horizon video world models.
  [Paper](https://arxiv.org/abs/2609.02886) · [Project](https://junchao-cs.github.io/SolarWM-Web/) · [Code](https://github.com/Junchao-cs/SolarWM) · [Models](https://huggingface.co/collections/junchaoh-cs/solarwm) · [Data](https://huggingface.co/datasets/junchaoh-cs/SolarWM-Data)
- **SolarRenderer**: few-step rendering from any structure to finished video.
  [Paper](https://arxiv.org/abs/2610.28630) · [Project](https://enderfga.cn/SolarRenderer/) · [Code](https://github.com/Enderfga/SolarRenderer) · [Models](https://huggingface.co/Enderfga/SolarRenderer) · [Data](https://huggingface.co/datasets/Enderfga/SolarRenderer-Data)

### Engineering notes

- **H3 Streaming VAE Decoder**: decodes each latent into frames as soon as it is generated.
  [Blog](https://solarx-team.github.io/H3-Streaming-VAE-Decoder/) · [Code](https://github.com/SolarX-Team/H3-Streaming-VAE-Decoder)
- **SolarWM H3 Realtime Interaction**: from 4.9 to 24.4 FPS end to end, playable in real time.
  [Blog](https://solarx-team.github.io/SolarWM-H3-Realtime/) · [Code](https://github.com/Junchao-cs/SolarWM/tree/main/deploy/solar_wm)
