![SPRINGTRAP](https://raw.githubusercontent.com/vvoaudio/springtrap-releases/main/media/springtrap-full-ui.png)

🇧🇷 **Português** · [🇬🇧 English (abaixo / below)](#english)

# SPRINGTRAP

**Um reverb de mola (spring) com estágio de drive, da VVO Audio.** Gratuito. VST3 para macOS e Windows.

**[⬇ Baixar a versão mais recente](https://github.com/vvoaudio/springtrap-releases/releases/latest)**

| | macOS | Windows |
|---|---|---|
| Arquivo | `SPRINGTRAP-<versão>-macOS-Universal.pkg` | `SPRINGTRAP-<versão>-Windows-Setup.exe` |
| Requisitos | macOS 11 Big Sur ou superior | Windows 10 ou superior · 64 bits |
| Macs | Apple Silicon (M1 em diante) ou Intel | — |
| Formato | VST3 | VST3 |
| Instala em | `/Library/Audio/Plug-Ins/VST3/` | `C:\Program Files\Common Files\VST3\` |

![O tanque de mola](https://raw.githubusercontent.com/vvoaudio/springtrap-releases/main/media/springtrap-spring.png)

## Instalação no Mac
1. Baixe o `.pkg` na [versão mais recente](https://github.com/vvoaudio/springtrap-releases/releases/latest) e dê um duplo clique.
2. O macOS vai avisar que não consegue verificar o desenvolvedor (o SPRINGTRAP é gratuito e não é registrado na Apple). Clique em **Concluído** (*Done*), abra **Ajustes do Sistema → Privacidade e Segurança** (*System Settings → Privacy & Security*), role até o fim e clique em **Abrir Mesmo Assim** (*Open Anyway*) ao lado da mensagem do SPRINGTRAP. Confirme com a sua senha.
3. Avance pelo instalador (ele pede a senha de administrador).
4. Reinicie a sua DAW ou faça um novo scan de plug-ins, e carregue o **SPRINGTRAP** entre os seus plug-ins VST3.

## Instalação no Windows
1. Baixe o `.exe` na [versão mais recente](https://github.com/vvoaudio/springtrap-releases/releases/latest) e execute-o.
2. Se o Windows mostrar **"O Windows protegeu seu computador"** (*Windows protected your PC*), clique em **Mais informações → Executar assim mesmo** (*More info → Run anyway*). O SPRINGTRAP é gratuito e não tem assinatura de código.
3. Avance pelo instalador (ele pede permissão de administrador).
4. Reinicie a sua DAW ou faça um novo scan de plug-ins, e carregue o **SPRINGTRAP** entre os seus plug-ins VST3.

## Atualização
Feche a sua DAW e execute o novo instalador da mesma forma. Ele substitui a versão anterior (inclusive uma cópia antiga na sua própria pasta de plug-ins) e mantém os seus presets e projetos.

### Aviso de atualização
Uma vez por dia o SPRINGTRAP pergunta ao GitHub qual é a versão mais recente (uma única requisição a `api.github.com`; nada mais é enviado). Se existir uma versão nova, aparece um botão **UPDATE AVAILABLE!** na barra superior. Clique nele: o instalador do seu sistema é baixado, conferido com o checksum SHA-256 publicado e aberto. Feche a sua DAW e conclua o instalador. Nada é instalado sem você.
Para desligar a verificação, clique com o botão direito no botão e escolha **Turn off update checks** (ou crie um arquivo vazio chamado `update-checks-off` em `~/Library/Application Support/SPRINGTRAP/` no Mac, ou `%APPDATA%\SPRINGTRAP\` no Windows). Apague esse arquivo para ligar de novo.

![Controles](https://raw.githubusercontent.com/vvoaudio/springtrap-releases/main/media/springtrap-knobs.png)

## Guia rápido
Os nomes dos parâmetros ficam em inglês, exatamente como aparecem no plug-in.

- **Decay** — por quanto tempo a mola continua soando, do curto ao longo.
- **Drive** — distorção/saturação: empurra o sinal da mola para um estágio de amplificador (só o reverb; o seu sinal seco, dry, continua limpo).
- **Pre Delay** — o tempo de espera antes de a mola começar (0–80 ms).
- **Input Gain / Output Gain** — nível de entrada na mola e nível de saída (±18 dB). O som reage ao nível de entrada, como em um equipamento de verdade.
- **Lowpass / Highpass** — cortam os agudos ou os graves apenas da mola.
- **Modulate** — uma oscilação lenta que dá vida ao som da mola. **HiFi** — um timbre de mola mais brilhante e limpo.
- **Mix** — equilíbrio entre o sinal seco e o molhado (dry/wet).
- **Presets, Save, Load, Undo, Redo, Bypass** — na barra superior. Passe o mouse ou gire qualquer knob para ver o valor exato; duplo clique volta ao padrão, Shift dá ajuste fino.

## Desinstalação
- **Mac:** apague `/Library/Audio/Plug-Ins/VST3/SPRINGTRAP.vst3`.
- **Windows:** Configurações → Aplicativos → **SPRINGTRAP (VST3)** → Desinstalar.

Os presets ficam em `~/Library/Application Support/SPRINGTRAP/Presets` (Mac) ou `%APPDATA%\SPRINGTRAP\Presets` (Windows).

---
O SPRINGTRAP é gratuito para uso pessoal e fornecido no estado em que se encontra, sem garantia. VST é uma marca registrada da Steinberg Media Technologies GmbH.
A fonte da interface é a Nunito (SIL Open Font License).

---

<a id="english"></a>

# English

# SPRINGTRAP

**A spring-tank reverb with a drive stage, by VVO Audio.** Free. VST3 for macOS and Windows.

**[⬇ Download the latest version](https://github.com/vvoaudio/springtrap-releases/releases/latest)**

| | macOS | Windows |
|---|---|---|
| File | `SPRINGTRAP-<version>-macOS-Universal.pkg` | `SPRINGTRAP-<version>-Windows-Setup.exe` |
| Needs | macOS 11 Big Sur or later | Windows 10 or later · 64-bit |
| Macs | Apple Silicon (M1 and later) or Intel | — |
| Format | VST3 | VST3 |
| Installs to | `/Library/Audio/Plug-Ins/VST3/` | `C:\Program Files\Common Files\VST3\` |

## Install on Mac
1. Download the `.pkg` from the [latest release](https://github.com/vvoaudio/springtrap-releases/releases/latest) and double-click it.
2. macOS will say it can't verify the developer (SPRINGTRAP is free and not registered with Apple). Click **Done**, then open **System Settings → Privacy & Security**, scroll down and click **Open Anyway** next to the SPRINGTRAP message. Confirm with your password.
3. Click through the installer (it asks for your administrator password).
4. Restart your DAW or rescan plug-ins, and load **SPRINGTRAP** from your VST3 plug-ins.

## Install on Windows
1. Download the `.exe` from the [latest release](https://github.com/vvoaudio/springtrap-releases/releases/latest) and run it.
2. If Windows shows **"Windows protected your PC"**, click **More info → Run anyway** (SPRINGTRAP is free and not code-signed).
3. Click through the installer (it asks for administrator permission).
4. Restart your DAW or rescan plug-ins, and load **SPRINGTRAP** from your VST3 plug-ins.

## Updating
Quit your DAW, then run the new installer the same way. It replaces the old version (including any older copy in your own plug-in folder) and keeps your presets and projects.

### Update notice
Once a day SPRINGTRAP asks GitHub which version is the latest (one request to `api.github.com`; nothing else is sent). If a newer one exists, an **UPDATE AVAILABLE!** button appears in the top bar. Click it: the installer for your system is downloaded, checked against the published SHA-256 checksum and opened. Quit your DAW and finish the installer. Nothing is installed without you.
To turn the check off, right-click the button and choose **Turn off update checks** (or create an empty file named `update-checks-off` in `~/Library/Application Support/SPRINGTRAP/` on Mac, `%APPDATA%\SPRINGTRAP\` on Windows). Delete that file to turn it back on.

## Quick guide
- **Decay** — how long the spring keeps ringing, from short to long.
- **Drive** — grit: pushes the spring signal into an amp stage (reverb only, your dry signal stays clean).
- **Pre Delay** — the wait before the spring starts (0–80 ms).
- **Input Gain / Output Gain** — level into the spring and level out (±18 dB). The sound reacts to the input level, like real hardware.
- **Lowpass / Highpass** — cut highs or lows of the spring only.
- **Modulate** — a slow wobble that makes the spring sound alive. **HiFi** — a brighter, cleaner spring tone.
- **Mix** — dry/wet balance.
- **Presets, Save, Load, Undo, Redo, Bypass** — in the top bar. Hover or turn any knob to read its exact value; double-click resets it, Shift gives fine control.

## Uninstall
- **Mac:** delete `/Library/Audio/Plug-Ins/VST3/SPRINGTRAP.vst3`.
- **Windows:** Settings → Apps → **SPRINGTRAP (VST3)** → Uninstall.

Presets live in `~/Library/Application Support/SPRINGTRAP/Presets` (Mac) or `%APPDATA%\SPRINGTRAP\Presets` (Windows).

---
SPRINGTRAP is free for personal use and provided as is, without warranty. VST is a trademark of Steinberg Media Technologies GmbH.
The interface font is Nunito (SIL Open Font License).
