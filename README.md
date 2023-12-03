# Awesome papers on LLMs detection
This repo is a curated list of papers about detection of LLMs-generated content. It includes most lastest papers about detection methods, datasets, attack, etc. We will consistently update this repo to include the most recent papers.

<div style="text-align: center">
<img src="main.jpg" atl="banner"/>
</div>


# Contents
- [Awesome_papers_on_LLMs_detection](#awesome_papers_on_LLMs_detection)
- [Contents](#contents)
- [Training-based Methods](#Training-based)
	- [Black-box](#black-box)
        - [2023](#2023)
        - [2022](#2022)
		- [2020](#2020)
	- [White-box](#white-box)
        - [2023](#2023-1)
        - [2019](#2019)
- [Zero-shot Methods](#zero-shot)
	- [Black-box](#black-box-1)
        - [2023](#2023-2)
	- [White-box](#white-box-1)
        - [2023](#2023-3)
        - [Before 2020](#before-2020)
- [Watermarking](#watermarking)
	- [Black-box](#black-box-2)
        - [2023](#2023-4)
        - [2022](#2022-1)
	- [White-box](#white-box-2)
        - [2023](#2023-5)
- [Attack](#attack)
- [Datasets](#datasets)
    - [2023](#2023-6)
    - [2022 and before](#2022-and-before)
- [Misc](#misc)

# Training-based
## Black-box
### 2023
+   **Token Prediction as Implicit Classification to Identify LLM-Generated Text** [[pdf]](https://arxiv.org/abs/2311.08723) Nov. 15, 2023
+   **AuthentiGPT: Detecting Machine-Generated Text via Black-Box Language Models Denoising** [[pdf]](https://arxiv.org/abs/2311.07700) Nov. 14, 2023
+   **G3Detector: General GPT-Generated Text Detector** [[pdf]](https://arxiv.org/abs/2305.12680)
+   **GPT-Sentinel: Distinguishing Human and ChatGPT Generated Content** [[pdf]](https://arxiv.org/abs/2305.07969)
+   **GPT Paternity Test: GPT Generated Text Detection with GPT Genetic Inheritance** [[pdf]](https://arxiv.org/abs/2305.12519)
### 2022
+   **OpenAI Text Classifier** [[link]](https://beta.openai.com/ai-text-classifier)
+   **GPTZero** [[link]](https://gptzero.me/)
+   **CoCo: Coherence-Enhanced Machine-Generated Text Detection Under Data Limitation With Contrastive Learning** [[pdf]](https://arxiv.org/abs/2212.10341)
+   **LLMDet: A Large Language Models Detection Tool** [[pdf]](https://arxiv.org/abs/2305.15004)
+   **Multiscale Positive-Unlabeled Detection of AI-Generated Texts** [[pdf]](https://arxiv.org/abs/2305.18149)
+   **RADAR: Robust AI-Text Detection via Adversarial Learning** [[pdf]](https://arxiv.org/abs/2307.03838)
+   **On the Zero-Shot Generalization of Machine-Generated Text Detectors** [[pdf]](https://arxiv.org/abs/2310.05165)
+   **ConDA: Contrastive Domain Adaptation for AI-generated Text Detection** [[pdf]](https://arxiv.org/abs/2309.03992)
+   **From Text to Source: Results in Detecting Large Language Model-Generated Content** [[pdf]](https://arxiv.org/abs/2309.13322)
+   **Ghostbuster: Detecting Text Ghostwritten by Large Language Models** [[pdf]](https://arxiv.org/abs/2305.15047)
+   **Deepfake Text Detection in the Wild** [[pdf]](https://arxiv.org/abs/2305.13242)
### 2020
+   **Automatic Detection of Generated Text is Easiest when Humans are Fooled** [[pdf]](https://aclanthology.org/2020.acl-main.164/)
## White-box
### 2023
+   **SeqXGPT: Sentence-Level AI-Generated Text Detection** [[pdf]](https://arxiv.org/abs/2310.08903)
+   **Origin Tracing and Detecting of LLMs** [[pdf]](https://arxiv.org/abs/2304.14072)
### 2019
+   **GLTR: Statistical Detection and Visualization of Generated Text** [[pdf]](https://arxiv.org/abs/1906.04043)
+   **Release strategies and the social impacts of language models** [[pdf]](https://arxiv.org/abs/1908.09203)

# Zero-shot
## Black-box
### 2023
+   **Detectgpt: Zero-shot machine-generated text detection using probability curvature** [[pdf]](https://arxiv.org/abs/2301.11305)
+   **DNA-GPT: Divergent N-Gram Analysis for Training-Free Detection of GPT-Generated Text** [[pdf]](https://arxiv.org/abs/2305.17359)
+   **Paraphrasing evades detectors of AI-generated text, but retrieval is an effective defense** [[pdf]](https://arxiv.org/abs/2303.13408)
+   **Smaller Language Models are Better Black-box Machine-Generated Text Detectors** [[pdf]](https://arxiv.org/abs/2305.09859)
+   **Intrinsic Dimension Estimation for Robust Detection of AI-Generated Texts** [[pdf]](https://arxiv.org/abs/2306.04723)
## White-box
### 2023
+   **DNA-GPT: Divergent N-Gram Analysis for Training-Free Detection of GPT-Generated Text** [[pdf]](https://arxiv.org/abs/2305.17359)
+   **DetectLLM: Leveraging Log Rank Information for Zero-Shot Detection of Machine-Generated Text** [[pdf]](https://arxiv.org/abs/2306.05540)
+   **Fast-DetectGPT: Efficient Zero-Shot Detection of Machine-Generated Text via Conditional Probability Curvature** [[pdf]](https://arxiv.org/abs/2310.05130)
+   **GPT-who: An Information Density-based Machine-Generated Text Detector** [[pdf]](https://arxiv.org/abs/2310.06202)
+   **Efficient Detection of LLM-generated Texts with a Bayesian Surrogate Model** [[pdf]](https://arxiv.org/abs/2305.16617)

### Before 2020
+   **Detecting Fake Content with Relative Entropy Scoring** [[pdf]](https://ceur-ws.org/Vol-377/paper4.pdf)
+   **Computer-generated text detection using machine learning: A systematic review** [[pdf]](https://link.springer.com/chapter/10.1007/978-3-319-41754-7_43)
+   **GLTR: Statistical Detection and Visualization of Generated Text** [[pdf]](https://arxiv.org/abs/1906.04043)

# Watermarking
## Black-box
### 2023
+   **Watermarking Text Generated by Black-Box Language Models** [[pdf]](https://arxiv.org/abs/2305.08883)
### 2022
+   **Tracing text provenance via context-aware lexical substitution** [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/21415)

### Before 2020
+   **Natural language watermarking and tamperproofing** [[pdf]](https://link.springer.com/chapter/10.1007/3-540-36415-3_13)
+   **Natural language watermarking** [[pdf]](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/5681/0000/Natural-language-watermarking/10.1117/12.593790.full?SSO=1)
+   **Natural language watermarking via morphosyntactic alterations** [[pdf]](https://www.sciencedirect.com/science/article/pii/S0885230808000284)
+   **The hiding virtues of ambiguity: quantifiably resilient watermarking of natural language text through synonym substitutions** [[pdf]](https://dl.acm.org/doi/abs/10.1145/1161366.1161397)

## White-box
### 2023
+   **I Know You Did Not Write That! A Sampling-Based Watermarking Method for Identifying Machine Generated Text** [[pdf]](https://arxiv.org/abs/2311.18054) 30/11/2023
+   **Improving the Generation Quality of Watermarked Large Language Models via Word Importance Scoring** [[pdf]](https://arxiv.org/abs/2311.09668) 16/11/2023
+   **Performance Trade-offs of Watermarking Large Language Models** [[pdf]](https://arxiv.org/abs/2311.09816) 16/11/2023
+   **X-Mark: Towards Lossless Watermarking Through Lexical Redundancy** [[pdf]](https://arxiv.org/abs/2311.09832) 16/11/2023
+   **WaterBench: Towards Holistic Evaluation of Watermarks for Large Language Models** [[pdf]](https://arxiv.org/abs/2311.07138) 13/11/2023
+   **Publicly Detectable Watermarking for Language Models** [[pdf]](https://arxiv.org/abs/2310.18491) 25/10/2023
+   **Unbiased Watermark for Large Language Models** [[pdf]](https://arxiv.org/abs/2310.10669) 18/10/2023
+   **A watermark for large language models** [[pdf]](https://arxiv.org/abs/2301.10226)
+   **Undetectable Watermarks for Language Models** [[pdf]](https://arxiv.org/abs/2306.09194)
+   **Provable Robust Watermarking for AI-Generated Text** [[pdf]](https://arxiv.org/abs/2306.17439)
+   **Robust Distortion-free Watermarks for Language Models** [[pdf]](https://arxiv.org/abs/2307.15593)
+   **SemStamp: A Semantic Watermark with Paraphrastic Robustness for Text Generation** [[pdf]](https://arxiv.org/abs/2310.03991)
+   **DiPmark: A Stealthy, Efficient and Resilient Watermark for Large Language Models** [[pdf]](https://arxiv.org/abs/2310.07710)
+   **Watermarking Conditional Text Generation for AI Detection: Unveiling Challenges and a Semantic-Aware Watermark Remedy** [[pdf]](https://arxiv.org/abs/2307.13808)
+   **A Semantic Invariant Robust Watermark for Large Language Models** [[pdf]](https://arxiv.org/abs/2310.06356)
+   **REMARK-LLM: A Robust and Efficient Watermarking Framework for Generative Large Language Models** [[pdf]](https://arxiv.org/abs/2310.12362)
+   **Robust Multi-bit Natural Language Watermarking through Invariant Features** [[pdf]](https://aclanthology.org/2023.acl-long.117/)
+   **Advancing Beyond Identification: Multi-bit Watermark for Language Models** [[pdf]](https://arxiv.org/abs/2308.00221)
+   **Three Bricks to Consolidate Watermarks for Large Language Models** [[pdf]](https://arxiv.org/abs/2308.00113)
### 2022
+   **My AI safety lecture for UT Effective Altruism** [[Link]](https://scottaaronson.blog/?p=6823)

# Code-detection
+   **Zero-Shot Detection of Machine-Generated Codes** [[pdf]](https://arxiv.org/abs/2310.05103)
+   **Who Wrote this Code? Watermarking for Code Generation** [[pdf]](https://arxiv.org/abs/2305.15060)



# Attack
+    **A Ship of Theseus: Curious Cases of Paraphrasing in LLM-Generated Texts** [[pdf]](https://arxiv.org/abs/2311.08374) Nov. 14, 2023
+   **Watermarks in the Sand: Impossibility of Strong Watermarking for Generative Models** [[pdf]](https://arxiv.org/abs/2311.04378) 11/8/2023
+   **Does Human Collaboration Enhance the Accuracy of Identifying LLM-Generated Deepfake Texts?** [[pdf]](https://arxiv.org/abs/2304.01002)
+   **Paraphrasing evades detectors of AI-generated text, but retrieval is an effective defense** [[pdf]](https://arxiv.org/abs/2303.13408)
+   **Red Teaming Language Model Detectors with Language Models** [[pdf]](https://arxiv.org/abs/2305.19713)
+   **Paraphrase Detection: Human vs. Machine Content** [[pdf]](https://arxiv.org/abs/2303.13989)
+   **Large Language Models can be Guided to Evade AI-Generated Text Detection** [[pdf]](https://arxiv.org/abs/2305.10847)
+   **Counter Turing Test CT\^2: AI-Generated Text Detection is Not as Easy as You May Think -- Introducing AI Detectability Index** [[pdf]](https://arxiv.org/abs/2310.05030)
+   **How Reliable Are AI-Generated-Text Detectors? An Assessment Framework Using Evasive Soft Prompts** [[pdf]](https://arxiv.org/abs/2310.05095)
+   **On the Reliability of Watermarks for Large Language Models** [[pdf]](https://arxiv.org/abs/2306.04634)

# Datasets
### 2023
+   **How Close is ChatGPT to Human Experts? Comparison Corpus, Evaluation, and Detection** [[pdf]](https://arxiv.org/abs/2301.07597)
+   **CHEAT: A Large-scale Dataset for Detecting ChatGPT-writtEn AbsTracts** [[pdf]](https://arxiv.org/abs/2304.12008)
+   **Ghostbuster: Detecting Text Ghostwritten by Large Language Models** [[pdf]](https://arxiv.org/abs/2305.15047)
+   **M4: Multi-generator, Multi-domain, and Multi-lingual Black-Box Machine-Generated Text Detection** [[pdf]](https://arxiv.org/abs/2305.14902)
+   **GPT-Sentinel: Distinguishing Human and ChatGPT Generated Content** [[pdf]](https://arxiv.org/abs/2305.07969)
+   **Mgtbench: Benchmarking machine-generated text detection** [[pdf]](https://arxiv.org/abs/2303.14822)
+   **HC3 Plus: A Semantic-Invariant Human ChatGPT Comparison Corpus** [[pdf]](https://arxiv.org/abs/2309.02731)
+   **MULTITuDE: Large-Scale Multilingual Machine-Generated Text Detection Benchmark** [[pdf]](https://arxiv.org/abs/2310.13606v1)
### 2022 and before
+   **TURINGBENCH: A Benchmark Environment for Turing Test in the Age of Neural Text Generation** [[pdf]](https://aclanthology.org/2021.findings-emnlp.172/)

# Misc
+   **LLM- Detect AI Generated Text. Kaggle.** [[link]](https://www.kaggle.com/competitions/llm-detect-ai-generated-text?utm_medium=email&utm_source=gamma&utm_campaign=comp-llm-text-2023)
+   **Can AI-Generated Text be Reliably Detected?** [[pdf]](https://arxiv.org/abs/2303.11156)
+   **On the Possibilities of AI-Generated Text Detection** [[pdf]](https://arxiv.org/abs/2304.04736)
+   **GPT detectors are biased against non-native English writers** [[pdf]](https://arxiv.org/abs/2304.02819)
+   **ChatLog: Recording and Analyzing ChatGPT Across Time** [[pdf]](https://arxiv.org/abs/2304.14106)
+   **On the Zero-Shot Generalization of Machine-Generated Text Detectors** [[pdf]](https://arxiv.org/abs/2310.05165)


If you find this repo useful, please cite our work.
```latex
@article{yang2023survey,
  title={A Survey on Detection of LLMs-Generated Content},
  author={Yang, Xianjun and Pan, Liangming and Zhao, Xuandong and Chen, Haifeng and Petzold, Linda and Wang, William Yang and Cheng, Wei},
  journal={arXiv preprint arXiv:2310.15654},
  year={2023}
}
```
