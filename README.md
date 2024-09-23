<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro de Disciplinas</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Cadastro de Disciplinas</h1>
    </header>
    
    <section id="cadastro-disciplinas">
        <h2>Cadastro de Disciplinas</h2>
        <form id="form-disciplina">
            <label for="tipo-disciplina">Tipo de Disciplina:</label>
            <input type="text" id="tipo-disciplina" name="tipo-disciplina">

            <label for="nome">Nome da Disciplina:</label>
            <input type="text" id="nome" name="nome">

            <label for="descricao">Descrição:</label>
            <textarea id="descricao" name="descricao"></textarea>

            <label for="professor">Professor:</label>
            <select id="professor" name="professor">
                <option value="prof1">Professor 1</option>
                <option value="prof2">Professor 2</option>
            </select>

            <label for="codigo-curso">Código do Curso:</label>
            <input type="text" id="codigo-curso" name="codigo-curso">

            <button type="submit">Salvar</button>
        </form>
    </section>

    <section id="cadastro-alunos">
        <h2>Cadastro de Alunos</h2>
        <form id="form-aluno">
            <label for="nome-aluno">Nome do Aluno:</label>
            <input type="text" id="nome-aluno" name="nome-aluno">

            <label for="curso">Curso:</label>
            <select id="curso" name="curso">
                <option value="curso1">Curso 1</option>
                <option value="curso2">Curso 2</option>
            </select>

            <button type="submit">Salvar</button>
        </form>
    </section>

    <section id="cadastro-cursos">
        <h2>Cadastro de Cursos</h2>
        <form id="form-curso">
            <label for="nome-curso">Nome do Curso:</label>
            <input type="text" id="nome-curso" name="nome-curso">

            <label for="tipo-curso">Tipo de Curso:</label>
            <input type="text" id="tipo-curso" name="tipo-curso">

            <button type="submit">Salvar</button>
        </form>
    </section>

    <script src="script.js"></script>
</body>
</html>
