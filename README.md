# Mining Assistant by Vorxen — Downloads

Overlay para **Star Citizen** que lê o número **RS (radar signature)** do scanner de mineração na sua tela e mostra qual minério provavelmente é, inclusive **quantas rochas** há no cluster.

> Só os downloads ficam aqui. O código-fonte é privado.

## ⬇ Baixar

**[MiningAssistant.zip — última versão](https://github.com/VorxenSC/MiningAssistant/releases/latest/download/MiningAssistant.zip)** (Windows 10/11 64-bit, portátil, não precisa instalar nada)

## Primeiro uso

1. **Extraia** o zip numa pasta sua (por exemplo `Documentos\MiningAssistant`) e abra `MiningAssistant.exe`.
   O Windows pode mostrar *"o Windows protegeu o computador"*: o app não tem assinatura digital paga. Clique em **Mais informações → Executar assim mesmo**. Outra opção: antes de extrair, clique com o botão direito no zip → *Propriedades* → marque **Desbloquear**.
2. **Ative.** Na tela de ativação, clique em **Copy name + code** e mande o texto para o **Vorxen** no Discord. Você recebe uma key; digite seu nome e a key e clique em **ACTIVATE**. A key vale só para o seu nome **neste PC** (se reinstalar o Windows, peça outra).
3. **Prepare o jogo:**
   - Window Mode **Borderless** ou **Windowed** (Fullscreen exclusivo esconde a imagem de outros programas);
   - resolução **1920×1080 ou maior**;
   - cores originais do HUD (desligue filtros NVIDIA/AMD/ReShade; se a leitura falhar com HDR ligado, teste sem HDR);
   - **não** rode o Star Citizen/RSI Launcher como administrador (senão os atalhos não funcionam dentro do jogo).
4. Clique em **START** e troque para o jogo durante a contagem de 5 segundos. Faça o ping do scanner: quando a placa âmbar com o RS aparecer, o overlay mostra o minério.

## Atualizações automáticas

A partir da **v0.1.9** o app pode se atualizar sozinho. Na primeira vez ele pergunta; se você aceitar, ele procura versões novas aqui ao abrir e a cada 6 horas, baixa só com a leitura parada e instala na próxima vez que você abrir o app. Cada atualização é **assinada digitalmente** pelo Vorxen e conferida antes de instalar. Desligar: *Functions → Automatic updates*. Atualizar na hora: *Advanced settings → Check for updates* e depois *Install update now*.

Quem tem a v0.1.8 ou anterior precisa baixar a versão nova **à mão uma única vez**.

## Atalhos

| Tecla | Ação |
|---|---|
| **Page Up** | mostrar/esconder o overlay |
| **Page Down** | mover o overlay (aperte de novo para travar) |
| **/** | salvar um *debug snapshot* deste instante |

## Algo não funciona?

- No painel: **Advanced settings → Run self-test**. O relatório diz o que falta.
- Se o código RS está na tela mas não é lido, aperte **/** nesse momento. Isso salva uma pasta em `debug_snapshots\`. Compacte essa pasta e mande para o Vorxen: é o que mais ajuda a melhorar a leitura, principalmente em 1080p.

## Assinatura desconhecida? Compartilhe

Quando aparecer um RS que o app não conhece, ele pergunta o que é e guarda **só no seu PC**. Para ajudar os outros jogadores, no painel: **Advanced settings →**
- **Share on Discord (copy)**: copia um texto pronto para colar no Discord;
- **Share on GitHub…**: abre no navegador um *issue* já preenchido neste repositório (precisa de conta no GitHub).

O app nunca envia nada sozinho: só vai o que você digitou, quando você clica.

## Segurança

O app é **totalmente externo** ao Star Citizen: só lê a imagem que já está na sua tela (como um print). Ele **não** injeta DLL, **não** lê nem altera a memória do jogo, **não** mexe em arquivos do jogo, **não** intercepta a rede, **não** envia teclas ou cliques ao jogo e **não** envia nenhum dado seu. A única conexão de rede é a de atualizações automáticas (se você aceitar), que só baixa os arquivos públicos deste repositório. O OCR (leitura do número) é feito pelo próprio Windows, no seu PC.

Ainda assim, só a CIG pode dizer como aplica as regras dela a ferramentas de terceiros. Use por sua conta.

---

**English (short).** Windows overlay for Star Citizen mining: reads the RS number on your screen (local OCR, fully external — no injection, no memory reading, no input automation, no network) and shows the ore and rock count. Download the zip above, extract, run, send your name + PC code (button *Copy name + code*) to Vorxen to get a key. Game in Borderless/Windowed, 1080p or higher. Hotkeys: Page Up overlay, Page Down move, / debug snapshot.

*Projeto de comunidade, sem afiliação com a Cloud Imperium Games. Star Citizen® é marca da CIG.*
