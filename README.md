# prompt-engineering
Estudo sobre Engenharia de Prompts

### Conceitos:
- <b>Prompt</b>: modelo de input(entrada) em um LLM(Large Languade Model), ou seja, é forma de entrada que um usuário interage com o modelo.
- <b>Alucinação(Hallucination)</b>: são respostas incorretas, inventadas ou sem sentido geradas por modelos de linguagem possivelmente baseadas em algum padrão probabilístico e não em fatos reais
  

### Dicas
- Os melhores prompts são feitos através de 3 pontos-chave: clareza, especificidade e tempo de resposta do modelo(fazer com o que o modelo tenha tempo de análise/pensamento/processamento)
- <b>Clareza</b>: adicionar contexto no prompt através de instruções ao modelo. Ex: quem você é(Sou um especialista em mercado imobiliário)
- <b>Especificidade</b>: trocar algo genérico por mais específico. Ex: Genérico: Passo a passo de como trocar a bateria de um carro. Específico: Sou um especialista em mecânica de automóveis e preciso de um plano detalhado incluindo as melhores práticas de segurança sobre como realizar a troca da bateria do carro de marca X e modelo Y.
- Tomar cuidado com Sobrecarga, Ambiguidade e Complexidade dos prompts
- <b>Temperatura</b>: usar o parâmetro de temperatura até valor 1. Pois acima desse valor irá fazer com o que o modelo retorne com respostas dinâmicas, imprecisas, incoerentes e fora de contexto. Entre 0 e 1 as respostas tendem a ser mais precisas e consistentes. Quando maior a temperatura mais dinâmica será a resposta, quanto menor a temperatura mais precisa a resposta.
- <b>Tokens</b>: limitar também os tokens de saída(resposta): Tokens com valor acima de 2048 também podem causar respostas ineficientes do modelo.

### Exemplos de prompts

<b>Genérico, sem clareza e sem especificidade</b>
```
Desenvolva um plano para aula sobre lógica de programação
```
<b>Com clareza e especificidade</b>:
```
Sou um professor especialista em desenvolvimento de software preparando uma aula sobre lógica de programação
para alunos do 1º ano do Ensino Médio e usando a linguagem de programação Portugol.
Desenvolva um plano de aula para uma turma de 18 alunos com duração de 90 minutos.
No laboratório haverá computadores e projetor disponíveis.
```
<b>Sobrecarga</b>
```
Sou uma costureira especialista em roupas de alto padrão para festas de formatura, gosto de usar roupas leves,
passear no shopping e pratico academia diariamente.
Preciso de 3 sugestões de tecidos antialérgicos para confecção das vestimentas para uma grupo de alunos.
```
<b>Ambiguidade</b>
```
Sou um exímio especialista em engenharia civil e gostaria de um plano detalhado para construção de um prédio
ou casa ou kitnet incluindo todas as normas de segurança em um terreno em torno de 69 a 75 metros quadrados.
```



### Plataforma para testes dos modelos:
platform.openai.com
