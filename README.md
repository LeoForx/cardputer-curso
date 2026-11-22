# M5Stack Cardputer-ADV — Curso Completo

Curso completo e ilustrado para o **M5Stack Cardputer-ADV** em **Arduino C/C++**, do zero ao nível avançado.
Entregue como dois arquivos HTML auto-contidos — funciona offline, sem dependências externas.

---

## O que é o Cardputer-ADV?

O **M5Stack Cardputer-ADV** é um mini computador programável que cabe no bolso.

Pense nele como um **smartphone sem tela de toque** — tem teclado físico, tela colorida, WiFi, Bluetooth e bateria. A diferença é que você programa ele do zero para fazer o que quiser.

**O que você consegue fazer com ele:**

🌐 **Conectar na internet** — busca informações em sites e APIs. Por exemplo: mostrar a previsão do tempo, cotação do dólar ou qualquer dado em tempo real na telinha.

📡 **Virar um controle remoto** — tem um emissor infravermelho embutido. Você programa ele para ligar/desligar sua TV, ar-condicionado ou qualquer aparelho que use controle remoto.

⌨️ **Digitar no computador sem fio** — via Bluetooth ele se conecta ao seu PC ou celular e funciona como um teclado — você digita no Cardputer e o texto aparece no computador.

💬 **Enviar dados para a nuvem** — manda informações para plataformas IoT como Node-RED, Home Assistant ou qualquer dashboard. Útil para monitorar sensores, temperatura, etc.

🔍 **Explorar redes WiFi** — varre as redes ao redor e mostra nome, sinal e canal de cada uma — como um scanner de rede portátil.

🗂️ **Salvar arquivos** — armazena configurações, histórico ou qualquer dado diretamente na memória interna.

⚡ **Durar dias na bateria** — entra em modo de economia profunda quando não está em uso e acorda sozinho no horário programado.

> É como ter um canivete suíço digital — compacto, programável e conectado. Você decide o que ele faz.

---

## Acesso rápido

| Arquivo | Descrição | Link |
|--------|-----------|------|
| `curso-cardputer.html` | Curso interativo (dark theme, sidebar, progresso) | [Abrir](https://leoforx.github.io/cardputer-curso/curso-cardputer.html) |
| `curso-cardputer-pdf.html` | Versão print-ready para gerar PDF via Ctrl+P | [Abrir](https://leoforx.github.io/cardputer-curso/curso-cardputer-pdf.html) |

---

## O que está incluído

- **24 módulos** em 3 fases (Iniciante, Intermediário, Avançado)
- **3 projetos práticos** (Calculadora, Terminal WiFi, Swiss Army Knife)
- **21 exercícios** com botão "Ver solução" em cada módulo
- **⚡ Gerador de Código** — descreva o projeto em português e receba um sketch Arduino completo
- Syntax highlight, navegação por teclado (← →), progresso salvo em `localStorage`

---

## Estrutura do curso

### Fase 1 — Iniciante (~6h)
| # | Módulo |
|---|--------|
| M1 | Conhecendo o Hardware |
| M2 | Configurando o Ambiente |
| M3 | Hello World no Display |
| M4 | Display Avançado |
| M5 | Lendo o Teclado |
| M6 | LED e Som |
| M7 | Bateria e Energia |
| P1 | **Projeto: Calculadora** |

### Fase 2 — Intermediário (~8h)
| # | Módulo |
|---|--------|
| M9  | WiFi Básico |
| M10 | HTTP e APIs REST |
| M11 | MQTT e IoT |
| M12 | Infravermelho (IR) |
| M13 | Armazenamento (SPIFFS) |
| M14 | Display UI Avançada |
| M15 | Deep Sleep e Otimização |
| P2  | **Projeto: Terminal WiFi** |

### Fase 3 — Avançado (~10h)
| # | Módulo |
|---|--------|
| M17 | BLE e Bluetooth |
| M18 | Scanner WiFi Avançado |
| M19 | IR Blaster Universal |
| M20 | OTA Updates |
| M21 | Criptografia e TLS |
| M22 | Microfone e Áudio |
| M23 | FreeRTOS e Multitask |
| P3  | **Projeto Final: Swiss Army Knife** |

---

## Hardware

**M5Stack Cardputer-ADV**

| Componente | Especificação |
|-----------|---------------|
| MCU | ESP32-S3FN8 — Dual-core Xtensa LX7 @ 240 MHz |
| Memória | 8 MB PSRAM + 8 MB Flash |
| Display | ST7789V2 TFT 1.14" — 135 × 240 px (SPI) |
| Teclado | 56 teclas QWERTY |
| Áudio | Speaker 1 W + Microfone PDM SPM1423 |
| Wireless | WiFi 802.11 b/g/n + BLE 5.0 |
| IR | Emissor 940 nm — GPIO 44 |
| Bateria | 120 mAh interna + slot para externa até 2000 mAh |
| USB | USB-C com CH9102F |

---

## Tecnologias

- **Linguagem:** Arduino C/C++
- **Bibliotecas:** `M5Cardputer.h` / `M5Unified`
- **IDE:** Arduino IDE 2.x
- **HTML:** puro, sem frameworks — funciona offline

---

## Como editar e publicar

```bash
# Clonar
git clone https://github.com/LeoForx/cardputer-curso.git
cd cardputer-curso

# Editar os arquivos HTML localmente
# ...

# Publicar
git add .
git commit -m "feat: ..."
git push
```

O GitHub Pages atualiza automaticamente em ~30 segundos após o push.

---

## Gerador de Código

A aba **⚡ Gerador de Código** (sidebar → Extras) permite descrever em português o que o projeto deve fazer e recebe um sketch Arduino completo gerado automaticamente.

Palavras-chave reconhecidas: `display`, `teclado`, `wifi`, `http`, `api`, `json`, `mqtt`, `iot`, `IR`, `infravermelho`, `bluetooth`, `BLE`, `bateria`, `sleep`, `LED`, `som`, `beep`, `menu`, `contador`, `timer`, `serial`, `sensor`...

---

## Licença

MIT — livre para usar, modificar e distribuir.
