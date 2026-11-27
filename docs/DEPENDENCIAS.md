# Dependências da versão jogável

O ZIP distribui o player Windows PCVR compilado em IL2CPP para x86-64. Os componentes da aplicação estão incluídos na pasta da distribuição.

## Instalados pelo jogador

| Componente | Finalidade |
|---|---|
| Windows de 64 bits | Sistema do computador que executa o jogo |
| Driver de vídeo compatível | Renderização do ambiente tridimensional |
| Meta Quest Link para PC | Conexão com o Quest 2 e runtime OpenXR utilizado na avaliação |
| Meta Quest 2 e controles Touch | Visualização e interação na configuração avaliada |

## Incluídos na distribuição

| Tecnologia | Versão do projeto | Uso |
|---|---|---|
| Unity | 6000.6.7f1 | Player e compilação Windows IL2CPP |
| Universal Render Pipeline | 17.6.0 | Renderização |
| XR Interaction Toolkit | 3.6.1 | Interações e locomoção |
| OpenXR Plugin | 1.18.0 | Integração com o runtime VR |
| Unity OpenXR: Meta | 2.6.1 | Suporte à plataforma Meta via OpenXR |
| XR Plug-in Management | 4.7.0 | Inicialização dos subsistemas XR |
| Input System | 1.20.1 | Entrada dos controles |
| glTFast | 6.20.0 | Importação dos modelos GLB/glTF no desenvolvimento |

O player contém, entre outros, `UnityPlayer.dll`, `GameAssembly.dll`, `openxr_loader.dll` e as bibliotecas de renderização e execução geradas pelo Unity. Elas devem permanecer na estrutura fornecida. As licenças e atribuições pertinentes acompanham o ZIP em `ThirdPartyNotices/`.
