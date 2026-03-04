# ECU Remap Tool Prototype

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![.NET 8.0](https://img.shields.io/badge/.NET-8.0-blue.svg)](https://dotnet.microsoft.com/)

Um protótipo de software desktop focado na edição de mapas de injeção e ignição para entusiastas automotivos. Este projeto abstrai a complexidade dos bytes hexadecimais em interfaces visuais intuitivas.

## Objetivo do Projeto

Desenvolver uma ferramenta que permita a entusiastas modificarem parâmetros de performance de seus veículos sem a necessidade de conhecimentos profundos em Mecânica Automotiva. O foco é a **segurança dos dados** e a **usabilidade mecânica**.

## Funcionalidades Principais

- **Visualização de Mapas:** Conversão de dados binários brutos em tabelas decimais compreensíveis.
- **Gráficos de Performance:** Visualização 3D de curvas de injeção e ignição (WPF).
- **Abstração de Dados:** Edição via fatores de conversão (Ex: Byte -> Milissegundos).
- **Gerenciamento de Offsets:** Sistema para identificar e salvar endereços de memória específicos de cada ECU.

## Tecnologias Utilizadas

- **Linguagem:** C#
- **Banco de Dados:** MySQL (Futuramente Oracle).
- **Interface:** WPF (Windows Presentation Foundation) com padrão MVVM.
- **Manipulação de Dados:** System.IO (BinaryReader/Writer) e LINQ.
- **Estética:** Custom UI com opções minimalistas, industriais ou 100% personalizáveis.

## Roadmap de Desenvolvimento

- [x] Leitura de arquivos binários e conversão para decimal.
- [ ] Implementação de interface gráfica com tabelas editáveis.
- [ ] Criação BD.
- [ ] Criação de gráficos 3D interativos.
- [ ] Integração com hardware de leitura OBD-II (Futuro).

## Autor

**João Pedro Pavani Falcão** Estudante de TI e entusiasta de preparação automotiva.  

---
*Este projeto faz parte do meu portfólio e certificado de conclusão de curso (TCC).*
