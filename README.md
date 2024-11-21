# image-generator
This project utilizes the Stable Diffusion model for generating high-quality images from text prompts.

By leveraging the diffusers library, the model produces visually captivating outputs tailored to user inputs. Running on a CUDA-enabled GPU with torch.float16, it ensures efficient computation and seamless integration for rapid text-to-image generation.

Technical Workflow:
The Stable Diffusion v2.1 model is fine-tuned with the DPMSolverMultistepScheduler for optimized performance. Users provide text prompts (e.g., "a dog licking the moon") to generate 400x400 pixel images. The results are displayed using Matplotlib, offering a simple yet powerful method to visualize creative AI-generated visuals.
