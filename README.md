# Explorar a Fala no Azure AI Foundry

## Descrição do Projeto
Este projeto explora o uso do **Azure AI Speech** no **Azure AI Foundry**, a plataforma da Microsoft para criar aplicativos inteligentes. O serviço de Fala de IA do Azure permite:
- **Transcrever fala em texto**: Ideal para anotações de reuniões ou transcrição de entrevistas.
- **Converter texto em fala audível**: Útil para gerar áudio a partir de conteúdos escritos.

Neste exercício, você usará o Azure AI Speech para transcrever áudio utilizando as experiências de teste internas do Azure AI Foundry.

---

## Funcionalidades
- **Conversão de Fala em Texto**: Transcrição em tempo real de áudio para texto.
- **Conversão de Texto em Fala**: Geração de áudio a partir de texto digitado.
- **Organização de Projetos**: Utilização de projetos como contêineres para organizar o trabalho eficientemente.

---

## Como Iniciar o Projeto

### 1. Acessar o Azure AI Foundry
- Abra uma guia do navegador e acesse o [Azure AI Foundry](https://portal.vision.cognitive.azure.com).
- Faça login com sua conta Microsoft.

### 2. Criar um Projeto no Azure AI Foundry
1. Na home page, clique em **Criar um projeto**. 
2. No painel **Criar um projeto**:
   - Um nome de projeto gerado automaticamente será exibido (você pode mantê-lo como está).
   - Se você já tiver um hub existente, ele aparecerá em um menu suspenso. Caso contrário:
     - Selecione **Criar novo hub**.
     - Crie um nome exclusivo para o seu hub.
     - Clique em **Avançar**.

3. Em **Personalizar**, escolha um dos locais compatíveis:  
   - Leste dos EUA  
   - França Central  
   - Coreia Central  
   - Europa Ocidental  
   - Oeste dos EUA  
4. Clique em **Criar**.

### 3. Recursos Criados
Ao concluir o projeto, os seguintes recursos serão provisionados:  
- **Serviços de IA do Azure**  
- **Hub de IA do Azure**  
- **Projeto de IA do Azure**  
- **Conta de Armazenamento**  
- **Cofre de Chaves**  
- **Grupo de Recursos**  

---

## Testando a Conversão de Fala em Texto
1. Após a criação do projeto, vá para a página **Visão geral**.
2. No menu à esquerda, clique em **Serviços de IA**.
3. Selecione o bloco **Fala**.
4. Role para baixo e escolha **Conversão de fala em texto em tempo real**.
   - Isso abrirá o **Speech Playground**.
5. Faça o download do arquivo de áudio: [speech.zip](https://aka.ms/mslearn-speech-files).  
6. Extraia o arquivo **WhatAICanDo.m4a** do zip.
7. No **Speech Playground**, clique em **Procurar arquivos** e carregue o arquivo de áudio.
8. O serviço de Fala transcreverá o áudio para texto em tempo real.

---

## Revisão e Resultados
- O texto transcrito será exibido enquanto o áudio é reproduzido.
- Revise a transcrição para verificar a precisão.
