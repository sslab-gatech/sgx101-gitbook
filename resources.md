---
layout: page
title: Resources
sidebar_link: true
sidebar_sort_order: 4
description: A collection of study resources related to Intel SGX technology.
---

# Other Resources

## From Intel

* [SGX developer guide from Intel](https://software.intel.com/en-us/documentation/sgx-developer-guide).
* [This](http://tce.webee.eedev.technion.ac.il/wp-content/uploads/sites/8/2015/10/SGX-for-Technion-TCE.pdf) is a comprehensive introduction of SGX presented by Dror Caspi from Intel in Israel Institute of Technology.
* [Introducing the Intel® Software Guard Extensions Tutorial Series](https://software.intel.com/en-us/articles/introducing-the-intel-software-guard-extensions-tutorial-series) is a set of tutorial blogs provided by Intel, which is focused on developing SGX applications for Windows platform.
* [This blog form Intel](https://software.intel.com/en-us/blogs/2016/06/10/overview-of-intel-software-guard-extensions-instructions-and-data-structures) provides the overview of the instructions and data structures used in SGX. It's useful as a reference for technical terms.
* [This blog from Intel](https://software.intel.com/en-us/articles/code-sample-intel-software-guard-extensions-remote-attestation-end-to-end-example) explains the Remote Attestation code example provided by Intel. Note that the code example from SGX SDK does not include the actual provisioning process with Intel Attestation Service.
* [Innovative Technology for CPU Based Attestation and Sealing](https://software.intel.com/en-us/articles/innovative-technology-for-cpu-based-attestation-and-sealing) is the initial white paper for the attestation and sealing techniques now offered by SGX.
* [Attestation Service for Intel® Software Guard Extensions \(Intel® SGX\): API Documentation](https://software.intel.com/sites/default/files/managed/7e/3b/ias-api-spec.pdf) provides the reference on how to interact with Intel Attestation Service using RESTful API.
* [Enhanced Privacy ID: A Direct Anonymous Attestation Scheme with Enhanced Revocation Capabilities](https://eprint.iacr.org/2007/194.pdf) is the initial paper from Intel that proposes Enhanced Privacy ID, the anonymous attestation scheme that is adopted by Intel Attestation Service.
* [Integrating Remote Attestation with Transport Layer Security](https://arxiv.org/pdf/1801.05863.pdf) introcudes how to use remote attestation to achieve a TLS connection.
* [This blog from Intel](https://eprint.iacr.org/2016/086.pdf) introduces the primitives associated with SGX sealing process. [More details](https://software.intel.com/en-us/node/702997) are also available from SGX developer guide.

## From Others

* [Intel SGX Explained](https://eprint.iacr.org/2016/086.pdf) is a comprehensive introduction to the technology, including the architecture background and the implementation. A must-have.
* [Trust is in the Keys of the Beholder: Extending SGX Autonomy and Anonymity](https://www.idc.ac.il/en/schools/cs/research/Documents/jackson-msc-thesis.pdf) is the dissertation for MS degree by Alon Jackson. It offers an extensive description of the SGX ecosystem and evaluations of SGX security guarentees.
* [SGX Secure Enclaves in Practice](https://www.blackhat.com/docs/us-16/materials/us-16-Aumasson-SGX-Secure-Enclaves-In-Practice-Security-And-Crypto-Review.pdf) is a review slides of the technology during BlackHat 2016. [This](https://github.com/kudelskisecurity/sgxfun/blob/master/paper/sgxpaper.md) is the corresponding review paper.
* [Information Security – Theory vs. Reality](http://www.cs.tau.ac.il/~tromer/istvr1516-files/lecture10-trusted-platform-sgx.pdf) is another good intruduction slides from Tel Aviv University.
* [Intel SGX Instructions in Enclave Initialization](https://insujang.github.io/2017-04-05/intel-sgx-instructions-in-enclave-initialization/) is a blog that explores and explains the implementation details of SGX enclave initialization very well.
* [SGX attestation process](https://courses.cs.ut.ee/MTAT.07.022/2017_spring/uploads/Main/hiie-report-s16-17.pdf) is a report from University of Tartu that gives a good high level explanation of attestation process.
* [Intel SGX Sealing](https://insujang.github.io/2017-10-09/intel-sgx-sealing/) is a blog that explains the details of SGX sealing process very well.

## Papers

Below are the best places to keep track of SGX related research papers for general purposes:

* [SGX Reading List](http://ina.kaist.ac.kr/~dongsuh/SGXReadingList.html) A well categorized SGX reading list.
* [An up-to-date list of system papers related to Intel SGX](https://github.com/vschiavoni/sgx-papers)

## Useful

Other useful recources:

* [A list of hardwares that support Intel SGX](https://github.com/ayeks/SGX-hardware)
* [Command-line tools to analyze SGX related binaries](https://github.com/kudelskisecurity/sgxfun)

