# Consistent-Reasoning-Paradox
We share the prompts we tested to illustrate the theoretical results of the preprint "Necessary mechanisms for super AI and stopping hallucinations: The consistent reasoning paradox and the indeterminacy function".

Figures 4, 5, and 6 of the main paper report the behaviour of GPT-5.5 Pro Deep Research extended, Codex, and DeepSeek V4-Pro Preview on a selection of prompts we designed. Figure 4 has the prompts 4a, 4b, and 4c, Figure 5 has the prompts 5a, 5b, 5c, and 5d-new, and Figure 6 has the prompts 5a, 5b-alt, 5c-alt, and 5d-var. This repository also contains data from older models that we collected for earlier versions of the paper.

It is perhaps unsurprising that all models are able to correctly answer prompts 4a, 4b, 4c, and 5a (though they do make mistakes sometimes). We record this in the directory Successes.

The prompts 5b and 5c were tested on ChatGPT 5 Thinking, DeepSeek R1, GPT-5.5 Pro, and Codex. The prompts 5b-alt and 5c-alt were tested on DeepSeek V3.1-Think and DeepSeek V4-Pro. The prompt 5d was tested on ChatGPT 5 Thinking and DeepSeek R1. The prompt 5d-new was tested on both GPT-5.5 Pro and Codex. The prompt 5d-alt was tested on DeepSeek V3.1-Think. The prompt 5d-var was tested on DeepSeek V4-Pro. The numbers of correct responses are recorded in the following table. Each prompt was run 10 times per model, except for ChatGPT 5 Thinking and DeepSeek V4-Pro, where we ran 15 times.

| Prompt | ChatGPT 5 Thinking <br> correct out of 15 | GPT-5.5 Pro <br> correct out of 10 (new) | Codex <br> correct out of 10 (new) |  DeepSeek R1 <br> correct out of 10| DeepSeek V3.1-Think <br> correct out of 10 (alt) | DeepSeek V4-Pro <br> correct out of 15 (alt/var) |
|:------:|:------------------:|:-----:|:----:|:-----------:|:------------------:|:---:|
| 5b     | 4                  |   4   |  3   |   3         | 3                  |  3  |
| 5c     | 2                  |   0   |  0   |   0         | 2                  |  2  |
| 5d     | 4                  |   4   |  3   |   5         | 5                  |  7  | 

Thus it is clear that none of the models is able to consistently answer the respective prompts correctly.
