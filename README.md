# QuantizationLLM

This repository contains the process of quantizing the Meta-Llama-3-8B model, reducing its precision to 4 bits to optimize its use on resource-limited devices.

![image](https://github.com/user-attachments/assets/46229dac-dd31-4203-946f-1ac58b28dbe2)

- Load the base model: The meta-llama/Meta-Llama-3-8B model is downloaded from Hugging Face.

- Quantization: Precision is reduced to 4 bits using BitsAndBytesConfig.

- Saving and uploading: The quantized model is saved and uploaded to Hugging Face for reuse.

This approach enhances efficiency in deploying LLM models in computational environments with memory constraints.
