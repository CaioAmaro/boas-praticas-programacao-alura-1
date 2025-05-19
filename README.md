# Adopet Console Application

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Gson](https://img.shields.io/badge/Gson-JSON-green?style=for-the-badge)

## 📋 Sobre o Projeto

Este é um sistema de linha de comando desenvolvido em **Java** que interage com a API REST do projeto **Adopet**. O sistema permite que o usuário cadastre e visualize **abrigos de animais** e **pets disponíveis para adoção**, além de importar pets a partir de arquivos CSV.

O projeto está sendo refatorado com o **objetivo de aplicar boas práticas de programação**, como:

- Separação de responsabilidades (principais regras de negócio fora do `main`)
- Uso de classes e métodos reutilizáveis
- Leitura de dados com tratamento de exceções
- Organização de código para facilitar a manutenção

## 🎯 Funcionalidades

- ✅ Listar abrigos cadastrados
- ✅ Cadastrar novo abrigo
- ✅ Listar pets de um abrigo
- ✅ Importar pets via CSV
- ✅ Comunicação com API REST usando `HttpClient`
- ✅ Manipulação de JSON com **Gson**

## 🛠️ Tecnologias Utilizadas

- Java 17+
- Biblioteca [Gson](https://github.com/google/gson) para manipulação de JSON
- `java.net.http.HttpClient` para chamadas HTTP
- Java IO para leitura de arquivos `.csv`

## 🚀 Como Executar

1. Certifique-se de ter o **Java 17** ou superior instalado.
2. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/adopet-console.git
cd adopet-console
