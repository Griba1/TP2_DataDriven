# TP2_DataDriven

Instalação de Dependências
Certifique-se de ter o Python 3.9 ou superior instalado. Execute o seguinte comando para instalar as dependências necessárias:
!pip install fastapi uvicorn langchain openai huggingface-hub transformers



Descrição das Dependências
FastAPI: Framework para construção de APIs rápidas e eficientes.
Uvicorn: Servidor ASGI para executar a aplicação FastAPI.
LangChain: Biblioteca para integração com modelos de linguagem (LLMs).
OpenAI: Permite chamadas à API da OpenAI.
HuggingFace Hub: Gerencia o acesso aos modelos da HuggingFace.
Transformers: Biblioteca para manipulação de modelos pré-treinados da HuggingFace.


Executando o Projeto
Inicie o servidor FastAPI utilizando o Uvicorn:
uvicorn <ARQUIVO_QUE_vAMOS_UTILIZAR>:app --reload

Acesse a documentação interativa da API em: http://127.0.0.1:8000/docs


Exemplos de Uso
Endpoint de Tradução
{
  "text": "Hello, how are you?"
}
