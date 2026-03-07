# DESAFIO-QA-BEEDOO-2026
DESAFIO-QA-BEEDOO-2026

# DESAFIO-QA-BEEDOO-2026
DESAFIO-QA-BEEDOO-2026

2. Exploração da aplicação
- Qual você acredita ser o objetivo da aplicação?

        A aplicação tem como objetivo permitir o gerenciamento de cursos através de funcionalidades de cadastro, visualização e exclusão de cursos. O sistema possibilita que usuários registrem cursos informando dados como nome do curso, descrição, instrutor, datas e tipo de curso, se é presencial ou online, além de visualizar os cursos cadastrados em uma lista organizada.

        Além disso, a interface sugere que o sistema pode ser utilizado para administração de treinamentos e cursos educacionais, permitindo o controle básico dessas informações.

- Quais são os principais fluxos disponíveis
       
       1. Cadastro de curso
        Fluxo:
           - Acessar "Curso Cadastrar"
           - Preencher todos os campos
           - Clicar em CURSO CADASTRAR

        2. Listagem de cursos
        Fluxo:
           - Acessar "Listar Cursos"
           - Visualizar cursos cadastrados em cards

        3. Exclusão de curso
        Fluxo:
           - Localizar curso na listagem
           - Clicar em Excluir Curso
           - Curso é removido da lista

- Quais pontos do sistema você considera mais críticos para teste?

        Validação dos campos de cadastros de cursos
        Campos que precisam ser testados:
           - Nome do curso
           - Descrição
           - Instrutor
           - URL da imagem
           - Data de início
           - Data de fim
           - Número de
           - Tipo de curso

        Testar:
           - campos vazios
           - dados inválidos
           - tamanho máximo
        
        Validação de datas
           Testar situações como:
           - Data de início maior que data de fim
           - Data de início no passado
           - Data inválida

        Exclusão de curso
           Verificar:
           - se existe confirmação antes de excluir
           - se realmente remove da lista
           - se a exclusão funciona após atualizar a página


        Persistência dos dados
            Testar:
            - se o curso continua na lista após recarregar a página
            
        Exibição na listagem
            Verificar se:
           - todas as informações aparecem  corretamente
           - datas são exibidas no formato correto
           - imagem da capa esta aparecendo 


3. Criação de cenários e casos de teste
    Link: https://docs.google.com/spreadsheets/d/1bKSplL-9Euoi39_j-yUSl_MeE3qdP_6GnmdntYZjDLU/edit?usp=sharing

4. Execução dos testes
    Link: https://drive.google.com/drive/folders/1nWYId9Tgc_BwjbqnQmYwwiMBGmkBmyxn?usp=sharing

5. Registro de bugs
    Link: https://docs.google.com/document/d/12QNQCXHUGRFngeXVfiT1rkghVrGX7n5OoIL9nuuf3a0/edit?usp=sharing
