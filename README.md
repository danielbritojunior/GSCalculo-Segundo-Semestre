# 🧠 Global Solution - Dashboard da Curva do Conhecimento

![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![Curso](https://img.shields.io/badge/Curso-Engenharia%20de%20Software-blue)
![Disciplina](https://img.shields.io/badge/Disciplina-Differentiated%20Problem%20Solving-orange)

## 👨‍💻 Autores

Trabalho desenvolvido pela turma **1ESR**:

* **Daniel Brito dos Santos Junior** (RM: 566236)
* **Gustavo Palomares Borsato** (RM: 564621)
* **Vitor Rampazzi Franco** (RM: 562270)

## 👋 Introdução

Este repositório contém o código-fonte de um **painel interativo (dashboard)** desenvolvido para a **Global Solution** da disciplina de *Differentiated Problem Solving*.

O objetivo deste painel é demonstrar visualmente como conceitos fundamentais do Cálculo (Funções, Limites, Derivadas e Integrais) modelam o aprendizado humano, a estabilização do conhecimento e a necessidade crítica de requalificação no contexto do **Futuro do Trabalho**.

## ✨ Funcionalidades Principais

O painel é uma página única (Single Page Application) totalmente interativa:

* **Simulação em Tempo Real:** Altere os parâmetros globais (Limite de Conhecimento e Taxa de Aprendizado) e veja como a curva de aprendizado se comporta instantaneamente.
* **Visualização Gráfica:** Utiliza **Chart.js** para renderizar gráficos dinâmicos de $K(t)$ (Nível) e $K'(t)$ (Velocidade).
* **Cálculo de Áreas (Integrais):** Permite definir um intervalo de tempo específico ($t_1$ a $t_2$) para calcular visualmente o "esforço acumulado" (área sob a curva).
* **Explicações Contextuais:** Cada métrica possui tooltips e legendas explicativas para facilitar a interpretação dos dados matemáticos.
* **Design Responsivo:** Construído com **TailwindCSS**, adaptando-se a desktops e dispositivos móveis.

## 📚 Conceitos de Cálculo Aplicados

O painel explora o modelo de **Crescimento Limitado**, essencial para entender a estagnação de habilidades no mercado de trabalho.

### 1. Função e Limite (A Curva de Aprendizado)
* **Modelo:** $K(t) = L \cdot (1 - e^{-k \cdot t})$
* **Conceito:** O Limite ($\lim_{t \to \infty} K(t) = L$) demonstra que o aprendizado de uma habilidade específica tem um "teto".
* **Aplicação:** Visualiza a **estabilização** (Maestria). No contexto dos **ODS 8**, isso alerta para o risco de obsolescência profissional se não houver requalificação.

### 2. Derivada (Velocidade de Aprendizado)
* **Modelo:** $K'(t) = L \cdot k \cdot e^{-k \cdot t}$
* **Conceito:** A taxa de variação instantânea do conhecimento.
* **Aplicação:** Mostra a **"Fase Intensa"** inicial (onde a derivada é alta) e como a velocidade de aprendizado cai drasticamente conforme nos aproximamos da maestria.

### 3. Integral (Conhecimento/Esforço Acumulado)
* **Modelo:** $\int_{t_1}^{t_2} K(t) \ dt$
* **Conceito:** A área sob a curva no gráfico de nível de conhecimento.
* **Aplicação:** Quantifica o **volume total de esforço** ou conhecimento consolidado em um período. É a diferença entre "saber" (ponto no gráfico) e "manter o conhecimento" (área sólida).

## 🚀 Tecnologias Utilizadas

* **HTML5:** Estrutura semântica.
* **TailwindCSS:** Estilização moderna e responsiva (via CDN).
* **JavaScript (ES6+):** Lógica matemática e manipulação do DOM.
* **Chart.js:** Biblioteca para renderização dos gráficos interativos.

## 🏃‍♂️ Como Executar

Este projeto é estático e não requer instalação de dependências (Node.js, Python, etc).

1.  **Clone ou baixe** este repositório.
2.  Abra o arquivo `index.html` em qualquer navegador moderno (Chrome, Firefox, Edge).
3.  O painel carregará automaticamente com as bibliotecas via CDN.

