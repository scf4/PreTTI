# Miscellaneous Notes

A collection of notes of potential methods for improved image generation.

## Negative weighting

People have reported the use of negatively-weighted context-dependent words and phrases to reduce flaws such as additional limbs. 

The effectiveness of this is unclear.

**Human anatomy**

> bad anatomy, extra legs, extra arms, extra fingers, poorly drawn hands, poorly drawn feet, disfigured, out of frame, tiling, bad art, deformed, mutated ([@BrentOzar](https://github.com/BrentOzar/stable-diffusion/blob/766028cff9de7fe1f86f8a73f21f6c5efe09aca4/docs/features/PROMPTS.md))

> Personally stopped using "mutated", and "extra" on my negative prompts a long time ago since they seemed to have no effect. I've had more success using "fused _bodypart_" instead. ([reddit.com](https://www.reddit.com/r/StableDiffusion/comments/xsrxhl/negative_prompt_is_just_as_important_as_the_main/))

> I very much doubt that SD is drawing bad limbs because it's actually drawing from pictures that were tagged "deformed" or "extra limbs". Instead, I think this helps (if it actually even does) because negating "limbs" or "hands" reduces the emphasis on those parts, making them less likely to be featured clearly in the picture. But I'd love to see someone do extensive testing on this. ([reddit.com](https://www.reddit.com/r/StableDiffusion/comments/xsrxhl/negative_prompt_is_just_as_important_as_the_main/))