# Semana 15 — Aula 01

## Git básico — repositório, commit e histórico.

### O que os comandos fazem
Nessa aula vimos os comandos essenciais do Git. Cada um tem uma função específica no fluxo de salvar e acompanhar as mudanças do projeto.

- `git init`: Inicia um repositório Git vazio na pasta. É ele quem cria a pasta `.git` e começa a "vigiar" os arquivos.
- `git status`: Mostra a situação atual dos arquivos. Diz o que foi modificado, o que está pronto pra ir pro commit e o que ainda não está sendo rastreado.
- `git add`: Pega os arquivos do diretório de trabalho e joga pra área de preparação. É como se você separasse o que vai entrar no próximo "snapshot".
- `git commit -m "mensagem"`: Tira a foto do projeto. Salva de forma definitiva no repositório tudo que estava na área de preparação, junto com uma mensagem explicando a mudança.
- `git log`: Mostra o histórico de commits. Exibe hash, autor, data e mensagem de cada "foto" que foi salva.



### O que aprendi
Nesta aula, revisamos o processo de clonar um repositório do GitHub diretamente para o Visual Studio Code. 
Além disso, organizamos a estrutura de pastas e arquivos no ambiente de desenvolvimento local e realizamos o registro dos conteúdos estudados em um arquivo Markdown (.md) utilizando a estrutura orientada pelo professor



### Atividade prática
Na prática fizemos um projeto do zero pra testar o fluxo. Inicializamos o repositório com `git init`, criamos e alteramos alguns arquivos, usamos `git add` pra mandar pra staging area e `git commit` pra salvar os snapshots. No final usamos `git log` pra conferir todo o histórico de alterações que fizemos.

### Dificuldades encontradas
Minha maior dúvida foi entender a diferença entre diretório de trabalho, staging area e repositório. No começo eu achava que o `git add` já salvava, mas entendi que ele só prepara. O commit de verdade só acontece depois. Também tinha esquecido como usar o `git log` pra ver o histórico direito.

### Resumo final
Aprendi que o Git funciona com "fotos" do projeto e não só com diferenças. O fluxo é: você mexe nos arquivos, adiciona com `git add` e salva com `git commit`. 
Entender o `git status` e o `git log` ajuda muito a não se perder. 
No fim, o Git dá segurança pra voltar no tempo e ver quem mudou o quê.

### Conceitos principais
- Snapshot (instantâneo)**: O Git não salva só o que mudou. Ele tira uma foto de todos os arquivos naquele momento.
- Diretório de trabalho (working directory)**: É a pasta onde você edita os arquivos normalmente.
- Área de preparação (staging area)**: É o "carrinho de compras". Você coloca aqui só o que quer commitar.
- Repositório (repository/.git)**: É onde ficam salvos todos os snapshots e o histórico completo do projeto.