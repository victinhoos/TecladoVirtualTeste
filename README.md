<div align="center">
  <img src="https://github.com/user-attachments/assets/e3c8f4df-e217-46f1-8a6b-98ecde76ee76" width="100%">
</div>
# ⌨️ Teclado Virtual Full Style


> Um simulador de teclado completo, responsivo e interativo desenvolvido com HTML, CSS e JavaScript.

## 📖 Sobre o Projeto

O **Teclado Virtual Full Style** é uma aplicação web que renderiza um layout de teclado completo (incluindo teclado numérico e teclas de navegação) na tela. O objetivo principal é fornecer feedback visual em tempo real: ao pressionar uma tecla no seu teclado físico, a tecla correspondente no teclado virtual acende e muda de cor.

Este projeto é excelente para testar códigos de teclas (`event.code`), visualizar inputs ou apenas como um exercício de manipulação de DOM e Layouts CSS complexos.

## ✨ Funcionalidades

- **Feedback Visual em Tempo Real:** As teclas virtuais reagem instantaneamente (mudança de cor e animação de "press") quando você digita no teclado físico.
- **Layout Completo (Full Size):** Inclui teclas de função (F1-F12), bloco de navegação (Home, End, Setas) e Numpad.
- **Prevenção de Atalhos Padrão:** O script bloqueia comportamentos padrão de teclas como `F1`, `Tab` e `Alt` para manter o foco na aplicação.
- **Design Moderno:** Tema escuro (Dark Mode) com acentos em laranja e variáveis CSS para fácil customização.
- **Mapeamento Preciso:** Utiliza a propriedade `event.code` do JavaScript para diferenciar teclas duplicadas (ex: Shift Esquerdo vs Shift Direito).

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica e atributos de dados (`data-code`).
* **CSS3:**
  * **Grid Layout & Flexbox:** Para o posicionamento preciso das teclas e seções.
  * **CSS Variables:** Para gerenciamento de paleta de cores.
  * **Animações:** Transições suaves de estado ativo/inativo.
* **JavaScript (Vanilla):** Manipulação de eventos de teclado (`keydown`, `keyup`).

## 🚀 Como Executar

Você pode rodar este projeto localmente de forma simples:

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/SEU-USUARIO/NOME-DO-REPO.git](https://github.com/SEU-USUARIO/NOME-DO-REPO.git)
