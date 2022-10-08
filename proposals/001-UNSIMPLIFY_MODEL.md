# Training a language model to “unsimplify” text prompts

There are many [large sets](https://github.com/Jeremy-Fuller/Prompts/blob/main/prompts.txt) of curated, carefully-crafted text-to-image prompts that will generally produce high quality images compared to a simplified version of the same prompt.

By using an LLM to take a large curated set of prompts and simplify each one to only its core elements, we could easily create a dataset of simple<->crafted prompt-pairs.

For example, the crafted prompt *"Keanu Reeves as spiderman, muscle extremely detailed, fantastic details full face, mouth, trending on artstation, pixiv, cgsociety, hyperdetailed Unreal Engine 4k 8k ultra HD, WLOP"* would be stripped down to the much more natural *"Keanu Reeves as Spiderman"*.

We could then train a language model to reverse this process (effectively “unsimplifying” prompts).

Further improvements could be made possible by iterating based on real-world feedback.

Could we train a language model to more closely align the language of the image model with the language of those writing prompts, even those already well-experienced with writing prompts for text-to-image models?

Could such a model even learn from patterns such as the ordering of miscellaneous keywords in order to produce more desirable results?