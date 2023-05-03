# Prompt Engine

## Overview
Prompt Engine is a powerful and flexible template designed to facilitate the creation and customization of interactive prompts. With a wide range of personalization options, commands, and formats, Prompt Engine provides prompt engineers and programmers with the ability to create highly tailored and dynamic content that adapts to user preferences and needs.

## Copy and Paste the Prompt
- [Prompt Engine v0.01](https://github.com/ruvnet/Prompt-Engine/blob/main/prompts/engine.toml)

## What is the Prompt Engine System?
The Prompt Engine System is a template-based framework designed to empower prompt engineers and programmers to create interactive prompts with ease. It offers a wide range of personalization options, commands, and features that allow users to create content tailored to their specific needs.

The system is built around the concept of configuration files, supporting formats such as TOML (Tom's Obvious, Minimal Language), YAML (YAML Ain't Markup Language), and JSON (JavaScript Object Notation). These formats provide a human-readable and easy-to-understand structure for defining the behavior and characteristics of interactive prompts. With the Prompt Engine System, users can define everything from the complexity of content and interaction styles to the rules and commands that govern the prompt's behavior. By offering support for multiple configuration formats, the system ensures flexibility and adaptability to suit the preferences and requirements of different users.

## Purpose
The primary purpose of Prompt Engine is to provide prompt engineers and programmers with a versatile and customizable template for creating interactive prompts that can be used in a wide range of applications, from chatbots and virtual assistants to educational platforms and customer support tools. The Prompt Engine is designed to be adaptable and extensible, allowing users to create dynamic and responsive interactions that can be easily configured to suit different use cases and contexts.

One of the key features of Prompt Engine is its emphasis on personalization. By offering a wide range of personalization options, such as content complexity levels, interaction styles, presentation styles, and tone styles, Prompt Engine enables prompt engineers to create content that is highly relevant and engaging for individual users. This level of personalization helps to create a more meaningful and effective user experience, as users are able to interact with content that is tailored to their specific needs, preferences, and interests.

In addition to personalization, Prompt Engine also provides a comprehensive set of commands and formats that can be used to define the behavior and structure of interactive prompts. These commands and formats provide prompt engineers and programmers with the flexibility to create interactive experiences that are intuitive and user-friendly, while also being capable of handling complex interactions and workflows.

## Benefits
- **Personalization**: Prompt Engine offers a variety of personalization features, including the ability to customize content complexity, interaction styles, presentation styles, and more. This allows prompt engineers to create content that is highly relevant and engaging for users.
- **Flexibility**: With a comprehensive set of commands and format options, Prompt Engine provides programmers with the flexibility to create interactive experiences that are intuitive and user-friendly.
- **Adaptability**: Prompt Engine is designed to adapt to different domains and areas of interest, making it suitable for a wide range of use cases and applications.
- **Efficiency**: Prompt Engine's structured and modular design makes it easy for prompt engineers and programmers to quickly develop and deploy interactive content, saving time and effort.

## Key Features of the Prompt Engine System
- Commands: The system provides a rich set of commands that users can input to interact with the platform. These commands enable users to navigate the content, request help, provide feedback, and perform various other actions.

- Rules: The Prompt Engine System allows users to define rules that govern the behavior of the prompt. These rules ensure that users adhere to certain guidelines and restrictions while interacting with the platform.

- Formats: The system offers various format settings that can be used to customize the presentation and structure of the content. This includes options for configuring the platform, setting reminders, and evaluating performance.

- Settings: The Prompt Engine System provides a range of settings that enhance the functionality of the platform. This includes options for integrating plugins, enabling internet access, using emojis, and supporting programming languages.


## Accessing the Prompt Template
The Prompt Engine template is available in three formats, which can be accessed via the following links:

- [YAML format:](https://github.com/ruvnet/Prompt-Engine/blob/main/templates/prompt.yaml)
- [TOML format:](https://github.com/ruvnet/Prompt-Engine/blob/main/templates/prompt.toml)
- [JSON format:](https://github.com/ruvnet/Prompt-Engine/blob/main/templates/prompt.json)

| Use Cases           | Description                                                                                                              |
|---------------------|--------------------------------------------------------------------------------------------------------------------------|
| Educational Platforms | Create interactive learning experiences that adapt to the learner's level of expertise, preferred interaction style, and area of interest. It can also be used to create quizzes, assessments, and self-evaluation tools. |
| Customer Support    | Build dynamic and personalized customer support prompts that provide users with relevant information and assistance based on their needs. It can also be used to automate common support tasks and provide real-time responses to customer inquiries. |
| Content Exploration | Create interactive content exploration tools that allow users to navigate and discover content in a personalized and engaging manner. It can also be used to create recommendation systems that suggest relevant content based on user preferences. |
| Virtual Assistants  | Create virtual assistants that provide personalized assistance and support to users. It can be used to build conversational agents that understand natural language input and provide contextually relevant responses. |
| Interactive Narratives | Create interactive narratives and storytelling experiences that adapt to user choices and preferences. It can be used to create branching narratives, interactive fiction, and role-playing scenarios. |
| Data Visualization  | Create interactive data visualization tools that allow users to explore and analyze data in a dynamic and intuitive manner. It can be used to create dashboards, charts, and interactive reports. |
| Workflow Automation | Create workflow automation tools that guide users through complex tasks and processes. It can be used to create interactive tutorials, onboarding experiences, and step-by-step guides. |
| Gaming              | Create interactive gaming experiences that adapt to player choices and preferences. It can be used to create text-based games, interactive puzzles, and simulation games. |
| Accessibility       | Create accessible content and interactions for users with disabilities. It can be used to create screen reader-friendly content, voice-activated interactions, and alternative input methods. |
| Language Learning   | Create language learning tools that provide personalized and interactive language lessons. It can be used to create language exercises, pronunciation guides, and vocabulary quizzes. |

## Examples

### Simple Example
In this simple example, we demonstrate how to create a basic prompt that allows users to choose their area of interest and receive content based on their selection.

```toml
[prompt]
Author = "rUv"
name = "Area of Interest Selector"
forked_from = "ruvnet"
version = "1.0"

# initial prompt
# Purpose: The initial prompt welcomes the user to the Area of Interest Selector and explains the purpose of the bot.
# It also informs the user that the bot will demonstrate how to create a basic prompt that allows users to choose their area of interest and receive content based on their selection.
init = "Welcome to the Area of Interest Selector. This bot will demonstrate how to create a basic prompt that allows users to choose their area of interest and receive content based on their selection. Let's get started!"

[prompt.features.personalization.domains]
Description = "Choose your area of interest."
Domain_A = "Science"
Domain_B = "History"

[prompt.commands.commands]
Description = "Available commands."
help = "Get help."
choose_domain = "Choose your area of interest."
```

### Advanced Example
In this advanced example, we demonstrate how to create a more complex prompt that includes additional personalization options, such as content complexity and interaction styles.

```toml
[prompt]
Author = "rUv"
name = "Advanced Prompt Engine Template Creator"
forked_from = "ruvnet"
version = "1.0"

# initial prompt
init = "Welcome to the Advanced Prompt Engine Template Creator. This bot will help you create a new Prompt Engine prompt with custom domain and use-specific templates. Let's get started!"

[prompt.features.personalization]
Description = "Personalized settings."

[prompt.features.personalization.domains]
Description = "Choose your area of interest."
Domain_A = "Science"
Domain_B = "History"

[prompt.features.personalization.complexity]
description = "Choose content complexity level."
Level_1 = "Basic"
Level_10 = "Advanced"

[prompt.features.personalization.interaction_styles]
Description = "Choose interaction style."
Style_A = "Text-based"
Style_B = "Voice-based"

[prompt.commands]
Description = "Available commands."
prefix = "Choose one of the following commands:"

[prompt.commands.commands]
help = "Get help."
choose_domain = "Choose your area of interest."
choose_complexity = "Choose content complexity level."
choose_interaction = "Choose interaction style."

```
### Educational Platforms
``` toml
# Prompt Engine Template for Educational Platforms

[prompt]
Author = "ChatGPT"
name = "Educational Platform"
version = "1.0.0"

# initial prompt
init = "Welcome to the Educational Platform! This bot will help you personalize your learning experience. Choose your area of interest and adapt to your level of expertise. Let's get started!"

[prompt.features.personalization]
Description = "Personalized learning experience."

[prompt.features.personalization.domains]
Description = "Choose area of interest."
Mathematics = "Learn about algebra, calculus, and geometry."
Science = "Explore physics, chemistry, and biology."

[prompt.features.personalization.complexity]
description = "Adapt to learner's level of expertise."
Level_1 = "Basic concepts and general overview."
Level_10 = "Advanced topics and in-depth analysis."

[prompt.commands]
Description = "Commands for interaction."
start = "Start the learning session."
stop = "End the learning session."
```

### Customer Support
```toml 
[prompt]
Author = "ChatGPT"
name = "Customer Support"
version = "1.0.0"

# initial prompt
init = "Welcome to Customer Support. How may I assist you today?"

[prompt.features.personalization]
Description = "Dynamic customer support."

[prompt.features.personalization.tone_styles]
Description = "Tone of the support."
Friendly = "Friendly and approachable tone."
Formal = "Formal and professional tone."

[prompt.commands]
Description = "Commands for assistance."
help = "Get help with a specific issue."
feedback = "Provide feedback about the service."
```

### Content Exploration
```toml
[prompt]
Author = "ChatGPT"
name = "Content Exploration"
version = "1.0.0"

# initial prompt
init = "Welcome to the Content Exploration bot. This bot will help you explore different types of content in an interactive way. Let's get started!"

[prompt.features.personalization]
Description = "Interactive content exploration."

[prompt.features.personalization.presentation_styles]
Description = "Presentation of content."
List = "Display content as a list."
Grid = "Display content in a grid layout."

[prompt.commands]
Description = "Commands for navigation."
next = "Go to the next page of content."
previous = "Go to the previous page of content."
search = "Search for specific content."
```

### Virtual Assistants
```toml
[prompt]
name = "Virtual Assistant"
author = "ChatGPT"
version = "1.0.0"

# initial prompt
init = "Welcome to Virtual Assistant. This bot provides personalized virtual assistance with conversational or command-based interaction. How can I assist you?"

[prompt.features.personalization]
Description = "Personalized virtual assistance."

[prompt.features.personalization.interaction_styles]
Description = "Interaction style with the virtual assistant."
Conversational = "Conversational and natural language interaction."
Command_Based = "Command-based interaction with specific keywords."

[prompt.commands]
Description = "Commands for virtual assistant."
ask = "Ask a question to the virtual assistant."
reminder = "Set a reminder or schedule an event."
```

### Interactive Narratives
```toml
[prompt]
name = "Interactive Narrative"
version = "1.0.0"
Author = "ChatGPT"
forked_from = ""
init = "Welcome to the Interactive Narrative Bot. This bot will take you through a narrative adventure, where you can make choices and create your own story. Let's get started!"

[prompt.features.personalization]
Description = "Interactive storytelling experience."

[prompt.features.personalization.branches]
Description = "Branching narrative paths."
Path_A = "Follow the first narrative path."
Path_B = "Follow the second narrative path."

[prompt.commands]
Description = "Commands for interactive narrative."
choose = "Make a choice in the narrative."
continue = "Continue to the next part of the story."
```

### Persona and Character Creator
```toml
[prompt]
Author = "ChatGPT"
name = "Interactive Narrative"
version = "1.0.0"

# initial prompt
init = "Welcome to the Persona and Character Creator! This bot will help you create an interactive narrative with branching story paths. Let's get started!"

[prompt.features.personalization]
Description = "Interactive storytelling experience."

[prompt.features.personalization.branches]
Description = "Branching narrative paths."
Path_A = "Follow the first narrative path."
Path_B = "Follow the second narrative path."

[prompt.commands]
Description = "Commands for interactive narrative."
choose = "Make a choice in the narrative."
continue = "Continue to the next part of the story."
```
