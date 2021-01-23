**Introduction

This example demonstrates how to use a LSTM model to generate text character-by-character.

At least 20 epochs are required before the generated text starts sounding locally coherent.

It is recommended to run this script on GPU, as recurrent networks are quite computationally intensive.

If you try this script on new data, make sure your corpus has at least ~100k characters. ~1M is better.
