# gnome-layout-switcher

Ferramenta gráfica (GTK) para alternar o layout do GNOME Shell entre configurações pré-definidas, como estilos tradicional, estilo Windows, estilo macOS, entre outros, ativando as extensões e os temas correspondentes de uma só vez, sem precisar ajustar cada um manualmente.

## Sobre este repositório

Este repositório redistribui o pacote **gnome-layout-switcher 0.8.40-2** (`any`), originalmente mantido pelo projeto **Manjaro Linux** e publicado no repositório `stable/extra`. O objetivo é facilitar o acesso ao pacote por usuários de Arch Linux e derivados que não usam os repositórios do Manjaro.

- Projeto original: https://gitlab.manjaro.org/Chrysostomus/gnome-layout-switcher
- Inspirado no [gnome-layout-manager](https://github.com/vmavromatis/gnome-layout-manager)
- Pacote de origem: [`gnome-layout-switcher-0.8.40-2-any.pkg.tar.zst`](https://linorg.usp.br/manjaro/stable/extra/x86_64/gnome-layout-switcher-0.8.40-2-any.pkg.tar.zst)

> **Aviso:** não sou o autor da ferramenta. Todo o crédito pelo desenvolvimento é da equipe do Manjaro e dos colaboradores do projeto original.

## Recursos

- Troca rápida entre layouts pré-configurados do GNOME Shell
- Gerenciamento de extensões e temas em conjunto com o layout
- Interface gráfica simples

## Instalação

Baixe o pacote na página de [Releases](https://github.com/elppans/gnome-layout-switcher/releases) e instale com:

```bash
sudo pacman -U gnome-layout-switcher-0.8.40-2-any.pkg.tar.zst
```

## Dependências e observações

- A ferramenta depende bastante de pacotes do Manjaro. Sem eles, algumas funções (como o alternador de branding do Manjaro) podem não funcionar fora dessa distro.
- A parte de layouts funciona em outras distros se as extensões necessárias estiverem instaladas manualmente. Instale as **dependências opcionais** do pacote, pois sem elas o layout pode não ser aplicado.
- <Informe aqui eventuais ajustes ou patches que você aplicou, se houver>

## Licença

Consulte a licença do projeto original no repositório do Manjaro. <Confirme o tipo de licença antes de publicar>
