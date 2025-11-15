# Orientador de Carreiras do Futuro

## Descrição do Projeto e Propósito

Este projeto consiste em uma aplicação interativa desenvolvida em Python com Tkinter, capaz de analisar competências pessoais e recomendar carreiras promissoras para o futuro.  
O sistema também apresenta uma tela dedicada a **faculdades recomendadas**, alinhadas às áreas tecnológicas e emergentes.

O objetivo é fornecer uma ferramenta simples, visual e intuitiva que ajude estudantes e profissionais a descobrirem possíveis caminhos profissionais com base em habilidades individuais.

---

## Instruções de Execução

### Pré-requisitos
- Python 3.10+
- Instalar dependências:
- `pip install pillow`

- Arquivo de imagem `bg.png` deve estar no mesmo diretório do projeto.

### Executando o programa
1. Baixe ou clone este repositório.  
2. Certifique-se de que o arquivo `gs_python.py` está no diretório principal.  
3. Execute a aplicação com:
python gs_python.py

4. Utilize a tela inicial para navegar entre:
- **Descobrir meu perfil**
- **Faculdades recomendadas**

---

## Estrutura de Arquivos e Classes

├── gs_python.py # Código principal do projeto

├── bg.png # Imagem de fundo da tela inicial

├── README.md # Documentação do projeto


### Classes Principais

#### `Perfil`
Representa o usuário avaliado, armazenando nome e competências.  
Métodos:
- `media()` → calcula a média das competências.

#### `Orientador`
Processa o conjunto de competências para gerar afinidade com carreiras do futuro.  
Métodos:
- `recomendar(perfil)` → retorna as três principais recomendações.

#### `TelaTeste`
Interface gráfica para preenchimento das competências e exibição das carreiras sugeridas.

#### `TelaFaculdades`
Exibe áreas de estudo e cursos promissores para o futuro.

#### `HomeApp`
Tela inicial e central de navegação da aplicação.

---

## Demonstração

A seguir estão **três áreas reservadas para demonstrar o funcionamento do projeto**.  
Substitua cada imagem abaixo pelos prints reais.

---

### 1. Demonstração – Caso 1: Recomendações de Carreira (Perfil A)

Descrição sugerida:  
Perfil com competências equilibradas ou focadas em lógica/análise.

**Imagem aqui:**  
![demonstracao_caso1](CAMINHO/IMAGEM1.png)

---

### 2. Demonstração – Caso 2: Recomendações de Carreira (Perfil B)

Descrição sugerida:  
Perfil com características mais criativas, colaborativas ou comunicacionais.

**Imagem aqui:**  
![demonstracao_caso2](CAMINHO/IMAGEM2.png)

---

### 3. Demonstração – Faculdades Recomendadas

Descrição sugerida:  
Print da tela exibindo as áreas promissoras e cursos recomendados.

**Imagem aqui:**  
![demonstracao_faculdades](CAMINHO/IMAGEM3.png)

---
