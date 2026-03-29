# prompt-engineering
Estudo sobre Engenharia de Prompts

### Conceitos:
- <b>Prompt</b>: modelo de input(entrada) em um LLM(Large Languade Model), ou seja, é forma de entrada que um usuário interage com o modelo.
- <b>Alucinação(Hallucination)</b>: são respostas incorretas, inventadas ou sem sentido geradas por modelos de linguagem possivelmente baseadas em algum padrão probabilístico e não em fatos reais
  

### Dicas
- Os melhores prompts são feitos através de 3 pontos-chave: clareza, especificidade e tempo de resposta do modelo(fazer com o que o modelo tenha tempo de análise/pensamento/processamento)
- <b>Clareza</b>: adicionar contexto no prompt através de instruções ao modelo. Ex: quem você é(Sou um especialista em mercado imobiliário)
- <b>Especificidade</b>: trocar algo genérico por mais específico. Ex: Genérico: Passo a passo de como trocar a bateria de um carro. Específico: Sou um especialista em mecânica de automóveis e preciso de um plano detalhado incluindo as melhores práticas de segurança sobre como realizar a troca da bateria do carro de marca X e modelo Y.
- <b>Temperatura</b>: usar o parâmetro de temperatura até valor 1. Pois acima desse valor irá fazer com o que o modelo retorne com respostas dinâmicas, imprecisas, incoerentes e fora de contexto. Entre 0 e 1 as respostas tendem a ser mais precisas e consistentes. Quando maior a temperatura mais dinâmica será a resposta, quanto menor a temperatura mais precisa a resposta.
- <b>Tokens</b>: limitar também os tokens de saída(resposta): Tokens com valor acima de 2048 também podem causar respostas ineficientes do modelo.

### Exemplos


### Plataforma para testes dos modelos:
platform.openai.com
