## Teste Prático Desenvolvedor(a) PHP Pleno

Caro desenvolvedor, o objetivo desta avaliação é medir o nível de conhecimento do candidato nas áreas em que a vaga será exigida.

### Objetivos
Conhecer um pouco de suas habilidades em: PHP / Laravel;
Entendimento e análise dos requisitos;
Capacidade de inovar;
Determinação na busca de soluções;
Responsabilidade na tomada de decisões.

### Disclaimer
Todo e qualquer código desenvolvido nesse teste não será utilizado em quaisquer outros softwares nem comercializados por nós.
O propósito deste teste é apenas avaliar o conhecimento em programação do candidato.

### Instruções
Você deve criar um gerenciador financeiro simples conforme os requisitos abaixo, utilizar o framework Laravel (versão 8). Fique a vontade para explorar todo o seu conhecimento em automação de tarefas, CSS e Javascript com JQuery, Vue.JS, AlpineJS ou qualquer outra ferramenta que lhe torne produtivo.

- Autenticação por login e senha
- CRUD de lançamentos de *receitas* (entrada) relacionado com o usuário logado
- CRUD de lançamentos de *despesas* (saidas) relacionado com o usuário logado
- CRUD de categorias para os lancamento relacionado ao usuário e lançamento realizado
- Todas as listagens devem possuir busca e paginação de 20 items
- API deverá conter uma busca com filtro, listagem de todas as entidades
- Ao cadastrar uma despesa, um email deverá ser enviado ao usuário
- O email deverá ter o título "Despesa cadastrada" e ser enviado de forma assíncrona (utilizar MailTrap)

### Exemplos de entidades
**Receita**
- ID
- ID usuário (relacionamento)
- ID categoria (relacionamento)
- Data - não pode ser passado, nem maior que o último dia do mês atual
- Descrição - não ultrapassar 191 caracteres
- Valor - não pode ser negativo
- Timestamps

**Despesa**
- ID
- ID usuário (relacionamento)
- ID categoria (relacionamento)
- Data - não pode ser passado, nem maior que 12 meses
- Descrição - não ultrapassar 191 caracteres
- Valor - não pode ser negativo
- Timestamps

**Categoria**
- ID
- Descrição - não ultrapassar 191 caracteres
- Timestamps

### Plus
 **Não é obrigatório, mas será muito bom se você:**
- Programar em Inglês
- Escrever testes
- Utilizar as melhores práticas da Orientação a Objetos
- Utilizar seeds e factories
- As tabelas do banco de dados criadas através de migrations com as devidas nomenclaturas em inglês
- Utilizar VueJS / AlpineJS 
- Utilizar Bootstrap / Tailwindcss

### Observações
O que será avaliado é a qualidade do código qualquer generator / scaffolding de CRUD, MVC, etc, é desnecessário.
Seu projeto não precisa ter um UX excelente. Você pode optar por templates para o frontend, se assim desejar.
Não precisa ser complexo, com varias lib’s e etc. O interessante é usar o necessário para ter um código de qualidade e de fácil evolução.
Lembrando código de qualidade, você pode e deve fazer o que achar necessário para isso, mesmo que não esteja listado aqui.

### Conclusão
Após concluir a aplicação basta enviar o link do projeto no github ou bitbucket através do Whatsapp
