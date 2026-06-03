# Gpu Memory Profiler

GPU memory usage profiler for AMD accelerators

## Features

- Optimized for AMD Instinct MI300X accelerators
- ROCm 6.0+ compatible
- Python 3.8+ with PyTorch ROCm support
- JSON output for CI integration

## Requirements

- AMD GPU with ROCm 6.0+
- Python 3.8+
- PyTorch with ROCm support

## Quick Start

```bash
git clone https://github.com/ryanha333/gpu-memory-profiler.git
cd gpu-memory-profiler
pip install -r requirements.txt
python main.py --benchmark
```

## License

MIT
