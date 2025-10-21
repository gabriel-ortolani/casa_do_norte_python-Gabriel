# Controle de Estoque de Comidas Nordestinas

Este é um sistema desenvolvido em Python utilizando a biblioteca Tkinter para interface gráfica. O sistema tem como objetivo a gestão de entradas, saídas e cadastro de comidas típicas da região nordestina do Brasil.

## Funcionalidades

- Login de usuários: permite que diferentes usuários acessem o sistema com autenticação.
- Cadastro, consulta, edição e exclusão de comidas típicas da culinária nordestina.
- Registro e histórico detalhado das movimentações no estoque (entradas e saídas).
- Alertas visuais para avisar quando o estoque de um alimento está abaixo do nível mínimo definido.

## Execução

1. Execute o arquivo `db_init.sql` para criar o banco de dados com suas tabelas e dados iniciais, ou deixe o sistema criar automaticamente no primeiro uso.
2. Execute o arquivo `main.py` para iniciar o sistema e acessar a interface gráfica.

## Estrutura de arquivos

- `main.py` : Arquivo principal que inicializa o sistema e gerencia as telas principais.
- `db.py` : Responsável pela conexão e inicialização do banco de dados SQLite.
- `login.py` : Tela e lógica de autenticação dos usuários.
- `comidas.py` : Cadastro, edição, exclusão e exibição das comidas típicas.
- `estoque.py` : Gestão das quantidades no estoque e registro das movimentações.
- `utils.py` : Funções auxiliares diversas, como centralização de janelas e ordenação.
- `db_init.sql` : Script SQL para criação do banco de dados com tabelas e dados iniciais.
- `README.md` : Este arquivo, com orientações e informações gerais sobre o sistema.

**Requisitos:** Python 3.12 ou superior, Tkinter e SQLite.

## Funcionamento
Ao iniciar você terá uma página de login<br>
<img width="506" height="299" alt="image" src="https://github.com/user-attachments/assets/d673b629-3af9-44f9-a117-e47ae2d45454" /><br>
Nesta página basta somente preencher os campos "usuario" e "senha" com as informações correspondentes.
Após isso você sera redirecionado para a página principal<br>
<img width="506" height="299" alt="image" src="https://github.com/user-attachments/assets/eb797e84-cfa4-464d-b9f8-fb97555585fe" /><br>
Neste local você pode gerenciar o estoque e cadastrar novas comidas pelos botões acima alem de deslogar<br>
<img width="506" height="299" alt="image" src="https://github.com/user-attachments/assets/5946a75a-08a8-409f-8e23-db35437b02ef" /><br>
Nessa página você pode verificar a quandidade presente dos alimentos no estoque e nos botões no canto inferior da página é possivel registrar movimentações e ver o historico e movimentações
Ao clicar no botão "Registrar movimentações" após selecionar um alimento abrira essa aba<br>
<img width="506" height="494" alt="image" src="https://github.com/user-attachments/assets/dd7ec297-8963-4786-9df4-a35b02ec8de8" /><br>
Basta preencher as informações e apertar em salvar e os movimentos serão registrados<br>
Ao clicar em um alimento e em "ver historico" abrira essa aba com o historico de movimentação do alimento correspondente
<img width="506" height="299" alt="image" src="https://github.com/user-attachments/assets/402a11c0-11a5-4ef3-a357-ff97978724df" /><br>
Voltando a página inicial ao clicar em "cadastro de comida" abrirá essa página
<img width="506" height="299" alt="image" src="https://github.com/user-attachments/assets/dd31e52f-abe6-45d3-98fc-244ffc9e16a7" /><br>
Nestá página você pode cadastrar novas comidas<br>
<img width="506" height="339" alt="image" src="https://github.com/user-attachments/assets/3417e01b-d40e-4ee5-979c-110a3d7a4fed" /><br>
editar as já cadastradas<br>
<img width="506" height="339" alt="image" src="https://github.com/user-attachments/assets/df20372e-0de5-46a1-b594-820da2808ac2" /><br>
e tambem excluir as cadastradas selecionando a comida indesejada e apertando em excluir<br>
<img width="506" height="299" alt="image" src="https://github.com/user-attachments/assets/a0cba082-3abd-4e26-bac4-8c635964e3fd" /><br>












