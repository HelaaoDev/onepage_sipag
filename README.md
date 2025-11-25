# onepage_sipag
Página Web com Integração SCORM para LMS

Este projeto consiste em uma página educacional desenvolvida para um curso com integração ao padrão SCORM, permitindo comunicação direta com plataformas LMS. O objetivo é demonstrar a criação de conteúdo web interativo capaz de registrar progresso, conclusão, tempo de estudo e demais dados necessários para trilhas de aprendizagem.

Funcionalidades

Integração SCORM (1.2 ou 2004), com inicialização, envio e recuperação de dados.

Registro de status do curso, progresso, conclusão e tempo de sessão.

Comunicação com a API SCORM utilizando métodos como Initialize, GetValue, SetValue, Commit e Terminate.

Interface responsiva desenvolvida em HTML, CSS e JavaScript.

Estrutura preparada para empacotamento SCORM e importação em qualquer LMS compatível.

Navegação simples e otimizada para cursos corporativos.

Tecnologias Utilizadas

HTML5

CSS3

JavaScript

Bootstrap (opcional)

SCORM API Wrapper (1.2 ou 2004)

Como Empacotar em SCORM

Verifique se o arquivo imsmanifest.xml está corretamente configurado na raiz do projeto.

Selecione todos os arquivos e compacte em formato ZIP.

Importe o ZIP diretamente no LMS de sua escolha (ex: Moodle, Totara, Docebo, Saba, SuccessFactors).

Publique e teste o curso dentro do ambiente LMS para validar a comunicação SCORM.

Como Testar Localmente

Algumas funcionalidades SCORM funcionam apenas dentro do LMS. Para testes locais:

Abra o arquivo index.html para visualizar a interface.

Para simular um ambiente SCORM, utilize:

SCORM Cloud

Reload SCORM Player

Outro simulador SCORM de sua preferência

Objetivo do Projeto

Demonstrar o desenvolvimento de uma página web educacional integrada ao padrão SCORM, evidenciando conhecimentos em UI, desenvolvimento front-end e integração com plataformas de aprendizagem.
