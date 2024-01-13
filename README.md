# Projeto Dogs 

##### O projeto Dogs foi desenvolvido através do curso de React oferecido pela Origamid, o foco principal do projeto é criar uma rede social dedicada aos nossos melhores amigos, os "Dogs" e poder através dela compartilhar informações e experiências vividas com eles.

###### Um dos pontos que mais senti dificuldade nesse projeto inicialmente foi a utilização de Hooks, porém, a cada novo componente desenvolvido esse conhecimento ficava mais fácil de ser entendido.

## Hooks Utilizados: 

#### O useState é um Hook que permite adicionar um estado a componentes de função. Alguns exemplos de utilização no projeto Dogs, é gerenciar o estado local de componentes, como o estado do formulário de login, o estado das fotos no feed, etc.

#### O useEffect é usado para realizar operações secundárias em componentes de função. Ele é comumente utilizado para buscar dados, manipular o DOM ou realizar outras ações após a renderização do componente. Neste projeto, foi usado para buscar dados do servidor e algumas outras tarefas assíncronas.

#### O useContext é usado para acessar o valor de um contexto React. Contextos são uma forma de compartilhar valores, como o estado de autenticação, entre componentes sem a necessidade de passar propriedades manualmente. No projeto Dogs, pode ser usado para acessar informações do usuário autenticado em componentes descendentes.

#### Alguns hooks customizados foram usados, eles foram criados para facilitar a lógica dos formulários e useFetch, ficando assim um código mais limpo e com menos verbosidade, além de permitir que a lógica seja reutilizada em vários componentes. Nesse projeto foi muito útil para esses 2 tópicos abordados: manipulação de formulários e requisições para a API. 
