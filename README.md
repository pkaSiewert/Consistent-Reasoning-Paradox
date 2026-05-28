# Consistent-Reasoning-Paradox
We share the prompts we tested to illustrate the theoretical results of the preprint "Necessary mechanisms for super AI and stopping hallucinations: The consistent reasoning paradox and the indeterminacy function".

Figures 4, 5, and 6 of the main paper report the behaviour of GPT-5.5 Pro Deep Research, Codex, and DeepSeek V4-Pro on a selection of prompts we designed. Figure 4 has the prompts 4a, 4b, and 4c, Figure 5 has the prompts 5a, 5b, 5c, and 5d, and Figure 6 has the prompts 5a, 5b-alt, 5c-alt, and 5d-alt. This repository also contains information on earlier models that we collected for earlier versions of the paper.

It is perhaps unsurprising that all models are able to correctly answer prompts 4a, 4b, 4c, and 5a (though they do make mistakes sometimes). We record this in the directory Successes.

The prompts 5b, 5c, and 5d were tested 15 times each on ChatGPT 5 Thinking and 10 times each on DeepSeek R1. The prompts 5b-alt, 5c-alt, and 5d-alt were tested 10 times each on DeepSeek V3.1-Think and ChatGPT 5.5. The number of correct responses are recorded in the following table.

| Prompt | ChatGPT 5 Thinking <br> correct out of 15 | GPT-5.5 pro <br> correct out of 10 | Codex <br> correct out of 10 |  DeepSeek R1 <br> correct out of 10| DeepSeek V3.1-Think <br> correct out of 10 (alt) | DeepSeek V4-Pro <br> correct out of 15 |
|:------:|:------------------:|:-----:|:----:|:-----------:|:------------------:|:---:|
| 5b     | 4                  |   4   | tbd  |  3          | 3                  |  3  |
| 5c     | 2                  |   4   | tbd  |   0         | 2                  |  2  |
| 5d     | 4                  |  tbd  | tbd  |   5         | 5                  | tbd | 

Thus it is clear that none of the models is able to consistently answer the respective prompts correctly.
