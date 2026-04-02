# 🚀 Guia de Carreira: Como e Quando Usar os Modos do Copiloto

Este guia define a estratégia de uso dos modos de IA (**Ask, Study, Plan, Agent**) baseada no seu momento de carreira e objetivo técnico. O uso correto da IA não é apenas sobre produtividade, mas sobre **gestão de conhecimento e evolução profissional**.

---

## 🧭 Visão Geral da Estratégia

| Perfil | Foco Principal | Objetivo na Carreira |
| :--- | :--- | :--- |
| **Júnior / Estudante** | `Study` & `Ask` | Construir fundamentos sólidos e aprender a diagnosticar problemas. |
| **Pleno / Mid-Level** | `Ask` & `Plan` | Refinar padrões arquiteturais e otimizar soluções existentes. |
| **Sênior / Tech Lead** | `Plan` & `Agent` | Focar na estratégia de negócio e escalar a entrega técnica. |

---

## 📚 1. Modo STUDY: O Construtor de Base

**Foco:** Conhecimento Teórico e Novas Stacks (ex: PHP 8.5 / Laravel 13).

* **Para o Júnior:** É o modo essencial. Ele impede que você se torne um "programador de colagem". Use para entender *por que* o Laravel usa Service Containers ou como o Strict Typing do PHP 8.5 protege seu código.
* **Para o Sênior:** Use ao migrar para uma stack completamente nova ou ao explorar paradigmas diferentes (ex: saindo de MVC para Event Sourcing).
* **⚠️ Risco:** Não use em momentos de "incêndio" ou prazos críticos. O aprendizado requer tempo para reflexão.

## ❓ 2. Modo ASK: O Mentor de Diagnóstico

**Foco:** Entendimento de Código e Debugging.

* **Uso Ideal:** Explicar logs de erro complexos, entender código legado de terceiros ou validar se uma lógica faz sentido antes de codar.
* **Evolução:** Treina sua **análise crítica**. Ao ler a explicação da IA em vez de ver o código pronto, você desenvolve a habilidade de "ler código" mentalmente — uma das marcas registradas de um desenvolvedor experiente.

## 🧭 3. Modo PLAN: O Arquiteto de Sistemas

**Foco:** Design de Software e Estratégia.

* **Uso Ideal:** Antes de tocar no teclado para qualquer feature que envolva mais de 3 arquivos.
* **Diferencial de Carreira:** Este modo separa o "codificador" do "engenheiro". Ele força você a pensar em **escalabilidade, acoplamento e contratos de interface** (Input/Output) antes da implementação.
* **Dica:** Use o `Plan` para criar rascunhos de propostas técnicas para seu time. É uma forma rápida de validar ideias com a IA antes de levá-las para a reunião de arquitetura.

## 🤖 4. Modo AGENT: O Multiplicador de Entrega

**Foco:** Automação e Produtividade (Boilerplate).

* **Para o Sênior:** É o seu "estagiário de elite". Use para gerar Migrations, Models, Testes Unitários e DTOs — tarefas que você já domina, mas que consomem tempo precioso.
* **Para o Júnior (Cuidado!):** Evite o uso excessivo. Delegar a execução sem entender o "como" cria uma lacuna de conhecimento que aparecerá em entrevistas técnicas ou em bugs complexos. Use apenas após validar o plano no modo `Plan`.

---

## 🧠 Mentalidade de Crescimento com IA

1. **A Regra dos 80/20:** Use a IA para 80% do trabalho repetitivo (`Agent`), mas dedique 20% do seu tempo para desafiar a IA no modo `Study`.
2. **Validação Inversa:** Periodicamente, peça para o modo `Ask` criticar um código que *você* escreveu. Isso ajuda a identificar vícios de programação e pontos cego de segurança.
3. **Antecipação de Versões:** Em stacks de vanguarda (PHP 8.5/Laravel 13), use o `Ask` para comparar o código sugerido com a documentação estável. Isso desenvolve seu faro para **alucinações de IA** e mudanças reais de breaking changes.

---

> *"A IA não vai substituir o desenvolvedor, mas o desenvolvedor que sabe usar o modo Plan e Study vai substituir aquele que só sabe usar o Agent."*
