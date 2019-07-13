# Memory Corruption

### Introduction

An SGX program may still suffer from traditional software attacks if the program binary contains vulnerabilities. One type of vulnerabilities is memory corruption that enables control-flow hijacking attacks such as return-oriented programming \(ROP\) and return-to-libc attacks. This section demonstrates an ROP attack against an enclave and our mitigation \(i.e., fine-grained ASLR\) against the attack. 

### Dark ROP

This video shows how the Dark ROP attack detects `memcpy()` and copy the entire memory contents of an enclave to the outside.

{% embed url="https://youtu.be/kixVRC-SHQE" %}

### SGX-Shield

This video demonstrates the effectiveness of fine-grained ASLR support of SGX-Shield.

{% embed url="https://youtu.be/0aSilQ5SR58" %}

