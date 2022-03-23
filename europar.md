---
layout: page
title: Euro-Par Workshop
subtitle: 22nd or 23rd August 2022, Glasgow Scotland
---

Scientists and engineers are ever demanding the ability to simulate larger, more complex, systems with reduced time to solution. Based on current trends, future exascale HPC machines will expose extremely large degrees of parallelism across highly heterogeneous architectures, and even to the relatively few highly skilled expert HPC programmers, fully exploit such machines will be a significant challenge. However, the majority of HPC users are domain scientists and engineers who, whilst they are experts in their own scientific fields, view HPC programming as a means to an end and do not possess the knowledge, time, or desire to undertake highly detailed, machine specific, low-level optimisations of their code.

Put simply, the languages and technologies that are currently ubiquitous in HPC (C, Fortran, MPI, OpenMP, CUDA) are too low level for end-user programming of future exascale machines. Determining complex and tedious, but also critically important, aspects of high-performance codes significantly reduces the productivity of scientists even on today’s supercomputers. Instead, HPC programmers should be presented with higher levels of abstraction where they can signal their intentions to the compiler which itself determines the tricky low level optimisation details.

Domain Specific Languages (DSLs) have the potential to revolutionize the development of scientific high-performance software by providing scientists with such abstractions that are tailored for their specific problem. It has been repeatedly demonstrated that, by levering the rich domain knowledge encoded by the programmer, the compilation tool-chain can make effective choices around parallelism. Furthermore, if the DSL is designed correctly, then the programmer is able to express their workload in an architecture-independent fashion, thus making portability across architectures possible, with the compilation tool-chain doing much of the heavy lifting.

In the past few years, DSLs have been more commonly delivered as domain-specific abstractions embedded inside existing, rather than new, languages. Consequently, the term language is a bit of a misnomer, and domain specific abstraction is often more apt. Embedding within existing languages, such as Python, C++, or Fortran, the programmer obtains the best of both worlds, a mature existing language but also domain-specific abstractions that suit their problem.

Many believe that DSLs have the potential to get us closer to achieving the three P’s; productivity, performance, and performance portability. Whilst historically this objective has been often seen as somewhat of a chimera, there is wide acceptance in the HPC community that we need to solve the programming challenges associated with future exascale machines. Furthermore, there is a growing consensus that the benefits that DSLs can deliver are paramount and could be critical in unlocking the full potential of future supercomputers.

However, there are numerous hurdles that must be overcome if DSLs are to be widely accepted. Some of the blockers to their adoption include the maturity of the compilation stack, little sharing of infrastructure between DSLs, difficulties mixing DSLs with other technologies, a lack of best practice porting to DSLs, and few widely publicised success stories of using DSLs. However, there are many on-going activities that look to address such drawbacks and the pace of advancement is rapid.

A workshop at Euro-Par 2022 would enable us to bring together application developers in the HPC community who are already using or interested in using DSLs, with DSL designers and compiler engineers. The resulting discussion and outcomes will enrich these communities and with our afternoon focus session (see next section) will enable concrete outcomes going forward that will increase skills of participants and we believe will lead to numerous real-world benefits.