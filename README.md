# 🎥 Baixar Vídeo NEM

Aplicação web desenvolvida com **Python + Flask** que permite informar a URL de um vídeo e realizar o download utilizando a biblioteca **yt-dlp**.

## 🚀 Tecnologias utilizadas

* 🐍 Python
* 🌐 Flask
* 📥 yt-dlp
* 🎨 HTML5
* 🅱️ Bootstrap 5

## 📂 Estrutura do projeto

```text
projeto/
│
├── app.py
│
└── templates/
    └── index.html
```

## ⚙️ Instalação

### 1. Clone o projeto

```bash
git clone URL_DO_SEU_REPOSITORIO
cd NOME_DO_PROJETO
```

### 2. Crie um ambiente virtual

```bash
python -m venv venv
```

### 3. Ative o ambiente virtual

No Windows:

```bash
venv\Scripts\activate
```

### 4. Instale as dependências

```bash
pip install flask yt-dlp
```

## ▶️ Executando o projeto

Execute:

```bash
python app.py
```

Depois, abra no navegador:

```text
http://127.0.0.1:5000
```

## 🖥️ Como utilizar

1. Acesse a aplicação pelo navegador.
2. Cole a URL do vídeo no campo de texto.
3. Clique em **Baixar vídeo**.
4. O `yt-dlp` será utilizado para realizar o download.

## 📌 Observações

O projeto utiliza o **yt-dlp** para processar as URLs fornecidas.

Utilize a aplicação somente para conteúdos que você tenha permissão para baixar e de acordo com os termos de uso da plataforma de origem.

## 📄 Licença

Este projeto foi desenvolvido para fins de **estudo e aprendizado em desenvolvimento web com Python e Flask**.
