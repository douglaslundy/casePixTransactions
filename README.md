# Análise e Previsão de Fraude em Transações Pix

Este projeto foi desenvolvido para analisar transações Pix e criar um modelo preditivo de fraude. Com a crescente adoção do Pix no Brasil, é crucial identificar padrões de uso que possam sinalizar comportamentos fraudulentos. Nosso objetivo principal foi entender as transações e desenvolver um modelo capaz de prever possíveis fraudes.

## Objetivo

- Analisar as transações Pix realizadas por clientes.
- Identificar padrões e comportamentos indicativos de possíveis fraudes.
- Desenvolver e implementar um modelo de machine learning para prever transações fraudulentas.

## Metodologia

1. **Coleta de Dados**: Os dados foram coletados de registros de transações Pix de um cliente específico.
2. **Análise Exploratória de Dados (EDA)**: Realizamos uma análise detalhada para identificar padrões de transações e comportamentos anômalos.
3. **Desenvolvimento do Modelo**: Utilizamos técnicas de machine learning para construir um modelo que identifica transações potencialmente fraudulentas.
4. **Validação e Avaliação**: O modelo foi testado e validado para garantir sua eficácia na previsão de fraudes.

## Resultados e Conclusões

### 1. Padrões de Transações

Foi constatado que o cliente **Jonathan Gonsalve** realiza um número elevado de transferências Pix mensais. A análise revelou que a principal categoria de transação é a transferência bancária.

### 2. Uso de Bancos

Observou-se que o segundo banco mais utilizado pelo cliente é o **BTG**. Embora Jonathan faça várias transferências para este banco, o valor total dessas transações é o menor entre os bancos analisados. Isso sugere que Jonathan realiza várias transferências de pequeno valor para o BTG.

### 3. Tentativas de Fraude

Um ponto crítico identificado foi o alto índice de tentativas de fraude na conta desse cliente. Todas as tentativas de fraude envolveram valores superiores a **R$19.999,00** e se enquadram na categoria de transferências. 

### 4. Modelo de Previsão de Fraude

Em resposta a essas observações, desenvolvemos um algoritmo de machine learning capaz de identificar transações fraudulentas com base nos padrões observados. O modelo mostrou-se eficaz em prever possíveis fraudes, especialmente em transações de alto valor.

### 5. Recomendações

Dado o elevado número de tentativas de fraudes e os padrões identificados, recomenda-se a seguinte ação:

- **Reduzir o limite máximo para as transferências Pix** desse cliente. Isso ajudará a mitigar o risco de grandes perdas financeiras devido a fraudes.

Adicionalmente, é provável que Jonathan esteja utilizando sua conta pessoal (PF) para finalidades empresariais (PJ), considerando o elevado volume e os altos valores das transferências. Sugere-se uma revisão do uso da conta para garantir a conformidade com as políticas bancárias.

## Como Executar o Projeto

Para reproduzir o projeto e analisar os dados:

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/seu-usuario/analise-pix-fraude.git
   ```
2. **Instale as Dependências**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Execute o Notebook de Análise**:
   Abra e execute o notebook `analise_pix.ipynb` para visualizar as análises e resultados.

## Contribuições

Contribuições são bem-vindas! Se você tiver sugestões de melhorias ou novas funcionalidades, sinta-se à vontade para abrir um pull request ou uma issue.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
