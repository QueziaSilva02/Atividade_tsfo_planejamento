<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4B0082,50:6A5ACD,100:00BFFF&height=220&section=header&text=CARRINHO%20DE%20COMPRAS&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Refatoração%20%7C%20Testes%20%7C%20Debugging&descAlignY=58&descSize=18"/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=22&duration=2200&pause=700&color=00BFFF&center=true&vCenter=true&width=750&lines=Analisando+o+código...;Executando+testes...;Encontrando+bugs...;Investigando+a+causa+raiz...;Refatorando+com+segurança...;Sistema+validado+%E2%9C%93"/>

<br>

<img src="https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-6A5ACD?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/FOCO-QUALIDADE-00BFFF?style=for-the-badge&logo=codefactor&logoColor=white"/>
<img src="https://img.shields.io/badge/ÁREA-SOFTWARE%20TESTING-8A2BE2?style=for-the-badge&logo=testinglibrary&logoColor=white"/>

</div>

## 🎯 O que eu fiz neste trabalho?

Neste trabalho prático, assumi o papel de desenvolvedor/QA para analisar, refatorar e validar o módulo de **Carrinho de Compras** de um e-commerce. O meu objetivo principal foi investigar o código existente, mapear regras de negócio cruciais, criar uma bateria de testes automatizados e utilizar ferramentas de *debugging* para localizar e corrigir falhas no cálculo de valores, taxas e validação de cupons.

---

## 📌 Por que essa prática foi fundamental?

O carrinho de compras é o coração de qualquer e-commerce. Durante o projeto, percebi na prática que pequenos erros na lógica — como calcular incorretamente o frete, aplicar descontos fora do prazo ou permitir produtos sem estoque — geram prejuízos financeiros diretos e frustram o cliente.

> 💡 **Perspectiva do Projeto:**  
> Em vez de criar uma aplicação do zero, trabalhei com a estrutura de um sistema legado real: **analisei o código existente, identifiquei inconsistências no fluxo de dados** e garanti que o código final ficasse seguro, limpo e totalmente funcional.

---

## 🚀 Passo a Passo: Como executei o projeto

* **Etapa 1 • Análise e Entendimento da Arquitetura**  
  Comecei estudando a estrutura das classes e o fluxo de dados do carrinho. Mapeei como os produtos eram adicionados, como o subtotal era calculado e como os serviços de frete e cupons interagiam com o sistema.

* **Etapa 2 • Inspeção de Código e Caça aos Bugs (`Code Smells`)**  
  Analisei as regras de negócio em busca de falhas ocultas. Identifiquei métodos muito extensos, acoplamento excessivo e falta de tratamento para cenários em que cupons inválidos ou quantidades negativas alteravam o total de forma incorreta.

* **Etapa 3 • Construção e Automação da Bateria de Testes**  
  Montei cenários de teste automatizados cobrindo tanto o fluxo principal ("caminho feliz") quanto casos de borda: tentativa de inserir produtos sem estoque, aplicação de cupons vencidos, alteração de limites e recálculo de frete.

* **Etapa 4 • Depuração Mão na Massa (`Debugging` e Correção)**  
  Com as falhas apontadas pelos testes, utilizei recursos de depuração (`breakpoints`, inspeção de variáveis em memória e análise de pilha de execução) para encontrar a linha exata dos erros no código e corrigi-los um a um.

* **Etapa 5 • Refatoração, Validação e Entrega**  
  Reestruturei as funções com problemas para deixá-las limpas e modulares. Rodei novamente toda a suíte de testes até obter 100% de aprovação, garantindo a estabilidade e manutenibilidade do módulo.

---

## 🏁 Conclusão e Resultados Obtidos

A realização deste trabalho me proporcionou uma visão completa e realista sobre a garantia de qualidade no desenvolvimento de software. A transição de apenas procurar bugs manualmente para construir uma suíte automatizada de testes com suporte de *debugging* mostrou como prevenir regressões em sistemas complexos.

Como resultado final, o módulo de **Carrinho de Compras foi totalmente estabilizado e refatorado**. Consegui eliminar os comportamentos inconsistentes no cálculo de descontos e taxas, elevar a cobertura de testes e entregar um código robusto, pronto para evoluir com segurança no ambiente de produção.

---

<div align="center">

### 👨‍🎓 Trabalho desenvolvido pela aluno
### Quezia Brito 
*Disciplina de Refatoração, Testes e Debugging em Software*  
**Orientador:** Prof. André Luis Denani

</div>
