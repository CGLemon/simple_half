# Simple Half Library

A very simple half library which supports the IEEE-754 float16. You may use it in the CUDA.

## Usage

Get the correspond float16 binary value and float32.

```cpp
    half_float_t v = GetFp16(1.5f); // float to binary16

    float o = GetFp32(v); // binary16 to float
```

