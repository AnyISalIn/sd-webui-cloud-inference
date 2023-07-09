# Stable Diffusion Web UI Cloud Inference

## What capabilities does this extension offer?

This extension enables faster image generation without the need for expensive GPUs and seamlessly integrates with the AUTOMAIC1111 UI.

## Benefits:
1. **No expensive GPUs required**
2. **No need to change your workflow**, compatible with the usage and scripts of sd-webui, such as X/Y/Z Plot, Prompt from file, etc.
3. **Support for 1000+ Checkpoint models**


## Docs

* [Quick Start - Stable Diffusion WebUI Cloud Inference Tutorial](https://github.com/omniinfer/sd-webui-cloud-inference/wiki/Stable-Diffusion-WebUI-Cloud-Inference-Tutorial)

## How it works

![how it works](./docs/how-it-works.png)

## Compatibility and Limitations

| Feature                    | Compatibility | Limitations                                                                   |
| -------------------------- | ------------- | ----------------------------------------------------------------------------- |
| txt2img                    | ✅✅✅           | 🚫 Hires.fix, Tiling, restore face                                             |
| txt2img_controlnet         | ✅✅✅           | 🚫 Hires.fix, Tiling, restore face, Ending Control Step, Starting Control Step |
| img2img                    | ✅✅✅           |                                                                               |
| img2img_controlnet         | ✅✅✅           | 🚫 Hires.fix, Tiling, restore face, Ending Control Step, Starting Control Step |
| scripts - X/Y/Z plot       | ✅✅✅✅✅         | 🚫 Tiling, restore face                                                        |
| scripts - Prompt matrix    | ✅✅✅✅✅         |                                                                               |
| scripts - Prompt from file | ✅✅✅✅✅         |                                                                               |
