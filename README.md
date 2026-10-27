### Arnav Sawhney

Biosystems Engineering + AI minor at Plaksha University, graduating 2027. I like problems that sit between ML research and things people actually use.

#### Right now

- **Building [ClinicPylot](https://clinicpylot.xyz)**, a WhatsApp SaaS that helps Indian dental clinics recover revenue lost to no-shows and missed recalls. Solo engineer. Follow-up selection is a contextual bandit, off-policy evaluated with SNIPS and Doubly-Robust estimators. Stack: FastAPI, Supabase (Postgres + RLS), Next.js 14, Redis, Docker, Razorpay.
- **Benchmarking vision-language models on surgical video** in [surg-retrieval-bench](https://github.com/ArnavSawhney/surg-retrieval-bench). Cholec80 is done; cross-dataset generalisation on Endoscapes2023 is in progress.
- **Previously** ML intern at Univlabs / CogniAxis.ai, working on surgical AI. Built MediaAxis (MedSigLIP + MedGemma for surgical-video summaries and search) and an OR-activity tracking model with CreateBytes; deployed and demoed the Collaborative Surgical Module in clinical settings.
- Undergrad research on early PCOS detection from ultrasound (Mask R-CNN) and DNA fibre analysis for cancer research (SAM3 + OpenCV).

#### Interests

Reinforcement learning (multi-agent, constrained, bandits and off-policy evaluation), robot learning, vision-language models, computer vision, and applied ML in healthcare.

#### Selected work

- [surg-retrieval-bench](https://github.com/ArnavSawhney/surg-retrieval-bench): open, pre-registered benchmark of CLIP, SigLIP, MedSigLIP and PeskaVLP for text-to-frame retrieval on laparoscopic video. The surgical-domain model leads zero-shot (mAP 0.278 vs 0.159 random). Linear probes on frozen embeddings lift phase accuracy from 13-35% to 67-74%, and causal temporal smoothing reaches 80%.
- [MARL-Environment](https://github.com/ArnavSawhney/MARL-Environment): MAPPO dual-policy framework (communication + navigation) for bandwidth-limited multi-robot coordination under CTDE, with a Lagrangian bandwidth constraint and per-feature PPO clipping. Extended to a partially observable predator-prey task: ~80% capture rate within a 12-byte message budget. Team project.
- [ClinicPylot-Demo](https://github.com/ArnavSawhney/ClinicPylot-Demo): public writeup of the platform above. Architecture, the bandit design, off-policy eval setup. Code is private (product).
- [Fin-RoBERTa](https://github.com/ArnavSawhney/Financial-Sentiment-Analysis): keyword masking + domain-adaptive pretraining for financial sentiment. Ablation from 79% to 84% to 88% accuracy (83.3 F1), beats FinBERT (86%). Team project.
- [PCOS_EarlyDetection](https://github.com/ArnavSawhney/PCOS_EarlyDetection): Mask R-CNN for pre-symptomatic ovarian follicle detection (2 to 9 mm range) from ultrasound. 98 to 100% classification accuracy on 772 held-out images.
- [FiberDetectionAnalysis](https://github.com/ArnavSawhney/FiberDetectionAnalysis): SAM3 + OpenCV pipeline extracting replication features (fork speeds, tract lengths, inter-origin distances) from DNA fibre microscopy.

#### Stack

Python, PyTorch, HuggingFace, OpenCV, FastAPI, Next.js, PostgreSQL / Supabase, Redis, Docker. Also R, TypeScript, C / C++.

#### Reach me

[arnavsawhney@clinicpylot.xyz](mailto:arnavsawhney@clinicpylot.xyz) · [LinkedIn](https://www.linkedin.com/in/arnav-sawhney-2bb391253/)
