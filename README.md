# Sinais e Sistemas em Tempo Discreto (SSTD)

Este repositório contém os materiais e projetos desenvolvidos durante a disciplina de **Sinais e Sistemas em Tempo Discreto**, ministrada pelo professor Eduardo Peixoto Fernandes na Universidade de Brasília (UnB), no semestre 2023.2.

O foco principal é a implementação prática de conceitos de processamento digital de sinais utilizando Jupyter Notebooks.

## Organização do Repositório:

- **`Projeto-1`**: Implementação inicial focada em conceitos básicos de sinais discretos.
- **`Projeto-2`**: Continuação das práticas, abordando transformadas e filtragem básica.
- **`Projeto-3`**: Análises mais aprofundadas em frequência e sistemas lineares.
- **`Projeto-4`**: Projeto final da disciplina consolidando os conhecimentos adquiridos.
- **`Tabelas`**: Materiais de apoio e referência, como tabelas de transformadas e propriedades.

## 📚 Detalhamento Técnico dos Projetos

### 📂 Projeto-1: Fundamentos e Operações Básicas
Introdução ao ambiente de simulação numérica (Jupyter/Python). O foco reside na geração e manipulação de sequências discretas fundamentais (impulso unitário, degrau, exponenciais complexas).
* **Destaque técnico:** Implementação manual da operação de **convolução discreta**, verificando propriedades de linearidade e invariância no tempo (LIT) de sistemas simples.

### 📂 Projeto-2: Análise no Domínio da Frequência
Aprofundamento na análise espectral de sinais. Este módulo explora a **Transformada de Fourier de Tempo Discreto (DTFT)** e a relação entre sinais contínuos e amostrados.
* **Destaque técnico:** Estudo do Teorema da Amostragem de Nyquist-Shannon, visualizando o fenômeno de *aliasing* (sobreposição espectral) e a reconstrução de sinais através de interpolação ideal.

### 📂 Projeto-3: Filtragem Digital e Transformada Z
Focado no design de sistemas seletivos em frequência. Utiliza-se a Transformada Z para análise de estabilidade e causalidade através do diagrama de polos e zeros.
* **Destaque técnico:** Projeto de filtros **FIR** (Resposta ao Impulso Finita) e **IIR** (Resposta ao Impulso Infinita), manipulando janelas de ponderação (Hamming/Hanning) para controle de vazamento espectral e resposta de fase.

### 📂 Projeto-4: Processamento de Áudio/Imagem (Aplicação)
Integração dos conceitos anteriores em um problema real. O projeto aplica cadeias de filtros para tarefas como remoção de ruído, equalização de áudio ou detecção de bordas em imagens.
* **Destaque técnico:** Implementação de algoritmos de filtragem em blocos e análise de complexidade computacional das transformadas rápidas (FFT) aplicadas ao problema.
