# Downloads oficiais do WoWHelp

Este repositório distribui os instaladores do **WoWHelp Cliente para Windows x64**. O código de desenvolvimento fica em repositórios privados.

## Download

[Baixar WoWHelp Cliente para Windows](https://github.com/wowhelpbr/wowhelp-downloads/releases/latest/download/WoWHelp-Cliente-Setup.exe)

O instalador configura o cliente Windows. Entre com sua conta WoWHelp, escolha sua instalação de World of Warcraft Retail e selecione Companion, Guide ou ambos. Atualizações dos addons são independentes das atualizações do cliente.

Ao minimizar ou fechar pelo X, o cliente permanece na bandeja do Windows por padrão. Clique no ícone para reabrir; para encerrar, use **Sair do WoWHelp** no menu do ícone. O Windows pode colocar o ícone na área de ícones ocultos, acessível pela seta ao lado do relógio.

## Verificação

Cada release inclui `SHA256SUMS.txt`. No PowerShell, confira o arquivo baixado com:

```powershell
Get-FileHash .\WoWHelp-Cliente-Setup.exe -Algorithm SHA256
```

O cliente está em desenvolvimento e o instalador ainda não tem assinatura digital de editor. A versão atual instala addons Retail; os demais tipos de jogo serão adicionados quando houver pacotes compatíveis.

Site: [wowhelp.com.br](https://wowhelp.com.br)
