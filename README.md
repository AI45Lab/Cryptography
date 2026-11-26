# A Conditional Subexponential Algorithm for Binary Quasi-Cyclic Syndrome Decoding

[Paper (PDF)](qcsd-subexponential.pdf) · [Lean 4 formalization](https://github.com/wangqy031216-cloud/qcsd-subexponential-lean)

## Overview

Under the exact Boolean tensor contraction hypothesis **TC**, this paper gives a deterministic algorithm for binary quasi-cyclic syndrome decoding in $2^{O(N/\sqrt{\log N})}$ time and polynomial space, where $N$ is the code length.

These are conditional asymptotic results. The improvement over elementary enumeration at linear error weights does not translate into a demonstrated security loss for HQC or BIKE, whose relevant decoding instances use sparse error weights.

## Formal verification

The [companion Lean 4 repository](https://github.com/wangqy031216-cloud/qcsd-subexponential-lean) contains the formalization and reproduction instructions, retaining TC as an explicit assumption. We thank the [Sage-Turing Agent (Turing Agent) team](https://github.com/wangqy031216-cloud/turing-agent) for their formal verification support.

## Contributors
The core contributors are **Hao Yan**, **Yuhang Cao**, and **Yao Tong**, with project leadership from **Qiaosheng Zhang**. 

For discussion, contact [yanfanpu@gmail.com](mailto:yanfanpu@gmail.com) · [@FanPUYen](https://github.com/FanPUYen).
