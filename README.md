## 🌟 Welcome to GenAI - Your Gateway to Turning CSV/EXCEL into Conversational Companions! 🌟

<span style="font-size: 14px;">Welcome to Chat with your EXCEL/CSV Files, your platform for seamless interaction with your Files! Whether you're looking to extract insights, brainstorm ideas, or simply explore your documents in a whole new way, Chat empowers you with AI-driven capabilities. Engage in natural language conversations with your PDFs, allowing you to extract valuable information, generate insights, and explore the contents like never before. Let PDF Chat unlock the potential of your documents and streamline your workflow effortlessly.</span>

## Technical Stack
**Programming Language:** Python

**Libraries:** Streamlit, SQLite, SQLAlchemy

**AI:** RAGs, Llama2/3index, IBM GenAI

## Usage
To run the Streamlit app, use the following command:

streamlit run MultiInsight-Text-to-SQL.py

## Instructions

🔑 *Collect Your API Key:*
Before diving into the exciting world of document conversations, you'll need to obtain your API key from BAM platform. This key serves as your passport to unlock the full potential of GenAI. Once you have it, simply enter it below to get started!

🚀 *High-Level Steps:*
Now that you have your API key ready, let's embark on the journey of transforming your CSVs/Excels into conversational companions. Here's a quick overview of what's ahead:

1. **Upload Your CSV/Excel Files:** 📊
   Begin by uploading your CSV/Excel files containing the data you want to interact with. First time, it will take time to create a database and indexing. Each file will be processed separately, and tables will be created for them.

2. **Start Chatting!** 💬
   Ask questions, seek insights, or simply explore the depths of your content - the possibilities are endless!

3. **Download Conversation:** 📥
   At any point during the conversation, you can download the chat transcript in various formats, including Text, Excel, and Word document. Simply choose the desired format and click the download link.

4. **Database Cleanup:** 🗄️
   If you need to manage your database tables, you can perform cleanup operations such as removing tables individually, removing all tables, or removing table schemas. Use the options provided in the sidebar to manage your database.

Ready to witness the transformation? Let's get started!

### Features

### 🤖 Chatbot Features 👦

1. **Versatile Data Support 📊:**
   - Seamlessly handle Excel and CSV formats, ensuring compatibility with a diverse range of datasets.
2. **CSV to SQL Conversion 📊:**

   - Your CSV data will be loaded into tables, with table schemas prepared automatically. The chatbot will convert your prompts into SQL queries to interact with the database.

3. **Intelligent Querying 💬:**

   - The chatbot understands user intent and identifies the right table to query. It intelligently prepares SQL queries to fetch the desired results.

4. **Multiple File Support 📁:**
   - You can upload multiple CSV/Excel files, and a separate table will be created for each file.
5. **Table Parser 🗄️:**

   - Parse structured tables for comprehensive data extraction and analysis, enabling deep insights into dataset dynamics.

6. **Indexing Rows 📈:**
   - Index each row for fast and efficient data retrieval, enhancing performance and user experience.
7. **Schema and Table Synchronization 🔄:**

   - Check for synchronization between table schemas, tables, and indexes to maintain data consistency and prevent discrepancies.

8. **Dynamic Content Generation 🔄:**

   - If an answer is not available in the uploaded CSV/Excel file, the chatbot can generate content for generic questions, code generation, Email writing, etc., using its language model capabilities.

9. **Color Formatting 🎨:**

   - Questions will be displayed in blue color, while Answers will be in green color.

10. **Reset Chat History 🔁:**

    - You can reset your chat history at any time to start afresh.

11. **Download Chat in Excel with Serial Number, Questions, and Answers 📥:**

    - You can download the chat conversation in Excel format with three columns: Serial Number, Questions, and Answers.

12. **Word Document Formatting 📝:**

    - For Word documents, the formatting, including colors, will be maintained. You can also provide a document template for customization.

13. **Download Conversation Output 📄:**

    - You can download the conversation output at any time during the chat in both **Text**, **Word**, and **EXCEL** format.

14. **Multi-Worksheet Support 📂:**

    - MultiInsight Text-to-SQL now supports multiple worksheets within a single Excel or CSV file. When uploading a file with multiple worksheets, MultiInsight Text-to-SQL automatically creates separate tables for each worksheet, enabling users to analyze and query data from different sheets seamlessly.

