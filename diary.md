# 📓 Developer's Diary – AI Collaboration Guide

This file shows sample entries for your **Developer's Diary**. You must document your AI collaboration throughout the project development. Each entry should have:
- **Artifact**: a screenshot, GIF, or snippet of your AI interaction
- **Context**: one-sentence description of your goal
- **Reflection**: analysis of what happened, what you learned, and how you improved the solution

**Key Principle**: You're directing AI like a junior developer - always review, critique, and improve their suggestions.

---

Entry 1

## Week 8 – Budget Buddy Planning and Six-Step Method

**Artifact:**  
![Budget Buddy Planning 1](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_planning%201.png)

![Budget Buddy Planning 2](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_planning%202.png)

![Budget Buddy Planning Structure 1](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_planning%20structure%201.png)

![Budget Buddy Planning Structure 2](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_planning%20structure%202.png)

![Budget Buddy Planning Structure 3](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_planning%20structure%203.png)

**Context:**  
I used AI to help choose a Budget Buddy theme and complete the planning stages of the six-step development methodology.

**Reflection:**  
AI helped me break the assignment into a clear finance problem, inputs and outputs, manual calculations, and pseudocode. The main improvement was changing the starter template into my own project-specific plan instead of leaving generic placeholder text. AI also helped me avoid formatting issues in Colab by using AUD instead of dollar signs in markdown. I learned that AI is most useful when I provide the project context and then review the output before adding it to my notebook.
---

### Entry 2 
## Week 9 – Data Cleaning and Spending Analysis

**Artifact:**

![Budget Buddy Code Cleaning](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_code%20cleaning%20.png)

![Budget Buddy Output](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_output.png)

![Budget Buddy Spending Analysis Function](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_spending%20analysis%20function.png)

**Context:**  
I used AI to help implement and test the first Python functions for Budget Buddy, including transaction data cleaning and spending analysis.

**Reflection:**  
AI helped me replace the starter template's placeholder code with working pandas functions. The data cleaning function converted dollar amounts into numeric values, converted dates into datetime format, and checked that required columns were present. I then tested the spending analysis function using `transactions.csv`, which produced category totals, average transactions, refund totals and spending percentages. I learned that testing each function immediately makes debugging easier and helps confirm that the assistant is producing meaningful finance insights.

---
### Entry 2.1
## Week 9 – Financial Recommendation + Updated decimal place (adding code)

**Artifact:**

![Budget Buddy 2 Decimal Code](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_%202%20decimal%20code.png)

![Budget Buddy 2 Decimal Place Code](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_2%20decimal%20place%20code.png)

![Budget Buddy Decimal Update](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_decimal%20update.png)

![Budget Buddy Financial Recommendation](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_finanical%20recommendation.png)

**Context:**  
I used AI to help implement the main Budget Buddy data pipeline: cleaning transaction data, analysing spending patterns, and generating financial recommendations.

**Reflection:**  
AI helped me turn the starter template into working Python functions. The cleaning function converted dollar values into numeric amounts and converted dates into datetime format. The spending analysis function grouped transactions by category and calculated totals, averages, transaction counts and percentages. The recommendation function then used those results to generate a readable Budget Buddy report. I tested the output using `transactions.csv` and confirmed that Groceries was correctly identified as the highest spending category. I learned that separating the project into cleaning, analysis and reporting functions made the code easier to test and improve.

I also used AI to refine the spending summary formatting by rounding currency and percentage values to two decimal places. This improved the readability of the recommendation report and made the output look more professional for a finance assistant.

---

### Entry 3 – Finance Chatbot Integration
![Hands-on-AI Fixed Output](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_handsonai_fixedoutput.png)

![Hands-on-AI Fix](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_handsonaifix.png)

![Hands-on-AI Updated API](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbudyhandsonaiupdated_api.png)

**Context:**  
I used AI to help update the hands-on-ai configuration and create a finance-focused chatbot personality for Budget Buddy.

**Reflection:**  
AI helped me identify that the original hands-on-ai server/model details were outdated. After updating the server, model and API key, the chatbot connection worked correctly. I then used AI to help design a Budget Buddy chatbot personality that gives friendly and practical budgeting advice without pretending to be a licensed financial advisor. I tested the chatbot with a coffee spending question and confirmed that it gave a useful response. I learned that AI integrations can break when external configuration changes, so it is important to test the connection and document the fix.
---

## Advanced Integration Examples

## Entry 5 – RAG Financial Document Retrieval

**Artifact:**

![Budget Buddy RAG AI Prompt](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_ragsystem_aicollab_prompt.png)

