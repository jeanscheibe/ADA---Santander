Containers e armazenamento - Por padrão containers não armazenam estados

Volumes são necessários para manter salvos os arquivos considerados como efêmeros

Docker Volume - Monta o diretório dentro do container

Docker bind - Mais antigo, porém mais limitado, menos volatil

tmpfs - Armazenamento temporário recursos como dados sensíveis, por exemplo. Só enquanto o container estiver ativo.

-d para rodar no background

docker ps paraae está rodando

Também se pode criar volumes comuns a dois containers para que os dois possam acessar aqueles arquivos
