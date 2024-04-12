# Pacote Comum de CQL da G3deon Inc

![Banner do repositório](/assets/g3-cqlx-banner.png)

## Traduções

Você pode visualizar a documentação no seu idioma preferido:

- Inglês. [Ver em Inglês](/README.md).
- Espanhol. [Ver em Espanhol](/README-ES.md).
- Português (Brasil). (Tradução atual)

## Perguntas Frequentes (FAQs)

### Por que g3-cqlx?

Na [G3deon Inc](https://g3deon.com), temos uma arquitetura distribuída, especificamente de microsserviços. Como não trabalhamos com um monorrepo, percebemos que em muitos de nossos microsserviços repetimos muito código. Diante desse cenário, para melhorar a manutenibilidade e a escalabilidade de nosso serviço, separamos esse código repetido em bibliotecas. É aí que entra o **g3-cqlx**, uma biblioteca para integrar cqlx aos padrões que seguimos na [G3deon Inc](https://g3deon.com).

### Por que não usar o gocqlx diretamente?

Com o **g3-cqlx**, nosso objetivo é ter as funções mais comumente usadas, mas isso não significa que você não possa usar o [gocqlx](https://github.com/scylladb/gocqlx) diretamente. Você pode, mas também pode utilizar as funções do g3-cqlx se estiver realizando ações básicas e repetitivas.

## Licença

Este projeto está licenciado sob a *Licença MIT*.

```md
Licença MIT

Direitos autorais (c) 2024 G3deon, Icon.

É concedida permissão, gratuitamente, a qualquer pessoa que obtenha uma cópia
deste software e dos arquivos de documentação associados (o "Software"), para lidar
no Software sem restrição, incluindo, sem limitação, os direitos
para usar, copiar, modificar, mesclar, publicar, distribuir, sublicenciar e/ou vender
cópias do Software, e para permitir que as pessoas a quem o Software é
fornecido o façam, sujeito às seguintes condições:

O aviso de copyright acima e este aviso de permissão devem ser incluídos em todos
cópias ou partes substanciais do Software.

O SOFTWARE É FORNECIDO "COMO ESTÁ", SEM GARANTIA DE QUALQUER TIPO, EXPRESSA OU
IMPLÍCITA, INCLUINDO, MAS NÃO SE LIMITANDO ÀS GARANTIAS DE COMERCIALIZAÇÃO,
ADEQUAÇÃO A UM DETERMINADO FIM E NÃO VIOLAÇÃO. EM NENHUM CASO O
AUTORES OU TITULARES DE DIREITOS AUTORAIS SERÃO RESPONSÁVEIS POR QUALQUER RECLAMAÇÃO, DANOS OU OUTROS
RESPONSABILIDADE, SEJA EM AÇÃO DE CONTRATO, DELITO OU DE OUTRA FORMA, DECORRENTE DE,
FORA DE OU EM CONEXÃO COM O SOFTWARE OU O USO OU OUTRAS NEGOCIAÇÕES NO
SOFTWARE.
