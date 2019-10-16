# Resumo das tarefas que deverão ser executadas para o aprendizado.

Salvem todos os arquivos, retornos e comandos que julgarem importântes em uma pasta em suas respectivas branches desse repositório.
Isso depois poderá servir de guia para vocês no futuro.

## Tarefa 1

### Implementação do dockerfile

- Neste primeiro exercício você deverá importar a aplicação helloworld.py para um dockerfile.
- Esta aplicação deverá estar rodando na porta 80 de seu container, porém deverá ser redirecionada para a porta 5000 de sua máquina.
- Qual a diferença entre o comando CMD e ENTRYPOINT?

### Checagem de status do container

- Após seu serviço estar sendo executado, gere um relatório com os logs da sua aplicação e do seu container.
- Entre dentro de seu container também para alterar o código em pyhon sendo executado para printar algo diferente de hello world.
- Ache o PID de seu processo no container e na máquina que está hosteando o mesmo.
- Finalize a aplicação de PID 1 em seu container (no caso, sua aplicação em python)


## Tarefa 2

### Segurança do container

- Altere o usuário do container.
- Como impedir que alguem que tem acesso ao container consiga acesso a maquina?

### Link entre container e PC

- Faça um link entre uma pasta que está presente em seu sistema operacional com uma pasta do container. (Caso ocorra alguma modificação no conteúdo dessa pasta pelo container, este conteúdo também irá mudar para o host, e vice versa).
- Crie um volume para persistencia de dados. Para isso, crie seu container, acesse ele, crie um documento na pasta com volume, e depois destrua o container. 
- Gere um container que execute um job, salvando seu resultado final na sua máquina local.

## Tarefa 3

### Exportação de imagens

- Crie e exporte uma imagem de sua máquina para o servidor indicado para testes.
- Builde a imagem no servidor alvo.

### Commit de containers

- Gere uma imagem com base em um container que está rodando, e houveram alterações dentro dele.
- Examine o resultado final, e indique o problema desta prática.

## Tarefa 4

### NFS

- Crie um servidor de NFS para armazenar os volumes criados.

### Registry

- Crie um servidor de registry privado para armazenarem todas as imagens geradas por vocês durante o treinamento.

