# Data-Bias

## Reflection on Bias Testing in Perspective Model

In testing the Perspective model for potential bias based on content length, I observed interesting patterns in the results. The hypothesis that shorter and more informal content, resembling tweets, might lead to more false positives or false negatives in toxicity scores was partially supported by the findings.

Surprisingly, the model demonstrated a high sensitivity to explicit toxic language. Comments containing offensive terms consistently received high toxicity scores, suggesting that the model is effective in identifying explicit toxicity.

One theory for the observed bias is that the model might struggle with the nuances of informal language, especially when combined with positive expressions like "cool" and "amazing." The use of such language might lead to an overestimation of toxicity, as the model may misinterpret enthusiasm or excitement as potentially offensive.
