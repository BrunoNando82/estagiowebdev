Questões Teóricas:

- Qual a função do "head" no HTML?
    R: A função dele é puxar informações para aquela página HTML específica no qual está sendo chamada, podendo ser chamado um arquivo css e até mesmo uma fonte de um site externo.

- Quando uma página é criada, ela automaticamente se adapta a todos os tipos de tela? Por que?
    R: Quando uma página é criada ela pode sim se adaptar a todos os tipos de tela, devido as diferenças de largura e altura que pode ter um monitor ou Tv e por consequência o site pode se comportar de forma diferente conforme as dimensões de um deles.

- O código HTML e CSS é renderizado no servidor e repassado para o navegador em forma de imagem?
    R: Os códigos são passados de forma binaria, a diferença é que quando renderizado o browser irá conseguir interpretar o que deve ser feito conforme código criado, e essa informação será passada para o monitor ou tv.

- Qual a função das tags H (h1, h2, h3, etc) no HTML?
    R: Elas dão destaques a titulos e sub-titulos da página HTML, sendo que eles em ordem crescente começando do h1 vão diminuindo o tamanho da fonte do texto escolhido. 

- O que é SEO e como funciona?
    R: SEO são tags especificas, que facilitam o site criado ser encontrado pelas ferramentas de pesquisa em toda a internet, como por exemplo o google.

- O uso de media query é obrigatório em todas as páginas?
    R: Dependendo do tipo de página e do projeto especifico ele não é obrigatório o uso em todas as páginas, sendo mais usado no estilo @media. 

- Qual a diferença entre CSS Inline e CSS em um arquivo?
    R: No CSS Inline nós aplicamos o código na página HTML usando a tag <style>, podendo ser dentro de uma div ou qualquer outro elemento do mesmo tipo. Ex: <div style="border:1px solid #fff";></div>. No CSS também podemo exportar ou "puxar" um arquivo do tipo css para a página html, no qual temos dessa forma uma página css para ser usada a vontade sem "poluir" muito os códigos html pela forma do CSS Inline.

- Como criar animações no CSS? Dê um exemplo.
    R: Podemos usar o keyframes onde após ele teriamos que escolher o nome da animação e escolher em quais momentos a animação deverá ocorrer, lembrando de colocar o nome da animação no seletor que queremos onde a animação seja aplicada.
    Ex: 
    @keyframes space{
        0% {opacity:0%;}
        100% {margin-top:5px; opacity:100%;} 
    }
    .text:hover .span{
        display:block;
        animation-name: space;
        animation-duration:3s;
        animation-delay:0.1s;
        animation-direction: normal;
        animation-iteration-count:infinite;
    }

- Qual a diferença entre class e ID no CSS?
    R: O class podemos defini-la na página HTML várias vezes, o que não é possivel com o ID. Outra diferença do class para o ID é a forma que são chamados no css, sendo "."para a class e "#" para o ID.

- Quais os diferentes tipos de seletores CSS?
    R: Alguns deles são "."(Para chamar uma class), "#"(Para chamar um ID), "*"(Corresponde a todos os elementos do documento)