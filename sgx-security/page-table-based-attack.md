# Page-table-based Attacks

### Introduction

In addition to traditional software attacks, another well-known attack vector against SGX is side channels. The threat model of SGX, which assumes that even privileged software \(e.g., an OS and a hypervisor\) is untrusted, enables broader and stronger classes of side channels. This section demonstrates one class of side-channel attacks \(i.e., page-table-based attacks\) that is unique to the SGX settings and our mitigation against the attacks.

### SGX page-table-based attack

This video presents the page-table-based attack, which is also known as the controlled-channel attack. By manipulating the page table and hooking the page fault handler, the attacker is able to observe precise page access patterns.

{% embed url="https://youtu.be/MCSlgEqNhIA" %}

### T-SGX

This video shows how T-SGX protect an SGX enclave from page-table-based attacks.

{% embed url="https://youtu.be/uHt6D-lHl68" %}

### 

