# Infini-former Attention in PyTorch

This repository contains a PyTorch implementation of the Infini-former attention mechanism, as proposed in the paper "[Infini-former: Towards Infinite-context Attention for Transformers]" by Google research.

## Overview

The Infini-former attention mechanism is designed to overcome the limitation of fixed-length context in traditional transformer models. It introduces a novel attention mechanism that can efficiently attend to an unbounded context, enabling the model to capture long-range dependencies and improve performance on various natural language processing tasks.

This implementation provides a toy implementation of a decoder only transformer, with infi-attention incorporated, written in pytorch.

## Features

- The repo downloads the dataset from an endpoint and gets it ready to train for causal LM, which is sherlock holmes text.
- PyTorch implementation of the Infini-former attention mechanism.
- Efficient computation of attention scores using a compressive memory scheme.
- Support for variable-length input sequences.
- Detailed documentation and code comments.