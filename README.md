# LLM


O que é um Large Language Model?

A language model (LM) é o modelo probabilístico do texto. 

Imaginem a seguinte frase: Eu pedi ao vendedor que me indicasse um veículo para ir ao trabalho. Ele me mostrou o…

O que a LM faz é fornecer a probalidade, para cada palavra em seu vocabulário, de aparecer como resposta.

Neste caso, as prováveis palavras poderiam ser: *Trator 0.1, ônibus 0.1, sedan 0.3, SUV 0.2, caminhão 0.05.*

Já o primeiro “large”, em “large language model”, refere-se ao número de parâmetros do model, porém não existe uma definição exata de a partir de quantos parâmetros se considera large.


## Arquitetura LLM

### Enconders

Modelo que converte uma sequencia de palavras em uma representação vetorizada (embedding).

**Exemplos:** BERT, MiniLM, SBERT, etc.

### Decoders

Modelos que pegam uma sequencia de palavras e produzem a próxima.

Os decoders produzem *apenas um pavalra por vez*.

**Exemplos:** GPT-4, Llama, Cohere, etc.
