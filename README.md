# alfa-printer-release

Instaladores do Alfa Printer. Este repositório só guarda as Releases; o código está em `bruno-delfim/alfa-printer`.

O app instalado lê as Releases daqui para se atualizar sozinho, por isso o repositório é público: assim nenhuma máquina de cliente precisa de token do GitHub.

As Releases são criadas automaticamente a cada commit na `main` do `bruno-delfim/alfa-printer` (GitHub Actions + `electron-builder`). Não suba arquivos na mão nem apague `latest.yml` de uma Release publicada, senão o auto-update quebra.

## Instalar

Baixe o instalador mais recente: [Alfa-Printer-Setup.exe](https://github.com/bruno-delfim/alfa-printer-release/releases/latest/download/Alfa-Printer-Setup.exe) e execute.
