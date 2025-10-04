<p align="center">
<img src="https://i.imgur.com/9mLm7RP.png" height="40%" width="40%" alt="AI Automation Project Logo"/>
</p>

<h1>AI-Powered Customer Feedback Reporting Engine</h1>
<p>
This Intelligent Automation (IA) workflow was designed to solve common issues (email fatigue, lack of metrics) found in a basic automation that sent emails for every negative feedback submitted. It transforms raw customer feedback into scheduled, actionable Business Intelligence (BI) reports. The system uses a weekly trigger to analyze data, generate strategic suggestions for improvement, and deliver visual insights via Google Looker Studio to leadership teams.
</p>

<h2>Environments and Technologies Used</h2>

<ul>
    <li>Make.com (Workflow Automation/Orchestration)</li>
    <li>Google Sheets (Data Source/Feedback Repository)</li>
    <li>Gemini AI (Sentiment Analysis, Summarization, Strategic Suggestion Generation)</li>
    <li>Google Looker Studio (Business Intelligence Visualization)</li>
    <li>Email (Weekly Report Delivery)</li>
    <li>Slack API (Team Notification)</li>
</ul>

<h2>High-Level Deployment and Configuration Steps</h2>

<ul>
    <li>Implemented the initial feedback intake workflow (Google Forms $\rightarrow$ Google Sheets).</li>
    <li>Redesigned the architecture from real-time alerting to a weekly scheduled report trigger.</li>
    <li>Configured a single Gemini AI agent to analyze sentiment, summarize feedback, and generate actionable improvement suggestions.</li>
    <li>Established the data connection and created a visual BI dashboard in Google Looker Studio.</li>
    <li>Built a consolidated reporting sequence: AI-generated email report $\rightarrow$ Slack notification $\rightarrow$ Link to visual dashboard.</li>
</ul>

<h2>Weekly Report Examples:</h2>
<p>
<img src="https://i.imgur.com/iLNnu92.png" height="60%" width="60%" alt="Example of AI-Generated Email Report with Suggestions"/>
<img src="https://i.imgur.com/6inLFSa.png" height="60%" width="60%" alt="Example of Google Looker Studio Visual Dashboard"/>
<img src="https://i.imgur.com/9I50cLL.png" height="70%" width="70%" alt="Example of Slack Message"/>
</p>
<br />


<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/dfk0fyv.png" height="80%" width="80%" alt="Miro Workflow Design Diagram"/>
<img src="https://i.imgur.com/HnLXhlU.png" height="80%" width="80%" alt="Make.com Automation Design"/>
</p>
<p>
The project's key value was the architectural redesign. The original simple alert system was replaced with a scheduled BI reporting engine to provide management with strategic, measurable insights.
</p>
<p>
<img src="https://i.imgur.com/WnnbRou.png" height="80%" width="80%" alt="Updated Miro Workflow Design"/>
<img src="https://i.imgur.com/tnjD0Nm.png" height="80%" width="80%" alt="Make.com Updated Automation Design"/>

</p>
<br />

<h3>Step 1: Raw Data Intake and Initial Classification</h3>
<p>
<img src="https://i.imgur.com/gJOLpxS.png" height="40%" width="40%" alt="Google Forms to Google Sheets Intake"/>
</p>
<p>
Customer feedback is captured via Google Forms and logged into Google Sheets. This provides the raw, unstructured data necessary for the subsequent sentiment analysis and BI reporting.
<p>
<img src="https://i.imgur.com/D21KK8N.png" height="80%" width="80%" alt="Google Sheets Report"/>
</p>
</p>
<br />

<h3>Step 2: Scheduled Data Analysis and Cognitive Reporting</h3>
<p>
<p>A weekly scheduled trigger activates the core reporting engine.</p>
<p>
<img src="https://i.imgur.com/KfZKq35.png" height="80%" width="80%" alt="Gemini Analysis"/>
</p>
<p>The single Gemini AI agent receives all new negative feedback entries and performs three cognitive tasks:</p>
<ul>
    <li>Sentiment Analysis: Confirms sentiment (Negative/Positive).</li>
    <li>Summary Creation: Generates a concise summary of the negative feedback themes.</li>
    <li>Strategic Suggestion: Generates 3-5 actionable suggestions for improvement.</li>
  
</ul>
<p>
<img src="https://i.imgur.com/EvRCGvH.png" height="80%" width="80%" alt="Sentiment Added to Sheets"/>
<img src="https://i.imgur.com/1MqciX1.png" height="80%" width="80%" alt="Gemini Generates Report"/>

</p>
<br />

<h3>Step 3: BI Dashboard Integration (Looker Studio)</h3>
<p>
<img src="https://i.imgur.com/6inLFSa.png" height="60%" width="60%" alt="Example of Google Looker Studio Visual Dashboard"/>
</p>
<p>
The Google Sheets data, including the AI-generated summaries and sentiments, is connected to Google Looker Studio. This creates a live, visual dashboard allowing leadership to track trends and quantify feedback categories over time.
</p>
<br />

<h3>Step 4: Consolidated Management Reporting</h3>
<p>
<img src="https://i.imgur.com/k0U6zjM.png" height="80%" width="80%" alt="Report Emailed"/>
<img src="https://i.imgur.com/RA52J88.png" height="80%" width="80%" alt="Slack Message Sent"/>
</p>
<p>
The final output is delivered in a consolidated manner to prevent notification fatigue:
</p>
<ul>
    <li>Email: An email report (generated by Gemini AI) containing the total number of negative feedbacks, the summarized themes, and the improvement suggestions is sent to leadership.</li>
    <li>Slack: A summarized report and direct link to the Looker Studio dashboard are posted to the designated #customer-feedback Slack channel.</li>
</ul>
<p>
<img src="https://i.imgur.com/iLNnu92.png" height="60%" width="60%" alt="Example of AI-Generated Email Report with Suggestions"/>
<img src="https://i.imgur.com/9I50cLL.png" height="70%" width="70%" alt="Example of Slack Message"/>
</p>
<br />
