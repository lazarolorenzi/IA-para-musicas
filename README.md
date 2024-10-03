# 🚀 Integração com Modelos de IA para Processamento de Texto, Imagem, Áudio, Vídeo e Documentos

Este projeto visa integrar múltiplos **Modelos de Inteligência Artificial** para processar texto, imagem, áudio, vídeo e documentos de forma eficaz e acessível. Utilizamos a interface de código aberto **OpenWebUI** para facilitar a interação com esses modelos diretamente do navegador, permitindo uma experiência fluida e simplificada para o usuário.

## 🌟 Funcionalidades Principais

### 📝 Processamento de Texto
Utilizamos os modelos **MiniCPM-V** e **ALIENTELLIGENCE** para análise e geração de texto. Estes modelos são ideais para criar respostas contextuais, resumo de textos e outras tarefas baseadas em linguagem natural.

### 🖼️ Processamento de Imagens
O **MiniCPM-V** também é capaz de processar e gerar imagens a partir de descrições textuais, sendo perfeito para tarefas criativas ou visuais automatizadas.

### 🎙️ Processamento de Áudio
O modelo **ALIENTELLIGENCE** lida com o processamento de áudio, incluindo transcrição e análise de fala, fornecendo uma solução robusta para aplicações que requerem interpretação de áudio.

### 🎥 Processamento de Vídeo
Além disso, o **MiniCPM-V** oferece suporte ao processamento de vídeos, extraindo informações relevantes, como objetos, cenas e texto dentro do conteúdo visual, automatizando análises e outputs.

### 📄 Leitura de Documentos
Utilizamos o **MiniCPM-V** para leitura e compreensão de documentos. Esta funcionalidade permite extrair informações de documentos em diversos formatos, como PDFs e arquivos de texto, facilitando a análise e processamento automatizado de dados contidos em documentos.

---

## 🏛️ Arquitetura do Projeto

### 💻 Interface Web (OpenWebUI)
A interface **OpenWebUI** proporciona uma maneira intuitiva de interagir com os modelos de IA diretamente através do navegador, facilitando o acesso tanto para desenvolvedores quanto para usuários finais.

### 🧠 Modelos de IA
- **Ollama**: Gerencia a execução dos modelos de IA localmente, permitindo uma execução eficiente sem dependências externas.
- **MiniCPM-V**: Um modelo poderoso para o processamento multimodal de texto, imagem, vídeo e documentos.
- **ALIENTELLIGENCE**: Especializado no processamento e transcrição de áudio, além de fornecer suporte para tarefas textuais.

---

## 🔧 Fluxo de Processo

1. **Entrada**: Através da interface web, o usuário pode fornecer entradas de texto, imagens, áudio, vídeo ou documentos.
2. **Processamento**: Os modelos de IA (**MiniCPM-V** e **ALIENTELLIGENCE**) processam essas entradas, gerando saídas relevantes.
3. **Saída**: Os resultados são exibidos diretamente na interface OpenWebUI, permitindo ao usuário visualizar, modificar ou salvar os outputs gerados.

---

## 🎶 Personalização Criativa

Neste projeto, fizemos adaptações personalizadas dos modelos de IA com foco no **mundo da música**. Exploramos o potencial dos modelos para transcrição de letras, identificação de instrumentos e, personalizamos um dos modelos com foco em **música brasileira**, na tentativa de capturar as diferenças culturais e rítmicas do estilo musical brasileiro.

### 🥁 Foco em Música Brasileira
Personalizamos um dos nossos modelos com foco especial na **música brasileira**, incluindo gêneros como **samba, bossa nova, forró, MPB, sertanejo** e outros. Agora, o modelo não só reconhece instrumentos característicos desses estilos, como também captura as diferenças culturais e melódicas presentes em suas composições.

### 🎧 Criatividade Musical com Alma Brasileira
Esse modelo foi desenhado com o objetivo de **despertar a criatividade musical**. Com uma **personalidade alegre e amigável**, a IA compartilha seu vasto conhecimento sobre os gêneros brasileiros, artistas icônicos e eventos históricos que moldaram a cultura musical do país. Seja para inspirar novas composições ou para revisitar clássicos, o modelo é capaz de sugerir **letras de música, insights sobre harmonias** e até narrativas sobre o impacto da música brasileira ao longo do tempo.


