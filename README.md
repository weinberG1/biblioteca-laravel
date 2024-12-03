# Projeto Final para a disciplina de Desenvolvimento Web II
Este repositório contém a última atividade desenvolvida na disciplina de Desenvolvimento Web II. O projeto tem como objetivo criar uma biblioteca virtual para gerenciar empréstimo de livros. 


## Projeto feito pelos seguintes alunos:

- Paulo Weinberger
- Célio Munch Junior
- Jeriel Castro


## Iniciando o projeto

Para poder abrir o projeto, você precisa executar os seguintes comandos no terminal com o projeto aberto (e tendo PHP && Composer instalados em sua máquina):

### Para instalar as dependências:
```bash
composer install
```

### Criar uma cópia do arquivo .env.example e renomeá-la para .env (Lembre-se de configurar o env após isso, com as variáveis corretas)
```bash
cp .env.example .env
```

### Gerar uma nova chave de aplicação:
```bash
php artisan key:generate
```

### Executar as migrações para criar as tabelas no banco de dados:
```bash
php artisan migrate
```

### Para servir o projeto na porta default:
```bash
php artisan serve
```



