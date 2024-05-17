### salve familia 👋

-meu nome é **leonardo** e estou estudando alura

-estou me desenvolvendo na linguagem de javaScript

### entre em contato comigo pelo

9et543@gmail.com

//const nome =
'Leonardo Oliveira Lima';
const email = '9et543@gmail.com';
const experiencia = [
  {
    cargo: 'Desenvolvedor Full Stack',
    empresa: 'Empresa XYZ',
    periodo: 'Janeiro 2020 - Presente',
    descricao: 'Desenvolvimento de aplicações web utilizando tecnologias como JavaScript, HTML, CSS, Node.js, React, etc.'
  },
  {
    cargo: 'Estagiário de Desenvolvimento',
    empresa: 'Empresa ABC',
    periodo: 'Julho 2018 - Dezembro 2019',
    descricao: 'Participação em projetos de desenvolvimento de software, aprendizado de tecnologias e boas práticas.'
  }
];

function mostrarCurriculo() {
  console.log(`Nome: ${nome}`);
  console.log(`Email: ${email}`);
  console.log('Experiência:');
  experiencia.forEach((job) => {
    console.log(`- Cargo: ${job.cargo}`);
    console.log(`  Empresa: ${job.empresa}`);
    console.log(`  Período: ${job.periodo}`);
    console.log(`  Descrição: ${job.descricao}`);
  });
}

mostrarCurriculo();
