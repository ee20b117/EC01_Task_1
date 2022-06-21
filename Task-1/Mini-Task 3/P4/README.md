# Detecting Unstable Electric Grid with TinyML
## Problem Statement
A TinyML approach to prevent Electric grid overload.
## Ideation and Planning
Dataset and Target Variable >>> Training and Analysis >>> Hardware setup (Particle Argon) >>> Model Embedding (Particle IDE and Neuton workbench)
### Pipeline Breaking
|Process|Feasibility|Advantages|Disadvantages|
|-----------|--------|------------|---------------|
|Dataset and Target variable|Datasets already available|Combining IoT with AI uplifts a lot of posed challenges|Scaling this on a large scale might require enormous data collection for highly accurate systems|
|Training/Analysis|Training done on device itself; fast inference|Correlation, model metrics and confusion matrix easily showcase the analysis|Updating the datset always needs to be done on the device; not cloud based|
|Particle Argon|Based on Wi-Fi|Has built-in battery charging circuitry; 20 mixed-signal GPIOs|The board has large footprint and high cost|
|Environment|Neuton TinyML-free platform with IoT platform as a service|Smart Grid Infrastructure helps transfer data faster and cheaper rates; No-code artificial intelligence is an added advantage|TinyML devices have limmited memory; restrictions on size and runtime; absence of cloud-based troubleshooting|
