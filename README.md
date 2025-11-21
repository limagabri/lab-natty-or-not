# 🛡️ Security Analyst Assistant - Natty or Not?

## 📒 Descrição
Este projeto explora o potencial das IAs Generativas na área de Segurança da Informação e Desenvolvimento Seguro. O objetivo foi criar um assistente capaz de analisar trechos de código em busca de vulnerabilidades comuns (como SQL Injection e XSS) e sugerir correções, comparando a eficácia da IA com a de um analista júnior.

## 🤖 Tecnologias Utilizadas
Baseado no *Base10 Trend Map*, utilizei as seguintes ferramentas:

* **ChatGPT (OpenAI):** Para análise lógica do código e geração das explicações de vulnerabilidade (Categoria: Text & Writing).
* **GitHub Copilot:** Para sugestão de refatoração de código seguro em tempo real (Categoria: Code generation).
* **Git:** Para versionamento.

## 🧐 Processo de Criação
O projeto foi desenvolvido seguindo o fluxo "Human-in-the-loop":

1.  **Seleção de Amostra:** Separei 5 trechos de código Python intencionalmente vulneráveis.
2.  **Prompt Engineering:** Criei prompts específicos para o ChatGPT atuar como um "Senior Security Engineer", pedindo não apenas a correção, mas a explicação do risco (CWE).
3.  **Refatoração:** Utilizei o Copilot para reescrever o código baseando-se nas críticas geradas na etapa anterior.
4.  **Validação Humana:** Revisei as saídas para garantir que não houvesse "alucinações" (falsos positivos).

## 🚀 Resultados
O resultado foi surpreendentemente "Natty" (Natural).
* A IA conseguiu identificar 100% das vulnerabilidades óbvias.
* As explicações geradas foram didáticas e indistinguíveis de um feedback humano técnico.
* **Conclusão:** A ferramenta atua como um excelente "segundo par de olhos", acelerando o Code Review em até 70%.

## 💭 Reflexão (Opcional)
O desafio de criar algo "Natty" com IA na área técnica reside na precisão. Diferente da arte, onde o erro pode ser estilo, no código o erro é um bug. A IA provou ser uma ferramenta poderosa de *aumento* da capacidade humana, e não apenas de substituição. O toque humano final (curadoria) ainda é essencial para garantir a segurança total.

---

### 🔗 Links Úteis
- [Base10 Trend Map: Generative AI](https://base10.vc/post/generative-ai-mission-critical/)
- [Laboratório DIO](https://web.dio.me/lab/natural-ou-fake-natty-como-vencer-na-era-das-ias-generativas)
