Suporte TopPortaria com IA

**Descrição:**

Este repositório contém um script Python que utiliza um modelo de inteligência artificial (IA) para fornecer suporte técnico para o produto TopPortaria da empresa Topdata. O script utiliza o manual do produto em formato PDF para extrair informações e responder às perguntas dos usuários de forma clara e concisa.

**Funcionalidades:**
* Extrai informações do manual do produto TopPortaria em formato PDF.
* Responde às perguntas dos usuários de forma amigável e informativa.
* Detecta e corrige termos incorretos relacionados ao produto.
* Informa quando a pergunta não está relacionada ao TopPortaria e pede para reformular.
* Utiliza um modelo de IA poderoso para gerar respostas precisas e relevantes.

**Requisitos:**
* Conta no GitHub
* Chave de API do Google Cloud Platform (GCP)
* Bibliotecas Python:
* requests
* PyPDF2
* google-generativeai

**Como usar:**
* Clone o repositório para o seu computador.

**Instale as bibliotecas necessárias:**
* pip install -q -U requests PyPDF2 google-generativeai
* Substitua a chave de API do GCP no código (linha 10).

**Exemplo de uso:**

Suporte TopPortaria: Olá! Estou aqui para te auxiliar com qualquer dúvida que você tenha sobre o TopPortaria. Pode perguntar!
O que é o TopPortaria?

Resposta: 
 O TopPortaria é um software desenvolvido pela Topdata para controle de acesso em condomínios  e portarias. Possui uma interface moderna e recursos realmente úteis para controlar a portaria do seu condomínio, como:

* **Controle de acesso de pessoas e visitantes:** Cadastre moradores, visitantes, funcionários e defina as permissões de acesso de cada um.
* **Integração com catracas e coletores:** Controle o acesso através de catracas e coletores Topdata.
* **Monitoramento em tempo real:** Acompanhe os eventos de acesso em tempo real, com informações sobre quem entrou, saiu ou teve o acesso bloqueado.
* **Limite de pessoas por local:** Permite configurar um limite máximo de pessoas em cada área do condomínio, ajudando a evitar aglomerações.
* **Relatórios completos:** Gere relatórios de horários, pessoas, acessos, presenças e visitas.
* **Cadastro de digitais:** Cadastre as digitais dos moradores e visitantes para um controle de acesso ainda mais seguro.
* **Backup e restauração:** Faça backup dos dados do sistema e restaure-os quando necessário.

O TopPortaria é uma solução completa para o controle de acesso do seu condomínio, proporcionando segurança, organização e praticidade! 😊 
 
Suporte RopPortaria: Teria outra pergunta? Estou aqui para ajudar! Para finalizar digite fim 
Como faço para cadastrar uma pessoa no sistema?

Resposta: 
 Para cadastrar uma pessoa no TopPortaria, siga estes passos:

1. **Acesse o menu "Cadastros" e clique em "Pessoas".**
2. **Clique no botão "Incluir".**
3. **Preencha os campos da aba "Dados pessoais":**
    * **Nome:** Nome completo da pessoa.
    * **Exibição:** Nome que aparecerá na catraca (pode ser abreviado).
    * **Cartão:** Selecione o número do cartão que será associado à pessoa.
    * **Perfil de Acesso:** Selecione o perfil de acesso que define as permissões da pessoa.
    * **CPF:** Digite o CPF da pessoa (obrigatório se a opção estiver habilitada em "Registro > Configurações").
    * **RG:** Digite o RG da pessoa.
    * **Telefone:** Digite o telefone da pessoa com DDD.
    * **Deseja Controlar Validade:** Marque esta opção se deseja definir um prazo de validade para o acesso da pessoa.
    * **Observação:** Campo para adicionar informações adicionais sobre a pessoa.
    * **Foto:** Clique em "Arquivo" para adicionar uma foto salva no computador ou em "Webcam" para tirar uma foto com a webcam.
4. **Clique em "Salvar" para finalizar o cadastro.**

**Dicas:**

* Você pode cadastrar um novo cartão diretamente na tela de cadastro de pessoas. Para isso, digite o número do cartão no campo "Cartão" e pressione "Enter".
* Para garantir um controle de acesso eficiente, configure corretamente os perfis de acesso e associe-os às pessoas cadastradas.

Com este passo a passo, você poderá cadastrar os moradores, funcionários e outras pessoas que precisam ter acesso ao seu condomínio de forma rápida e fácil! 😉 
 
Suporte RopPortaria: Teria outra pergunta? Estou aqui para ajudar! Para finalizar digite fim 
fim

**Observações:**
* Este script ainda está em desenvolvimento e pode ser aprimorado com novas funcionalidades.
* É importante testar o script com diferentes tipos de perguntas para garantir que ele esteja funcionando corretamente.
* O script pode ser adaptado para outros produtos e manuais.

**Contribuições:**
* Se você tiver sugestões ou melhorias para o script, sinta-se à vontade para contribuir no repositório.

**Licença:**
* Este repositório está licenciado sob a licença MIT.

**Agradecimentos:**
* Google Cloud Platform
* Equipe do Google AI
* Alura
