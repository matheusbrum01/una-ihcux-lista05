## 🧠 Resumo das Heurísticas de Nielsen Aplicadas

Este projeto aplica três importantes heurísticas de usabilidade propostas por Jakob Nielsen, com o objetivo de melhorar a experiência do usuário mesmo em uma aplicação de console.

---

### 📢 1. Visibilidade do Status do Sistema

O sistema mantém o usuário sempre informado sobre o que está acontecendo.

🔹 Como foi aplicado:

* Exibição de mensagens como “Verificando CPU...” e “Processando...”
* Atualização em tempo real usando `\r`
* Simulação de progresso com `Thread.Sleep`
* Mensagem final indicando conclusão

✅ Resultado: o usuário entende claramente o andamento do sistema e não fica perdido.

---

### ⚠️ 2. Prevenção de Erros

O sistema evita falhas ou lida com erros de forma controlada.

🔹 Como foi aplicado:

* Uso de `try-catch` para tratar exceções
* Validação de entradas do usuário
* Mensagens de erro claras e amigáveis

✅ Resultado: o sistema não quebra e orienta o usuário corretamente quando algo dá errado.

---

### 🎨 3. Estética e Design Minimalista

A interface deve ser simples, organizada e sem informações desnecessárias.

🔹 Como foi aplicado:

* Uso de cores para destacar informações importantes
* Layout limpo no console
* Separadores visuais (`---`)
* Mensagens diretas e objetivas

✅ Resultado: interface mais agradável, fácil de entender e sem poluição visual.

---

## 📚 Conclusão

A aplicação dessas heurísticas torna o sistema mais:

* ✔️ Intuitivo
* ✔️ Seguro
* ✔️ Agradável de usar

Mesmo sendo uma aplicação simples de terminal, é possível aplicar conceitos de UX que fazem grande diferença na experiência do usuário.

---

## 👨‍💻 Autor

Desenvolvido por **Matheus Brum**
