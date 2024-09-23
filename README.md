document.addEventListener("DOMContentLoaded", function() {
    const formDisciplina = document.getElementById('form-disciplina');
    const formAluno = document.getElementById('form-aluno');
    const formCurso = document.getElementById('form-curso');

    formDisciplina.addEventListener('submit', function(event) {
        event.preventDefault();
        alert('Disciplina cadastrada com sucesso!');
        // Aqui você pode adicionar lógica para salvar os dados
    });

    formAluno.addEventListener('submit', function(event) {
        event.preventDefault();
        alert('Aluno cadastrado com sucesso!');
        // Aqui você pode adicionar lógica para salvar os dados
    });

    formCurso.addEventListener('submit', function(event) {
        event.preventDefault();
        alert('Curso cadastrado com sucesso!');
        // Aqui você pode adicionar lógica para salvar os dados
    });
});
