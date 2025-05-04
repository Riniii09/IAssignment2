# LoRA Fine-Tuned Stable Diffusion

This project fine-tunes Stable Diffusion using LoRA and generates images with the trained model.

## Steps

1. **Prepare Dataset**
   - Collected and processed images for training.

2. **Train with LoRA**
   - Used `diffusers` and LoRA method for efficient training.
   - Output saved as `pytorch_lora_weights.safetensors`.

3. **Load Model**
   - Loaded base Stable Diffusion model (`v1-5` or `2-1`).
   - Applied the trained LoRA weights.

4. **Generate Images**
   - Prompt-based image generation using the pipeline.
   - Example: `"A watercolour style image of sam123 in a spacesuit"`

5. **Download Trained Weights**
   - Exported LoRA weights for reuse or sharing.

## Notes

- LoRA warning during generation is safe to ignore.
- Image generation requires a GPU.
- **This task actually needs a larger dataset** for better results.


