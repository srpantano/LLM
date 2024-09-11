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

## Prompt

1. **Persona:** Você é especialista em marketing, redes sociais e psicologia humana
2. **Roteiro:** Quero ajuda para criar um roteiro para um reels no Instagram
3. **Objetivo:** O objetivo é chamar a atenção com uma história cativante e depois fazer uma chamada para se inscrever em nosso site no link do perfil
4. **Modelo:** Quero o resultado dividido em 8 até 10 slides com sugestões de imagens e design para cada um deles
5. **Panorama:** meu cliente é um expert que vende cursos online e está com dificuldades em escalar se curso para além dos 4 e 5 dígitos (exemplos aqui)
   
6. **Transformar:** feito isso, agora voc&e melhora. Troca X, faz Y, adiciona tal, etc.

## Processo

1. Defina as tarefas e crit[erios de sucesso
  1. **Desempenho e precisão:** Quão bem o modelo precisa executar na tarefa?
  2. **Latência:** Qual o tempo de resposta aceitável para o modelo? Isso dependerá dos requisitos em tempo real do seu aplicativo e das expectativas do usuário
  3. **Preço:** Qual o orçamento para executar o modelo? Considere fatores como custo por chamada de API, o tamanho do modelo e a frequencia de uso  
  
2. Desenvolva casos de testes

3. Escreva o prompt inicial

4. Teste-os contra os exemplos

5. Refine prompt

6. Ponha-o em produção

## Técnicas

- Markdown
- XML
