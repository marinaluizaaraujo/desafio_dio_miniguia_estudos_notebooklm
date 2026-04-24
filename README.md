# 📑 Tudo sobre Java, Spring Boot e POO com Java

## 🎯 Contexto e Objetivos
Este repositório é o resultado de um estudo aprofundado utilizando o **NotebookLM** como tutor inteligente. O projeto foca no ecossistema Java, abordando desde os fundamentos da Programação Orientada a Objetos até a construção de APIs robustas com Spring Boot.

**Objetivos de Estudo:**
* **Fundamentação:** Consolidar os 4 pilares da POO (Herança, Polimorfismo, Encapsulamento e Abstração).
* **Prática com Framework:** Entender como o Spring Boot automatiza configurações e gerencia o ciclo de vida de objetos (Beans).
* **Maturidade Técnica:** Aplicar boas práticas de desenvolvimento e arquitetura de software.

---

## 📚 Curadoria de Fontes
Para alimentar o NotebookLM, selecionei fontes de alta qualidade que garantem a precisão técnica das respostas:
1.  **[Documentation Overview :: Spring Boot]**: (Documentação Oficial Spring Boot) - [https://docs.spring.io/spring-boot/documentation.html]
2.  **[Conceito de POO | Documentação Java DIO]**: (Artigo sobre Programação Orientada a Objetos em Java) - [https://felipe-aguiar.gitbook.io/dio-java/gitbook/programacao-orientada-a-objetos/conceito-de-poo]
3.  **[Java Documentation - Get Started]**: (Documento Java Oracle) - [https://docs.oracle.com/en/java/]
4.  **[Principais IDEs para desenvolvimento Java | Blog da TreinaWeb]**: (IDEs para desenvolvimento Java) - [https://www.treinaweb.com.br/blog/principais-ides-para-desenvolvimento-java]

---

## 🧠 Engenharia de Prompts e "Cicatrizes"
O segredo para extrair valor da IA foi o refinamento constante das perguntas. Abaixo, documento o raciocínio por trás da interação:

### Prompts Estratégicos
* **Contextualização:** *"Com base nos documentos, crie uma analogia do mundo real para explicar a diferença entre uma Interface e uma Classe Abstrata no contexto de Java."*
* **Refinamento:** *"A explicação anterior foi boa, mas agora mostre um exemplo de código Spring Boot onde o uso de uma Interface é obrigatório para a Injeção de Dependência."*

### 🛠 Troubleshooting (Cicatrizes)
> **Desafio:** Inicialmente, a IA gerou exemplos de código usando versões antigas do Java (Java 8).
> 
> **Solução:** Ajustei o prompt mestre para: *"Atue como um desenvolvedor Java Sênior e utilize apenas sintaxe do Java 17+ (como Records e Text Blocks) em todos os exemplos"*. Isso corrigiu a saída e trouxe o conteúdo para a atualidade do mercado.

---

## 🏁 Miniguia de Estudo (Entrega Final)

### 📝 Resumo Estruturado
* **POO:** O Java utiliza o paradigma de objetos para aproximar a representação do código ao mundo real, facilitando a manutenção e o reuso.
* **Spring Boot:** Facilita a criação de aplicações "ready to run", utilizando o conceito de *Convention over Configuration* (Convenção sobre Configuração).

### 📖 Glossário de Conceitos
| Termo | Definição Curta |
| :--- | :--- |
| **Injeção de Dependência** | Padrão onde o Spring fornece as instâncias das classes automaticamente. |
| **JPA / Hibernate** | Tecnologias que mapeiam as classes Java para tabelas no banco de dados. |
| **Annotation (@)** | Metadados que dão instruções especiais ao compilador ou ao Spring (ex: `@RestController`). |

### 🚀 Prompts Reutilizáveis
* `"Explique o erro 'BeanCreationException' e liste 3 causas comuns baseadas nos manuais."`
* `"Compare as anotações @Component, @Service e @Repository e quando usar cada uma."`

---

🔧 **Tecnologias Utilizadas:**
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=flat&logo=spring&logoColor=white)
