# prompt-engineering
Estudo sobre Engenharia de Prompts

### Conceitos:
- <b>Prompt</b>: modelo de input(entrada) em um LLM(Large Languade Model), ou seja, é forma de entrada que um usuário interage com o modelo.

### Dicas
- <b>Temperatura</b>: usar o parâmetro de temperatura até valor 1. Pois acima desse valor irá fazer com o que o modelo retorne com respostas dinâmicas, imprecisas, incoerentes e fora de contexto. Entre 0 e 1 as respostas tendem a ser mais precisas e consistentes. Quando maior a temperatura mais dinâmica será a resposta, quanto menor a temperatura mais precisa a resposta.

- <b>Tokens</b>: limitar também os tokens de saída(resposta): Tokens com valor acima de 2048 também podem causar respostas ineficientes do modelo.

### Plataforma para testes dos modelos:
platform.openai.com
