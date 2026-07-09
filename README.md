# 🥤 Copiloto de Vendas B2B: Operação "Menos Marketing, Mais Margem" (FYS nas Padarias)

Este repositório contém o projeto final do desafio **Copiloto de Vendas com IA para Atendimento ao Cliente**, focando em uma solução estratégica para a marca **FYS** (Grupo HEINEKEN).

---

## 🎯 1. Qual tema foi escolhido?
O tema escolhido foi a **Estratégia B2B de inserção da marca FYS no canal de padarias**. O projeto foca em utilizar a IA não para falar com o consumidor final, mas para capacitar e apoiar o representante comercial da Heineken a vender o produto para o dono do estabelecimento (B2B).

## 👤 2. Quem é o usuário principal da solução?
O usuário final deste copiloto é o **Representante Comercial / Vendedor B2B** do Grupo Heineken, que faz as rotas diárias de vendas e precisa de argumentos rápidos e persuasivos para inserir novos produtos nos pontos de venda.

## 💡 3. Qual problema de vendas a solução resolve?
1. **Falta de tempo e foco do vendedor:** O vendedor ganha comissão e tende a focar na venda de cervejas, que têm maior saída. O copiloto entrega "mastigado" um argumento de rentabilidade rápida para vender FYS sem perder tempo.
2. **Resistência do dono da padaria:** Donos de padaria hesitam em adicionar novos refrigerantes por falta de espaço ou por acharem que não vai vender. O copiloto ajuda o vendedor a contornar essas objeções propondo o **"Combo Menos Culpa"** (Salgado + FYS).

## 🤖 4. Qual abordagem foi utilizada?
Foi utilizado um **Agente/Copiloto Consultivo baseado no NotebookLM**. A ferramenta atua como um assistente de bolso, onde o vendedor pode consultar rapidamente qual a melhor forma de abordar uma padaria, como estruturar o pitch de vendas e como responder às objeções do cliente no balcão.

## 📚 5. Quais informações foram usadas como Base de Conhecimento?
A base de conhecimento da IA foi alimentada com:
* **Transcrições de Lives e Documentos do Repositório de Apoio FYS:** Fornecendo o contexto real dos desafios comerciais da marca.
* **Site Oficial da FYS (www.fys.com.br):** Para absorver o posicionamento da marca de "50% menos açúcar e menos marketing" e o tom de voz ácido.
* **Guia de Vendas B2B (Trade Marketing):** Documento customizado contendo horários ideais de abordagem, estratégias de cross-merchandising na estufa de salgados e matriz de objeções.

## 💬 6. Exemplo de Uso (Simulação)

**🧑‍💼 Vendedor (Prompt):** > *"Estou em uma padaria no centro. O dono disse que não tem espaço na geladeira para colocar a FYS e que os clientes dele só pedem a marca líder. O que eu respondo?"*

**🤖 Copiloto IA (Resposta):** > *"Não peça para ele tirar a marca líder! Use este argumento: 'A FYS não substitui a marca líder, ela captura o cliente que parou de tomar refrigerante por achar muito doce. É uma venda adicional.' Sobre o espaço, proponha um teste rápido: 'Só precisamos de uma fileira na altura dos olhos. Se o combo de Coxinha + FYS não girar em 15 dias, nós repensamos a estratégia.' Lembre-o de que a margem de lucro dele com a FYS será maior nesse combo."*

## 🚀 7. Possíveis Melhorias Futuras
* **Integração Omni-channel:** Conectar o copiloto diretamente ao WhatsApp corporativo do vendedor para consultas via áudio enquanto dirige entre uma rota e outra.
* **Análise de Dados de PDV (KPIs):** Capacidade de o vendedor inserir dados ("Vendi 2 fardos, mas sobrou 1") e a IA sugerir táticas de Trade Marketing (como mudar o cartaz de lugar) para girar o produto encalhado.
* **Geolocalização:** A IA sugerir abordagens diferentes dependendo se a padaria está em um bairro universitário (foco no humor ácido) ou bairro residencial familiar.
