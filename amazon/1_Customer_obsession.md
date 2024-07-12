# Customer Obsession
## 1. Definition
Leaders start with the customer and work backwards. They work vigorously to earn and keep customer trust. Although leaders pay attention to competitors, they obsess over customers.

## 2. Sample questions
<details>
<summary><b>Describe a situation where you had to deal with a difficult customer.</b></summary>
<ul>
    <li>
        <b>Situation: </b><br>
        - Software Engineer for a healthcare company<br>
        - In charge of a feature which is about looking for the nearest hospitals in a fixed distance. At first, it worked fine as the search list is sorted in alphabetical order. But when search for a specific hospital starting with 'T' or 'V', it caused problems (crash)<br>
        - The key client felt dissatisfied with it because it was a crucial feature for patients to look up for hospitals in case of emergency<br>
    </li>
    <li>
        <b>Task:</b><br>
        - The feature is deployed on Production Env with Acceptance test -> how important the situation is<br>
        - My task was to identify the root cause of the issues, propose a solution, and implement it to improve the system's performance, ensuring the client could use the app without any issues.<br>
    </li>
    <li>
        <b>Action:</b><br>
        - I began by analyzing the system to pinpoint bottlenecks. This involved reviewing execution plans, examining data retrieval processes, and auditing the entire workflow.<br>
        - Upon identifying the issues, I realized that the table in database is not correctly indexed and pageing<br>
        - To quickly address the client's concerns, I prioritized the implementation of these changes and worked over night to ensure minimal downtime.<br>
        - I maintained transparent and regular communication with the client, providing updates on progress and suggesting new filters that can improve the search engine. I also received their feedback to ensure the solutions met their expectations.<br>
    </li>
    <li>
        <b>Result</b><br>
        - Led to a 19% improvement in execution time and searching<br>
        - The client was satisfied with the increased performance and happy about new features I suggested, gaining their trusts
    </li>
</ul>
</details>

<details>
<summary><b>Describe a situation where you negotiated a win-win.</b></summary>
<ul>
    <li>
        <b>Situation: </b><br>
        - Data Engineer at Bank, marketing team needed access to real-time data analytics to launch a new campaign<br>
        - Data infrastructure was not equipped to handle the increased load without impacting the performance of other critical systems.<br>
        - Created a conflict between the marketing team's needs and the ability to maintain system stability since it run daily.<br>
    </li>
    <li>
        <b>Task:</b><br>
        - Negotiate a solution that would allow the marketing team to access the necessary real-time data without compromising the performance and stability of our data infrastructure<br>
    </li>
    <li>
        <b>Action:</b><br>
        - Initiated meetings with the marketing team and the our IT department to fully understand their needs, concerns, and limitations. This helped in identifying the critical requirements and constraints of each side.<br>
        - After analyzing the requirements, I proposed implementing a dedicated data pipeline for the marketing team using Apache Kafka for real-time data streaming. This would ensure they had access to the necessary data without overloading our primary data infrastructure.<br>
        - In the future, our team can also benefit from those new real-time pipeline => have another plan for combining those pipeline into 1.<br>
        - Negotiated with the IT department to allocate the necessary resources for setting up the new pipeline, ensuring it would not affect our ongoing projects. I also worked with the marketing team to adjust their campaign timelines to accommodate the implementation period.<br>
    </li>
    <li>
        <b>Result</b><br>
        - The implementation of the dedicated data pipeline was successful, allowing the marketing team to access real-time analytics for their campaign without impacting the performance of other systems. => contribute to more than 40% of user engagement.
        - The project resulted in a successful campaign launch, improved collaboration between departments, and enhanced trust in our ability to provide innovative solutions.
    </li>
</ul>
</details>
