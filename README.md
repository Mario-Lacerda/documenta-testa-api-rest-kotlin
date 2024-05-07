# Desafio Dio - Criando uma Api Rest com Kotlin e Persistência de Dados
## **Documentando e Testando sua API REST com Kotlin**

Neste projeto, vamos criar uma API REST com Kotlin e documentá-la com Swagger. Também escreveremos testes para garantir que nossa API esteja funcionando corretamente. Projeto de API com Rest Assured e Junit5. Nesse teste fiz um teste dependente de outro, o ideal que cada teste seja independente, mas é uma opção fazer partes separadas, fiz também porque tive pouco tempo pra elaborar o mesmo, reduzindo o código o máximo possível.

REST Assured 4.1.0 introduziu um novo módulo chamado "kotlin-extensions". Este módulo fornece algumas funções de extensão úteis ao trabalhar com REST Assured do Kotlin. Primeiro você precisa adicionar o módulo ao projeto:

O projeto foi criado com intuito de mostrar o ServeRest (https://serverest.dev/), que permite o estudo de:

- Verbos *GET, POST, PUT* e *DELETE* com persistência de dados
- Autenticação no header
- Query string
- Teste de schema json


### Para subir o servido localmente com NPM

Execute o seguinte comando no terminal:  

```sh
npx serverest@latest
```

Para rodar os testes no terminal use o comando abaixo:
```
./mvnw clean test
```


### **Estrutura do Projeto**

Nossa API REST será estruturada da seguinte forma:

- **Controladores:** Contêm a lógica de negócios da API.
- **Modelos:** Representam os dados que nossa API manipula.
- **Repositórios:** Fornecem acesso a dados persistentes.
- **Serviços:** Contêm a lógica de negócios que não está diretamente relacionada à persistência de dados.

### **Documentação com Swagger**

Usaremos Swagger para gerar documentação para nossa API. Isso facilitará para os desenvolvedores entenderem como usar nossa API e quais dados ela espera e retorna.

### **Lógica de Negócios**

Nossa API REST implementará as seguintes operações CRUD:

- **Criar:** Cria um novo recurso.
- **Ler:** Recupera um recurso existente.
- **Atualizar:** Atualiza um recurso existente.
- **Deletar:** Exclui um recurso existente.

**Dependências**

Nossa API REST dependerá das seguintes bibliotecas:

- Kotlin

- Spring Boot

- Spring Web

- Swagger

  

### **Testes**

Usaremos JUnit e Mockito para testar nossa API REST. Isso garantirá que nossa API esteja funcionando corretamente e conforme o esperado.

### **Conclusão**

Neste projeto, criamos uma API REST com Kotlin, documentada com Swagger e testada com JUnit e Mockito. Ao seguir as melhores práticas de documentação e teste, criamos uma API REST robusta e confiável.

### **Aplicabilidade Prática**

Esta API REST pode ser aplicada em vários cenários do mundo real, como:

- Fornecer dados para aplicativos móveis e web.
- Integrar com outros sistemas.
- Expor dados para consumo público.



##### ** Obs: Precisa configurar o Java JDK 11 e adicionar o JAVA_HOME nas variáveis de ambiente, senão vai dar erro na execução.

https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html

Vídeo curto explicando o projeto:
https://www.youtube.com/watch?v=DfNLaGjjN4o  

Reporte no GitHub: https://reinaldorossetti.github.io/rest-assured-kotlin/index.html#suites  

References:  
Doc: https://github.com/rest-assured/rest-assured/wiki/Usage#kotlin-extension-module  
Site pra gerar esquecelo do Kotlin com Maven: https://start.spring.io  

