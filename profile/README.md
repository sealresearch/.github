<img src="https://seal.computer/favicon.svg" alt="Seal" width="56" height="56">

# Seal Research

Tiny AI models that run entirely on the device. No cloud, no account.

Seal Research builds the models behind [Seal](https://seal.computer), a small computer you carry in your pocket. Each model is built for one job and is small enough to ship inside an app. We publish how we test them, including where they lose.

## Models

| Model | What it does | Size | Licence |
| --- | --- | --- | --- |
| [Relay](https://github.com/sealresearch/gust/tree/main/models/relay) | Turns a request and a list of tools into exact function calls, on the device. It reads the answer instead of writing it, so it cannot invent a phone number. | 11.5 MB | CC BY 4.0 |

The weights are on [Hugging Face](https://huggingface.co/sealresearch/relay). The code that runs them is [Gust](https://github.com/sealresearch/gust), our dependency-free C runtime, under the MIT licence. More models will follow as they are ready.

## Research

We write up every model: how it works, how we tested it against other models, and where it falls short.

- [Relay 1](https://seal.computer/research/relay-1)

## Links

- Website: [seal.computer](https://seal.computer)
- Research: [seal.computer/research](https://seal.computer/research)
- Code: [github.com/sealresearch/gust](https://github.com/sealresearch/gust)
- Weights: [huggingface.co/sealresearch](https://huggingface.co/sealresearch)
- Contact: [support@seal.computer](mailto:support@seal.computer)
