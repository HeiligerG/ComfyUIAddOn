# ComfyUI Add-On

Enhance your ComfyUI setup with powerful Flux models for specialized image generation workflows. Follow the steps below to get started!

## Installation

### 1. Download ComfyUI

First, download the latest ComfyUI release for Windows (NVIDIA-compatible):

[Download ComfyUI (Windows Portable)](https://github.com/comfyanonymous/ComfyUI/releases/latest/download/ComfyUI_windows_portable_nvidia.7z)

### 2. Install the Manager

Copy the `Manager` folder from this repository and paste it into the `ComfyUI` folder:
```
ComfyUI_windows_portable_nvidia\ComfyUI_windows_portable\ComfyUI\custom_nodes
```
Restart ComfyUI if running and the manager should pop up on the right screen side.

But if you want to have a realy cool Manager then install all the Nodes of the Workflow: **Refined(upscale)** and you will see.

### 3. Choose and Download Models

Next, download the models you’d like to work with. Here are some options:

- **Flux Models**  
  - **dev**: [Download FLUX.1-dev](https://huggingface.co/black-forest-labs/FLUX.1-dev/tree/main) *(Requires Login)*
  - **schnell**: [Download FLUX.1-schnell](https://huggingface.co/black-forest-labs/FLUX.1-schnell/tree/main) *(No Login)*
  - **dev-gguf**: [Download FLUX.1-dev-gguf](https://huggingface.co/city96/FLUX.1-dev-gguf/tree/main) *(No Login)*
  - **schnell-gguf**: [Download FLUX.1-schnell-gguf](https://huggingface.co/city96/FLUX.1-schnell-gguf/tree/main) *(No Login)*

- **Additional Model Requirements**
  - **Text Encoders**: [Download Flux Text Encoders](https://huggingface.co/comfyanonymous/flux_text_encoders/tree/main)
  - **VAE (Variational AutoEncoder)**: [Download VAE](https://huggingface.co/black-forest-labs/FLUX.1-schnell/tree/main/vae)
 
### 4. Upscale Models

- **RealESRGAN**: [Download Real-ESRGAN](https://huggingface.co/ai-forever/Real-ESRGAN) *(.pth PyTorch-spezific, direct --> Workflow: Refined(upscale))*
- **More**: [Download Collection](https://huggingface.co/yuvraj108c/ComfyUI-Upscaler-Onnx/tree/main) *(.onnx Cross-platform, optimized --> custom Nodes)*

### 5. Example Workflows

In this repository, you will find example workflows specifically optimized for Flux image generation. These workflows can help you get started quickly with your projects.

## Tutorials and Resources

- **Resources**: [Models, VAE, Encoders](https://huggingface.co/)
- **Resources**: [Models, Loras, Checkpoints](https://civitai.com/)


Here are some helpful video guides to assist you with setup and usage:

- **Image Generation**: [Watch on YouTube](https://www.youtube.com/watch?v=z3v55ax_PSU)
- **Video Generation**: [Watch on YouTube](https://youtu.be/UD3ZFLj-3uE?si=LOt8sYjU02TnH5BH)

## Get Started

Once you’ve completed the setup, you're ready to start creating! Enjoy exploring the creative possibilities of Flux-powered image and video generation with ComfyUI.
