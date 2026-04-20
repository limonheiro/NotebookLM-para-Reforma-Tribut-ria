# 📚 Miniguia de Estudos: Reforma Tributária e o funcionamento da Contingência.

Este repositório contém um Caderno Temático criado com o apoio da Inteligência Artificial (NotebookLM), como parte do Desafio de Projeto da DIO. O objetivo é demonstrar o uso da IA como ferramenta de aprendizagem ativa, curadoria de conhecimento e engenharia de prompts.

---

## 🎯 1. Contexto e Objetivos

**Tema Escolhido:** Reforma Tributária e o funcionamento da Contingência.

**Objetivos de Estudo:**
* Entender o que mudou com a Reformma Tributária
* Quando utilizar a Contingência forçada
* E ter uma base de conhecimento para consulta sobre o fiscal

---

## 🗂️ 2. Curadoria de Fontes

Para alimentar o NotebookLM e garantir que a IA utilizasse informações confiáveis e técnicas, os seguintes materiais foram selecionados e carregados na ferramenta:

1. **Anexo II – Manual de Especificações Técnicas do DANFE e Código de Barras** - *Este manual técnico estabelece as diretrizes rigorosas para a emissão e impressão do **DANFE**,  uma extensão essencial do Manual de Orientação do Contribuinte no Brasil. O texto detalha a estrutura visual obrigatória do documento, definindo desde o **padrão de código de barras CODE-128C** até as dimensões precisas de campos sobre emitentes, produtos e transportadores. Além de organizar o layout para diferentes formatos de papel e modos de impressão, o guia foca na **padronização da chave de acesso** e nas regras para situações de **contingência**, garantindo que o documento mantenha sua legibilidade e validade jurídica durante o trânsito de mercadorias. O objetivo central é assegurar a **uniformidade fiscal** e facilitar a fiscalização, permitindo que os dados digitais da NF-e sejam fielmente representados e facilmente consultados pelas autoridades* - [[MOC 7.0 - Anexo III – Manual de Especificações Técnicas do DANFE e Código de Barras](https://www.confaz.fazenda.gov.br/legislacao/arquivo-manuais/moc7-anexo-ii-manual-especificacoes-tecnicas-danfe-codigo-barras.pdf]]
2. **Anexo III - Manual de Contingência - Estabelece as diretrizes técnicas e operacionais para a emissão da **Nota Fiscal Eletrônica (NF-e)** em situações de falha técnica ou indisponibilidade dos sistemas autorizadores. O documento detalha as diferentes **modalidades de contingência**, como o formulário de segurança (**FS-DA**), o evento prévio (**EPEC**) e a utilização da **Sefaz Virtual de Contingência (SVC)**, que permite a autorização por servidores alternativos quando a infraestrutura estadual de origem falha. O objetivo central é garantir a **continuidade das operações comerciais** e a legalidade do trânsito de mercadorias, definindo procedimentos específicos para a geração de arquivos XML e a posterior **transmissão das notas** pendentes.* - [[https://www.confaz.fazenda.gov.br/legislacao/arquivo-manuais/moc7-anexo-iii-manual-contingencia-nf-e.pdf]]
3. **Manual de Orientação ao Contribuinte - MOC - versão 7.0 - *Este documento constitui a **Visão Geral** do **Manual de Orientação ao Contribuinte (MOC)**, versão 7.00, que estabelece as diretrizes técnicas para a implementação da **Nota Fiscal Eletrônica (NF-e)** e da **Nota Fiscal de Consumidor Eletrônica (NFC-e)** no Brasil. O texto detalha o **modelo operacional**, os padrões de **comunicação via Web Services** e a arquitetura de **mensageria XML**, garantindo que as empresas sigam protocolos rigorosos de **assinatura digital** e validação. Entre os temas centrais, destacam-se a gestão de **eventos fiscais** — como cancelamentos, cartas de correção e manifestação do destinatário — e os procedimentos de **contingência** para assegurar a continuidade da emissão em caso de falhas técnicas.* - [[https://www.confaz.fazenda.gov.br/legislacao/arquivo-manuais/moc7-visao-geral.pdf]]
4. DANFE: o que é, para que serve e qual sua importância - É um guia educativo que define o DANFE como uma representação simplificada e impressa da Nota Fiscal Eletrônica, essencial para o acompanhamento físico de mercadorias. A estrutura do artigo diferencia claramente o documento auxiliar do arquivo digital oficial, ressaltando que, embora o DANFE facilite a fiscalização e conferência, ele não possui a validade jurídica intrínseca da NF-e. Os temas centrais abordam a obrigatoriedade legal de sua emissão para o transporte e a utilidade da chave de acesso para consultas tributárias. Por fim, o conteúdo promove a automação de processos por meio de sistemas de gestão, visando reduzir erros manuais e garantir a conformidade administrativa das empresas. - [[https://www.omie.com.br/blog/o-que-e-danfe-e-qual-sua-importancia/]]
5. Legislação da nota fiscal 2025: entenda o que mudou e o que fazer - O texto detalha a transição para a Legislação da nota fiscal 2025, destacando a inserção de novos tributos como IBS, CBS e IS nos documentos eletrônicos para alinhar o país à Reforma Tributária. A estrutura da fonte abrange desde as mudanças técnicas nos leiautes e validações automáticas até os riscos severos para empresas que ignorarem os novos prazos, incluindo multas e rejeição de notas. O propósito central é orientar empreendedores sobre a importância da atualização tecnológica e capacitação de equipes para manter a conformidade fiscal. Por fim, o conteúdo posiciona o sistema Omie como uma solução estratégica para automatizar e simplificar esse processo de adequação obrigatória. - [[https://www.omie.com.br/blog/legislacao-da-nota-fiscal-2025-entenda-o-que-mudou-e-o-que-fazer/]]

---

## 🛠️ 3. Engenharia de Prompts e "Cicatrizes"

Nesta seção, documento o processo de iteração com a IA, mostrando como os prompts foram ajustados para obter respostas mais precisas.

### Teste 1: Explicando sobre a nova Reforma Tributária
* **Prompt Original:** *"Quais são as novas regras da reforma tributária?"*
* **Resposta Obtida (Resumo):** A IA deu uma resposta muito genérica 
* **Troubleshooting (A "Cicatriz"):** Percebi que precisava ser mais específico e detalhar o que realmente queria.
* **Prompt Refinado:** *Quais serão as mudanças fiscais em comparação com o que se tinha com a nova reforma tributária?*
* **Resultado:** A resposta foi exatamente o que eu precisava.


---

## 📖 4. Miniguia de Estudo (Entrega Final)

### Resumo Estruturado
*Quais serão as mudanças fiscais em comparação com o que se tinha com a nova reforma tributária?*

A principal mudança fiscal com a nova Reforma Tributária é a substituição de diversos tributos antigos por um novo modelo unificado de cobrança sobre o consumo. Em comparação com o que se tinha, as mudanças são:

- **Substituição do ICMS e do ISS:** Estes impostos (estadual e municipal, respectivamente) deixarão de existir e serão substituídos pelo **IBS (Imposto sobre Bens e Serviços)**.
- **Substituição do PIS e da Cofins:** Estas contribuições federais serão substituídas pela **CBS (Contribuição sobre Bens e Serviços)**.
- **Criação do IS (Imposto Seletivo):** Passará a ser cobrado um novo tributo voltado especificamente para produtos que causam impactos negativos à saúde ou ao meio ambiente.

Para acomodar essas mudanças, a legislação e a estrutura das notas fiscais (NF-e e NFC-e) passarão por atualizações importantes em 2025, o que inclui:

- Inclusão obrigatória de novos campos nos leiautes das notas para informar o IBS, a CBS e o IS.
- Validações automáticas mais rigorosas pelos sistemas do Fisco, resultando na rejeição imediata da nota se houver inconsistências nesses novos campos.
- Implementação de um QR Code "enriquecido" para permitir maior rastreabilidade das operações.
- Padronização nacional obrigatória para a Nota Fiscal de Serviços eletrônica (NFS-e), com previsão para 2026, visando maior uniformidade.
- Uma versão simplificada do Documento Auxiliar da Nota Fiscal Eletrônica (DANFE) para operações presenciais com CNPJ.

### Glossário

**NF-e (Nota Fiscal Eletrônica)**: É o documento digital oficial usado para registrar a venda de produtos, geralmente entre empresas

**NFC-e (Nota Fiscal de Consumidor Eletrônica)**: É a nota fiscal digital usada no varejo para vendas diretas ao consumidor final (como supermercados e farmácias)

**XML**: É o arquivo digital real gerado pelo sistema. Esse arquivo é a verdadeira nota fiscal e é o que tem validade jurídica perante a lei

**DANFE (Documento Auxiliar da Nota Fiscal Eletrônica)**: É o papel impresso que acompanha a mercadoria. Ele é apenas um resumo visual para facilitar o transporte e não substitui o arquivo XML

**Contingência**: É o "plano B" usado para conseguir emitir notas fiscais quando você está sem internet ou o sistema do governo cai

**QR Code:** Aquele código em formato retangular impresso no DANFE que você ou o seu cliente podem escanear com a câmera do celular para conferir se a nota é válida

### Prompts Reutilizáveis
Abaixo estão os prompts mais eficientes que criei durante este estudo e que podem ser reutilizados para revisões futuras sobre este ou outros temas:

> 1. *"Pedir para o notebookLM criar um inforgrafico sobre "Guia da NFC-e e Transição 2025"* - ![Infografico](https://raw.githubusercontent.com/limonheiro/NotebookLM-para-Reforma-Tribut-ria/refs/heads/main/inforgrafico.png)



> 2. *"Pedi para criar um video de resumo sobre a contingência"* - 


https://github.com/user-attachments/assets/04881cb7-1927-44ab-8d51-938ca62947d1




> 3. *Crie uma manual de conceitos iniciais sobre a DANFE e suas principais regras fiscais e de estrutura.* - arquivo

---
*Projeto desenvolvido para o bootcamp da [DIO](https://www.dio.me/).*
[NotebookLM](https://notebooklm.google.com/notebook/41ab8938-0d38-4489-b5df-cde7eb1d3942)
