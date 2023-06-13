# G3

## Descrição
   Na visão de muitas empresas de diferentes setores, existe uma enorme diferença de conhecimento técnico e comportamental entre a expectativa/necessidade de uma empresa e o que se encontra à disposição para trabalhar. Algumas empresas, portanto, estão tomando a dianteira e estão propondo desenvolver competências técnicas e comportamentais antes de recrutarem, assim eles treinam um número grande de pessoas e conseguem contratar aqueles que se destacam.
   Desenvolver um sistema para administrar e acompanhar todos os alunos e empresas parceiras nessa jornada.



## Pré-requisitos
Antes de executar o projeto, verifique se você possui os seguintes pré-requisitos instalados em sua máquina:

- Node.js
- Docker

## Equipe
O projeto foi desenvolvido por uma equipe de colaboradores. Abaixo está a lista de membros da equipe que contribuíram para o projeto:

- Gabriel Zanandre Guadagnini - 21002973
- Lucas Beltrão - 21001927
- Bruno Nascimento - 21008214
- Igor Roelli - 21003446
- Giancarlo Biagini – 21004808

## Como Executar o Projeto

Siga as etapas abaixo para executar o projeto em sua máquina:

1. Faça o clone deste repositório em um diretório de sua escolha.


2. Abra um terminal e navegue até o diretório raiz do projeto.
   Execute os comandos para baixar os submodules
  ```shell
   git submodule init
   ```
   ```shell
   git submodule update
   ```
   #fique atento com a branch em que está em cada modulo
   
   
3. Execute o seguinte comando para iniciar o backend:

   ```shell
   docker compose -f backend/docker-compose.yml up -d
   ```

   Esse comando irá iniciar os contêineres Docker necessários para o funcionamento do backend.

4. Em seguida, execute o seguinte comando para iniciar o frontend:

   ```shell
   docker compose up
   ```

   Esse comando irá iniciar o frontend e estabelecer a comunicação com o backend.

5. Por fim, navegue até o diretório `frontend` no terminal:

   ```shell
   cd frontend
   ```

   E execute o comando abaixo para iniciar o aplicativo Electron:

   ```shell
   npm run electron
   ```

   O aplicativo será iniciado e você poderá visualizá-lo em sua máquina.

Agora você pode explorar o projeto e desfrutar de seus recursos.

