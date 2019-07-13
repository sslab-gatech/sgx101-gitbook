# Branch Shadowing

### Introduction

Another unique class of side-channel attacks in the SGX settings is branch-prediction-based attacks. By exploiting the branch predictor, the attacks infer the states \(taken or non-taken\) of branches executed by an enclave. This section demonstrates the attack.

### Branch Shadowing

This video shows how the branch shadowing attack can extract RSA private key bits

* Target code: Sliding window exponentiation of **mbedTLS**
* Attack code: We modified Linux SGX SDK to run our shadow code
* Kernel log: Our attack code prints the output of LBR via `dmesg`

{% embed url="https://youtu.be/R\_C0rfbg3p8" %}

### 

