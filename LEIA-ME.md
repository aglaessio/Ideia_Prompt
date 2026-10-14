# Ideia em Prompt

Aplicativo em português para transformar ideias em prompts estruturados para o ChatGPT.

## Arquivos

- `Ideia-em-Prompt.html`: versão completa em um único arquivo. Abra no navegador.
- `src/index.html`: estrutura da página.
- `src/style.css`: estilos, modo escuro e layout para smartphone.
- `src/app.js`: geração de prompts, temas, biblioteca, busca, cópia e download.

## Como usar

Abra `Ideia-em-Prompt.html`, escreva uma ideia, ajuste as opções e clique em **Criar meu prompt**. Copie o resultado e cole no ChatGPT. O botão no topo alterna entre os modos claro e escuro.

Você também pode abrir `src/index.html` mantendo os três arquivos da pasta juntos.

## Como colocar online

Publique os três arquivos de `src/` na mesma pasta de uma hospedagem de sites estáticos. Use `index.html` como página inicial. Não é necessário compilar, instalar dependências ou configurar uma chave de API.

Depois da publicação, abra o endereço HTTPS no computador ou smartphone. O layout se adapta à tela. A publicação online deste projeto ainda não foi concluída.

## Como funciona

O programa monta instruções a partir dos campos preenchidos. Ele não faz chamadas à API do ChatGPT e não gera respostas por inteligência artificial.

A biblioteca e a preferência de tema são salvas no armazenamento local do navegador. Não há sincronização entre celulares, computadores ou navegadores. Limpar os dados do navegador pode apagar os prompts salvos. Use **Baixar .txt** para guardar uma cópia dos prompts importantes.

A cópia automática depende das permissões do navegador. Se ela não estiver disponível, selecione o texto e copie manualmente. A fonte do Google Fonts precisa de internet; sem conexão, o navegador usa uma fonte alternativa.

## Edição

Edite os arquivos da pasta `src/` com um editor de texto. O arquivo único é uma cópia independente; alterações na pasta `src/` não atualizam automaticamente `Ideia-em-Prompt.html`.
