# LLM Inference Notes

Personal notes on running open LLMs, vLLM/SGLang, and quantization.

## Focus

- Open model serving with vLLM and SGLang
- Quantization basics: AWQ, GPTQ, GGUF
- Interest in AMD ROCm / MI300X inference

## Checklist

- Fit model to VRAM after quantization
- Measure tokens/sec and TTFT
- Validate ROCm + PyTorch before long runs

## Smoke snippet

```python
prompt = "Quantization trade-offs for LLM serving"
print(len(prompt))
```

Independent WIP experiment notes.
















