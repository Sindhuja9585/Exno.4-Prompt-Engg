# Ex-3.Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE:                                                                            
### REGISTER NUMBER : 212222220047
## Aim: 
The aim of this experiment is to design and develop an AI-powered chatbot that can assist users with product-related queries, such as troubleshooting, order tracking, and general inquiries. The chatbot should be capable of responding accurately and promptly by leveraging various prompting techniques to deliver natural, context-sensitive conversations. This approach enhances both efficiency and user satisfaction in digital customer service interactions.

## Algorithm: 
## 1. Problem Identification
Understand the nature of queries customers commonly raise—e.g., order tracking, product availability, and technical issues.

## 2. Prompt Categorization
Identify and categorize different types of prompts based on interaction type:

    Direct questions
    Data-driven queries
    Contextual follow-ups

## 3. Prompt Design
Design prompt templates that correspond to each category:

    Direct: Straightforward prompts
    Data-driven: Tabular format prompting
    Contextual: Preceding question prompting

## 4. Chatbot Integration
Integrate the prompt templates into the chatbot using appropriate AI/NLP frameworks.

## 5. Testing and Optimization
Evaluate performance with different user scenarios and improve clarity, context-awareness, and naturalness of responses.

# 1. STRAIGHTFORWARD PROMPTS
### Objective:
To handle simple, single-turn interactions where users expect brief and clear answers without additional information or dialogue.

### Use Cases:
    Order status inquiries
    Store hours or contact details
    Shipping fee inquiries

### Prompt Pattern:
"When a customer asks for the status of their order, reply with:
'Your order is currently being processed and will be delivered.'"

### Explanation:
#### Straightforward prompting is suitable when:

    The user query is concise
    No additional background context is needed
    The chatbot needs to respond quickly and clearly

#### This pattern ensures:

    Minimal cognitive load on the user
    Faster resolution of common questions
    Consistent tone and response structure

### Example Interactions:
User: “When will I receive my headphones?”
Chatbot: “Your order is currently being processed and will be delivered by May 15.”

User: “What’s your return policy?”
Chatbot: “You can return any product within 7 days of delivery.”

# 2. TABULAR FORMAT PROMPTING
### Objective:
To present complex information involving multiple attributes—like availability, delivery time, and product specs—in a structured and readable format.

### Use Cases:
    Comparing multiple products
    Displaying availability across locations
    Delivery time estimation

### Prompt Pattern:
"If a customer asks for product availability, respond with:
| Product Name   | Availability Status|    Expected Delivery  |
|----------------|--------------------|-----------------------|
| XYZ Headphones |       In Stock     | 3-5 days business days|
| ABC Laptop	 |       Out of Stock | 2 weeks               |

### Explanation:
Tabular prompts are ideal when the answer includes:

    More than one product/item
    Multiple variables per item (stock status, delivery, price)
    Side-by-side comparisons

### Benefits:
    Reduces text overload
    Highlights key differences
    Saves the customer time

### Example Interaction:
### User: “What products are available under ₹50,000?”
Chatbot:

| Product        | Price     | Availability | Delivery        |
|----------------|-----------|--------------|-----------------|
| HP Pavilion    | ₹45,999   | In Stock     | 3-5 days        |
| Dell Inspiron  | ₹49,000   | Out of Stock | Available in 2 weeks |


# 3. PRECEDING QUESTION PROMPTING
### Objective:
To provide contextually aware responses by referencing previous user input or conversation history. This improves continuity and makes the interaction feel human-like.

### Use Cases:
    Multi-turn troubleshooting
    Follow-up questions
    Personalized recommendations

### Prompt Pattern:
"If the customer previously asked for troubleshooting help, respond with:
'Based on your previous message about troubleshooting your device, here’s what you can do next…'"

### Explanation:
### This pattern:

    Enhances continuity in dialogue
    Reduces repetition for the user
    Makes the chatbot feel intelligent and attentive

### Benefits:
    Supports natural conversation flow
    Builds user trust and satisfaction
    Handles complex support cases more effectively

### Example Interaction:
User: “My device won’t turn on.”
Chatbot: “Have you tried holding the power button for 10 seconds?”

User (later): “Still nothing.”
Chatbot: “Based on your previous message, try charging the device with a different cable. If the issue continues, we recommend visiting a service center.”

## IMPLEMENTATION AND EXECUTION
Each prompting technique was implemented and tested in a chatbot development environment. The development followed these steps:

### 1.Prompt Scripting:
Templates were coded using placeholders (e.g., [date], [product name]) for dynamic response generation.

### 2.Scenario Testing:
Each technique was tested against real-world queries, with variations to assess flexibility.

### 3.User Feedback Simulation:
Mock feedback was collected to assess clarity, usefulness, and tone.

### 4.Refinement:
Adjustments were made to improve transitions, grammar, and data formatting.

### The chatbot responded appropriately across all use cases. For instance:

    Troubleshooting: Handled step-by-step instructions by building on previous interactions.
    Order Tracking: Delivered specific delivery estimates.
    Product Comparison: Used tables to present structured responses.
# CONCLUSION:
In this experiment, we explored how different prompt patterns can be used to enhance chatbot performance. The implementation of straightforward, tabular, and preceding question prompting allowed the chatbot to:

    Provide precise and structured answers
    Handle contextual and multi-turn queries
    Create a seamless user experience

Prompt engineering is an essential skill in building AI chatbots. Choosing the right prompt type based on the user’s need improves response accuracy and overall satisfaction. This experiment validates that prompt design is as critical as the underlying AI model for effective chatbot deployment.

# RESULTS:
The AI chatbot was successful in demonstrating the functionality of diverse prompting techniques. Observed results include:
|       Prompt Type	        |       Strengths	                  |  Challenges                         |
|---------------------------|-----------------------------------|-------------------------------------|
|Straightforward Prompting	| Quick responses, easy to implement|  Limited in scope                   |
| Tabular Prompting	        | Excellent for multi-item data     |  Requires proper formatting support |
| Preceding Prompting	      | Feels personalized, improves UX	  |  Needs memory/context tracking      |

Overall, the chatbot could respond intelligently, adaptively, and professionally to varied customer situations. The conversation flow felt natural and enhanced user satisfaction.
