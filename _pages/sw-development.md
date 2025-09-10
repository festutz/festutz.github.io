---
permalink: /software/
title: ""
excerpt: ""
author_profile: true
---

# Research Prototypes and Frameworks

I have worked on a variety of problems that give rise to different kinds of software artifacts. Some projects require concrete implementations or tool support, like the annotation library for PaSh. Others are more theoretical -- focused on formalization and proofs -- yet we still enjoy building prototype tools to explore our ideas and validate our findings.


- <span class="bluelinks">
<strong>Sprout</strong> -- Symbolic Protocol Verifier
[[*code*](https://github.com/nyu-acsys/sprout)]
</span>
<br>
Sprout is an implementability checker for symbolic multiparty protocols. 
It takes as input a global protocol specification with dependent refinements on message values and loop memory. 
It then determines if the desired behaviour can be realised in a distributed setting. 
Our [OOPSLA 2025](https://2025.splashcon.org/track/OOPSLA) paper provides the theoretical foundations while 
our [CAV 2025](https://conferences.i-cav.org/2025/) paper gives details on the implementation. 

- <span class="bluelinks">
<strong>AMGC</strong> -- From Global Protocol Specifications to Participant Specifications
[[*code*](https://gitlab.mpi-sws.org/fstutz/async-mpst-gen-choice)]
</span>
<br>
For our work on asynchronous multiparty session types, we implemented our techniques to generate verified participant specifications from global protocol specifications.
For the theoretical foundations, check out our [CONCUR21](https://arxiv.org/pdf/2107.03984.pdf) and [CAV23](https://arxiv.org/abs/2305.17079) papers. 

- 
<strong> 
Annotation Library for Command Invocations
</strong>
in 
<strong>[PaSh](https://binpa.sh)</strong> 
<span class="bluelinks">
[[*code*](https://github.com/binpash/annotations), [*PyPI*](https://pypi.org/project/pash-annotations/)]
</span>
<br>
<span class="bluelinks">
<!-- I have contributed to the shell script parallelization framework PaSh -->
<!-- [[*code*](https://github.com/binpash/pash)]. -->
I designed, implemented and integrated an 
annotation library for command invocations
that provides means to specify command invocation behaviours in the form of annotations.
For PaSh, it provides parallelizability and input-output information and its accuracy is crucial both for correctness and performance.
<!-- Input-output information is required for the translation between actual shell scripts and the internal model for transformations. -->
</span>

- 
<strong>Heimdall</strong> 
-- Message Interception and Scheduling Utilities for Erlang Applications 
[[*code*](https://github.com/Heimdall-message-interception-framework)] 
<br>
<!-- Together with [Julian Haas](https://julian-haas.de/), I have built  -->
Erlang has built-in primitives to send and receive messages as well as standard libraries for message-passing programs.
We instrumented these libraries to intercept and control the delivery of messages with different schedulers.
This can be used to test Erlang programs with different scheduling algorithms.

- <span class="bluelinks">
<strong>Lemma9</strong> -- Inductive Invariants for Security Protocols 
[[*code*](https://github.com/festutz/lemma9)] 
<br>
This prototype implements our approach for verifying security protocols, presented 
</span>
at [CONCUR20](https://arxiv.org/pdf/1911.05430.pdf).
It can infer and check inductive invariants for protocols with an unbounded number of sessions. 

- <strong>[PROSA](https://prosa.mpi-sws.org/)</strong> -- Coq framework of and for definitions and proofs for real-time schedulability [[*repo*]](https://gitlab.mpi-sws.org/RT-PROOFS/rt-proofs)
<br>
As an undergraduate assistant, I helped with the initial version of this framework, which has been presented at [ECRTS16](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7557887).
