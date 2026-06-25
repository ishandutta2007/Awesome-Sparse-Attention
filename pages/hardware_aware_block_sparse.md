# The Hardware-Aware Block-Sparse Era

## Overview
Introduced in 2022 with FlashAttention. This era focuses on grouping parameters into dense localized blocks to utilize GPU SRAM effectively.

## Diagram
```mermaid
graph TD
    A[Block Queries] -->|Block Sparse| B[Block Keys]
```
