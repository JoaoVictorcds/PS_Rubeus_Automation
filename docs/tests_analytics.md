# Relatório de Testes e Análise de Interface

Este documento detalha as inconsistências, falhas críticas e sugestões de melhoria identificadas durante o mapeamento das aplicações.

---

##  1. Página de Certificação

###  Falhas Críticas (Alta Prioridade)
* **Bloqueio de Inscrição (Base Legal):** Exibição do alerta "É necessário informar a base legal" impedindo o avanço, mesmo com dados corretos.
* **Validação de Campos:** Aceitação de caracteres alfabéticos em campos de telefone e numéricos em nomes, sem alertas específicos de formato.
* **Links Quebrados/Inativos:** O botão "Saiba mais" no Header e nos cards de "Outros Cursos" não possui funcionalidade.
* **Redirecionamento Indevido:** O botão "Quero me certificar" do rodapé direciona para o Google, retirando o usuário do fluxo.
* **Conteúdo Incompleto:** Uso generalizado de "Lorem Ipsum", prejudicando a compreensão do produto pelo usuário.
* **Responsividade:** Sobreposição de elementos e desalinhamento de textos ao aplicar zoom de 250%.

###  Falhas Médias e Baixas
* **Redirecionamento de Redes Sociais:** Ícone do YouTube configurado para abrir o TikTok da empresa.
* **Sugestões de Melhoria:** Ausência de provas sociais (depoimentos) e falta de canal de suporte imediato via IA ou chat.

---

##  2. Página do Site

###  Falhas Críticas (Alta Prioridade)
* **Integridade de Dados (Newsletter):** Falta de máscara e validação nos campos de nome e telefone, permitindo cadastros inválidos, como na página de certificação.
* **Acessibilidade e Navegação (Eventos):** Fontes excessivamente pequenas na seção de eventos e todos os links apontando para a mesma URL.

###  Melhorias e Usabilidade
* **Validação de Tamanho:** Campo "Nome" permite envio com apenas 1 caractere.
* **Quebra de Layout:** O banner superior não responde corretamente ao zoom negativo, causando cortes na interface.
* **Poluição Visual:** Excesso de chamadas para redes sociais ao longo da página.
* **Qualidade de Ativos:** Pixelização de ícones em zoom negativo e erros de formatação (subtraços e distanciamentos indevidos) no Header.