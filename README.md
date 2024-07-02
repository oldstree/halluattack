# HALLUATTACK-Mitigating-Hallucinations-in-LLMs-via-Counterfactual-Instruction-Fine-Tuning
## abstract
LLMs encapsulate a vast range of world knowledge with huge mount of pretraining data. While these models have demonstrated remarkable capabilities in various applications, they are prone to generating content infused with hallucinations, compromising the trustworthiness of their output. This phenomenon raises concerns of LLM applications, particularly when the dissemination of misleading information can have detrimental impacts. In this paper, we propose a simple yet effective method called \textsc{HalluAttack} which generates high quality counterfactual instruction data in order to reduce the hallucinations. We observe that these counterfactual instruction data can unlock the self-reflection ability of LLMs, and the LLMs will use knowledge learnt from pretraining phase more accurately. We conducted experiments across multiple open-source LLMs to evaluate the effectiveness of our proposed approach\footnote{The data we used for fine-tuning is publicly available in \url{https://github.com/oldstree/halluattack}}. Results consistently demonstrate that, through counterfactual attack and subsequent fine-tuning, we are able to significantly improve the model performance on hallucination benchmarks (e.g. TruthfulQA and HalluQA). Moreover, we also find that the LLMs fine-tuned with counterfactual instruction data can also achieve gains on public general benchmarks like C-Eval, MMLU and GSM8K, which also demonstrate the effectiveness of our approach on hallucination mitigation.
