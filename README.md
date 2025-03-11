Key Technologies Used
🔹 Streamlit – For building the interactive web interface.
🔹 LangChain – To facilitate prompt engineering and LLM chaining.
🔹 Hugging Face Hub – Hosting and serving the OpenAssistant/oasst-sft-4-pythia-12b-epoch-3.5 model.
🔹 Streamlit-Extras – Used for UI enhancements such as colored headers and vertical space adjustments.
🔹 Dotenv – For loading environment variables (API keys).

🎯 Features & Functionality
✅ 1. Chat Interface with Memory
The chatbot maintains a conversation history.
Responses are stored in Streamlit session state to ensure continuity.
✅ 2. Interactive User Input
Users can enter their queries via a text input field.
The chatbot processes input and returns relevant responses.
✅ 3. Pretrained LLM from Hugging Face
Uses OpenAssistant/oasst-sft-4-pythia-12b-epoch-3.5, a fine-tuned model optimized for conversational AI.
Generates natural, context-aware responses.
✅ 4. Streamlined Prompt Engineering
The PromptTemplate ensures structured input for the LLM.
Uses LangChain’s LLMChain to process user queries effectively.
✅ 5. Customizable & Extendable
The app can be easily modified to use other Hugging Face models.
Supports adjusting model parameters (e.g., max_new_tokens).
💡 How It Works
1️⃣ The user enters a message in the text input box.
2️⃣ The LLM processes the message via LangChain and Hugging Face Hub.
3️⃣ The chatbot generates a response and updates the conversation history.
4️⃣ The UI displays the user’s query and the chatbot’s response in a structured format.
