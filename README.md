# Ex-4.Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE:                                                                            
### REGISTER NUMBER : 212222220047
### Aim: 
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Algorithm: 

## 1. Straightforward Prompts

#### Objective: 
  The goal of straightforward prompts is to ensure the chatbot responds directly and clearly to customer inquiries. This approach works best for simple, direct questions where a short and to-the-point answer is sufficient.

#### Prompt Pattern: 
  *Prompt:*  
  "When a customer asks for the status of their order, reply with:  
  'Your order is currently being processed and will be delivered by [date].'"

#### Explanation:  
  This approach enables the chatbot to provide a succinct, no-frills response. It reduces complexity by sticking to the essential details, ensuring that customers receive the information they need without unnecessary elaboration. The tone remains polite and professional, maintaining a positive customer experience.


## 2. Tabular Format Prompting

#### Objective:  
  This technique is used to present data in a structured and visually organized manner. When a customer asks for information that involves multiple variables (such as product availability or order details), using a table can help convey the information in an easily digestible format.

#### Prompt Pattern: 
  Prompt:  
  "If a customer asks for product availability, respond with the following table format:  

  | Product Name   | Availability Status | Expected Delivery |  
  |----------------|---------------------|-------------------|  
  | XYZ Headphones | In Stock            | 3-5 business days |  
  | ABC Laptop     | Out of Stock        | 2 weeks           |"

#### Explanation:  
  Tabular format prompting is effective when the chatbot needs to handle multiple pieces of information simultaneously. A table helps to organize data, making it clear and easy for the customer to compare and understand. This approach is particularly useful when providing details like availability, delivery times, or product specifications, as it minimizes confusion.
  
## 3. Preceding Question Prompting
#### Objective:  
  Preceding question prompting tailors the chatbot’s responses by referencing the customer’s previous inquiries. This technique adds context to the conversation, allowing the chatbot to give more personalized and relevant answers. It is especially useful in troubleshooting scenarios or when the customer has ongoing issues.

#### Prompt Pattern: 
  Prompt:*  
  "If the customer previously asked for troubleshooting help, respond with:  
  'Based on your previous message about troubleshooting your device, here’s what you can do next…'"

#### Explanation:
  By referencing the previous question, this approach ensures that the chatbot provides a more context-aware response. It helps to reduce redundancy by acknowledging the customer's prior issue and offering a continuation of the support. This technique makes the conversation feel more natural and less repetitive, enhancing the overall customer experience.


### Implementation and Execution:

The chatbot was developed to incorporate the following prompting techniques:

1. Straightforward Prompts were employed to handle simple inquiries such as order status or product availability. These prompts ensured that the chatbot provided concise and clear responses to direct questions.
   
2. Tabular Format Prompting was used when customers requested detailed information, such as product availability or shipping details. Presenting this data in a structured format helped the chatbot deliver responses that were both clear and easy to understand.

3. Preceding Question Prompting was applied when the chatbot needed to continue a conversation based on previous customer inquiries. This allowed the chatbot to offer context-sensitive responses, improving the flow and relevance of the interaction.


### Result:
The chatbot successfully handled a variety of customer queries, including troubleshooting, order tracking, and general product inquiries, using the designed prompting techniques.
