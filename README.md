# MongoDB
MongoDB - O banco baseado em documentos

![image](https://user-images.githubusercontent.com/82824988/119204543-123aa680-ba6c-11eb-8c0c-675c6b9a4a61.png)


# O que significa “baseado em documentos”?

A principal diferença entre MongoDB e os principais sistemas tradicionais de bancos de dados relacionais conhecidos como RDBMS, é que, em vez de tabelas, linhas e colunas, a base para armazenamento no MongoDB é um documento.

Os documentos são normalmente modelados usando a formatação JSON e, em seguida, inseridos no banco de dados onde são convertidos em um formato binário para armazenamento.

Relacionado à base de documentos para armazenamento, está o fato de que os documentos MongoDB não têm esquema fixo. O principal benefício disso é a sobrecarga amplamente reduzida.

A reestruturação do banco de dados é fácil de ser aplicada e não causa os problemas massivos, travamentos de sites e violações de segurança observados em aplicativos que utilizam banco de dados relacionais.

# Quais as vantagens do MongoDB?

Outro recurso que faz com que o MongoDB se destaque de outras tecnologias de banco de dados é sua capacidade de garantir alta disponibilidade por meio de um processo conhecido como replicação ou replication do inglês.

Um servidor que executa o MongoDB pode ter cópias de seus bancos de dados duplicadas em mais dois servidores. Essas cópias são conhecidas como conjuntos de réplicas (ou replica sets do inglês).

Os conjuntos de réplicas são organizados por meio de um processo de eleição em que os membros da réplica votam em qual servidor se torna o principal. Outros servidores são então atribuídos à função de secundários.

Outro recurso, entre muitos, é a capacidade do MongoDB de lidar com uma grande quantidade de dados. Isso é feito dividindo uma coleção considerável em vários servidores, criando um cluster fragmentado. No processo de divisão da coleção, uma chave de fragmento é escolhida entre os campos presentes nos documentos da coleção.

A chave de shard é então usada pelo balanceador de cluster shard para determinar a distribuição apropriada de documentos.



# Link: Documento Oficial
https://www.mongodb.com/what-is-mongodb
