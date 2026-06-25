# Longformer & BigBird

## Overview
Combines local sliding window, strided, and global anchor token attention.

## Diagram
```mermaid
graph TD
    A[Local] --> B[Combined Attention]
    C[Global] --> B
```
