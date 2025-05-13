🤔# Adivinhe o Número Secreto

Um jogo web simples em que o usuário tenta adivinhar um número aleatório entre 1 e 10. Desenvolvido como projeto inicial do curso da Alura.

---

## 📖 Descrição

- Ao carregar a página, o jogo exibe um título e pede para você “Escolher um número entre 1 e 10”.  
- Você digita seu palpite e clica em **“Chutar”**.  
- O script compara seu chute com o número secreto e:
  - Se acertar, mostra quantas tentativas você levou e habilita o botão **“Novo jogo”**.
  - Se errar, informa se o número secreto é **maior** ou **menor** e incrementa o contador de tentativas.  
- O jogo usa a [ResponsiveVoice](https://responsivevoice.org/) para ler as mensagens em voz alta.

---

## 🚀 Tecnologias

## 🚀 Tecnologias

- **JavaScript** — lógica do jogo  
- **HTML** — estrutura da página  
- **CSS** — estilos e layout

---

## 🗂️ Estrutura do Projeto

projeto_inicial-Alura/
├── img/ ← Imagens de fundo, ícones e pessoa ilustrada
│ ├── code.png
│ ├── Ruido.png
│ ├── ia.png
│ └── JS Game_files/ ← assets gerados pelo navegador
├── index.html ← Marcações da página principal
├── style.css ← Estilos (gradiente, responsividade, botões etc.)
└── app.js ← Lógica do jogo (geração de número, tratamento de chute, TTS)
