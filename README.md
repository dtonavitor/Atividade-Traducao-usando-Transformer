# Atividade: Tradução usando Transformer
## Pontos Positivos
- Resultado: Apesar de uma acurácia de aproximadamente 70%, o que poderia indicar uma tradução possivelmente errada, a tradução dos textos de teste fazem bastante sentido com o texto original, mesmo sendo uma tradução mais literal.
- Gráficos dos heads: A visualização das attention heads no modelo Transformer permite uma melhor interpretação do modelo, ajudando a entender como ele distribui a atenção entre as palavras ao realizar a tradução. Cada head foca em diferentes partes da frase, capturando relações variadas, o que aprimora a capacidade do modelo de entender contextos complexos.

## Pontos Negativos
- Custo computacional: Apesar de ser eficiente em termos de paralelismo, o modelo Transformer exige muita memória e poder de processamento, especialmente para tarefas que envolvem sequências longas. Isso pode ser um problema para usuários com hardware limitado.
- Treinamento demorado: Embora os Transformers sejam eficientes para inferência em comparação com modelos sequenciais, o treinamento pode ser muito demorado, especialmente em dados grandes ou complexos, o que pode ser um obstáculo para quem não tem acesso a recursos computacionais avançados.
