# Kit de treinamento do GitHub
# Adcionado esse trecho de código para criar um conflito ao fazer merge.

Material didático de código aberto da equipe de Serviços Profissionais do GitHub.

## Nós ❤️ colaboradores como você

**Estamos ansiosos para trabalhar com você**, nossa comunidade de usuários, para melhorar esses materiais e desenvolver novos. Confira nosso [guia de CONTRIBUIÇÃO](CONTRIBUTING.md) para obter mais informações sobre como começar.

## Procurando um recurso que antes estava no training-kit?

Este repositório contém atualmente folhas de referência do Git e do GitHub. Se você estiver procurando um projeto que costumava estar aqui, como treinamento sob demanda, listas de leitura, vídeos e recomendações de livros, consulte [este commit](https://github.com/github/training-kit/tree/4fbf180e980ef973ba4cc4b8ef3d5f278ddc8c08) no histórico do repositório.

## Projetos usados no kit de treinamento

- Usamos [Jekyll](https://jekyllrb.com/) e [Markdown](https://guides.github.com/features/mastering-markdown/).
- Nosso conteúdo é estilizado usando o [kit de ferramentas Primer CSS](https://github.com/primer/primer-css).

## Empacotamento para visualização atrás do seu firewall

Se você deseja ter uma cópia dos arquivos para serem servidos a partir de um servidor web dentro do seu firewall, comece executando `script/package`.

1. Execute `script/package` para criar um tarball de lançamento. Ele terá o formato `release-XXXXXXX.tgz` para você levar para onde quiser.
2. Para testar se está tudo certo, crie algumas pastas `mkdir -p test_site/kit`.
3. Extraia o release, `tar -xzf release-XXXXXXX.tgz -C test_site/kit`.
4. Mude para o diretório test_site, `cd test_site`.
5. Visualize o site:
- Para a versão 2.x do Python, execute: `python -m SimpleHTTPServer`
- Para a versão 3.x do Python, execute: `python -m http.server`
- _Observação: alguns servidores são mais avançados do que outros e podem lidar com redirecionamentos, reconhecimento inteligente de arquivos `.html`, etc_

O conteúdo do site está licenciado sob [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/). A CC-BY-4.0 concede permissão para usar o conteúdo para quase qualquer finalidade, mas não concede nenhuma permissão de marca registrada, desde que você indique a licença e dê crédito, como segue:

> Conteúdo baseado em [github.github.com/training-kit/](https://github.github.com/training-kit) usado sob a licença [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/).

O código usado para construir e testar o site, bem como os exemplos de código no site, se houver, são licenciados sob [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/legalcode). A CC0 renuncia a todas as restrições de direitos autorais, mas não concede nenhuma permissão de marca registrada.

Isso significa que você pode usar o conteúdo e o código deste repositório, exceto as marcas registradas do GitHub, em seus projetos.

Ao contribuir para este repositório, você o faz sob as licenças acima.

## Gustavo Alex de Souza edited this file in 09/22/25 and translated it to Brazilian Portuguese for his Software Engineering class