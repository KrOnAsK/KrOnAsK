### Hi, I'm Jonas

Data Science master's student at [TU Wien](https://www.tuwien.at/) (graduating February 2027) and student researcher at TU Wien's recsys-lab in Vienna.

I build data pipelines in Python and PostgreSQL, and I run what I build myself: CI/CD, containers, reverse proxies, a two-node Proxmox homelab.

#### Main project: Biografiemaschine

A research tool I'm building at TU Wien's recsys-lab for the [Wienbibliothek im Rathaus](https://www.wienbibliothek.at/). An LLM pipeline turns the library's source material into structured biographies, which librarians review, correct and export to Word.

- Built the extraction pipeline, the PostgreSQL data model and the full-stack app (FastAPI, React/Vite)
- Deployed with GitLab CI/CD (Kaniko builds on Kubernetes) behind nginx with TLS
- Ran user tests with Wienbibliothek librarians and fed the findings back into the product, e.g. telling apart people with the same name and showing the model's confidence

The code lives on the university's GitLab, so it isn't public. Happy to walk through it or show a demo.

#### Projects here

- [**Wiener Netze Smart Meter Integration**](https://github.com/KrOnAsK/Wiener-Netze-Smart-Meter-Integration): Home Assistant integration for Wiener Netze smart meters. Hourly energy statistics, per-hour cost tracking for dynamic tariffs, full history import. Installable through HACS.
- [**Zeche**](https://github.com/KrOnAsK/billsplitting): self-hosted bill splitting. Photograph the receipt, Tesseract reads the line items, everyone taps what they had via a QR code. FastAPI, SQLite, Docker.
- [**Narrative classification in online news**](https://github.com/KrOnAsK/nlp_Backpropagandists_2024): SVM vs. BERT vs. LLaMA for detecting narratives in multilingual news on the Ukraine war and climate change. TU Wien group project.
- [**Climate & agriculture dashboard**](https://github.com/KrOnAsK/visualdatascience26): interactive Vega-Lite dashboard of crop yields and climate patterns ([live demo](https://kronask.github.io/visualdatascience26/)).

**Stack:** Python · SQL / PostgreSQL · FastAPI · Docker · Kubernetes · GitLab CI · Proxmox · LLM pipelines

[LinkedIn](https://www.linkedin.com/in/jonas-kruse-a67857124)
