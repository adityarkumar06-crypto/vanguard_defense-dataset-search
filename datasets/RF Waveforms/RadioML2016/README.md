# RadioML2016.10a Dataset

**Source:** [DeepSig - RML2016.10a](https://www.deepsig.io/datasets)

## Description
RadioML2016.10a is a synthetic dataset for modulation recognition, widely used in RFML benchmarks and research.

- 11 modulation types (AM-DSB, QPSK, 8PSK, etc.)
- SNR range: -20 dB to +18 dB
- File format: `.h5`
- 220,000 total samples (1000 vectors per class per SNR)

## Sample Contents
This folder contains sample `.h5` files from the dataset for reference.

## Instructions

1. Go to the [DeepSig dataset portal](https://www.deepsig.io/datasets) and download `RadioML2016.10a`.
2. Load the `.h5` files using Python (e.g., with `h5py` or `scipy.io`).
3. Each sample includes 128 complex-valued IQ samples and a label for modulation + SNR.

## Example Load Snippet
```python
import h5py

with h5py.File('RML2016.10a_dict.h5', 'r') as f:
    keys = list(f.keys())
    print("Keys:", keys)
    sample_data = f[keys[0]][:]

