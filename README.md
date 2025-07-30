# 🧮 Calculadora com Interface Gráfica (Python + Tkinter)

Este projeto é uma **calculadora com interface gráfica** desenvolvida em **Python**, utilizando a biblioteca `Tkinter`. Ela permite realizar operações matemáticas básicas como **adição, subtração, multiplicação, divisão** e cálculo de porcentagem.

---

## 🖥️ Interface

A interface da calculadora foi construída usando **Frames**, **Labels** e **Buttons** do Tkinter, com um layout organizado para simular o visual de uma calculadora real.

---

## ⚙️ Funcionalidades

- Operações básicas: `+`, `-`, `*`, `/`, `%`
- Botão "C" para limpar a tela
- Botão "=" para calcular o resultado
- Exibição do valor em tempo real
- Interface responsiva e estilizada com cores

---

## 📦 Requisitos

- Python 3.x (recomendado)
- Tkinter (já vem incluso com a instalação padrão do Python)

---

## ▶️ Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/alissondev-btu/calculadora
   cd calculadora-python-tkinter
Execute o arquivo:

bash
Copiar
Editar
python calculadora.py
📁 Estrutura do Código
🎨 Cores utilizadas
python
Copiar
Editar
cor1 = '#1e1f1e' # fundo da janela
cor2 = '#feffff' # branco (texto)
cor3 = '#38576b' # azul escuro (display)
cor4 = '#ECEFF1' # cinza claro (botões)
cor5 = '#FFAB40' # laranja (botões de operações)
🧠 Lógica principal
entrar_valores(event)
Adiciona o número ou operador pressionado ao visor da calculadora.

calcular()
Avalia a expressão digitada e exibe o resultado usando eval().

limpar_tela()
Limpa todos os valores do visor e reinicia a variável de controle.

📱 Layout
Frame superior: display da calculadora com Label.

Frame inferior: botões organizados com place() manualmente para maior controle visual.

🚧 Melhorias futuras
Suporte a teclas do teclado

Operações mais complexas (potência, raiz quadrada)

Histórico de operações

Tratamento de erros mais robusto

🧑‍💻 Autor
Desenvolvido por Seu Nome
Projeto educacional para praticar interfaces gráficas e manipulação de eventos em Python.

📄 Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.
