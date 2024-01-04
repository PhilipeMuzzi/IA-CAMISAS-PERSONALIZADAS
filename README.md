# Construção e implementanção de um website 3D com inteligência artificial usando o React

<p align="center">
  <img src="client/src/assets/persona1.PNG" />
</p>

<p align="center">
  <img src="client/src/assets/persona2.PNG" />
</p>

<p align="center">
  <img src="client/src/assets/persona3.PNG" />
</p>

## Sobre o projeto
O projeto permite com que o usuário crie e personalize camisas com auxílio de inteligência artificial,
permitindo com que seja criada uma arte individual de preferência única, sendo as solicitações enviadas através de:

- Chat;
- Upload de imagens;
- Interface de cores personalizadas.
## Introdução
Neste projeto, foi utilizado tecnologias como ThreeJS, React Three Fiber, TailwindCSS e Framer Motion para criar um site 3D interativo com animações envolventes. Também foi integrado inteligência artificial para uma melhor experiência do usuário.

## Descrição breve sobre as tecnologias utilizadas nesse website:
- ThreeJS - uma poderosa biblioteca de gráficos 3D para renderizar e animar o modelo 3D
- React Three Fiber - uma biblioteca popular para criar gráficos 3D com ThreeJS no React
- TailwindCSS - um framework de estilo CSS utilitário
- Framer Motion - a biblioteca mais popular usada para dar vida ao seu site React com animações

## Dependências e pacotes

Utilize cd para instalar pacotes necessários na pasta principal do projeto:

npm install
npm install react react-dom
npm install three @react-three/fiber @react-three/drei maath valtio react-color framer-motion

## Como executar o projeto
Passo 1: Configurar a chave de ambiente
- Abra a pasta do projeto e navegue até a pasta "server".
- Crie um arquivo chamado ".env" em server/.env e abra-o.
- Adicione sua key (gerada através da OpenIA)

por exemplo:   export OPENAI_API_KEY=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


Passo 2: Executar o servidor

- Abra o terminal ou prompt de comando.
- Navegue até a pasta "server" do projeto usando o comando cd.
- Uma vez dentro da pasta "server", execute o comando "npm start" no terminal para startar o servidor.
- Aguarde até que o servidor seja iniciado com sucesso. Você deverá ver mensagens indicando que o servidor está sendo executado e pronto para receber solicitações.

Passo 3: Executar o cliente

- Abra um novo terminal ou prompt de comando.
- Navegue até a pasta "client" do projeto usando o comando cd 
- Dentro da pasta "client", execute o comando "npm run dev" no terminal.
- Aguarde até que o cliente seja iniciado. Você deverá ver mensagens indicando que o cliente está sendo executado e pronto para uso.


Agora você executou o projeto com sucesso ! Certifique-se de que tanto o servidor quanto o cliente estejam em execução para garantir que toda a aplicação funcione corretamente.


## Observação
Com constantes atualizações da API oficial da OPENAI, algumas modificações podem ser implementadas. 