# Cache Attacks

### Introduction

One well-known class of side channels is cache attacks. By exploiting the timing difference between accessing cached and non-cached data, the attacks infer the particular the memory accesses of a victim process by manipulating CPU caches. Because an enclave shares the CPU caches with the rest of system, the enclave is vulnerable to cache attacks by design. Moreover, cache attacks launched by privileged software \(under the SGX threat model\) are much more powerful \(e.g., more accurate\) than launched by non-privileged software.



