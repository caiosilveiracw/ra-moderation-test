# Calculadora de Score RA

## Descrição
A **Calculadora de Score RA** é uma ferramenta que permite calcular indicadores de reputação com base em reclamações e avaliações de clientes. Os principais índices calculados são:
- **Índice de Solução (IS)**
- **Média das Avaliações (MA)**
- **Índice de Negócio (IN)**
- **Índice de Resposta (IR)**
- **Score Final**

O sistema permite inicializar valores e adicionar ou remover avaliações para recalcular os índices dinamicamente.

## Tecnologias Utilizadas
- **HTML**
- **CSS** (estilização básica)
- **JavaScript** (lógica de cálculo e manipulação do DOM)

## Como Usar
1. Abra o arquivo `index.html` no navegador.
2. Preencha os campos iniciais:
   - Total de reclamações
   - Reclamações respondidas
   - Reclamações avaliadas
   - Índices atuais (IS, MA e IN)
3. Clique no botão **Iniciar Valores** para carregar os dados iniciais.
4. Para adicionar uma nova avaliação:
   - Escolha se a reclamação foi resolvida
   - Informe a nota da reclamação
   - Escolha se o cliente voltaria a fazer negócio
   - Clique no botão **Adicionar Avaliação**
5. Para remover uma avaliação, informe os mesmos dados e clique em **Remover Avaliação**.
6. Os resultados dos índices e o Score serão atualizados automaticamente.

## Estrutura do Código
O código utiliza uma classe `ReclamacaoRA` que:
- Armazena os dados das reclamações e avaliações.
- Realiza os cálculos matemáticos para cada índice.
- Atualiza os valores dinamicamente no HTML.

A lógica principal está dentro da função `window.onload`, onde os eventos dos botões são configurados.

## Melhorias Futuras
- Adicionar um banco de dados para persistência dos dados.
- Criar um design responsivo e mais intuitivo.
- Implementar uma API para consumo externo.

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença
Este projeto está sob a licença MIT.
