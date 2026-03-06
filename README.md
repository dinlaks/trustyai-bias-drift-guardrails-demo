# OpenShift AI - TrustyAI Demos
This repository features a collection of demos highlighting TrustyAI’s capabilities within OpenShift AI, with a primary focus on Bias Monitoring, Drift Monitoring, and Guardrails.

**Caveat**: These demos are tested and intended to work on OpenShift AI 2.25 and above

## Contents
1) [Installing RHOAI and TrustyAI](1-Installation/README.md): How to install OpenShift AI and TrustyAI on your cluster.
2) [Bias Monitoring](2-BiasMonitoring/kserve-demo/README.md): How to use TrustyAI to examine your deployed models for unfair biases.
3) [Data Drift](3-DataDrift/kserve-demo/README.md): How to detect if the production data your models are receiving matches the data they were trained on.
4) [Guardrails-quickstart-demo](4-Guardrails/guardrails-quickstart-demo/README.md): A quickstart walkthrough on enabling TrustyAI Guardrails to protect your LLM applications.
5) [Guardrails-language-detector-demo](4-Guardrails/guardrails-language-detector-demo/README.md): Use a language detection model as a guardrail to restrict allowed input/output languages.
6) [eval-quickstart-demo](5-LM-Eval/eval-quickstart-demo/README.md): Quick evaluation of LLM outputs using TrustyAI's integrated evaluation tools.


## Acknowledgements

All of this work was made possible with the support from various product teams. I would like to express gratitude to everyone who contributed their time, expertise, and resources to help realize these demos. Thank you!