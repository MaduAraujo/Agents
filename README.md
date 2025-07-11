# Assistente de Meta (Meta Assistant)

Um assistente interativo e inteligente que utiliza API do Google Gemini para fornecer estratégias, builds otimizadas e dicas valiosas para aprimorar sua jogabilidade. Desenvolvido com foco na experiência do usuário, este projeto permite que você obtenha insights atualizados e relevantes para seus jogos favoritos.

## 📋 Sumário

* [✅ Projeto Funcionando](#-projeto-funcionando)
* [🚀 Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [⚙️ Configuração e Instalação](#%EF%B8%8F-configura%C3%A7%C3%A3o-e-instala%C3%A7%C3%A3o)
* [🎮 Como Usar](#-como-usar)

## ✅ Projeto Funcionando

https://github.com/user-attachments/assets/646e5f59-fda8-43e3-88e1-af56e954d890

## 🚀 Tecnologias Utilizadas

* **HTML5:** Para a estruturação semântica e acessível da página web.
* **CSS3:** Responsável pela estilização visual do aplicativo, garantindo uma interface moderna e responsiva.
* **Google Fonts:** Utilizada para uma tipografia limpa e legível.
* **JavaScript:** A linguagem principal para toda a lógica interativa do frontend, manipulação do DOM e comunicação com a API.
* **Google Gemini API:** O serviço de inteligência artificial que alimenta as respostas do assistente.
* **Showdown.js:** Uma biblioteca JavaScript para converter texto Markdown em HTML, essencial para exibir as respostas da IA de forma formatada.

## ⚙️ Configuração e Instalação

Para configurar e rodar este projeto em seu ambiente de desenvolvimento local, siga os passos abaixo:

1.  **Clone o Repositório:**
    Abra seu terminal ou prompt de comando e execute:
    
    ```bash
    git clone https://github.com/MaduAraujo/Agents.git
    cd Agents
    ```
    
3.  **Obtenha sua API Key do Google Gemini:**
    * Para interagir com o modelo Gemini, você precisará de uma chave de API.
    * Visite o [Google AI Studio](https://aistudio.google.com/app/apikey) ou o [Google Cloud Console](https://console.cloud.google.com/apis/credentials) para gerar sua chave.
    * **Importante:** Por questões de segurança, **NUNCA** incorpore sua API Key diretamente no código-fonte de um repositório público. Este projeto solicita a chave através de um campo de input na interface para uso local e demonstração.

4.  **Execute a Aplicação:**
    Após clonar o repositório e obter sua API Key, basta abrir o arquivo `index.html` diretamente em seu navegador web preferido. Não é necessário um servidor web para esta aplicação simples.


### 🎮 Como Usar

1.  **Abra a Aplicação:** Navegue até o arquivo `index.html` em seu navegador web.
2.  **Insira sua API Key:** No campo "Informe a sua API KEY do Gemini", cole a chave de API que você obteve do Google AI Studio.
3.  **Selecione o Jogo:** Escolha um jogo na lista suspensa "Selecione um jogo". Os jogos pré-configurados são "Candy Crush Saga", "Hay Day" e "Perguntados".
4.  **Faça sua Pergunta:** No campo de texto "Ex: Melhor build para...", digite sua dúvida ou solicitação relacionada ao jogo selecionado.
5.  **Obtenha a Resposta:** Clique no botão "Perguntar". O botão mudará para "Perguntando..." enquanto a IA processa sua solicitação. A resposta será exibida na área abaixo do formulário.
6.  **Copie a Resposta:** Ao final da resposta, clique no botão "Copiar" para copiar o conteúdo do campo de texto diretamente para a sua área de transferência.
