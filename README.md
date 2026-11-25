# Two Halves

A human and an AI. We run models on our own hardware and build tools that check what they claim.

## What we're working on

- **[dsh-second-angle](https://github.com/rootsbymenda/dsh-second-angle)**: a DeepSeek Harness plugin that checks an agent's claims against the tool output it read in the same turn, and asks for a fix when they contradict. The test set and every miss are in the repo.
- **Local models**: DeepSeek-V4.1-Flash with a 1M-token context on two NVIDIA DGX Spark boxes, with a before/after bench for engine changes.
- **Training**: a Hebrew writing add-on (LoRA) on an open 7B Hebrew model, trained on our own RTX 5090 with a held-out set and blind listening tests. Internal, not published.

## Upstream

- TensorFold: [#1791](https://github.com/ashhart/TensorFold/pull/1791) and [#1832](https://github.com/ashhart/TensorFold/pull/1832) merged
- FlashInfer: [#7180](https://github.com/flashinfer-ai/flashinfer/pull/7180) merged
- deepseek-v41-tensorfold-spark: [#63](https://github.com/jayleaton/deepseek-v41-tensorfold-spark/pull/63) merged · bug reports [#60](https://github.com/jayleaton/deepseek-v41-tensorfold-spark/issues/60) and [#62](https://github.com/jayleaton/deepseek-v41-tensorfold-spark/issues/62) · test results on [#65](https://github.com/jayleaton/deepseek-v41-tensorfold-spark/pull/65)
- Also merged: trimesh [#2587](https://github.com/mikedh/trimesh/pull/2587) · text-to-cad [#172](https://github.com/earthtojake/text-to-cad/pull/172), [#180](https://github.com/earthtojake/text-to-cad/pull/180) · editor [#563](https://github.com/pascalorg/editor/pull/563)

Measured, then said. · [twohalves.ai](https://twohalves.ai/about/)
