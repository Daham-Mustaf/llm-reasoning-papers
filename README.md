# llm-reasoning-papers

## Train LLM to reason 
1. **[DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via
Reinforcement Learning](https://arxiv.org/pdf/2501.12948)**
   <details>
     <summary>TL;DR</summary>
     Making LLM reason through pure RL (open-source) 
   </details>

2. **[DRT: Deep Reasoning Translation via Long Chain-of-Thought](https://arxiv.org/pdf/2412.17498)**
   <details>
     <summary>TL;DR</summary>
     Agentic + CoT for Machine Translation
   </details>
3. **[Scaling up Test-Time Compute with Latent Reasoning:
A Recurrent Depth Approach](https://arxiv.org/pdf/2502.05171)**
   <details>
     <summary>TL;DR</summary>
     Recurrent reasoning in latent space as compared to using tokens.
   </details>
4. **[On the Emergence of Thinking in LLMs I:
Searching for the Right Intuition](https://arxiv.org/pdf/2502.06773)**
   <details>
     <summary>TL;DR</summary>
     Propose RLSP (Reinforcement Learning via Self-Play) as a framework to understand and build large reasoning models.
   </details>
4. **[Competitive Programming with Large Reasoning Models
](https://arxiv.org/abs/2502.06807)**
   <details>
     <summary>TL;DR</summary>
    Demonstrates that competitive coding scaling test time computing leads to better performance than hand-crafted features used to choose a particular solution.
   </details>

5. **[Sky-T1-32B: Data-Efficient Training for Large Reasoning Models](https://github.com/NovaSky-AI/SkyThought)**
   <details>
     <summary>TL;DR</summary>
     Shows that Long Chain-of-Thought (Long CoT) reasoning can be efficiently learned through supervised fine-tuning (SFT) and LoRA with just 17k samples, significantly improving performance on math and coding benchmarks.
   </details>

6. **[d1: Scaling Reasoning in Diffusion Large Language Models via Reinforcement Learning](https://arxiv.org/abs/2504.12216)**
<details>
  <summary>TL;DR</summary>
  Proposes d1, a two-stage post-training framework (SFT + novel diffu-GRPO algorithm) that adapts pre-trained masked diffusion LLMs (dLLMs) for reasoning tasks. Their approach shows significant improvements over baseline models on math and logical reasoning benchmarks, demonstrating that non-autoregressive models can also benefit from reinforcement learning techniques that were previously limited to autoregressive models.
</details>

## Efficient Reasoning methods 
1. **[s1: Simple test-time scaling](https://arxiv.org/pdf/2501.19393v2)**
   <details>
     <summary>TL;DR</summary>
     Post-training using SFT on 1000 samples leads to a reasoning model similar to o1 
   </details>

2. **[Stop Overthinking: A Survey on Efficient Reasoning for Large Language Models](https://arxiv.org/pdf/2503.16419?)**
<details>
  <summary>TL;DR</summary>
  First systematic survey categorizing efficient reasoning in LLMs into model-based, reasoning output-based, and input prompts-based approaches, addressing the "overthinking phenomenon" in reasoning models.
</details>

3. **[Think Deep, Think Fast: Investigating Efficiency of Verifierfree Inference-time-scaling Methods](https://arxiv.org/abs/2504.14047)**
<details>
  <summary>TL;DR</summary>
  Comprehensive analysis of verifier-free inference-time scaling methods across reasoning and non-reasoning models, showing that majority voting consistently outperforms more complex methods and that non-reasoning models (even with high inference budgets) still underperform reasoning-specialized models.
</details>

## Vision/Multimodal Reasoning 
1. **[Imagine while Reasoning in Space:
Multimodal Visualization-of-Thought](https://arxiv.org/pdf/2501.07542)**
   <details>
     <summary>TL;DR</summary>
    Proposes Multimodal Visualization-of-Thought (MVoT) having an intermediate thinking stack composed of vision and language.   
   </details>
## Related Blogs
1. **[Reinforcement Learning with Verifiable Rewards](https://vinija.ai/concepts/RFT)**
   <details>
     <summary>TL;DR</summary>
     Introduction to RLVR 
   </details>


