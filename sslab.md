---
layout: page
title: SSLab
sidebar_link: true
sidebar_sort_order: 2
---

# SSLab

SSLab represents the [Systems Software & Security Lab](https://gts3.org/) from Georgia Institute of Technology led by [Prof. Taesoo Kim](https://taesoo.kim/).

We have been actively working on SGX related research. These research projects can be broadly classified into three different categories: System Design, Defense, and Attack.

## System Design

* [OpenSGX](https://github.com/sslab-gatech/opensgx): An open-source platform for SGX research that consists of a QEMU-based emulator and a software development kit \(SDK\)
* S-NFV: A protection scheme for network function virtualization \(NFV\) applications that uses SGX to secure the applications' internal states
* AirBox: A secure design of edge function platforms using SGX for ensuring code integrity and data confidentiality of an edge function
* [SGX-Tor](https://github.com/kaist-ina/SGX-Tor): A design of Tor that enhances the security and privacy of the protocol by utilizing SGX

## Defense

* [T-SGX](https://github.com/sslab-gatech/t-sgx): A compiler-level approach that incorporates Intel TSX to prevent SGX enclaves from controlled-channel attacks
* [SGX-Shield](https://github.com/jaebaek/SGX-Shield): A software-based design of SGX enclaves that enables fine-grained address space layout randomization \(ASLR\)

## Attack

* Branch Shadowing: A novel side-channel attack against SGX exploiting branch history states preserved across an SGX mode switch and last branch record \(LBR\)
* Dark ROP: A novel blind return-oriented programming \(ROP\) attack against SGX exploiting uninitialized registers across an enclave exit
* SGX-Bomb: A rowhammer attack against SGX resulting in processor lockdown, i.e., a cold reboot is necessary to use the machine again
* SGX-Bleed: A vulnerability that can leak uninitialized SGX memory through structure padding

## Publications

* Leaking Uninitialized Secure Enclave Memory via Structure Padding \(Extended Abstract, arXiv.org\) [\[pdf\]](https://arxiv.org/abs/1710.09061)
* SGX-Bomb: Locking Down the Processor via Rowhammer Attack \(SysTEX 2017\) [\[pdf\]](https://sslab.gtisc.gatech.edu/assets/papers/2017/jang:sgx-bomb.pdf)
* Inferring Fine-grained Control Flow Inside SGX Enclaves with Branch Shadowing \(Security 2017\) [\[pdf\]](https://sslab.gtisc.gatech.edu/assets/papers/2017/lee:sgx-branch-shadow.pdf)
* Hacking in Darkness: Return-oriented Programming against Secure Enclaves \(Security 2017\) [\[pdf\]](https://sslab.gtisc.gatech.edu/assets/papers/2017/lee:darkrop.pdf)
* Enhancing Security and Privacy of Tor's Ecosystem by using Trusted Execution Environments \(NSDI 2017\) [\[pdf\]](https://sslab.gtisc.gatech.edu/assets/papers/2017/kim:sgx-tor.pdf)
* SGX-Shield: Enabling Address Space Layout Randomization for SGX Programs \(NDSS 2017\) [\[pdf\]](https://sslab.gtisc.gatech.edu/assets/papers/2017/seo:sgx-shield.pdf)
* T-SGX: Eradicating Controlled-Channel Attacks Against Enclave Programs \(NDSS 2017\) [\[pdf\]](https://sslab.gtisc.gatech.edu/assets/papers/2017/shih:tsgx.pdf)
* Fast, Scalable and Secure Onloading of Edge Functions using AirBox \(SEC 2016\) [\[pdf\]](https://sslab.gtisc.gatech.edu/assets/papers/2016/bhardwaj:airbox.pdf)
* S-NFV: Securing NFV states by using SGX \(SDNNFVSEC 2016\) [\[pdf\]](https://sslab.gtisc.gatech.edu/assets/papers/2016/shih:snfv.pdf)
* OpenSGX: An Open Platform for SGX Research \(NDSS 2016\) [\[pdf\]](https://sslab.gtisc.gatech.edu/assets/papers/2016/jain:opensgx.pdf)

