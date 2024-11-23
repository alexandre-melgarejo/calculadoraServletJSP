# calculadoraServletJSP

Calculadora simples - MVC, desenvolvida em java utilizando JSP para views e Servlet para Controller.<br>
Desenvolvida como objeto de estudo.

## Tecnologias utilizadas:
- IDE IntelliJ Community 2024.1.4
- Apache Tomcat/11.0.1
- JVM 21.0.5+11-LTS
- jakarta.servlet-api-6.1.0.jar [https://repo1.maven.org/maven2/jakarta/servlet/jakarta.servlet-api/6.1.0/]
- Java
- JSP
- Servlet
- Sem gerenciador de dependências

## Como executar:

1. Baixar ou clonar o repositório da calculadora

2. Obter a imagem docker do tomcat

```

docker pull tomcat:latest


```

3. Executar o tomcat

```

docker run -it --rm -p 8080:8080 -v 'c:\CalculadoraServletJSP\src\main\webapp':/usr/local/tomcat/webapps/calculadora tomcat:latest


```

Observe que o path "c:\CalculadoraServletJSP\src\main\webapp" deve ser substituído pelo caminho onde a Calculadora foi baixada.
Se o seu sistema operacional for unix-based, aplique o path no formato adequado.

Obrigado pelo interesse na calculadora.
Se tiver elogios, sugestões ou críticas, fique à vontade para abrir uma issue. Opiniões sempre serão bem vindas.

