# Polar Codes and Decoding Techniques

This repository contains a Python implementation of Polar Codes and various decoding techniques, developed for the CT-216 Project at IIT Gandhinagar.

## 📚 Overview

Polar Codes are a class of error-correcting codes that achieve the capacity of symmetric binary-input memoryless channels. This project implements:

- Hard Decision Decoding
- Successive Cancellation (SC) Decoding — Iterative
- Successive Cancellation (SC) Decoding — Recursive
- Successive Cancellation List (SCL) Decoding with CRC

## 📁 Files

| File | Description |
|------|-------------|
| `Encoding+Hard_decoding.py` | Implementation of hard decision decoding |
| `Encoding+Successive_Cancellation_decoding_iterative.py` | SC decoding using an iterative approach |
| `Encoding+Successive_Cancellation_decoding_recursive.py` | SC decoding using a recursive approach |
| `Encoding+Successive_Cancellation_list_decoding.py` | List decoding with CRC (SCL decoding) |

## ⚙️ How to Run

### Prerequisites

- Python 3.x
- `numpy`, `matplotlib`

Install dependencies using:

```bash
pip install numpy matplotlib
