Projeto de Automação - UiPath (Case Redesign Consultoria)
📋 Descrição
Este repositório contém duas automações desenvolvidas em UiPath como parte do case técnico para a empresa Redesign Consultoria.
O objetivo é automatizar o cadastro de oportunidades para o time de vendas, dividindo o processo em duas automações distintas.

Automação 1: Extração de dados do site Report: Opportunities e envio para uma fila no UiPath Orchestrator.

Automação 2: Leitura dos dados da fila e cadastro no Sistema Forms, apenas para oportunidades com origem USA e Germany.

Ao final da execução, é enviado um e-mail de confirmação informando a conclusão do processo.

🛠 Tecnologias Utilizadas
UiPath Studio

UiPath Orchestrator

UiPath Robot

GitHub (versionamento)

📂 Estrutura do Repositório

/Automacao1
  - Projeto de extração de dados e envio para a fila
/Automacao2
  - Projeto de leitura da fila e cadastro no sistema
README.md

🚀 Como Executar as Automações
Clonar este repositório:

git clone https://github.com/seu-usuario/seu-repo.git
Abrir os projetos no UiPath Studio:

Abra o Projeto 1 (Automacao1) para realizar a extração dos dados.

Abra o Projeto 2 (Automacao2) para realizar o cadastro no Sistema Forms.

Requisitos:

Conta no UiPath Orchestrator configurada.

Fila criada no Orchestrator para receber os dados.

Robô conectado ao Orchestrator.

Acesso ao site Report: Opportunities e ao Sistema Forms.

Configurações de e-mail para envio da confirmação.

Execução:

Rode primeiro a automação 1 para preencher a fila.

Depois rode a automação 2 para processar os dados e cadastrar no sistema.

✨ Observações
Os projetos foram desenvolvidos considerando boas práticas de RPA.

Os dados sensíveis (como credenciais de login) devem ser armazenados com segurança usando UiPath Assets ou Windows Credential Manager.

O tratamento de erros foi implementado para garantir maior robustez do processo.

👨‍💻 Desenvolvedor
Nome: João Victor Pires

LinkedIn: https://www.linkedin.com/in/jo%C3%A3o-victor-pires-nascimento-dos-santos-985b561b4/

GitHub: github.com/JoaoSortudo

