# Faithful-COT


  Here are the accuracy scores in comparison to the original **Codex** (`code-davinci-002`), using the same prompt + greedy decoding:

|         | **GSM8K** | **SVAMP** | **MultiArith** | **ASDiv** | **AQUA** | **saycan** | **StrategyQA** | **date** | **sports** | **CLUTRR** |
|-----------------------------|:---------:|:---------:|:--------------:|:---------:|:--------:|:----------:|:--------------:|:--------:|:----------:|:----------:|
| **Codex** |   72.2    |   83.5    |    **98.8**    |   80.2    |   47.2   | 89.3       |    **63.0**    | 81.6     | 99.1       | 58.9       |
| **ChatGPT**  |   75.8    |   83.0    |      95.3      |   81.7    |   53.5   | 80.6       |      51.5      | 73.5     | 52.3       | 12.1       |
| **GPT-4**     | **95.0**  | **95.3**  |      98.5      | **95.6**  |  **73.6**  | **92.2**       |      54.0      | **95.8**     | **99.3**       | **62.7**       |

With GPT-4, Faithful CoT achieves❗**95.0+** few-shot accuracy❗on almost all Math Word Problem datasets, Date Understanding, and Sports Understanding.









