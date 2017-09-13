# Palestra-USJT-Desenvolvimento-de-aplica-es-h-bridas
Palestra do dia 12/09/2017 na universidade São Judas Tadeu Mooca sobre Desenvolvimento de aplicações mobile híbridas com HTML, CSS e Javascript

Abaixo o link dos slides da palestra:
[https://pt.slideshare.net/secret/bDXK41qUfpg9V2](https://pt.slideshare.net/secret/bDXK41qUfpg9V2)

O código nesse repositório é apenas para uma pequena demonstração de uma aplicação hibrida com Cordova. Inclui um teste com a camera, movimentação do dispositivo e listagem dos contatos do aparelho.
O código HTML, CSS e Javascript encontra-se na pasta `www` desse projeto e está comentado para ajudar no entendimento.


## Como Iniciar o projeto e testar em um android
- Instale o cordova e as dependencias para fazer build para um android seguindo até o passo 9 desse tutorial [https://pt.slideshare.net/secret/bDXK41qUfpg9V2](https://pt.slideshare.net/secret/bDXK41qUfpg9V2)
- Instale o cordova com o comando: `npm install -g cordova`
- Faça o download do repositório ou clone usando o git
- Abra um terminal ou cmd na pasta do projeto baixado ou clonado
- Execute o comando `cordova plugin add cordova-plugin-camera`
- Execute o comando `cordova plugin add cordova-plugin-contacts`
- Execute o comando `cordova plugin add cordova-plugin-device-motion`
- Execute o comando `cordova platform add android` (para adicionar o android as possíveis builds do projeto
- No seu android habilite o modo debug e conecte-o ao computador com um cabo USB
- Execute o comando `adb devices` (para que ele seja identificado)
- Execute o comando `cordova run android`, caso você queira executa-lo em um emulador android que já esteja aberto basta usar o comando `cordova run android --emulator`


Caso tenha ficado curioso e queira aprender mais sobre cordova e desenvolvimento mobile hibrido, existem vários artigos e tutoriais que podem te ajudar, abaixo listo alguns deles:
- Curso completo de Phonegap/Cordova da Loiane Groner no youtube
[https://www.youtube.com/playlist?list=PLGxZ4Rq3BOBrsK_yegY0fViqXKyNhUlxP](https://www.youtube.com/playlist?list=PLGxZ4Rq3BOBrsK_yegY0fViqXKyNhUlxP)
- Dê uma lida ness artigo sobre ionic do Luis Vasconcellos[https://medium.com/@lfv89/nessa-s%C3%A9rie-divida-em-3-partes-vou-falar-um-pouco-mais-a-fundo-sobre-desenvolvimento-h%C3%ADbrido-914f22453c83](https://medium.com/@lfv89/nessa-s%C3%A9rie-divida-em-3-partes-vou-falar-um-pouco-mais-a-fundo-sobre-desenvolvimento-h%C3%ADbrido-914f22453c83)
- Leia a documentação do Cordova, tem vários exemplos e explicações (em inglês):
[https://cordova.apache.org/docs/en/latest/](https://cordova.apache.org/docs/en/latest/)