# Navegação imersiva no campus da UNEMAT

O projeto representa o Bloco C do Campus Universitário de Barra do Bugres em um ambiente de realidade virtual. A visita permite conhecer as instalações e consultar informações sobre os cursos e as atividades da universidade.

## Autoria

Matheus Gomes de Souza Alves, do curso de Ciência da Computação da Universidade do Estado de Mato Grosso (UNEMAT), desenvolveu o projeto sob orientação do Prof. Dr. Leo Manoel Lopes da Silva Garcia.

[ORCID do autor](https://orcid.org/0009-0006-8683-8462).

## Desenvolvimento

A modelagem do campus foi realizada no Blender e integrada ao Unity 6000.6.7f1. O ambiente usa Universal Render Pipeline 17.6.0, XR Interaction Toolkit 3.6.1, OpenXR 1.18.0 e Input System 1.20.1. Os modelos GLB/glTF foram importados com glTFast 6.20.0.

O computador executa a aplicação Windows PCVR e envia a imagem ao Meta Quest 2 pelo Quest Link. Os controles Touch movimentam as mãos virtuais e permitem apontar, selecionar e segurar objetos.

## Visita e interações

O visitante pode caminhar pelo campus ou usar o teleporte para percorrer áreas externas e interiores. O celular virtual reúne o mapa e os destinos CTMAT, Jardim, 2º andar e Pós-graduação. Seus ajustes permitem regular a altura, recentralizar a visão e escolher o lado de guarda do aparelho.

As portas acessíveis abrem pela maçaneta. Nas salas, o visitante pode sentar, manipular objetos e escrever nos quadros. Os banheiros possuem espelhos com reflexão em tempo real. O tutorial de gestos orienta as interações por proximidade.

Os expositores apresentam a história do campus, os cursos e as pesquisas da UNEMAT. O conteúdo informativo reúne oito expositores e 39 páginas. A visita também inclui vídeo e painéis de boas-vindas.

[Assista à demonstração](https://youtu.be/x7Kz4oLqQ98).

## Desempenho

A medição durou 179,97 segundos e reuniu 18.909 registros dos contadores do runtime Meta/Oculus PC. O teste ocorreu após aquecimento, com a seguinte configuração:

| Componente | Configuração |
|---|---|
| Processador | Intel Core i9-9900 |
| Placa de vídeo | NVIDIA GeForce RTX 3070 |
| Memória RAM | 32 GB |
| Sistema operacional | Windows 10 Home |
| Headset | Meta Quest 2, conectado por Quest Link |
| Frequência do headset | 120 Hz |
| Resolução indicada no Link | 3.200 × 1.632 pixels, modo automático, escala 1,0× |

| Medida | Resultado |
|---|---:|
| FPS médio da aplicação | 119,70 FPS |
| FPS médio do compositor | 119,72 FPS |
| Tempo médio de CPU nas amostras | 3,68 ms |
| Tempo médio de GPU nas amostras | 4,41 ms |
| Quadros perdidos pela aplicação | 18 |
| Quadros perdidos pelo compositor | 0 |

[Baixar a versão medida](https://github.com/Quafw/campus-unemat-bloco-c/releases/download/v1.0.0/Campus-UNEMAT-Bloco-C-Windows-PCVR-v1.0.0.zip) · [Dados da coleta](https://github.com/Quafw/campus-unemat-bloco-c/releases/download/v1.0.0/pcvr-samples.csv)

## Artigo

ALVES, Matheus Gomes de Souza. *Desenvolvimento de navegação imersiva no Campus Universitário de Barra do Bugres por meio de realidade virtual*. 2026.

A referência do software está em [CITATION.cff](../CITATION.cff).
