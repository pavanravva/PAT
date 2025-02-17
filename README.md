# PAT
![Alt text](DataGenerationPipeline.png)
This framework shows how the Personalized Agent Chat (PAT) dataset was generated to help LLMs create more natural, personality-driven responses. It simulates an AI-Human Dialogue in for everyday common scenerio. It starts by using ChatGPT4 to extract personas from the Multi-Session Chat (MSC) dataset, identifying traits like demographics, motivations, and decision-making styles. Based on this, Meta's LLAMA 405B is used to generate a persona description and personalized scene are generated, followed by tailored questions that match the user's traits. These elements come together in a structured prompt for response generation, with new responses continuously added to the PAT dataset.

## Adaptive Friend Agent (AFA)
![Alt text](FrameworkDiagram.png)
This framework takes in audio input, transcribes it to text, and uses it for voice identification. It then extracts relevant persona attributes and retrieves user data from a vector database. Tt combines persona details with conversation history, and creates a context-aware prompt for the LLM to generate a personalized response. Finally, the system updates temporary records to improve future interactions, to establish a more adaptive and engaging experience.
![Alt text](PerformanceComparisonTable.png)
