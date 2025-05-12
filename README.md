**Expt. No.: 4**
 
**Date:**

**Register number : 212222060093**

**Developed by : Jayasurya S**

**Experiment Title:** Scenario-Based Report Development Utilizing Diverse Prompting Techniques

**Aim:** To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone.

---

**Table of Contents:**

1. Introduction
2. Objective
3. Prompting Techniques Overview
4. Methodology
5. Implementation with Prompting Techniques

   * 5.1 Straightforward Prompting
   * 5.2 Tabular Format Prompting
   * 5.3 Preceding Question Prompting
6. Use Case Scenarios
7. Evaluation
8. Results and Discussion
9. Conclusion

---

**1. Introduction**

Customer support services have seen a transformation with the integration of artificial intelligence (AI). Among AI applications, chatbots stand out as a cost-effective and scalable solution for handling customer interactions. Chatbots provide timely, automated responses while reducing human workload. This experiment focuses on developing an AI-powered chatbot capable of product troubleshooting, order tracking, and managing general inquiries using various prompting techniques.

**2. Objective**

To implement a scenario-driven AI chatbot using three prompting techniques to ensure enhanced understanding, response accuracy, and conversational flow:

* Straightforward Prompts
* Tabular Format Prompting
* Preceding Question Prompting

**3. Prompting Techniques Overview**

Prompting techniques are strategies for instructing AI models effectively. The three techniques explored are:

* **Straightforward Prompting**: Involves direct questions to obtain precise responses.
* **Tabular Format Prompting**: Uses tabular data for structured information delivery.
* **Preceding Question Prompting**: Leverages prior conversation context to guide responses.

**4. Methodology**

We used scenario-based analysis to simulate user interactions across different functions. Each scenario was implemented using a selected prompting technique. The chatbot’s responses were evaluated for relevance, clarity, and consistency.

Steps:

1. Define user intent for each function (e.g., troubleshooting, tracking, inquiry)
2. Frame prompts based on each technique
3. Generate chatbot responses using simulated AI logic
4. Analyze responses for quality metrics

**5. Implementation with Prompting Techniques**

**5.1 Straightforward Prompting**

This technique is most suitable for singular queries with no context.

**Example:**

* **User Query:** “How can I reset my password?”
* **Prompt to AI:** “Provide steps to reset password.”
* **Expected Response:** “Go to the login page, click 'Forgot Password', and follow the instructions sent to your registered email.”

**Analysis:**

* Response is clear and concise
* Minimal computational effort

**5.2 Tabular Format Prompting**

Used to process and respond to structured data such as order tracking.

**Example Table:**

| Order ID | Status     | Delivery Date |
| -------- | ---------- | ------------- |
| 70123    | Shipped    | 2025-05-13    |
| 70124    | In Transit | 2025-05-14    |

**Prompt to AI:** “Summarize the delivery status of these orders.”

**Expected Response:** “Order 70123 has been shipped and will arrive by May 13. Order 70124 is in transit, expected on May 14.”

**Analysis:**

* Efficient for multiple entries
* Easy to interpret

**5.3 Preceding Question Prompting**

Retains context over a session for multi-turn queries.

**Example:**

* **User:** “My laptop won't charge.”
* **AI:** “Have you checked the power adapter and port?”
* **User:** “Yes, both seem fine.”
* **Prompt to AI:** “Suggest reasons and solutions if adapter and port are fine.”

**Expected Response:** “The battery may be faulty or the internal charging circuit may be damaged. Please visit a service center.”

**Analysis:**

* Context retention improves relevance
* Natural conversation flow

**6. Use Case Scenarios**

| Scenario | Prompting Technique | Function                |
| -------- | ------------------- | ----------------------- |
| S1       | Tabular Format      | Order tracking          |
| S2       | Straightforward     | Password reset          |
| S3       | Preceding Question  | Product troubleshooting |

Each scenario was executed and results were documented to evaluate chatbot performance.

**7. Evaluation**

The chatbot was assessed based on the following criteria:

* **Accuracy**: Did it provide the correct response?
* **Clarity**: Was the response understandable?
* **Relevance**: Was the response suitable for the prompt?
* **Continuity**: Especially for multi-turn conversations

**Results Summary:**

| Technique          | Accuracy | Clarity | Relevance | Continuity |
| ------------------ | -------- | ------- | --------- | ---------- |
| Straightforward    | High     | High    | High      | Low        |
| Tabular Format     | High     | Medium  | High      | Low        |
| Preceding Question | Medium   | High    | High      | High       |

**8. Results and Discussion**

* Straightforward prompts yielded quick and effective answers but lacked multi-turn capabilities.
* Tabular format prompting was ideal for structured responses but required precise formatting.
* Preceding question prompting showed the best contextual understanding, ideal for troubleshooting.

Challenges included ambiguity in user input and occasional overreliance on previous turns. These were mitigated by including clarification prompts and session reset mechanisms.

**9. Conclusion**

The experiment successfully demonstrated the effectiveness of diverse prompting techniques in building a scenario-based AI chatbot. Each technique serves a unique purpose, and their combined use can create a robust, user-friendly assistant for customer service.

