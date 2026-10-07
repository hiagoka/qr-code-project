# QR Code Project

Gerador de QR Code via terminal feito com Node.js. Você digita uma URL e o programa gera a imagem do QR Code e salva o endereço em um arquivo de texto.

## Como funciona

1. O programa pergunta a URL no terminal (usando [inquirer](https://www.npmjs.com/package/inquirer)).
2. Gera o QR Code em PNG (usando [qr-image](https://www.npmjs.com/package/qr-image)) e salva como `qr_img.png`.
3. Salva a URL digitada em `URL.txt`.

## Pré-requisitos

- [Node.js](https://nodejs.org/) 18 ou superior

## Instalação

```bash
git clone https://github.com/hiagoka/qr-code-project.git
cd qr-code-project
npm install
```

## Uso

```bash
node index.js
```

Digite a URL quando solicitado:

```
? Type in your URL:  https://github.com/hiagoka
The file has been saved!
```

Arquivos gerados na pasta do projeto:

| Arquivo      | Conteúdo                      |
|--------------|-------------------------------|
| `qr_img.png` | Imagem do QR Code             |
| `URL.txt`    | URL usada para gerar o código |

## Tecnologias

- Node.js (ES Modules)
- inquirer
- qr-image

## Autor

Hiago Kalil — [@hiagoka](https://github.com/hiagoka)
