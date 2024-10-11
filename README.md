![N|Solid](https://upload.wikimedia.org/wikipedia/commons/thumb/8/88/SpaCy_logo.svg/1920px-SpaCy_logo.svg.png)
## Extração de Tags com NLP Usando spaCy

Este projeto utiliza a biblioteca spaCy para criar um pipeline de processamento de linguagem natural (NLP) que extrai tags personalizadas de textos, como, **HORA**, **O**, **GR**, e **TURNO**.

# Funcionalidades
* Extração de HORA: Identifica e extrai menções de horas no texto (ex.: 14:30).
* Extração de O (Objeto): Detecta termos ou frases associados a objetos ou entidades que não possuem relevância ao contexto.
* Extração de GR (Codigo da Turmma): Extrai Codigos de Turma específicos mencionados no texto (ex.: GR100052-00528).
* Extração de TURNO: Identifica menções de turnos (ex.: Manha, Tarde, Noite).

# Tecnologias Utilizadas

* **spaCy**: Uma das principais bibliotecas de processamento de linguagem natural em Python, usada para criar o modelo de extração de informações.
* **Python**: Linguagem de programação principal para desenvolvimento do projeto.
* **Regex**: Expressões regulares são usadas no dataset para reconhecer padrões específicos de tags.
