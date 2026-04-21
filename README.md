## Instructions:
1. Load main.ipynb into Google Collab
2. Add huggingface token called 'HF_TOKEN' as Collab secret
3. Select A100 or L4 as GPU
4. Run all cells

## Video:
https://umsystem.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=0af1a6fe-09ce-4fa7-ad46-b43300592972

## Misc.
Dataset Description

    Source: Raw Amazon product metadata.

    Content: High-density technical strings including Product Titles and Feature Bullet Points.

    Preprocessing: Metadata is dynamically parsed and mapped into two categories: Naive (raw concatenation) and Structured (LLM-templated photographic descriptors).

Tools and Libraries

    Core Frameworks: PyTorch, Diffusers, Transformers, Accelerate.

    Generative Models: SDXL Turbo (Drafting), SDXL 1.0 (Refinement), Zero123++ (3D Synthesis).

    Evaluation Metrics: Jina-CLIP (Alignment), LPIPS (Diversity), Cafe-Aesthetic (Quality).

    Hardware: Nvidia A100 GPU (40GB VRAM).

    Utilities: Pandas, Matplotlib, PIL (Pillow).
