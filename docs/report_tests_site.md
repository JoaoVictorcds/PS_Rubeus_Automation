# Relatório de Testes

**URL avaliada:** https://qualidade.apprbs.com.br/site  

---

## Itens Identificados


### ITEM 01 — Validação inadequada de dados na Newsletter

**Tipo:** Correção  
**Classificação:** Utilidade  
**Prioridade:** Alta  

**Descrição:**  
Na seção de assinatura da Newsletter:

- O campo **Telefone** aceita inserção de letras  
- O campo **Nome** aceita inserção de números  

Pode gerar inconsistência na base de dados e comprometer futuros cadastros.

---

### ITEM 03 — Redirecionamento incorreto e baixa legibilidade na seção Eventos

**Tipo:** Correção  
**Classificação:** Utilidade  
**Prioridade:** Alta  

**Descrição:**  

- A fonte descritiva dos eventos é pequena, prejudicando acessibilidade.  
- Todos os eventos redirecionam para o mesmo endereço, impedindo o acesso a conteúdos individuais.

---

### ITEM 04 — Ausência de limite mínimo de caracteres no campo "Nome"

**Tipo:** Correção  
**Classificação:** Utilidade  
**Prioridade:** Média  

**Descrição:**  
O formulário da Newsletter permite envio com apenas um caractere no campo **Nome** (ex: "A"), indicando ausência de validação de tamanho mínimo.

---

### ITEM 05 — Quebra de layout ao aplicar zoom negativo

**Tipo:** Melhoria  
**Classificação:** Usabilidade  
**Prioridade:** Média  

**Descrição:**  
Ao reduzir o zoom do navegador:

- O banner superior permanece fixo  
- Outros elementos são cortados ou desalinhados  


---

### ITEM 06 — Poluição visual nos blocos de redes sociais

**Tipo:** Melhoria  
**Classificação:** Usabilidade  
**Prioridade:** Baixa  

**Descrição:**  
Há excesso de chamadas para redes sociais ao longo da página.

---

### ITEM 08 — Pixelização de ícones e inconsistências visuais

**Tipo:** Melhoria  
**Classificação:** Desejabilidade  
**Prioridade:** Baixa  

**Descrição:**  

- Ícones de contato e redes sociais perdem qualidade ao aplicar zoom negativo  
- Subtraço indesejado na legenda "Conheça Nossos diferenciais"  
- Ícone do menu "Biblioteca" apresenta espaçamento excessivo em relação ao texto  


---

### ITEM 09 — Mensagem de erro genérica para campos inválidos

**Tipo:** Correção  
**Classificação:** Utilidade  
**Prioridade:** Média  

**Descrição:**  
Ao detectar dados inválidos, o sistema exibe apenas a mensagem:

> "Preencha este campo"

Sem indicar o formato correto esperado.  
O mesmo comportamento foi observado na página de Certificação.
