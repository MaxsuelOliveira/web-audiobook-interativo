# AudioBook Interativo

![Status](https://img.shields.io/badge/status-publicavel-brightgreen)
![Stack](https://img.shields.io/badge/stack-Web%20estatico-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Descricao

Player de audiobooks em JavaScript puro com busca na biblioteca LibriVox via Internet Archive, player HTML5, lista de episodios e persistencia local de progresso.

## Demonstracao Visual

| Desktop | Mobile |
| --- | --- |
| ![Captura desktop](docs/screenshots/desktop.png) | ![Captura mobile](docs/screenshots/mobile.png) |

## Funcionalidades

- Busca de audiobooks por titulo
- Carregamento dinamico de capas e metadados via Archive.org
- Player HTML5 com play, pause, avancar, voltar, repetir e embaralhar
- Lista de episodios com selecao individual
- Persistencia de volume e progresso no localStorage
- Layout responsivo para desktop e mobile

## Tecnologias

- HTML5
- CSS3
- JavaScript ES Modules
- Internet Archive API
- localStorage

## Estrutura

- `.gitignore`
- `README.md`
- `docs/`
- `index.html`
- `js/`
- `styles/`

## Requisitos

- Navegador moderno
- Servidor HTTP local para ES Modules

## Instalacao

- Nao ha dependencias para instalar.

## Variaveis de Ambiente

- Nao utiliza variaveis de ambiente.

## Comandos Disponiveis

| Acao | Comando |
| --- | --- |
| Executar | `python -m http.server 4173` |

## Execucao

Acesse http://127.0.0.1:4173/ apos iniciar um servidor estatico na pasta do projeto.

## Build

Nao possui etapa de build.

## Observacoes

- O projeto depende de conectividade com archive.org para buscar catalogo, capas e arquivos de audio.
- Por usar ES Modules, prefira HTTP local em vez de abrir o arquivo diretamente com file://.

## Autor

Maxsuel Oliveira

## Licenca

Este projeto esta licenciado sob a licenca MIT.
