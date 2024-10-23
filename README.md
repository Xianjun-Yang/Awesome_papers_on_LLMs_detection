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
   		- [2024](#2024-1)
        	- [2023](#2023-2)
	- [White-box](#white-box-1)
        - [2023](#2023-3)
        - [Before 2020](#before-2020)
- [Watermarking](#watermarking)
	- [Black-box](#black-box-2)
 	- [2024](#2024-2)	 
        - [2023](#2023-4)
        - [2022](#2022-1)
	- [White-box](#white-box-2)
        - [2024](#2024-3)
   	- [2023](#2023-5)
- [Attack](#attack)
- [Datasets](#datasets)
    - [2024](#2024-4)
    - [2023](#2023-6)
    - [2022 and before](#2022-and-before)
- [Misc](#misc)

# Training-based
## Black-box
### 2024
+   **EAGLE: A Domain Generalization Framework for AI-generated Text Detection** [[pdf]](https://arxiv.org/pdf/2403.15690.pdf) 03/25/2024
### 2023
+   **DETECTING MACHINE-GENERATED TEXTS BY MULTI-POPULATION AWARE OPTIMIZATION FOR MAXIMUM MEAN DISCREPANCY** [[pdf]](https://arxiv.org/pdf/2402.16041.pdf) 02/27/2024
+   **Threads of Subtlety: Detecting Machine-Generated Texts Through Discourse Motifs** [[pdf]](https://arxiv.org/pdf/2402.10586.pdf) 02/19/2024
+   **LLM-Detector: Improving AI-Generated Chinese Text Detection with Open-Source LLM Instruction Tuning** [[pdf]](https://arxiv.org/pdf/2402.01158.pdf) 02/04/2024
+   **FEW-SHOT DETECTION OF MACHINE-GENERATED TEXT USING STYLE REPRESENTATIONS** [[pdf]](https://arxiv.org/pdf/2401.06712.pdf) 01/12, 2024
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
### 2024
+   **Improving Logits-based Detector without Logits from Black-box LLMs** [[pdf]](https://arxiv.org/abs/2406.05232) 06/11/2024
### 2023
+   **Ten Words Only Still Help: Improving Black-Box AI-Generated Text Detection via Proxy-Guided Efficient Re-Sampling** [[link]](https://arxiv.org/pdf/2402.09199.pdf) 15/02/2024
+   **Raidar: geneRative AI Detection viA Rewriting** [[link]](https://arxiv.org/abs/2401.12970) 23/01/2024
+   **SPOTTING LLMS WITH BINOCULARS: ZERO-SHOT DETECTION OF MACHINE-GENERATED TEXT** [[link]](https://arxiv.org/abs/2401.12070)
+   **Detectgpt: Zero-shot machine-generated text detection using probability curvature** [[pdf]](https://arxiv.org/abs/2301.11305)
+   **DNA-GPT: Divergent N-Gram Analysis for Training-Free Detection of GPT-Generated Text** [[pdf]](https://arxiv.org/abs/2305.17359)
+   **Paraphrasing evades detectors of AI-generated text, but retrieval is an effective defense** [[pdf]](https://arxiv.org/abs/2303.13408)
+   **Smaller Language Models are Better Black-box Machine-Generated Text Detectors** [[pdf]](https://arxiv.org/abs/2305.09859)
+   **Intrinsic Dimension Estimation for Robust Detection of AI-Generated Texts** [[pdf]](https://arxiv.org/abs/2306.04723)
## White-box
### 2024
+   **Detecting Machine-Generated Long-Form Content with Latent-Space Variables** [[pdf]](https://arxiv.org/pdf/2410.03856) 10/04/2024
+   **Zero-Shot Detection of LLM-Generated Text using Token Cohesiveness** [[pdf]](https://arxiv.org/pdf/2409.16914) 09/25/2024
### 2023
+   **Does DETECTGPT Fully Utilize Perturbation? Selective Perturbation on Model-Based Contrastive Learning Detector would be Better** [[pdf]](https://arxiv.org/pdf/2402.00263.pdf) 02/03/2024
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
### 2024
+   **POSTMARK: A Robust Blackbox Watermark for Large Language Models**  [[pdf]](https://arxiv.org/pdf/2406.14517) 06/20/2024
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
### 2024
+   **Less is More: Sparse Watermarking in LLMs with Enhanced Text Quality**   [[pdf]](https://arxiv.org/pdf/2407.13803)  07/21/2024
+   **Waterfall: Framework for Robust and Scalable Text Watermarking** [[pdf]](https://arxiv.org/pdf/2407.04411)  07/08/2024
+   **A Resilient and Accessible Distribution-Preserving Watermark for Large Language Models** [[pdf]](https://openreview.net/pdf?id=c8qWiNiqRY)  06/27/2024
+   **CODEIP: A Grammar-Guided Multi-Bit Watermark for Large Language Models of Code** [[pdf]](https://arxiv.org/pdf/2404.15639)  04/25/2024
+   **Watermark-based Detection and Attribution of AI-Generated Content** [[pdf]](https://arxiv.org/pdf/2404.04254.pdf)  04/07/2024
+   **A Statistical Framework of Watermarks for Large Language Models: Pivot, Detection Efficiency and Optimal Rules** [[pdf]](https://arxiv.org/pdf/2404.01245.pdf)  04/01/2024
+   **WaterJudge: Quality-Detection Trade-off when Watermarking Large Language Models** [[pdf]](https://arxiv.org/pdf/2403.19548.pdf) 03/29/2024
+   **Duwak: Dual Watermarks in Large Language Models** [[pdf]](https://arxiv.org/pdf/2403.13000.pdf) 03/20/2024
+   **WaterMax: breaking the LLM watermark detectability-robustness-quality trade-off** [[pdf]](https://arxiv.org/pdf/2403.04808.pdf) 03/11/2024
+   **Token-Specific Watermarking with Enhanced Detectability and Semantic Coherence for Large Language Models** [[link]](https://arxiv.org/pdf/2402.18059.pdf) 02/28/2024
+   **EmMark: Robust Watermarks for IP Protection of Embedded Quantized Large Language Models** [[link]](https://arxiv.org/pdf/2402.17938.pdf) 02/28/2024
+   **Multi-Bit Distortion-Free Watermarking for Large Language Models** [[link]](https://arxiv.org/pdf/2402.16578.pdf) 02/27/2024
+   **Can Watermarks Survive Translation? On the Cross-lingual Consistency of Text Watermark for Large Language Models** [[pdf]](https://arxiv.org/pdf/2402.14007.pdf) 02/22/2024
+   **GumbelSoft: Diversified Language Model Watermarking via the GumbelMax-trick** [[link]](https://arxiv.org/pdf/2402.12948.pdf) 20/02/2024
+   **k-SEMSTAMP : A Clustering-Based Semantic Watermark for Detection of Machine-Generated Text** [[link]](https://arxiv.org/pdf/2402.11399.pdf) 19/02/2024
+   **Permute-and-Flip: An optimally robust and watermarkable decoder for LLMs** [[link]](https://arxiv.org/abs/2402.05864) 08/02/2024
+   **Provably Robust Multi-bit Watermarking for AI-generated Text via Error Correction Code** [[link]](https://arxiv.org/abs/2401.16820) 30/01/2024
+   **Adaptive Text Watermark for Large Language Models** [[pdf]](https://arxiv.org/pdf/2401.13927.pdf) 26/01/2024
### 2023
+   **WatME: Towards Lossless Watermarking Through Lexical Redundancy** [[pdf]](https://arxiv.org/abs/2311.09832) 16/11/2023
+   **Optimizing watermarks for large language models** [[pdf]](https://arxiv.org/pdf/2312.17295.pdf) 31/12/2023
+   **Hey That’s Mine! Imperceptible Watermarks are Preserved in Diffusion Generated Outputs** [[pdf]](https://arxiv.org/pdf/2308.11123)  11/09/2023
+   **Towards Optimal Statistical Watermarking** [[pdf]](https://arxiv.org/pdf/2312.07930.pdf) 13/12/2023
+   **ON THE LEARNABILITY OF WATERMARKS FOR LANGUAGE MODELS** [[pdf]](https://arxiv.org/pdf/2312.04469.pdf) 7/12/2023
+   **Mark My Words: Analyzing and Evaluating Language Model Watermarks** [[pdf]](https://arxiv.org/abs/2312.00273) 3/12/2023
+   **I Know You Did Not Write That! A Sampling-Based Watermarking Method for Identifying Machine Generated Text** [[pdf]](https://arxiv.org/abs/2311.18054) 30/11/2023
+   **TOWARDS CODABLE WATERMARKING FOR INJECTING MULTI-BIT INFORMATION TO LLM** [[pdf]](https://arxiv.org/abs/2307.15992) 27/11/2023
+   **Improving the Generation Quality of Watermarked Large Language Models via Word Importance Scoring** [[pdf]](https://arxiv.org/abs/2311.09668) 16/11/2023
+   **Performance Trade-offs of Watermarking Large Language Models** [[pdf]](https://arxiv.org/abs/2311.09816) 16/11/2023
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
+   **RAFT: Realistic Attacks to Fool Text Detectors** [[pdf]](https://arxiv.org/pdf/2410.03658) 10/04/2024
+   **AI-generated text boundary detection with RoFT** [[pdf]](https://arxiv.org/pdf/2311.08349) 09/04/2024
+   **A Transfer Attack to Image Watermarks** [[pdf]](https://arxiv.org/pdf/2403.15365) 09/12/2024
+   **LLM Detectors Still Fall Short of Real World: Case of LLM-Generated Short News-Like Posts** [[pdf]](https://arxiv.org/pdf/2409.03291) 09/05/2024
+   **Watermark Smoothing Attacks against Language Models** [[pdf]](https://arxiv.org/pdf/2407.14206) 07/19/2024
+   **Investigating the Influence of Prompt-Specific Shortcuts in AI Generated Text Detection** [[pdf]](https://arxiv.org/pdf/2406.16275) 06/20/2024
+   **Black-Box Detection of Language Model Watermarks** [[pdf]](https://arxiv.org/abs/2405.20777) 05/28/2024
+   **Humanizing Machine-Generated Content: Evading AI-Text Detection through Adversarial Attack** [[pdf]](https://arxiv.org/pdf/2404.01907.pdf) 04/01/2024
+   **Bypassing LLM Watermarks with Color-Aware Substitutions** [[pdf]](https://arxiv.org/pdf/2403.14719.pdf) 03/19/2024
+   **Watermark Stealing in Large Language Models** [[pdf]](https://arxiv.org/pdf/2402.19361v1.pdf) 02/29/2024
+   **Attacking LLM Watermarks by Exploiting Their Strengths** [[pdf]](https://arxiv.org/pdf/2402.16187.pdf) 02/27/2024
+   **Can Watermarks Survive Translation? On the Cross-lingual Consistency of Text Watermark for Large Language Models** [[pdf]](https://arxiv.org/pdf/2402.14007.pdf) 02/22/2024
+   **Machine-generated Text Localization** [[pdf]](https://arxiv.org/pdf/2402.11744.pdf) 02/19/2024
+   **Stumbling Blocks: Stress Testing the Robustness of Machine-Generated Text Detectors Under Attacks** [[pdf]](https://arxiv.org/pdf/2402.11638.pdf) 02/19/2024
+   **Authorship Obfuscation in Multilingual Machine-Generated Text Detection** [[pdf]](https://arxiv.org/pdf/2401.07867.pdf) 01/17/2024
+   **LANGUAGE MODEL DETECTORS ARE EASILY OPTIMIZED AGAINST** [[pdf]](https://openreview.net/pdf?id=4eJDMjYZZG) 11/28/2023
+   **A Ship of Theseus: Curious Cases of Paraphrasing in LLM-Generated Texts** [[pdf]](https://arxiv.org/abs/2311.08374) 11/14/2023
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
### 2024
+   **CoAT: Corpus of artificial texts** [[pdf]](https://www.cambridge.org/core/journals/natural-language-processing/article/coat-corpus-of-artificial-texts/7E2CA97E21663CC031FB6BAFE56E0046) 09/07/2024
+   **Detecting Machine-Generated Texts: Not Just “AI vs Humans” and Explainability is Complicated** [[pdf]](https://arxiv.org/pdf/2406.18259) 06/27/2024
+   **Spotting AI’s Touch: Identifying LLM-Paraphrased Spans in Text** [[pdf]](https://arxiv.org/pdf/2405.12689) 05/22/2024
+   **RAID: A Shared Benchmark for Robust Evaluation of Machine-Generated Text Detectors** [[pdf]](https://arxiv.org/pdf/2405.07940) 05/16/2024
+   **M4GT-Bench: Evaluation Benchmark for Black-Box Machine-Generated Text Detection** [[pdf]](https://arxiv.org/pdf/2402.11175.pdf) 02/19/2024
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
+   **Can Watermarking Large Language Models Prevent Copyrighted Text Generation and Hide Training Data?** [[pdf]](https://arxiv.org/pdf/2407.17417) 07/24/2024
+   **Monitoring AI-Modified Content at Scale: A Case Study on the Impact of ChatGPT on AI Conference Peer Reviews** [[pdf]](https://arxiv.org/pdf/2403.07183.pdf) 03/13/2024
+   **A Survey of AI-generated Text Forensic Systems: Detection, Attribution, and Characterization** [[pdf]](https://arxiv.org/pdf/2403.01152.pdf) 03/05/2024
+   **Hidding the Ghostwriters: An Adversarial Evaluation of AI-Generated Student Essay Detection** [[pdf]](https://arxiv.org/pdf/2402.00412.pdf) 02/01/2024
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

@inproceedings{yangdna,
  title={DNA-GPT: Divergent N-Gram Analysis for Training-Free Detection of GPT-Generated Text},
  author={Yang, Xianjun and Cheng, Wei and Wu, Yue and Petzold, Linda Ruth and Wang, William Yang and Chen, Haifeng},
  booktitle={The Twelfth International Conference on Learning Representations}
}

@article{yang2023zero,
  title={Zero-shot detection of machine-generated codes},
  author={Yang, Xianjun and Zhang, Kexun and Chen, Haifeng and Petzold, Linda and Wang, William Yang and Cheng, Wei},
  journal={arXiv preprint arXiv:2310.05103},
  year={2023}
}

@article{zeng2024improving,
  title={Improving Logits-based Detector without Logits from Black-box LLMs},
  author={Zeng, Cong and Tang, Shengkun and Yang, Xianjun and Chen, Yuanzhou and Sun, Yiyou and Li, Yao and Chen, Haifeng and Cheng, Wei and Xu, Dongkuan and others},
  journal={arXiv preprint arXiv:2406.05232},
  year={2024}
}
```
