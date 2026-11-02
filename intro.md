# 👋 Boas-vindas

Olá e seja muito **bem-vindo(a)** ao nosso minicurso **Visão Computacional**

Se você já se perguntou **como um computador enxerga o mundo, processa imagens e reconhece padrões**, este curso foi pensado para responder exatamente essa pergunta. Sendo assim, ao longo desses **cinco dias**, aprenderemos desde a estrutura de dados bruta das imagens até a implementação e aplicação de **redes neurais convolucionais** e ferramentas do **estado da arte**.

Você aprenderá a manipular desde um **único pixel** até **filtros manuais de convolução**, **fundamentos de aprendizado de máquina** e **modelos avançados de visão**. E mais do que apenas aplicar bibliotecas, o objetivo é entender a **matemática e a mecânica por trás do processamento visual e do treinamento de IAs**.

---

# 🚀 Ao final do curso...

Você terá desenvolvido e treinado **suas próprias redes e pipelines de Visão Computacional**, tornando-se capaz de:

- **Aplicar** conceitos de visão computacional diretamente em imagens estáticas;
- **Familiarizar-se** com a matemática por trás do treinamento de modelos de inteligência artificial;
- **Implementar** (com suporte) uma rede neural no contexto de visão;
- **Manejar** as IAs e ferramentas de maior relevância do segmento (como OpenCV, YOLO e MediaPipe);
- **Compreender** para onde está caminhando o estado da arte da área.

---

# 🎯 Objetivo do Curso

Neste minicurso, você construirá uma **base sólida em Visão Computacional**, partindo da manipulação básica de matrizes até o uso de modelos modernos de inteligência artificial.

Ao final do curso, você será capaz de:

- [x] **Compreender** a estrutura de dados bruta de imagens digitais (pixels, matrizes e espaços de cor);
- [x] **Implementar** e aplicar filtros manuais e a mecânica da convolução para suavização e detecção de bordas;
- [x] **Entender** os fundamentos de aprendizado de máquina, neurônios artificiais e funções de perda;
- [x] **Construir** e visualizar o funcionamento interno de Redes Neurais Convolucionais (CNNs);
- [x] **Treinar** modelos de classificação e explorar ferramentas industriais como YOLO e MediaPipe.

---

# 📦 Pré-requisitos

Para acompanhar o conteúdo com tranquilidade, exige-se ter cursado:

- **Introdução à Inteligência Artificial (IMD3001)**.

Essa disciplina fornece a base conceitual necessária para absorver os tópicos de inteligência artificial e aprendizado de máquina abordados durante o minicurso.

:::{important}
Alguns conceitos práticos e matemáticos específicos **serão aprofundados durante as aulas**. Sendo assim, ao longo do minicurso faremos introduções graduais a assuntos como:

- **Mecânica da Convolução** e aplicação de kernels;
- **Descida do Gradiente** e ajuste automático de pesos.

**Não se preocupe** caso precise de reforço nesses conteúdos: eles serão apresentados de forma intuitiva conforme forem necessários.
:::

---

# 🛠️ Como o curso será conduzido

O minicurso é estruturado em torno da **evolução prática**: da manipulação direta de matrizes ao treinamento e execução de modelos de IA.

Os participantes realizarão **atividades práticas hands-on** a cada aula, utilizando ambientes interativos e datasets didáticos para implementar os algoritmos e visualizar instantaneamente os resultados das transformações visuais e do aprendizado do modelo.

:::{note}
Este minicurso é **fortemente baseado em prática**.

Cada novo conceito apresentado — seja a conversão para tons de cinza, a aplicação de filtros de borda ou o treinamento de uma CNN — será **implementado ou visualizado na prática**, permitindo consolidar o aprendizado imediatamente.
:::

---

# 📅 Cronograma

## 🟢 Dia 1 — Fundamentos da Imagem Digital

- **Amostragem e Quantização**: Discretização de valores de cor
- **O Pixel e a Matriz**: A imagem como tabela bidimensional
- **Espaços de Cor**: Sistema RGB e conversão para Greyscale
- **Histograma**: Distribuição de luz/sombra e ajuste de contraste
- **Thresholding (Limiarização)**: Binarização para separação de fundo e objeto
- **Prática**: Manipulação direta de matrizes, conversão de cores na mão, construção de histogramas e introdução ao OpenCV

---

## 🔵 Dia 2 — Filtros Manuais e a Mecânica da Convolução

- **Conceito de Convolução**: Operações de vizinhança usando matrizes de pesos (kernels)
- **Filtros de Blur (Suavização)**: Redução de ruído e baixas frequências
- **Filtros de Detecção de Bordas**: Gradientes e filtro de Sobel para encontrar contornos
- **Prática**: Aplicação de filtros para limpeza de ruído e desenho automático de contornos

---

## 🟡 Dia 3 — Fundamentos do Aprendizado de Máquina (A Ponte)

- **A Intuição do Aprendizado**: Limites da programação de regras lógicas vs. padrões dinâmicos
- **O Neurônio Artificial**: Pesos (*weights*) e viés (*bias*)
- **Corrigindo Erros**: Função de Perda (*Loss*) e Descida do Gradiente
- **O Problema do Achatamento**: Redes MLPs e a perda de informação espacial

- **Prática**: Visualização interativa do ajuste de pesos (ex: TensorFlow Playground)
---

## 🟠 Dia 4 — O Salto para as Redes Convolucionais (CNNs)

- **O Gargalo da Visão Clássica**: Inviabilidade de filtros manuais para variabilidade complexa
- **A Camada Convolucional**: Aprendizado automático de kernels dinâmicos
- **Função de Ativação (ReLU)**: Destaque de características (*features*)
- **Pooling**: Redução espacial e retenção de características fortes (Max Pooling)
- **Prática**: Extração e visualização de *Feature Maps* internos em uma CNN

---

## 🔴 Dia 5 — Treinamento, Classificação e o Estado da Arte

- **A Camada Densa**: Flatten, Fully Connected e vetores de probabilidade
- **O Ciclo de Treinamento Básico**: Comparação de palpites e atualização de parâmetros
- **Métricas Básicas**: Acurácia e prevenção de *Overfitting*
- **O Salto para a Indústria**:
  - **YOLO**: Detecção e classificação de objetos em tempo real
  - **MediaPipe**: Rastreamento de poses e articulações via APIs
  - **DINOv3**: Vislumbre do aprendizado autossupervisionado
- **Prática**: Treinamento de uma CNN no dataset MNIST e demonstração prática interativa com webcam via YOLO/MediaPipe

---

# 💻 Ferramentas utilizadas

Durante o curso utilizaremos principalmente:

- **Python**
- **OpenCV**
- **TensorFlow / PyTorch**
- **YOLO** e **MediaPipe**
- **Google Colab / Jupyter Notebooks**

Todo o material e código base serão disponibilizados pelos organizadores.

---

# 🤝 Suporte

Durante todo o minicurso, os organizadores estarão disponíveis para **esclarecer dúvidas** e **auxiliar na implementação** das atividades propostas.

**Não tenha receio de perguntar!**

Visão Computacional envolve bastante **matemática**, **programação** e **experimentação**, e é completamente normal precisar de ajuda durante o processo.

---

Esperamos que este minicurso desperte sua curiosidade pela área e mostre que, por trás de **cada sistema de visão e inteligência artificial**, existe uma enorme quantidade de **matemática**, **algoritmos** e **engenharia**.

# **Vamos começar! 🚀**
