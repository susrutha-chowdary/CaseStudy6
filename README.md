# GenAI Based ShopAssist Application
### Introduction
In this project, task is to build ShopAssist AI, which is a laptop recommendation chat-bot that can:

- Interact with users interactively,
- Understand the user’s laptop requirements, and,
- Recommend the most suitable laptops based on their needs and preferences.
### Project Background
Given a dataset containing laptop information (including product names, specifications, descriptions, etc.), develop a chatbot named ShopAssist AI that parses the dataset and provides accurate laptop recommendations based on user requirements. ShopAssist AI will:

- Interact with users,
- Understand their laptop requirements,
- Recommend the most suitable laptops from the dataset based on their needs and preferences.

Primarily, this chatbot will analyze the ‘Description’ column for each laptop to determine if the user’s requirements match the laptop’s specifications, and then forward a relevant laptop as a recommendation

### 1.Understanding User Requirement
This stage will proactively engage with the user to understand their requirements. It’s crucial for the user to provide all necessary information to filter products from the database. Therefore, this stage will maintain an active conversation with the user until all required product information is gathered. Once all necessary details are obtained, they will be passed to the next stage in the appropriate format.

### 2.Product Mapping & Extraction

First, all details about the products in the database are gathered, and information is extracted in the same format as provided by Stage 1. A strict comparison is then made to filter out only those products that match the user requirements specified in Stage 1. Consequently, only the top 3 filtered products will be sent to the next stage for recommendation to the user.
### 3.Product Recommendation
At this stage, the chatbot acts as an effective sales representative, elaborating on the products provided by the previous stage. The chatbot needs to explain the filtered products to the user from their perspective or profile, carefully detailing all the information accurately.

Finally, all the stages are combined to form an interactive chat-bot.
