## Reflexão sobre a Modelagem
**Pergunta:** Qual tabela deve receber a Foreign Key (Chave Estrangeira)?

**Resposta:** A tabela `albuns` deve receber a Foreign Key (`artista_id`), pois o relacionamento entre Artistas e Álbuns é do tipo 1:N (Um para Muitos). Como um Artista pode possuir vários Álbuns,
a chave estrangeira precisa estar na tabela do lado "Muitos" para permitir que cada álbum referencie o seu respectivo artista.
