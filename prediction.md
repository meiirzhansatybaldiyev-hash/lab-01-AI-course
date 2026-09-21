### Part 1 — Prediction

Before measuring the actual token counts, I predicted that the Russian version would require more tokens than the English version, while the Kazakh version would require even more tokens.

My prediction was:

* **Russian / English ≈ 1.5×**
* **Kazakh / English ≈ 2.0×**

I based this prediction mainly on the difference in the number of characters and the way multilingual text can be split into subword tokens. English is expected to be the most token-efficient, while Russian and especially Kazakh may require more tokens for the same meaning. Tokenization can produce different token counts even when texts have similar meanings and lengths.