## 📘 Como Funciona o OpenWebUI

### Visão Geral

O **OpenWebUI** é uma interface web de código aberto projetada para facilitar a interação entre usuários e modelos de inteligência artificial. Ele atua como uma ponte entre o usuário final e os modelos de IA, proporcionando uma experiência intuitiva e amigável diretamente no navegador.

### Principais Características

- **Interface Intuitiva**: Layout organizado que permite ao usuário inserir prompts e receber respostas de forma simples.
- **Suporte Multimodal**: Capacidade de lidar com diferentes tipos de mídia, incluindo texto, imagem, áudio, vídeo e documentos.
- **Customização**: Opções para ajustar parâmetros e personalizar a interação com os modelos de IA conforme as necessidades do usuário.

### Funcionamento Interno

1. **Entrada do Usuário**: O usuário fornece uma entrada (prompt) na interface web. Isso pode ser texto, imagem, áudio, vídeo ou documento.
2. **Processamento da Solicitação**: O OpenWebUI encaminha a entrada para o modelo de IA apropriado, como o **MiniCPM-V** ou o **ALIENTELLIGENCE**, dependendo do tipo de mídia.
3. **Geração de Resposta**: O modelo de IA processa a entrada e gera uma resposta ou resultado.
4. **Exibição do Resultado**: O OpenWebUI apresenta o resultado ao usuário na interface, permitindo visualização imediata e interação adicional.

### Benefícios do Uso

- **Acessibilidade**: Não requer conhecimento técnico avançado para operar os modelos de IA.
- **Eficiência**: Simplifica o processo de interação com modelos complexos, reduzindo o tempo e esforço necessários.
- **Flexibilidade**: Pode ser integrado com diversos modelos e ajustado para diferentes aplicações e setores.

### Integração com Ollama e MiniCPM-V

O **Ollama** gerencia a execução local dos modelos de IA, garantindo eficiência e segurança dos dados. Quando integrado com o OpenWebUI, permite que modelos como o **MiniCPM-V** sejam acessados e utilizados diretamente pelo navegador, sem a necessidade de serviços externos.

---

## 📚 Documentação

### Modelos Utilizados

- **OpenWebUI**
  - Documentação: [https://docs.openwebui.com/](https://docs.openwebui.com/)
- **MiniCPM-V**
  - Ollama Library: [https://ollama.com/library/minicpm-v](https://ollama.com/library/minicpm-v)
  - Repositório GitHub: [https://github.com/OpenBMB/MiniCPM-V](https://github.com/OpenBMB/MiniCPM-V)
- **ALIENTELLIGENCE**
  - Modelo AVENGINER: [https://ollama.com/ALIENTELLIGENCE/avengineer](https://ollama.com/ALIENTELLIGENCE/avengineer)

### Como Usar com Ollama

**Ollama** é um gerenciador de modelos de linguagem que permite executar modelos localmente de forma eficiente. Integrar o **MiniCPM-V** com o Ollama permite que você execute o modelo em sua máquina sem depender de serviços externos.

#### Passo a Passo para Configuração

1. **Instalar o Ollama**

   Primeiro, instale o Ollama em sua máquina:

   https://ollama.com/

2. **Abra o terminal**
```bash
#Modelo de audio
ollama run ALIENTELLIGENCE/avengineer
#Modelo de Imagem, Video, Texto, Documentos
ollama run minicpm-v
```
3. **Instalação do OpenWebUi via Docker**
```bash
#Abra o terminal e execute

docker run -d -p 3000:8080
--add-host=host.docker.internal:host-gateway -v
open-webui:/app/backend/data --name open-webui --restart
always ghcr.io/open-webui/open-webui:main
```
4. **Com o docker e o Ollama em execução abra no seu navegador na URL [http://localhost:3000/](http://localhost:3000/)**

5. **Personalização de modelos com OpenWebUi**

   **Para começar a personalização precisamos acessar a workspace da OpenWebUi [http://localhost:3000/workspace/models](http://localhost:3000/workspace/models)**

![image](https://github.com/user-attachments/assets/b577c526-bd78-4eb3-9d07-db59016455cd)



