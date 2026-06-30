# 🎟️ Ingresso Oficial — 1º Aniversário do Bento ⚽❤️

Convite digital interativo em formato de ingresso premium de futebol, criado para o primeiro aniversário do Bento — torcedor caçula do Internacional.

Um único arquivo HTML, sem dependências externas, sem build, sem instalação. Abre no navegador e já era: experiência completa de "dia de jogo".

![status](https://img.shields.io/badge/status-pronto-success)
![tipo](https://img.shields.io/badge/tipo-single--file-blue)
![tema](https://img.shields.io/badge/time-Internacional-C8102E)

## ✨ A experiência

1. **Ingresso fechado** — tela inicial com fumaça discreta, luzes do estádio pulsando e um convite para "validar" o ingresso.
2. **Catraca virtual** — ao tocar, o código de barras é escaneado, o ingresso é validado e desliza para o lado como se estivesse sendo destacado de verdade.
3. **Entrada no estádio** — as luzes acendem, o placar exibe o nome do aniversariante e a foto do Bento aparece em destaque, como o craque da partida.
4. **Ingresso completo** — todas as informações da festa reveladas com confete, contagem regressiva ao vivo e visual de ingresso premium (QR code, código de barras, setor, portão, textura de papel).
5. **Ações rápidas** — confirmar presença pelo WhatsApp, traçar rota no Google Maps e adicionar o evento ao calendário, tudo em um toque.

A sequência inteira dura entre 8 e 12 segundos, pensada para parecer a abertura de uma grande final.

## 🛠️ Stack

- **HTML5** — estrutura única, sem frameworks
- **CSS3** — animações, gradientes, máscaras e responsividade nativa
- **JavaScript puro (Vanilla JS)** — toda a lógica de interação, sem bibliotecas
- **Web Audio API** — torcida simulada e som de validação, gerados em tempo real (sem arquivos de áudio)
- **SVG inline** — ilustração do estádio, QR code decorativo e código de barras

Tudo embutido em um único arquivo `.html`, incluindo a foto do Bento em base64 — zero requisições externas, zero dependências.

## 🎨 Identidade visual

| Cor | Hex | Uso |
|---|---|---|
| Vermelho Inter | `#C8102E` | Cor principal |
| Vermelho escuro | `#9B0B22` | Gradientes e profundidade |
| Dourado | `#D4AF37` | Detalhes premium |
| Off-white | `#F8F5F0` | Papel do ingresso |

Tipografia: **Oswald**, **Barlow Condensed** e **Roboto**, trazendo a personalidade de ingressos esportivos oficiais.

## 📝 Personalizando para outro evento

Tudo pode ser editado direto no arquivo HTML:

- **Foto** → troque a string base64 da variável `BENTO_IMG` no `<script>` (ou troque o `src` das tags `img` se preferir usar um link de imagem)
- **Data/hora** → edite a constante `target` na função `updateCountdown()` e os campos de data/hora no `info-grid`
- **Local** → altere o texto dentro de `.info-item.full-width`
- **WhatsApp** → atualize o número e a mensagem no link do botão `🎟️ Confirmar presença`
- **Google Maps** → troque o link do botão `📍 Como chegar`
- **Cores do time** → ajuste as variáveis CSS em `:root`

## 📄 Licença

Projeto pessoal e afetivo — sinta-se à vontade para usar como inspiração para o convite do seu próprio pequeno craque. 

---

Com carinho, Dindo Marçal ❤️⚽
