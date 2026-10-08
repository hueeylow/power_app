<h2>Power App x Copilot Studio - SmartServe AI Corporate Service Agent</h2>
<h3>1. Introduction</h3>
<p><b>SmartServe AI</b> is a mini corporate service management solution built using <b>Microsoft Power Apps and Microsoft Copilot Studio</b>.</p>

<p>The solution is designed to provide employees with two ways to raise corporate service requests:</p>

<ul>
  <li><b>Submit a service request manually</b> through a structured Power Apps form. </li>
    <li><b>Use an AI-powered conversational agent</b> to guide employees through the request process and submit a ticket on their behalf.  </li>
</ul>

<p>The objective of this MVP is to demonstrate how Power Apps and AI Agent can work together to streamline the employee service request process and provide a more intuitive way for employees to raise and manage service requests.</p>

<p>Instead of requiring employees to navigate through multiple forms or determine which information is required upfront, the AI agent can interact conversationally with the user, identify the nature of the request, collect the necessary information, and seek confirmation before creating the ticket.</p>

<h3>2. Application Design</h3>
<p>The application focuses on the following MVP capabilities:</p>
<ul>
  <li>Create a corporate service request manually </li>
  <li>Create a service request through an AI agent</li>
  <li>Allow the AI agent to collect missing information through conversation with user</li>
  <li>Capture request details such as title, category, description, priority, file attachment</li>
  <li>Store details of submitted request in a central SharePoint list</li>
  <li>View records of submitted service request</li>
</ul>

<p>The application provides <b>two ticket request submission routes</b>, allowing employees to choose between a traditional form-based experience and an AI-assisted conversational experience.</p>

<h4><b>2.1 Manual Service Request Route</b></h4>
<p>Employees can raise a ticket directly through a structured service request form.</p>
<b>Process:</b></br>
Click "Submit New Request"</br> &darr;</br>
Complete the Service Request Form</br> &darr;</br>
Submit the Request</br> &darr;</br>
View the Submitted Record</br>
</br>
<p>The manual approach offers a straightforward and structured way in raising a service ticket request.</p>
<b>insert demo</b> </br></br>


<h4><b>2.2 AI-Assisted Service Request Route</b></h4>
<p>Employees can alternatively use the <b>SmartServe AI Agent </b> to raise a service request through a conversational experience.</p>
<b>Process:</b></br>
Click "Ask AI Agent"</br> &darr;</br>
Start a conversation with the AI Agent</br> &darr;</br>
Describe the service request</br> &darr;</br>
AI Agent asks for any missing information</br> &darr;</br>
AI Agent summarises the request</br> &darr;</br>
User confirms the request</br> &darr;</br>
Ticket is submitted</br> &darr;</br>
View the Submitted Record</br>
</br>

<p>The AI agent is designed to make the ticket-raising process more intuitive by allowing employees to describe their issue naturally rather than filling out every field manually.
For example, instead of navigating through a form, an employee could simply tell the agent:</br></br>
"My laptop monitor is faulty, I need a replacement."</br> </br>
The agent can then ask relevant follow-up questions, collect the required information, and present a summary for confirmation before submitting the service request.
</br></br>
<b>insert demo</b> </br></br>

</p>

<h4><b>2.3 Solution Architecture</b></h4>

The solution combines several Microsoft technologies: </br></br>
<b>Power Apps</b></br>
Employee-facing application and service request interface</br>

<b>Copilot Studio</b></br>
Conversational AI agent for understanding and collecting service requests</br>

<b>Workflow / Automation</b></br>
Processes the request and creates the service ticket</br>

<b>SharePoint</b></br>
Central data store for submitted service requests</br></br>

<b>Insert solution architecture diagram</b> </br></br>

<h3>3. Key Takeaways</h3>

<p>This project demonstrates how <b>Power Apps and Copilot Studio can work together to create a more flexible employee service experience.</b></p>

<p>The key idea is not to replace the traditional form, but to provide employees with <b>alternative to accomplish the same task></b>:</p>
<ul>
  <li><b>Manual route</b> → Structured and familiar </li>
  <li><b>AI route</b>  → Conversational and guided </li>
</ul>

  <p>This MVP also demonstrates how conversational AI can be integrated into an existing business process rather than being used as a standalone chatbot.</p>

  </br>
<a href= "https://www.github.com/hueeylow"> << Back </a>
