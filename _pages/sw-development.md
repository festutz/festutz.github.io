---
permalink: /software/
title: ""
excerpt: ""
author_profile: true
---

# Research Prototypes and Frameworks

I have been coding for different kind of projects.
For some types of problems, tool support or an implementation is crucial -- like the shell script parallelization framework PaSh.
But some of my research has quite a theoretical focus so this is not necessarily the case.
I still usually implement a prototype to play around with our ideas and evaluate them.


- <span class="bluelinks">
For our work on asynchronous multiparty session types, I developed the prototype <strong>AMGC</strong> 
[[*code*](https://gitlab.mpi-sws.org/fstutz/async-mpst-gen-choice)]
which implements our technique to generate verified participant specifications from global protocol specifications.
</span>
For the theoretical foundations, check out our [CONCUR21 paper](ihttps://arxiv.org/pdf/2107.03984.pdf).

- I have contributed to the shell script parallelization framework 
<strong>[PaSh](https://binpa.sh)</strong> 
<span class="bluelinks">
[[*code*](https://github.com/binpash/pash)].
Mainly, <nobr>I designed</nobr>, implemented and integrated an 
<strong> annotation library for command invocations</strong> [[*code*](https://github.com/binpash/annotations), [*PyPI*](https://pypi.org/project/pash-annotations/)]
that provides means to specify command invocation behaviours in the form of annotations.
For PaSh, it provides parallelizability and input-output information.
The accuracy of this information is crucial both for correctness and performance.
Input-output information is required for the translation between actual shell scripts and our internal model for transformations.
</span>

- Together with [Julian Haas](https://julian-haas.de/), I have built 
<span class="bluelinks">
<strong>Heimdall</strong> [[*code*](https://github.com/Heimdall-message-interception-framework)] which provides message interception and scheduling utilities for Erlang applications.
Erlang has built-in primitives to send and receive messages as well as standard libraries for message-passing programs.
We instrumented these libraries to intercept and control the delivery of messages with different schedulers.
This can be used to test Erlang programs with different scheduling algorithms.
</span>

- <span class="bluelinks">
The prototype <strong>Lemma9</strong> [[*code*](https://github.com/festutz/lemma9)] implements our approach for verifying cryptographic protocols that we presented 
</span>
at [CONCUR20](https://arxiv.org/pdf/1911.05430.pdf).
It can infer and check inductive invariants for protocols with an unbounded number of sessions. 

- As an undergraduate assistant, I helped with the initial version of 
<strong>[PROSA](https://prosa.mpi-sws.org/)</strong>, 
which is a Coq framework of and for definitions and proofs for real-time schedulability analysis.
