  <h1>Projeto Servidor - Controle de Acesso aos Laboratórios</h1>
    <p>
        Este projeto tem como objetivo implementar um sistema de controle de acesso aos laboratórios de informática do Instituto Federal de Educação, Ciência e Tecnologia de São Paulo (IFSP), Campus Birigui. O sistema foi desenvolvido para gerenciar e monitorar o uso dos laboratórios, garantindo que apenas usuários autorizados possam acessar os recursos disponíveis.
    </p>

    <h2>Funcionalidades do Sistema</h2>
    <ul>
        <li>Autenticação de usuários através de login e senha.</li>
        <li>Controle de acesso baseado em permissões, permitindo que diferentes perfis de usuários tenham diferentes níveis de acesso.</li>
        <li>Registro de entradas e saídas dos laboratórios, permitindo o monitoramento em tempo real.</li>
        <li>Geração de relatórios detalhados sobre o uso dos laboratórios, incluindo informações como horários de uso e identificação dos usuários.</li>
        <li>Integração com o sistema de câmeras de segurança para monitoramento visual.</li>
    </ul>

    <h2>Tecnologias Utilizadas</h2>
    <p>
        O sistema foi desenvolvido utilizando a linguagem de programação <strong>C#</strong> e a plataforma <strong>.NET</strong>. Para a interface com o usuário, foi utilizado o framework <strong>ASP.NET MVC</strong>, que permite a criação de aplicações web robustas e escaláveis. O banco de dados utilizado é o <strong>SQL Server</strong>, garantindo a integridade e segurança dos dados armazenados.
    </p>

    <h2>Arquitetura do Sistema</h2>
    <p>
        A arquitetura do sistema é baseada no padrão <strong>Model-View-Controller (MVC)</strong>, que separa a aplicação em três componentes principais:
    </p>
    <ul>
        <li><strong>Model:</strong> Representa a lógica de negócios e as regras de manipulação dos dados.</li>
        <li><strong>View:</strong> Responsável pela apresentação dos dados ao usuário, utilizando HTML e CSS.</li>
        <li><strong>Controller:</strong> Intermediário que manipula as interações do usuário, atualiza o Model, e seleciona a View apropriada para exibição.</li>
    </ul>

    <h2>Como Funciona</h2>
    <p>
        Ao acessar o sistema, o usuário é solicitado a realizar o login. Com base nas permissões associadas ao seu perfil, ele poderá acessar determinadas funcionalidades, como reserva de laboratórios, visualização de horários disponíveis, e consulta de históricos de acesso.
    </p>
    <p>
        Os administradores do sistema têm acesso a funcionalidades avançadas, como a criação e gerenciamento de contas de usuário, geração de relatórios, e monitoramento em tempo real através das câmeras integradas.
    </p>

    <h2>Como Executar o Projeto</h2>
    <ol>
        <li>Clone o repositório para o seu ambiente local.</li>
        <li>Abra o projeto em uma IDE compatível, como Visual Studio.</li>
        <li>Configure a conexão com o banco de dados SQL Server.</li>
        <li>Compile e execute a aplicação.</li>
        <li>Acesse a aplicação através do navegador utilizando a URL configurada.</li>
    </ol>

    <h2>Contribuições</h2>
    <p>
        Contribuições são bem-vindas! Se você deseja contribuir com este projeto, siga os passos abaixo:
    </p>
    <ul>
        <li>Fork o repositório.</li>
        <li>Crie uma nova branch com a sua feature: <code>git checkout -b minha-feature</code>.</li>
        <li>Commit as suas mudanças: <code>git commit -m 'Adiciona nova feature'</code>.</li>
        <li>Envie as mudanças para a sua branch: <code>git push origin minha-feature</code>.</li>
        <li>Abra um Pull Request.</li>
    </ul>

    <h2>Licença</h2>
    <p>
        Este projeto está licenciado sob os termos da <a href="https://opensource.org/licenses/MIT">MIT License</a>.
    </p>
</body>
</html>
