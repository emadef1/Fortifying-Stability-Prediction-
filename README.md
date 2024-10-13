# Fortifying-Stability-Prediction
<div id="top"></div>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/emadef1/Fortifying-Stability-Prediction-/tree/main">
    <img src="Figure/logo.png" alt="Logo" width="150" height="150">
  </a>

  <h1 align="center">Fortifying Stability Prediction</h1>

  <p align="center">
    Fortifying Stability Prediction in Smart Grids: A Defense Framework Against Adversarial Attacks
    <br />
    <a href="https://github.com/emadef1/Fortifying-Stability-Prediction-/tree/main"><strong>Paper in progress »</strong></a>
    <br />
    <br />
    <a href="">Anonymous Authors</a>
  </p>
</div>


## 🧩 Abstract

The increasing global energy demand, coupled with the growing adoption of renewable energy sources, presents significant challenges for modern energy grids. Smart grids have emerged as a solution to manage this complexity, integrating advanced technologies for efficient and stable energy distribution. However, these systems are increasingly vulnerable to cyberattacks, especially adversarial attacks targeting AI-driven stability prediction models. In this paper, we introduce a novel framework designed to defend smart grid stability prediction systems against both white-box and query-based generative attacks, such as the GAN-GRID attack. We propose two key approaches: (1) a Gated Recurrent Unit (GRU)-based anomaly detection system trained with adversarial samples to classify normal grid behavior as "real" and adversarial examples as "anomalies," and (2) a Bayesian LSTM model that leverages uncertainty quantification techniques. By utilizing Joint Entropy and Mutual Information Metric (JEM), which incorporates uncertainty metrics such as Predictive Entropy (PE) and Mutual Information (MI), our approach has the ability to detect sophisticated adversarial attacks like GAN-GRID. Our framework is evaluated on the Electrical Grid Stability Simulated Dataset, demonstrating high detection accuracy, with the GRU-based system achieving up to 0.976 accuracy in detecting adversarial behavior and the uncertainty-based system achieving 0.914 accuracy against GAN-GRID attacks. This work provides the first comprehensive defense mechanism tailored to smart grid stability prediction models under adversarial threats, offering a robust solution to enhance grid security.
<p align="right"><a href="#top">(back to top)</a></p>
<div id="usage"></div>

## ⚙️ Usage

To execute the attacks or to deploy the framework, start by cloning the repository:

```bash
git clone https://github.com/emadef1/Fortifying-Stability-Prediction-.git
```
<sup>NOTE: if you're accessing this data from the anonymized repository, the above command might not work..</sup>

Then, install the required Python packages by running:

```bash
pip install -r requirements.txt
```

<p align="right"><a href="#top">(back to top)</a></p>
<div id="models"></div>
