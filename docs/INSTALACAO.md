# Instalação e uso

## Antes de começar

O jogo roda no computador com Windows de 64 bits. A configuração utilizada no trabalho foi Windows 10 Home, Intel Core i9-9900, NVIDIA GeForce RTX 3070, 32 GB de RAM e Meta Quest 2 conectado ao PC.

Para jogar com Quest 2, instale o [Meta Quest Link para PC](https://www.meta.com/help/quest/1517439565442928/), conecte o headset por cabo USB ou Air Link e entre no ambiente Link. Confira no aplicativo Meta que o runtime OpenXR ativo é o Meta Quest Link. O jogo utiliza os dois controles Touch.

## Download

1. Abra a [Release v1.0.0](https://github.com/Quafw/campus-unemat-bloco-c/releases/tag/v1.0.0).
2. Baixe `Campus-UNEMAT-Bloco-C-Windows-PCVR-v1.0.0.zip`.
3. Extraia o ZIP inteiro para uma pasta local com permissão de escrita.
4. Com o headset conectado e o Link aberto, execute `Campus UNEMAT Bloco C.exe`.

Mantenha ao lado do executável a pasta `Campus UNEMAT Bloco C_Data`, as DLLs e a pasta `D3D12`. A versão jogável depende desses arquivos.

O pacote inclui as bibliotecas da aplicação. Instale o runtime VR e o driver de vídeo fornecidos pelos fabricantes.

## Interações

Use os analógicos para navegação e orientação. Para teleporte por apontamento, acione o modo de teleporte no analógico direito, aponte para uma superfície válida e solte para confirmar. Os botões laterais de pegada permitem segurar objetos, o celular e as maçanetas; o gatilho frontal aciona as interações disponíveis.

O celular virtual oferece mapa, destinos de teleporte e ajustes da experiência. Os destinos cadastrados são **CTMAT**, **Jardim**, **2º andar** e **Pós-graduação**. O tutorial e o [vídeo de demonstração](https://youtu.be/x7Kz4oLqQ98) mostram as interações em uso.

## Se não iniciar corretamente

- Se a janela abrir no monitor, confira a conexão do headset e o runtime OpenXR ativo. Essa versão foi avaliada com Quest 2 e Meta Quest Link.
- Se aparecer mensagem de dados ausentes, extraia novamente o ZIP inteiro e confira o nome da pasta `_Data`.
- Se o controle de uma interação não responder, consulte o tutorial e teste a pegada pelo botão lateral.
- Para relatar uma falha, descreva o local, a ação realizada e a configuração do PC/headset nas [Issues](https://github.com/Quafw/campus-unemat-bloco-c/issues). Não envie dados de login ou arquivos pessoais.

## Verificar o download

O arquivo `SHA256SUMS.txt` publicado na Release informa o hash do ZIP. No PowerShell, execute:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\Campus-UNEMAT-Bloco-C-Windows-PCVR-v1.0.0.zip'
```

Compare o resultado com o hash publicado. A versão é identificada pela tag `v1.0.0` e pelo manifesto de arquivos em `release/manifest.json`.
