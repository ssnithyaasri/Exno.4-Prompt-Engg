# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE:                                                                            
### REGISTER NUMBER : 212222230100
### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Introduction
This case study explores the design of an AI-powered customer service chatbot focused on product troubleshooting, order tracking, and general inquiries. We'll examine three different prompt engineering approaches to achieve optimal performance:

### Straightforward Prompts
### Tabular Format Prompting
### Preceding Question Prompting

### Approach 1: Straightforward Prompts
### Design Pattern
Straightforward prompts provide clear, direct instructions for the AI without complex formatting or structure.
Example Implementation
You are a helpful customer service chatbot for TechGadgets Inc. Your goal is to assist customers with:
1. Product troubleshooting
2. Order tracking
3. General inquiries

When responding:
- Be conversational and friendly
- Keep responses concise
- Ask clarifying questions when needed
- Provide specific solutions when possible
- Escalate complex issues to human support

How would you respond to a customer asking about a delayed order?
Analysis
Strengths:

Simple to implement and maintain
Clear instructions for basic functionality
Accessible for non-technical team members

## Limitations:

May lack nuance for complex scenarios
Limited context for diverse customer situations
No structured guidance for different query types

### Approach 2: Tabular Format Prompting
### Design Pattern
Tabular prompts organize information in structured tables to provide clear guidelines for different types of customer interactions.
Example Implementation
You are a customer service chatbot for TechGadgets Inc. Use the following response framework:

| Query Type | Response Approach | Example Phrases | Escalation Criteria |
|------------|-------------------|-----------------|---------------------|
| Product troubleshooting | 1. Ask for product model<br>2. Identify specific issue<br>3. Provide step-by-step solution | "Could you share which model you're using?"<br>"Let's try these steps..." | After 3 failed solution attempts |
| Order tracking | 1. Request order number<br>2. Provide status update<br>3. Explain next steps | "I'll need your order number to check that"<br>"Your order is currently..." | Shipping delays >7 days |
| Product information | 1. Identify product category<br>2. Provide key features<br>3. Share pricing details | "Our latest model includes..."<br>"This product is priced at..." | Highly technical specifications |
| Returns/refunds | 1. Verify purchase details<br>2. Explain policy<br>3. Provide process steps | "Our return policy allows..."<br>"To initiate a return..." | Special circumstances outside policy |

Maintain a conversational tone while following these guidelines. How would you handle a customer asking about a delayed order?
Analysis
## Strengths:

Highly structured approach for consistency
Clear guidelines for different query categories
Explicit escalation criteria
Easy to update specific response types

## Limitations:

More complex to maintain
May feel rigid if followed too strictly
Requires regular updates for new query types

### Approach 3: Preceding Question Prompting
### Design Pattern
This approach provides example Q&A pairs that model desired chatbot responses, helping establish the right tone and approach through demonstration.
Example Implementation
You are a customer service chatbot for TechGadgets Inc. Use these example interactions as a guide for your response style:

Q: "My order #TG78921 was supposed to arrive yesterday but it's still not here."
A: "I understand how frustrating shipping delays can be. I've checked your order #TG78921, and I see it's currently in transit. According to our tracking system, there was a weather delay affecting deliveries in your region. Your package is now expected to arrive tomorrow. Would you like me to send you an updated tracking link?"

Q: "My new SmartHome Hub keeps disconnecting from WiFi."
A: "I'm sorry to hear you're having connection issues with your SmartHome Hub. Let's troubleshoot this together. First, which model of the SmartHome Hub do you have? Also, have you tried power cycling both your hub and router by unplugging them for 30 seconds?"

Q: "What's the difference between your Basic and Premium subscription plans?"
A: "Great question! Our Basic plan includes access to standard features at $9.99/month. The Premium plan adds priority support, cloud storage, and advanced analytics for $14.99/month. Based on your needs, are you looking for specific features from either plan?"

Using a similar conversational style, how would you respond to a customer asking: "My order is delayed"?
Analysis
## Strengths:

Teaches by example rather than explicit rules
Demonstrates natural conversation flow
Shows nuanced handling of different scenarios
Establishes appropriate tone and depth

## Limitations:

Requires careful selection of representative examples
May not cover all edge cases
Can be lengthy in the prompt

### Comparative Analysis:
### Response Quality
### Straightforward Prompts:
Provides adequate responses for common queries
May lack depth for complex troubleshooting scenarios.
### Tabular Format:
Delivers consistent, structured responses
Better handling of category-specific nuances
### Preceding Questions:
Produces most comprehensive and thoughtful responses
Better anticipates customer needs and follow-up questions
### Implementation Complexity
### Straightforward Prompts:
Minimal design effort required
Simple to deploy and modify
Limited planning or categorization needed
### Tabular Format:
Requires careful planning of query categories
Needs thoughtful examples for each category
More structured maintenance process
### Preceding Questions:
Demands sophisticated prompt engineering
Requires deep understanding of customer journey
More difficult to debug and optimize
## Adaptability to Different Scenarios
### Straightforward Prompts:
Functions adequately for expected queries
Struggles with unusual or complex requests
### Tabular Format:
Good handling of predefined categories
Can accommodate new categories with prompt updates
Some rigidity when queries cross multiple categories
### Preceding Questions:

Excellent adaptation to unexpected scenarios
Better synthesis of multiple information sources
Superior handling of emotionally charged interactions



# Result: 
This case study concludes with a recommended hybrid implementation strategy that combines elements from multiple approaches to create an effective customer service solution. .

