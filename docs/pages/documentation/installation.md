???+ abstract "Prerequisites"

      - [x] **Install Java Development Kit (JDK) 8+**
      
      Use [java reference documentation](https://docs.oracle.com/javase/8/docs/technotes/guides/install/install_overview.html) targetting your operating system to install a Java Development Kit. You can then validate your installation with the following command.

      ```bash
      java --version
      ```

      - [x] **Install Apache Maven (3.8+)**
      
      Samples and tutorials have been designed with `Apache Maven`. Use the [reference documentation](https://maven.apache.org/install.html) top install maven validate your installation with 

      ```bash
      mvn -version
      ```

## Core Dependency

> `${project.version}` (_Latest version_) =   
> [![](https://maven-badges.herokuapp.com/maven-central/dev.langchain4j/langchain4j/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.langchain4j/langchain4j/)


To install the latest version of `langchain4j` with **Maven**, add the following dependency to your `pom.xml` file.

```xml
 <dependency>
    <groupId>dev.langchain4j</groupId>
    <artifactId>langchain4j</artifactId>
    <version>${project.version}</version>
</dependency>
```

To install with **Gradle** here is the line to add to the `build.gradle` file:

```groovy
implementation 'dev.langchain4j:langchain4j:${project.version}'
```

## External Stores

If you save your embeddings in an external vector store database, you can use the following dependency:(_here we use pinecone but several are available)
to learn more please check the [integration page](../../pages/integrations/index.md)

```xml
 <dependency>
    <groupId>dev.langchain4j</groupId>
    <artifactId>langchain4j-pinecone</artifactId>
    <version>${project.version}</version>
</dependency>
```

With Gradle it will translate to:

```groovy
implementation 'dev.langchain4j:langchain4j-pinecone:${project.version}'
```




