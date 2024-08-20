<h1>Controle de Acesso aos Laboratórios - README</h1>

<h2>Visão Geral</h2>
<p>O <strong>Controle de Acesso aos Laboratórios</strong> é um projeto desenvolvido no Instituto Federal de Educação, Ciência e Tecnologia de São Paulo (IFSP) - Campus Birigui, com o objetivo de gerenciar e controlar o acesso aos laboratórios do campus. O sistema foi projetado para garantir que apenas pessoas autorizadas, como alunos, servidores e funcionários, possam acessar os laboratórios, utilizando uma senha individual cadastrada.</p>

<h2>Objetivo do Projeto</h2>
<p>O principal objetivo deste projeto é implementar um sistema seguro e eficiente de controle de acesso, capaz de registrar e gerenciar as permissões de entrada nos laboratórios. Este sistema se baseia em uma interface com teclado 4x3 para entrada de senha, que é verificada antes de liberar o acesso por meio de uma fechadura eletrônica.</p>

<h2>Funcionalidades do Sistema</h2>
<p>O sistema de controle de acesso foi desenvolvido com uma série de funcionalidades que permitem uma administração completa e segura:</p>
<ul>
    <li><strong>Cadastro de Funções:</strong> O sistema permite o cadastro, alteração e remoção de funções (Aluno, Servidor, Funcionário da Limpeza). Cada função é identificada por um ID único.</li>
    <li><strong>Gerenciamento de Matrículas:</strong> É possível cadastrar, alterar e remover matrículas de usuários, associando informações como nome, CPF, sigla e número da matrícula, e função.</li>
    <li><strong>Gerenciamento de Senhas:</strong> Cada usuário deve ter uma senha cadastrada, que pode ser alterada ou removida conforme necessário. A senha é validada junto com a matrícula previamente cadastrada.</li>
    <li><strong>Cadastro de Blocos e Salas:</strong> O sistema permite o gerenciamento dos blocos e salas do campus, garantindo que cada sala esteja corretamente associada a um bloco e que números duplicados não sejam permitidos dentro de um mesmo bloco.</li>
    <li><strong>Gerenciamento de Microcontroladores:</strong> Cada sala pode ter um microcontrolador associado, que é responsável por controlar a trava eletrônica da porta.</li>
    <li><strong>Controle de Travas:</strong> O sistema gerencia as travas eletrônicas, associando-as aos prontuários dos usuários e às respectivas salas e blocos.</li>
</ul>

<h2>Tecnologias e Arquitetura do Sistema</h2>
<p>O projeto foi desenvolvido utilizando uma abordagem de Orientação a Objetos, com a criação de diagramas de caso de uso, diagramas de classes, e modelos de entidades para a estruturação do banco de dados. A arquitetura do sistema é robusta, permitindo fácil manutenção e expansão futura.</p>
<ul>
    <li><strong>Diagrama de Caso de Uso:</strong> Representa as interações entre os usuários do sistema (administradores) e as funcionalidades disponíveis.</li>
    <li><strong>Diagrama de Classes:</strong> Define a estrutura e os relacionamentos entre as principais classes do sistema, como Usuário, Função, Matrícula, Bloco, Sala, Microcontrolador, e Trava.</li>
    <li><strong>Modelo Entidade-Relacionamento:</strong> Representa a organização dos dados e suas relações no banco de dados, garantindo integridade e consistência nas operações.</li>
</ul>

<h2>Implementação e Testes</h2>
<p>O sistema foi implementado com foco na segurança e na facilidade de uso. Foram realizados testes exaustivos para assegurar que o sistema responde corretamente às diversas condições de uso, incluindo tentativas de acesso com senhas incorretas, gestão de múltiplos usuários e salas, e integridade dos dados armazenados.</p>

<h2>Conclusão</h2>
<p>O <strong>Controle de Acesso aos Laboratórios</strong> é uma solução eficaz para garantir a segurança e a organização no acesso aos laboratórios do IFSP - Campus Birigui. Com funcionalidades abrangentes e uma arquitetura sólida, o sistema oferece uma ferramenta poderosa para a gestão de acesso, garantindo que apenas pessoas autorizadas possam acessar as instalações.</p>