![Budget Buddy RAG AI Collaboration 1](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_ragsystem_aicollab.png)

![Budget Buddy RAG AI Collaboration 2](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_ragsystem_aicollab_2.png)

![Budget Buddy RAG Explanation](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_ragsystem_aicollab_explaination.png)

**Context:**  
I used AI to help design and implement a simple RAG component for Budget Buddy.

**Reflection:**  
AI helped me understand how RAG could fit into my Smart Finance Assistant without making the project too complex. Instead of using a large external vector database, I used short financial guidance documents inside the notebook and retrieved the most relevant document based on the user’s question. I chose this approach because it works well in Google Colab, is beginner-friendly, and clearly connects to the Budget Buddy theme.

The RAG system retrieves context about topics such as budgeting basics, coffee spending, groceries, entertainment spending, and savings goals. This retrieved context is then passed to the AI model so that the chatbot response is more focused and relevant. I learned that RAG is not just about generating an answer; it is about retrieving useful information first and using that information to improve the quality of the response.

---

## Entry 6 – Custom Savings Goal Tool

**Artifact:**

![Custom Financial Tool Prompt](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_custom_financial_tool_prompt.png)

![Custom Financial Tool Logic](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_custom_financial_tool_code_logic.png)

![Custom Financial Tool Considerations](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_custom_financial_tool_considerations.png)

![Custom Financial Tool Code Output](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_custom_financial_tool_code_output.png)

![Custom Financial Tool Output](AI-CONVERSATIONS/AI%20EVIDENCE/budgetbuddy_custom_financial_tool_output.png)

**Context:**  
I used AI to help design and implement a custom savings goal calculator tool for Budget Buddy.

**Reflection:**  
AI helped me plan the logic for a savings calculator that takes current savings, monthly contribution and target amount, then estimates how many months are needed to reach the goal. The AI collaboration was useful because it helped identify important edge cases, such as invalid inputs, negative values, zero monthly contribution and situations where the user has already reached the savings target. I reviewed the suggested logic and implemented it as a user-friendly Budget Buddy tool. I learned that custom tools make the assistant more useful because they perform specific calculations rather than only giving general advice.

---------------------------------------------------

### Entry 7 – Professional Error Handling
**Artifact:** Code snippet showing error handling for file uploads.

**Context:** I needed my Gradio interface to handle bad CSV files gracefully.

**AI Suggestion:** Generated try/catch blocks with business-appropriate error messages:
```python
try:
    df = pd.read_csv(file.name)
    # Analysis code...
except FileNotFoundError:
    return "Please upload a valid CSV file."
except pd.errors.EmptyDataError:
    return "The uploaded file appears to be empty. Please check your data."
```

**Reflection:** AI helped me think about user experience, not just technical functionality. Good error messages help users understand what went wrong and how to fix it. This is crucial for business applications.

---

## AI Collaboration Best Practices I've Learned

### 🎯 Effective Prompting Strategies
1. **Always provide business context**: "I'm building a finance assistant for..."
2. **Specify data structure**: "My CSV has columns X, Y, Z with these data types..."  
3. **Request professional formatting**: "Format output for business presentation"
4. **Ask for comments**: "Include clear comments explaining the business logic"

### 🤔 Critique Questions I Always Ask
- "Does this handle edge cases like negative amounts or missing data?"
- "Are the variable names clear for a business context?"
- "How would I explain this code to a non-technical manager?"
- "What assumptions is this code making about my data?"

### 🔄 Iterative Improvement Process
1. **Get basic working code** from AI
2. **Test with real data** and find issues  
3. **Ask AI to fix specific problems** with context
4. **Simplify complex solutions** for maintainability
5. **Add business-appropriate formatting** and error handling

### 📊 Business Value Focus
- Always connect code back to business decisions
- Format outputs for non-technical users
- Include actionable insights, not just data summaries
- Consider the end user's needs and context

---

## 📝 Documentation Template for Your Entries

Use this format for consistent diary entries:

```markdown
### Entry [Number] – [Descriptive Title]
**Artifact:** [Screenshot/code snippet/GIF of AI interaction]

**Context:** [One sentence: what you were trying to achieve]

**My Prompt:** "[Your exact prompt to AI]"

**AI Response Summary:** [Brief description of what AI provided]

**My Critique/Improvement:** [How you modified or improved the AI's suggestion]

**Result:** [What you ended up with and why it's better]

**Reflection:** [What you learned about AI collaboration, business programming, or problem-solving]
```

---

✅ **Remember**: Document your AI collaboration throughout your project development. Each entry should show learning and improvement, not just successful interactions. Show how you direct AI like a junior developer to create business-appropriate solutions.

