# Hey, I'm Khoi 👋

ML Scientist in Toulouse, France. I build deep learning models for medical imaging.

Most of my day-to-day involves computer vision for **dermatology** (skin lesion segmentation, disease classification), **trichoscopy** (hair & scalp analysis — segmentation, follicle counting, disease detection), and **ECG** (signal classification + digitizing paper ECGs into structured data). I work closely with dermatologists and trichologists to make sure the models actually make sense clinically.

I also care about making models **reliable** — I did research on runtime monitoring of neural networks and how to set thresholds that hold up when the data shifts. And I've explored the LLM/RAG side of things during an internship, building a private-data chatbot with LlamaIndex and benchmarking multimodal RAG pipelines.

Outside of work: enthusiastic but terrible at badminton 🏸, ping pong 🏓, and chess ♟️. Always down for a board game night.

---

### What I work with

**Day-to-day:** Python · PyTorch · PyTorch Lightning · image segmentation & classification & detection

**Curious about:** self-supervised learning · vision transformers · weak supervision · label noise handling

---

### Publication

*Can We Defend Against the Unknown? An Empirical Study About Threshold Selection for Neural Network Monitoring*
UAI 2024 · [[paper]](https://hal.science/hal-04579393v1/document)

---

### A few things I've worked on

🔬 **Skin lesion & dermoscopic analysis** — segmentation with U-Net variants, multi-label disease classification, OOD detection for clinical classifiers

💇 **Hair & scalp analysis suite** — hair segmentation, follicle detection/counting, erythema detection, hair type & disease classification (built with trichologist feedback)

❤️ **ECG pipelines** — disease classification from signals + a digitization pipeline that turns paper ECG images into structured waveform data

🤖 **RAG chatbot prototype** — private-data Q&A with LlamaIndex, multimodal RAG evaluation for PDF documents
