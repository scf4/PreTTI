# PreTTI: Improving Text-to-Image Models with Large Language Models

The goal of this project is to explore potential uses of large language models for the task of improving current state of the art [text-to-image models](https://en.wikipedia.org/wiki/Text-to-image_model) such as [Stable Diffusion](https://github.com/CompVis/stable-diffusion).
## The state of prompt writing

Writing optimal text prompts to best guide a text-to-image model towards a desired result can be a complex task, often requiring the use of seemingly arbitrary keywords and various style modifiers.

Heavy use of these modifiers is common practice among experienced users due to their frequent positive effect on subjective aesthetic quality, as well as their ability to generate images more closely aligned with the desired result. Even subtle changes in word placement can have a significant effect, creating potentially unnecessary work for even the most skilled prompt writers.

Given this complexity and lack of intuitiveness, prompt input as UI for text-to-image models is currently less than ideal.

## Next steps

This project is currently in the exploratory phase. We welcome any and all feedback from the community and would love to discuss potential proposals with anyone interested in the project. Check out the [discussions](https://github.com/scf4/PreTTI/discussions) tab to get started.

# Proposals

Name | Description | Status
---|---|---
[Initial experiment](/proposals/000-INITIAL.md) | Expand prompt detail with a LLM | Complete
[Trained “Unsimplification” Model](/proposals/001-UNSIMPLIFY_MODEL.md) | Train a model to “unsimplify” prompts | Feedback requested
