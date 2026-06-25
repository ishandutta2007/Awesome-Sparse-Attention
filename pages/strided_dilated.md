# Strided / Dilated Attention

## Overview
The attention mask skips indices at a fixed periodic interval to capture long-range patterns without extra token budget.

## Diagram
```mermaid
graph LR
    T1 -.- T3 -.- T5
```
