---
layout: page
title: Technion 2018  Summer School Program
---

# Technion'18 Summer School Program

During the 7th Summer School on Cyber and Computer Security held by **Technion Insrael Institute of Technology** and **Hiroshi Fujiwara Cyber Security Research Center**, several talks were given on trusted execution and hardware side channels. Talks on day 1 focused mostly on Intel SGX technology. Those from day 2 were more on security issues on trusted execution. On day 3, more side channel related topics were discussed.

This page includes selected talks with slides. Original website can be found [here](http://cyber.technion.ac.il/2018-summer-school-on-cyber-computer-security/2018-summer-school-program/). Unfortunately, videos of those talks are not available online.

## Day 1

### Software Guard Extension – from dream to reality

#### Speaker: Ittai Anati

#### Abstract:

> In 2015, Intel launched its 6th generation Core, codenamed Skylake, that implements a new ISA for security – Intel® SGX. We’ll start with the fundamentals of SGX1, and gradually dive deeper into more advanced topics of SGX. 1. SGX1 fundamentals 2. Advanced SGX1 topics and SGX2 3. Flexible launch control, VMM Oversubscription, key separation and sharing 4. Provisioning, attestation and recovery

{% file src="../.gitbook/assets/ittai.pdf" caption="Slides here" %}

### Attacks and Defenses for Intel SGX

#### Speaker: Taesoo Kim

#### Abstract:

> The Intel Software Guard Extensions \(SGX\)---a gamechanging feature introduced in the recent Intel Skylake CPU---is a new technology likely to make secure and trustworthy computing in a hostile environment practical. At a high level, SGX consists of a set of new instructions that can be used to create secure regions \(i.e., enclaves\) to defeat attacks that aim to steal or tamper with the data within an enclave. Without a doubt, we expect that SGX will allow developers to protect sensitive code and data from unauthorized access or modification by software running at higher privilege levels such as an OS or a hypervisor.
>
> However, SGX is merely a set of instructions; it lacks support from the OS and libraries. These deficiencies allow programmers to easily introduce naive yet preventable bugs that often lead to critical security holes in an enclave program. Further, designing a correct and secure SGX infrastructure is also far from straightforward; enclave programs rely on the support of an underlying OS, but their security models exclude the OS from the TCB. This unconventional dependency makes various attack vectors, which are often considered impractical in a traditional setting, immediate and practical, especially in a cloud environment.
>
> In this tutorial, I will first provide a security-focused introduction to Intel SGX, including its internal mechanisms to implement the security features. Then, I will explain known security concerns, including recent research outputs from the community: e.g., memory safety issues, cache/branch side-channel attacks, and rowhammer attacks. I will not just only demonstrate these attacks but also guide you to the proper defense mechanisms.

{% file src="../.gitbook/assets/taesoo.pdf" caption="Slides here" %}

## Day 2

### Application-oriented Security: Secrets Management and SideChannel Protection for TEEs

#### Speaker: Christof Fetzer

#### Abstract:

> This tutorial will first introduce the problems one faces when trying to run unmodified applications inside of TEEs. Alternative solutions are presented but the focus will be on the use of cross-compilers and runtime support to execute applications inside of TEEs. We will introduce some example applications running inside of SGX using the SCONE platform.
>
> Second, we will motivate the need for integrating secrets management and remote attestation. We will motivate the problem of remote attestation and configuration management and show how to solve this. We show how that helps with transparent protection of files and secrets.
>
> We show how attestation can help to protect against some side-channel attacks. The main focus will, however, on a novel approach to protect against L1/L2-based side channels attacks.

{% file src="../.gitbook/assets/christof.pdf" caption="Slides here" %}

### The house is built on sand: exploiting hardware glitches and side channels in perfect software

#### Speaker: Herbert Bos

#### Abstract:

> For years, we have tried to address security problems by fixing software bugs and misconfigurations. For critical systems we may even choose to formally verify software to guarantee the absence of bugs. However, the question is whether getting rid of bugs in the software is sufficient. In this talk, I will discuss vulnerabilities in hardware that allow attackers to compromise systems even in the absence of software bugs. In particular, these vulnerabilities offer attackers the read and write primitives needed to leak and modify sensitive information. For the write primitive, we will look at the evolution of the Rowhammer vulnerability in DRAM chips that has matured from a mere curiosity to a serious attack vector across all sorts of systems in just a few years. For read primitives, we will discuss several advanced side channel vulnerabilities, such as found in memory deduplication and Translation Lookaside Buffers.

{% file src="../.gitbook/assets/herbert.pdf" caption="Slides here" %}

## Day 3

### From black to white \(box\) attacks on secure systems - Or why do your light bulbs need a firmware update

#### Speaker: Eyal Ronen

#### Abstract:

> I will go over the process of RE and attacking the Philips Hue. It is partially based on the IoT Goes Nuclear paper \(iotworm.eyalro.net\). But I will mostly describe the process of breaking the secure SoC, including what we tried and didn't work.

{% file src="../.gitbook/assets/eyal.pdf" caption="Slides here" %}

### Side-Channel Attacks on Human Secrets

#### Speaker: Yossi Oren

#### Abstract:

> Side-channel analysis techniques have been traditionally applied toward the recovery of computer-related secrets such as cryptographic keys. Humans, however, also share secrets of their own with their computers – for example, their browsing habits, their political or religious beliefs, or sensitive information about their health. This secret information is increasingly vulnerable to emerging low-cost side-channel attacks that are highly scalable, employing malicious peripheral devices or turning components of a system against itself. There are countermeasures which can be applied to protect systems from the theft of human secrets via side channel attacks. These countermeasures, however, have different designs, and exact different costs, than those designed to protect against the theft of cryptographic secrets.

{% file src="../.gitbook/assets/yossi.pdf" caption="Slides here" %}

### What if your phone’s battery could talk? Inference attacks using malicious battery

#### Speaker: Mark Silberstein

#### Abstract:

> Mobile devices are equipped with increasingly smart batteries designed to provide responsiveness and extended lifetime. However, such smart batteries may present a threat to users’ privacy. We demonstrate that the phone’s power trace sampled from the battery at 1KHz holds enough information to recover a variety of sensitive information. We show techniques to infer typed characters to reduce the password search space; to accurately recover browsing history in an open-world setup; to reliably detect incoming calls and the photo shots including their lighting conditions. Combined with a novel exfiltration covert channel that allows communication from the battery directly to a remote server without installing software on the phone, these attacks turn the malicious battery into a stealthy surveillance device. We deconstruct the attack by analyzing its robustness to sampling rate and execution conditions, and identify the sources of the information leakage to find the best way to defend against the attacks. We discover that an attacker can distinguish the browsed website by observing the GPU or DRAM power traces alone. However, the CPU and other power-hungry peripherals such as a touch screen are often the primary sources of fine-grain information leakage. We highlight the challenge to defend against the attacks by designing and evaluating several possible mitigation mechanisms. In summary, our work shows the feasibility of the malicious battery and motivates further research into system and application-level defenses to fully mitigate this emerging threat.
>
> Based on the joint work with Pavel Lifshits and Mohit Tiwari presented at the Symposium on Privacy Enhancement Technologies \(2018\)

{% file src="../.gitbook/assets/mark.pdf" caption="Slides here" %}

