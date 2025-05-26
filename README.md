# Geração de Imagens com Redes Adversárias Generativas (GANs)

As **GANs (Generative Adversarial Networks)** são uma das abordagens mais poderosas da inteligência artificial para **geração de dados realistas**. Elas consistem em dois modelos que se enfrentam: um **gerador** e um **discriminador**.

- O **gerador** cria dados sintéticos (ex: imagens falsas)
- O **discriminador** tenta distinguir entre dados reais e falsos
- O objetivo do gerador é **enganar o discriminador**, e o do discriminador é **não ser enganado**

Esse processo competitivo leva ao **aperfeiçoamento contínuo do gerador**, que acaba produzindo saídas cada vez mais realistas.

### Por que GANs são revolucionárias?

- Geram imagens, vídeos, vozes e textos **sintéticos, mas realistas**
- Aprendem **sem rótulos** diretamente a partir de distribuições de dados
- Possibilitam aplicações como **deepfakes, arte generativa, reconstrução de imagens, super-resolução e simulações realistas**

### Funcionamento Intuitivo

Imagine que o gerador é um **falsificador de arte** e o discriminador é um **especialista em obras originais**. Ao longo do tempo, o falsificador melhora tanto que se torna quase indistinguível do original.

---

## 📂 Estrutura do Notebook

### `GAN1_Digitos_Orlando.ipynb`
**📌 Tarefa:** Geração de dígitos manuscritos com GAN  
**📚 Dataset:** [MNIST](http://yann.lecun.com/exdb/mnist/)  
**🔍 Destaques:**
- Estrutura completa de uma GAN com gerador e discriminador
- Treinamento adversarial passo a passo
- Visualização das imagens falsas geradas ao longo das épocas
- Acompanhamento da evolução da qualidade visual

---

## 📈 Métricas e Avaliação

GANs são avaliadas com:

- **Evolução qualitativa das imagens geradas**
- **Perda (loss) do gerador e do discriminador**
- **FID Score** (em aplicações mais avançadas)
- **Comparação visual com dados reais**

---

## ⚙️ Técnicas Utilizadas

- Redes densas com ReLU e Sigmoid
- Otimizadores Adam para estabilidade
- Normalização e reshape de imagens
- Treinamento sequencial com atualização alternada dos modelos
"""
