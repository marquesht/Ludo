# Ludo Game em C# 🎲

![Status do Projeto](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![Linguagem](https://img.shields.io/badge/Linguagem-C%23-9A208C?style=for-the-badge&logo=c-sharp&logoColor=white)
![Plataforma](https://img.shields.io/badge/Plataforma-Console-blue)
![Licença](https://img.shields.io/badge/Licen%C3%A7a-MIT-blue)

Um projeto divertido e funcional que implementa o clássico jogo de tabuleiro Ludo, desenvolvido inteiramente em C#. Suporta múltiplos jogadores e segue as regras tradicionais do jogo.

---

## 📖 Tabela de Conteúdo

* [Sobre o Projeto](#-sobre-o-projeto)
* [Funcionalidades](#-funcionalidades)
* [Estrutura do Projeto](#-estrutura-do-projeto)
* [Como Jogar](#-como-jogar)
* [Requisitos e Execução](#-requisitos-e-execução)
* [Logs do Jogo](#-logs-do-jogo)
* [Desenvolvedores](#-desenvolvedores)
* [Contribuições](#-contribuições)
* [Licença](#-licença)

---

## 🎯 Sobre o Projeto

Este jogo de Ludo em C# foi concebido como projeto final para a disciplina de Algoritmos e Técnicas de Programação, parte do curso de Sistemas de Informação na **PUC-Minas**. Nosso objetivo foi aplicar os conceitos de programação orientada a objetos e lógica de algoritmos para criar uma experiência de jogo completa no console.

---

## ✨ Funcionalidades

O Ludo em C# oferece uma experiência de jogo robusta com as seguintes características:

* **Modos de Jogo Flexíveis:** Suporte para 2 ou 4 jogadores.
* **Regras Completas:** Implementação fiel das regras tradicionais do Ludo, incluindo:
    * Movimento intuitivo dos peões no tabuleiro.
    * Captura estratégica de peões adversários para enviá-los de volta ao início.
    * Lógica para entrada segura na "casa final" e vitória.
    * Sistema de controle da "regra dos três 6" consecutivos, que impede o movimento adicional.
* **Interface de Console:** Interação simples e direta via linha de comando (sem visualização gráfica do tabuleiro).
* **Sistema de Log:** Registro detalhado de todas as ações e eventos do jogo em um arquivo externo.

---

## 🏗️ Estrutura do Projeto

O projeto é modularizado em diversas classes, cada uma com responsabilidades bem definidas, facilitando a manutenção e a compreensão do código:

* `Peao`: Gerencia o estado e as operações de um peão individual (posição, cor, etc.).
* `Jogador`: Representa um participante do jogo, seus peões e ações específicas (lançar dado, mover peão).
* `Tabuleiro`: Define a estrutura e as constantes do tabuleiro de Ludo, incluindo caminhos e casas especiais.
* `Jogo`: Orquestra a lógica principal do jogo, controlando o fluxo das rodadas, turnos e interações entre jogadores.
* `Program`: Contém o método `Main`, sendo o ponto de entrada da aplicação para iniciar a execução do jogo.

---

## 🕹️ Como Jogar

Para começar a se divertir com o Ludo em C#, siga estes passos simples:

1.  **Execute o Programa:** Inicie o executável do jogo.
2.  **Escolha os Jogadores:** Opte por jogar com 2 ou 4 jogadores quando solicitado.
3.  **Siga as Instruções:** O jogo guiará você através dos turnos, indicando quando lançar o dado e qual peão mover.

---

## 🚀 Requisitos e Execução

Para rodar este projeto em sua máquina:

**Requisitos:**

* [.NET Framework](https://dotnet.microsoft.com/download/dotnet-framework) (versão compatível com C#) ou [.NET Core](https://dotnet.microsoft.com/download) (recomendado para maior compatibilidade e recursos).

**Como Executar:**

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/marquesht/NomeDoSeuRepositorioLudo.git](https://github.com/marquesht/NomeDoSeuRepositorioLudo.git)
    cd NomeDoSeuRepositorioLudo
    ```
    (Substitua `NomeDoSeuRepositorioLudo` pelo nome real do repositório onde está o projeto Ludo).
2.  **Abra o Projeto:** Utilize seu IDE C# preferido (ex: Visual Studio, VS Code com C# Dev Kit).
3.  **Compile e Execute:** Compile a solução e execute o programa diretamente do seu ambiente de desenvolvimento.

---

## 📄 Logs do Jogo

Todas as ações e eventos importantes durante uma partida são automaticamente registrados em um arquivo de log. Este arquivo, chamado `ludo_log.txt`, será criado no mesmo diretório de execução do programa. É útil para depuração e para revisar o andamento de uma partida.

---

## 👥 Desenvolvedores

Este projeto foi desenvolvido com dedicação por:

* **Matheus Filipe de Deus** - [![LinkedIn Matheus](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matheusfilipesilva/)
* **Arthur Marques** - [![LinkedIn Arthur](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arthur-marques-b984162a9/)

---

## 🤝 Contribuições

Contribuições são **extremamente bem-vindas** para aprimorar este projeto de Ludo! Se você tiver ideias para melhorias, encontrar bugs ou quiser adicionar novas funcionalidades, sinta-se à vontade para:

1.  Fazer um **fork** deste repositório.
2.  Criar uma nova branch para sua feature (`git checkout -b feature/sua-feature`).
3.  Realizar suas alterações e fazer o commit (`git commit -m 'feat: sua nova feature'`).
4.  Enviar suas alterações para o seu fork (`git push origin feature/sua-feature`).
5.  Abrir um **Pull Request** detalhado, descrevendo suas mudanças.

Agradecemos o seu apoio!

---

## ⚖️ Licença

Este projeto está licenciado sob a Licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
