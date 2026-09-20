# Verified facts: Attention Is All You Need (arXiv 1706.03762)

- Architecture in one line: The Transformer - an encoder-decoder sequence transduction architecture built entirely from stacked self-attention and point-wise fully connected (feed-forward) layers, with no recurrence or convolution (base model: N=6 identical encoder and decoder layers, each with multi-head self-attention, plus an encoder-decoder attention sub-layer in each decoder layer).
- WMT 2014 English-to-German BLEU (big model): 28.4
- WMT 2014 English-to-French BLEU (big model): 41.8
- Training time and hardware for the big model: 3.5 days (300,000 training steps at 1.0 second per step) on one machine with 8 NVIDIA P100 GPUs
- Total parameters of the big model (stated in the paper body, not the abstract): 213 million (Table 3, "big" row, params x 10^6 = 213)
- Exact BLEU difference between the two translation tasks: 13.4 BLEU (41.8 - 28.4 = 13.4, computed by exact decimal arithmetic)
- Projects currently visible in our Weights & Biases account: platform-ops, weather-watch, breakfast-and-learn, simulated_env_tau2 (entity: hezil6643)
