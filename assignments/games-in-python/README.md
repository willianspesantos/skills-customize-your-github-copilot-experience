
# 🎮 Hangman Game Challenge

Build the classic word-guessing game using Python strings, loops, and user input.

## � What You'll Build

Create a Hangman game where players guess letters to reveal a hidden word before running out of attempts.

**Skills practiced:** String manipulation, loops, conditionals, random selection

## ✅ Must Have's

Your game must:
- Randomly select words from a predefined list
- Accept letter guesses and show current progress (_ _ _ format)
- Track incorrect guesses remaining
- End when word is guessed or attempts exhausted
- Display win/lose messages

```markdown
# 📘 Assignment: Hangman (Games in Python)

## 🎯 Objetivo

Construir uma versão do jogo Hangman (Forca) em Python para praticar manipulação de strings, estruturas de repetição, condicionais e entrada do usuário.

## 🎒 Nível e Duração

- **Nível:** Intermediário (iniciante com experiência básica em Python)
- **Estimativa:** 1–2 horas

## 📝 Tarefas

### 🛠️ Implementar o jogo Hangman

#### Descrição
Implemente um jogo de Forca que selecione uma palavra aleatória de uma lista, solicite palpites de letras ao jogador e exiba o estado atual da palavra (ex.: `h _ n g m a n`). O jogo deve encerrar quando o jogador adivinhar a palavra inteira ou quando ficar sem tentativas.

#### Requisitos
O programa completo deve:

- Selecionar aleatoriamente uma palavra de uma lista interna ou de um arquivo simples
- Aceitar palpites de letras do usuário e exibir o progresso atual da palavra
- Mostrar as letras já testadas e o número de tentativas restantes
- Encerrar com mensagens de vitória ou derrota apropriadas
- Tratar entradas inválidas (ex.: mais de uma letra, caracteres não alfabéticos)

## 📁 Arquivos fornecidos

- Starter code: [assignments/games-in-python/starter-code.py](assignments/games-in-python/starter-code.py#L1)

> Use o `starter-code.py` como ponto de partida — ele contém esqueleto e exemplos de leitura/execução.

## ▶️ Como executar

Execute com Python 3 no terminal:

```bash
python3 assignments/games-in-python/starter-code.py
```

Ou, se implementar o jogo em outro arquivo `hangman.py`:

```bash
python3 assignments/games-in-python/hangman.py
```

## ✅ Critérios de Avaliação

- O jogo funciona conforme os requisitos listados
- Entrada e saída são claras e amigáveis ao usuário
- Código organizado, com funções separadas quando apropriado
- Tratamento básico de erros e validação de entrada

## ✨ Exercícios de Extensão (Opcional)

- Carregar palavras de um arquivo CSV/JSON
- Permitir diferentes níveis de dificuldade (palavras maiores, menos tentativas)
- Implementar uma versão com interface gráfica simples (Tkinter)
- Salvar histórico de pontuações em um arquivo

## Referências e Dicas

- Use o módulo `random.choice()` para escolher palavras
- Mantenha a lógica de exibição separada da lógica de jogo para facilitar testes

---

Boa sorte — divirta-se codando e praticando lógica!

```
