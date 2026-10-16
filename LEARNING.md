# My AI Engineering Path
<!-- Managed by the ai-engineering-from-scratch learning skills.
     Repo: https://github.com/rohitg00/ai-engineering-from-scratch -->

## Mission
i already know some fundamentals but i want revisiona , learn new things and standard practices. I want to build a project that will look good on resume and not just average but good which will get me hired.

## Placement
- Date: 2026-09-30
- Score: 8/10 (Math & Statistics: 2/2, Classical ML: 2/2, Deep Learning: 1/2, NLP & Transformers: 1/2, Applied AI: 2/2)
- Entry point: Phase 11: LLM Engineering
- Pace: ~13 hours/week

## Path
| Phase | Name | Status | Est. hours |
|-------|------|--------|------------|
| 0 | Setup & Tooling | Done | 14 |
| 1 | Math Foundations | Skip | -- |
| 2 | ML Fundamentals | Skip | -- |
| 3 | Deep Learning Core | Done | 15 |
| 4 | Computer Vision | Skip | -- |
| 5 | NLP — Foundations to Advanced | Review | 30 |
| 6 | Speech & Audio | Skip | -- |
| 7 | Transformers Deep Dive | Review | 14 |
| 8 | Generative AI | Skip | -- |
| 9 | Reinforcement Learning | Do | 13 |
| 10 | LLMs from Scratch | Skip | -- |
| 11 | LLM Engineering | Do | 19 |
| 12 | Multimodal AI | Do | 65 |
| 13 | Tools & Protocols | Do | 43 |
| 14 | Agent Engineering | Do | 55 |
| 15 | Autonomous Systems | Do | 20 |
| 16 | Multi-Agent & Swarms | Do | 28 |
| 17 | Infrastructure & Production | Do | 32 |
| 18 | Ethics, Safety & Alignment | Do | 31 |
| 19 | Capstone Projects | Do | 620 |

## Progress log
| Date | Lesson | Quiz | Note |
|------|--------|------|------|
| 2026-09-30 | 00/01 | 3/3 | Knew Git & uv, focused on pnpm/rust setup |
| 2026-10-12 | 00/02 | 3/3 | Understood git DAG, daily workflow, and why weights bloat .git/ |
| 2026-10-12 | 00/03 | 3/3 | Mastered CPU vs GPU throughput, fp16 VRAM sizing, and torch.cuda.synchronize() |
| 2026-10-12 | 00/04 | 3/3 | Understood env var secret management, raw HTTP vs SDK wire format, and 401/429 status codes |
| 2026-10-12 | 00/05 | 3/3 | Mastered notebook vs kernel architecture, %timeit vs %%time, and out-of-order execution traps |
| 2026-10-12 | 00/06 | 3/3 | Understood env isolation, where python verification, pip/conda pitfalls, and CUDA driver mismatch |
| 2026-10-12 | 00/07 | 3/3 | Mastered AI Dockerfiles, GPU passthrough with NVIDIA toolkit, volumes, and Compose networking |
| 2026-10-12 | 00/08 | 3/3 | Configured VS Code LSP basic type checking, output scrolling, and Remote SSH for cloud GPUs |
| 2026-10-13 | 00/09 | 3/3 | Mastered streaming vs mmap, Parquet columnar storage, and DVC data versioning |
| 2026-10-13 | 00/10 | 3/3 | Mastered SIGHUP lifecycle, line-buffered grep, tmux multiplexing, and SSH -L tunnels |
| 2026-10-13 | 00/11 | 2/3 | Navigated Linux permissions and line-endings; review du -h vs /proc/meminfo |
| 2026-10-13 | 00/12 | 3/3 | Mastered AI debugging levels, tensor health checks, timer profiling, and NaN detection |
| 2026-10-14 | 03/01 | 3/3 | Mastered perceptron update rule, linear separability, and MLP coordinate transformation for XOR |
| 2026-10-14 | 03/02 | 3/3 | Mastered Layer/Network forward pass, matrix dimension tracking (out x in), and batch parallelization intuition |
| 2026-10-14 | 03/03 | 3/3 | Mastered computational graphs, autograd chain rule, topological sort, vanishing gradients, and optimizer.zero_grad() necessity |
| 2026-10-14 | 03/04 | 3/3 | Mastered activation evolution (Sigmoid/Tanh -> ReLU -> GELU/Swish), dying ReLU failure mode, and softmax stability trick |
| 2026-10-14 | 03/05 | 3/3 | Mastered loss function selection (MSE vs BCE vs CCE vs InfoNCE), 0.5 prediction failure mode, and label smoothing |
| 2026-10-14 | 03/06 | 2/3 | Built SGD/Momentum/Adam/AdamW; review Adam cold-start bias correction vs LR scheduling |
| 2026-10-14 | 03/07 | 3/3 | Mastered inverted dropout scaling 1/(1-p), BatchNorm vs LayerNorm, RMSNorm efficiency in LLMs, and model.eval() contract |
| 2026-10-14 | 03/08 | 3/3 | Mastered symmetry breaking, Xavier vs Kaiming variance derivation (ReLU halving), and transformer residual scaling |
| 2026-10-16 | 03/09 | 2/3 | Mastered warmup intuition & cosine decay schedules; review 1cycle policy exploration mechanism |
| 2026-10-16 | 03/10 | 2/3 | Built 500-line mini-framework with Modules, Sequential, Adam, and DataLoader; review training loop step order |
| 2026-10-16 | 03/11 | 3/3 | Mastered PyTorch tensors, autograd tape, CrossEntropyLoss logits contract, and C++/CUDA kernel acceleration |
| 2026-10-16 | 03/12 | 3/3 | Mastered JAX pure functions, functional autodiff jax.grad, vmap vectorization, and XLA JIT compilation |
| 2026-10-16 | 03/13 | 2/3 | Mastered diagnostic protocols (overfit-one-batch, hooks, anomaly detection); review flat loss root causes |
| 2026-10-16 | 05/01 | 3/3 | Built regex tokenizer, Porter stemmer step 1a, and POS lemmatizer; understood train/serve skew |
| 2026-10-16 | 05/02 | 3/3 | Built BoW, smoothed IDF, and L2-normalized TF-IDF; understood negation/semantic blind spots |
| 2026-10-16 | 05/03 | 2/3 | Built Skip-gram with negative sampling; review unsupervised relational vector arithmetic |

## Review queue
- [ ] Phase 0, Lesson 11: Linux for AI (Disk forensics: `df -h` vs `du -h` vs RAM `/proc/meminfo`)
- [x] Phase 3, Lesson 06: Optimizers (Adam cold-start bias correction mechanism)
- [x] Phase 3, Lesson 09: Learning Rate Schedules (1cycle policy mechanism: ramping LR up for exploration/regularization, then down)
- [x] Phase 3, Lesson 10: Mini Framework (Canonical training loop order: zero_grad -> forward -> loss -> backward -> step)
- [x] Phase 3, Lesson 13: Debugging (Flat loss triage: nonzero gradients, learning rate scale, loss graph connectivity)
- [ ] Phase 5, Lesson 03: Word2Vec (Vector arithmetic: emergent linear relational directions from unsupervised co-occurrence)
