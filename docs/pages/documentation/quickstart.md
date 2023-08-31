
## Hello World

- [x] **Make sure you have java and maven installed**

```java
java --version
mvn --version
```

- [x] **Make sure you have an openAI account.**

Specify your key as the environment variable `OPENAI_API_KEY`

```console
export OPENAI_API_KEY=sk-...
```

- [x] **Implementation**

Here is the simplest snippet of code. It ia direct integration with the OpenAI API. 
You can find more examples in the [sample codes](../../../pages/samples) section.

```java
import dev.langchain4j.data.message.AiMessage;
import dev.langchain4j.model.chat.ChatLanguageModel;
import dev.langchain4j.model.openai.OpenAiChatModel;

public class HelloWorldExample {

    public static void main(String[] args) {

        // Create an instance of a model
        ChatLanguageModel model = OpenAiChatModel
                .withApiKey(System.getenv("OPENAI_API_KEY");

        // Start interacting
        AiMessage answer = model.sendUserMessage("Hello world!");

        System.out.println(answer.text()); // Hello! How can I assist you today?
    }
}
```

