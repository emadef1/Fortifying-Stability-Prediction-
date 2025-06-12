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
    <a href="https://github.com/emadef1/Fortifying-Stability-Prediction-/tree/main"><strong>Paper accepted (link will be availble shortly) »</strong></a>
    <br />
    <br />
    <a href="">Emad Efatinasab, Nahal Azadi, Gian Antonio Susto, Chuadhry Mujeeb Ahmed, Mirco Rampazzo</a>
  </p>
</div>


## 🧩 Abstract

The growing global energy demand and renewable adoption pose challenges for modern grids. Smart grids have emerged as a solution to manage this complexity, integrating advanced technologies for efficient and stable energy distribution. However, these systems are increasingly vulnerable to cyberattacks, especially adversarial attacks targeting AI-driven stability prediction models. This paper introduces a novel framework to defend smart grid stability prediction models against white-box and query-based grey-box attacks like GAN-GRID, including a real-world modified version of GAN-GRID tailored for targeted adversarial scenarios, as well as data anomalies caused by faulty measurements and communication anomalies. It employs two key independent approaches: (1) a Gated Recurrent Unit(GRU)-based anomaly detection system, trained with adversarial samples, classifying normal grid behavior as "real" and adversarial examples as "anomalies"; and (2) a Bayesian LSTM model utilizing uncertainty quantification techniques through Joint Entropy and Mutual Information (JEM), combining Predictive Entropy (PE) and Mutual Information (MI). Our framework is evaluated on the Electrical Grid Stability Simulated Dataset, demonstrating high detection accuracy, with the GRU-based system achieving up to 0.984 accuracy in detecting adversarial behavior and the uncertainty-based system achieving 0.994 accuracy against modified GAN-GRID attacks. This framework provides a robust, comprehensive defense mechanism to enhance smart grid security under adversarial threats and measurement anomalies.
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
