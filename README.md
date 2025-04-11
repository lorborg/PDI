

Depositar a versão funcional do projeto num drive ou no github, e indicar o link. Colocar todos arquivos necessários, e documentos.
Elaborar um texto explicativo de como executar o código, bibliotecas necessárias, ambiente (colab ou jupyter), e outros requisitos; e descrever o procedimento detalhado para execução.

Projeto criado para a disciplina de Processamento Digital de Imagens 2025.1 

# Projeto da disciplina de Processamento Digital de Imagens 2025.1

Este projeto realiza o processamento de imagens capturadas via webcam de textos, livros ou documentos físicos, com a finalidade de extrair o texto da imagem e gerar um arquivo digital nos formatos de .txt, .pdf, entre outros.

---

## 📁 Estrutura do Projeto

```
PDI/
├── projeto.ipynb          ← Notebook collab com todo o código
└── README.md              ← Arquivo de instruções
```

---

## 🚀 Como Executar

### Ambiente recomendado:
> **Google Colab** 

### Passo a passo:

1. Acesse [Google Colab](https://colab.research.google.com/)
2. Faça upload do arquivo `projeto.ipynb`
3. Execute as células na ordem
4. Capture a imagem pela webcam
5. O sistema fará:
   - Pré-processamento da imagem
   - OCR (Tesseract em português)
   - Correção gramatical com LanguageTool

---

## 📦 Requisitos

As bibliotecas são instaladas automaticamente no notebook, mas caso seja necessário instalar manualmente, seguem os comandos:

```bash
pip install numpy
pip install opencv-python
pip install matplotlib
pip install scikit-image
pip install pillow
pip install pytesseract
pip install language-tool-python

sudo apt install tesseract-ocr
sudo apt install libtesseract-dev
sudo apt install tesseract-ocr-por
```

## 📷 Tecnologias utilizadas

- **OpenCV**, **Pillow**, **scikit-image** – processamento de imagem
- **Tesseract OCR** – extração de texto
- **LanguageTool** – correção ortográfica e gramatical
- **Google Colab** – captura de imagem via webcam
