# Consulta de pontos — Energisa Paraíba

Página simples para localizar pontos registrados em arquivos KML ou KMZ e abrir suas coordenadas no Google Maps.

## Como usar

1. Abra `index.html` no Google Chrome. No celular, abra o arquivo HTML pelo navegador.
2. Toque ou clique em **Carregar KML/KMZ** e selecione um ou mais arquivos.
3. Aguarde a mensagem informando quantos pontos foram carregados.
4. Digite o código do ponto na caixa **Código do ponto**. A busca encontra o código dentro do nome do ponto e aceita também parte do nome.
5. Selecione o resultado desejado. O Google Maps será aberto em outra aba na localização do ponto.

## Compartilhar com colegas

Envie apenas o arquivo `index.html`. A logo e a biblioteca usada para ler KMZ já estão incorporadas nele. Quem receber o arquivo poderá abrir no Chrome e carregar seus próprios arquivos KML/KMZ.

Os pontos carregados ficam na memória da página durante aquela sessão. Se a página for fechada ou recarregada, será necessário carregar os arquivos novamente. A página lê os arquivos no próprio navegador; é necessária uma conexão com a internet para abrir o Google Maps.

## Formatos aceitos

- **KML:** pontos (`Placemark`) com nome e coordenadas de `Point`.
- **KMZ:** arquivo compactado que contenha um arquivo KML.
- É possível selecionar vários arquivos de uma vez.
- A busca não diferencia maiúsculas de minúsculas e procura correspondências parciais.
- São exibidos até 50 resultados por busca. Digite mais caracteres para restringir a lista.

Para encontrar um ponto pelo código, o código precisa estar no nome (`name`) do ponto no KML. Os resultados mostram o nome, as coordenadas e o arquivo de origem.

## Se algo não funcionar

- **Nenhum ponto carregado:** confira se o KML contém pontos com coordenadas válidas ou se o KMZ contém um arquivo KML.
- **Nenhum resultado:** confirme se o código está no nome do ponto e tente pesquisar apenas parte dele.
- **Google Maps não abriu:** verifique a conexão com a internet e tente selecionar o resultado novamente.
