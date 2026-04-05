🤖 Bot de Automação: Cadastro de Produtos
Este projeto automatiza o processo de login e cadastro de produtos em um sistema web. Utilizando a biblioteca PyAutoGUI, o bot simula movimentos de mouse e teclado para ler dados de uma planilha CSV e preenchê-los automaticamente no formulário da empresa.

🚀 Funcionalidades
Login Automatizado: Acessa o navegador, entra no link do sistema e realiza o login.

Processamento de Dados: Utiliza a biblioteca Pandas para ler uma base de dados externa (produtos.csv).

Loop de Cadastro: Percorre todas as linhas da tabela e preenche os campos:

Código do Produto

Marca

Tipo

Categoria

Preço Unitário

Custo

Observações (com verificação de campos vazios)

Interface Amigável: Inclui pausas estratégicas para garantir que o sistema web acompanhe o processamento do bot.

🛠️ Tecnologias Utilizadas
Python: Linguagem base do projeto.

PyAutoGUI: Para automação da interface gráfica (mouse e teclado).

Pandas: Para manipulação e análise da base de dados em CSV.

Time: Para controle de intervalos e sincronização.

📋 Pré-requisitos
Antes de executar o bot, você precisará instalar as dependências necessárias:

```bash
pip install pyautogui pandas
```

Nota: Certifique-se de que o arquivo produtos.csv esteja na mesma pasta que o script main.py.

⚙️ Como Usar
Ajuste de Coordenadas: Como o pyautogui utiliza pixels, as coordenadas (x, y) no script podem variar dependendo da resolução do seu monitor.

Execução: Rode o script através do terminal ou do seu editor (como o VS Code):


```bash
python main.py
```
Segurança: Caso precise interromper o bot rapidamente, mova o mouse para um dos quatro cantos da tela (recurso fail-safe do PyAutoGUI).
