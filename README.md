# 🥤 Quebra-Gelo FYS: Copiloto de Objeções de Balcão

## 🎯 O Desafio
Este projeto foi desenvolvido como parte do desafio "Copiloto de Vendas com IA para Atendimento ao Cliente". A solução utiliza Inteligência Artificial para atuar como um assistente de vendas focado na marca **FYS**, do grupo HEINEKEN. O objetivo é ajudar a força de vendas a contornar objeções de donos de pontos de venda (PDVs) com argumentos rápidos, perspicazes e alinhados ao tom de voz irreverente da marca.

## 👤 Usuário Principal
Vendedores externos, promotores de vendas e equipe comercial B2B do grupo HEINEKEN que atendem padarias, bares, mercados e conveniências.

## 🛠️ O Problema Resolvido
Durante a rotina comercial, o vendedor frequentemente enfrenta resistências no balcão: o cliente diz que não tem espaço na geladeira, que a marca é desconhecida ou que os consumidores só pedem "o de sempre". Pensar em uma resposta convincente e fora do clichê corporativo ali na hora é um desafio. O Copiloto resolve isso sugerindo abordagens em tempo real, quebrando o gelo e facilitando a entrada do produto.

## 🧠 Base de Conhecimento Utilizada
Para garantir que a IA não dê respostas genéricas e mantenha a "pegada FYS", o copiloto consome os seguintes arquivos presentes na pasta `knowledge/`:
1. **`produtos-fys.md`**: Detalhes técnicos, diferenciais (menos açúcar, qualidade Heineken) e portfólio.
2. **`guia-de-objecoes.md`**: Diretrizes de tom de voz (ácido, bem-humorado, direto) e mapeamento das resistências mais comuns.
3. **`transcricao-live-fys.txt`**: Contexto estratégico extraído diretamente do material oficial da marca.

## 💻 Exemplo de Uso (Simulação)

> **Situação:** O vendedor está em uma padaria de bairro tentando colocar a FYS Tônica na geladeira.
> 
> **Vendedor (Prompt):** "O dono da padaria disse que não vai levar a FYS porque a geladeira dele já está lotada com o refrigerante da concorrência e ele não quer arriscar perder espaço com marca nova."
> 
> **Copiloto FYS (Resposta da IA):** "Essa é clássica! Vamos tirar ele do piloto automático. Diga a ele: *'Entendo que o espaço é concorrido, mas geladeira cheia da mesma coisa não traz cliente novo, só atende quem já ia comprar de qualquer jeito. A FYS tem a qualidade Heineken, menos açúcar e chama a atenção de quem quer sair da mesmice. Me dá um espacinho de teste na prateleira por 15 dias. Se não girar, a gente repensa.'* Mantenha a postura confiante e sorriso no rosto. Menos é mais!"

## 🔮 Melhorias Futuras
Como próximos passos para evoluir essa arquitetura de software, planeja-se:
* Desenvolvimento de uma API RESTful em Java utilizando o framework Spring Boot para integrar o copiloto diretamente aos sistemas de ERP e CRM já utilizados pela equipe de vendas.
* Implementação de análise de dados das objeções mais frequentes por região para retroalimentar a estratégia de marketing.