15. **SQL Query Visibility 👁️:**

    - Enhancing transparency and user experience, MultiInsight Text-to-SQL now displays the SQL query being executed alongside the query result in a side panel. This provides users with full visibility into the backend processes, empowering them to understand and validate the actions performed by the tool.

16. **Downloadable SQL Query Results 💾:**

    - In scenarios where the SQL query result is extensive and cannot be accommodated within the chat output window, MultiInsight Text-to-SQL offers the option to download the complete SQL query result in an Excel sheet format directly from the side panel. This feature ensures that users can access and analyze large datasets conveniently, even when the output exceeds the capacity of the chat interface.

17. **Intelligent Header Detection 🧠:**

    - MultiInsight Text-to-SQL now features intelligent header detection functionality, capable of processing Excel sheets where the header is not located in the first row. Leveraging advanced algorithms, the tool automatically identifies the header row based on contextual clues and data patterns, ensuring accurate parsing and analysis of non-standard Excel datasets. This feature enhances the tool's versatility and usability, allowing users to seamlessly work with Excel files structured in diverse formats without manual intervention.

18. **Additional Features 🛠️:**
    - Display list of available tables
    - Remove a single table
    - Remove all tables
    - Remove table schema

### Try it Out!

Feel free to explore the features of GenAI and turn your CSV/Excel files into conversational companions!

### Use Cases for MultiInsight Text-to-SQL:

1. **Sales Data Analysis:**

   - Scenario: A sales manager wants to analyze sales data to identify trends, top-performing products, and customer demographics.
   - Usage: Upload sales data in Excel or CSV format, use MultiInsight Text-to-SQL to generate SQL queries to extract relevant insights such as sales by region, product categories, or customer segments.

2. **Employee Data Management:**

   - Scenario: HR professionals need to manage and analyze employee data for performance evaluation, payroll processing, and resource planning.
   - Usage: Utilize MultiInsight Text-to-SQL to parse employee data, retrieve specific information like employee demographics, performance metrics, and salary details, facilitating informed decision-making and resource allocation.

3. **Incident Data Handling:**

   - Scenario: IT support teams aim to efficiently manage and resolve incidents reported by users to maintain system uptime and reliability.
   - Usage: Employ MultiInsight Text-to-SQL to parse incident data, analyze trends, identify recurring issues, and prioritize resolution efforts based on severity and impact.

4. **Performance Log Analysis:**

   - Scenario: System administrators need to analyze performance logs to optimize system performance, identify bottlenecks, and troubleshoot issues.
   - Usage: Upload performance log data in Excel or CSV format, leverage MultiInsight Text-to-SQL to parse and analyze log data, extract performance metrics, and identify optimization opportunities.

5. **Generic Use Cases of Large Language Models (LLM):**

   - Scenario: Users require assistance with various tasks such as code generation, email drafting, understanding already written code, debugging code, and responding to generic queries based on the uploaded data.
   - Usage: Utilize MultiInsight Text-to-SQL for a wide range of applications, including:
     - Generating code snippets for programming tasks across different languages and frameworks.
     - Drafting emails or other communication based on provided templates or user input.
     - Translating code between different programming languages for interoperability or migration purposes.
     - Understanding and analyzing already written code, including identifying errors, optimizing performance, or enhancing readability.
     - Debugging code by providing insights into potential issues, suggesting fixes, or tracing execution paths.
     - Responding to generic queries by leveraging the power of large language models (LLM), providing relevant information, recommendations, or explanations based on the context of the query and the uploaded data. These capabilities enhance productivity and collaboration across various domains and tasks, empowering users to efficiently handle diverse challenges in software development, communication, and data analysis.

6. **Interactive Communication with Data:**
   - Scenario: Users need to communicate and interact with data stored in Excel or CSV files, including those with multiple worksheets, in plain English language.
   - Usage: MultiInsight Text-to-SQL facilitates seamless communication and interaction with data through plain English queries, enabling users to ask questions, retrieve information, and receive answers in a natural language format. This capability extends to datasets of varying sizes and structures, ensuring accessibility and ease of use for users across different scenarios and requirements.
