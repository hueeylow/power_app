<h2>Power App x Copilot Studio - SmartServe AI Corporate Service Agent</h2>
<h3>1. Introduction</h3>
<p><b>SmartServe AI</b> is a corporate service management solution built using <b>Microsoft Power Apps and Microsoft Copilot Studio</b>.</p>

<p>The solution is designed to provide employees with two ways to raise corporate service requests:</p>

<ul>
  <li><b>Submit a service request manually</b> through a structured Power Apps form. </li>
    <li><b>Use an AI-powered conversational agent</b> to guide employees through the request process and submit a ticket on their behalf.  </li>
</ul>

<p>The objective of this MVP is to demonstrate how Power Apps and an AI agent can be seamlessly integrated into a unified employee service request solution, making it easier for employees to submit and manage their service requests.</p>

<p>The AI agent simplifies the request submission process by allowing employees to describe their needs in their own words. It understands the request, guides employees through the relevant details, and generates a summary for confirmation before creating the service ticket.</p>

<h3>2. Application Design</h3>
<p>The application focuses on the following MVP capabilities:</p>
<ul>
  <li>Create a service request manually, or </li>
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

<p align="center">
  <img src="https://github.com/hueeylow/power_app/blob/main/new_req_clip_1080px.webp" width="1080">
</p>


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

<p>The AI agent is designed to make the ticket-raising process more intuitive by allowing user to describe their issue rather than filling out every field manually.
For example, instead of navigating through a form, the user could simply tell the agent:</br></br>
"My laptop monitor is faulty, I need a replacement."</br> </br>
The agent can then ask relevant follow-up questions, collect the required information, and generate a summary for confirmation before submitting the service request.
</br>

<p align="center">
  <img src="https://github.com/hueeylow/power_app/blob/main/ai_req_clip_1080px.webp" width="1080">
</p>


<h3>3. Key Takeaways</h3>

<p>This project demonstrates how a conversational  AI agent built within Power Apps can streamline service request processes and deliver a more seamless corporate user experience.</b></p>

<p>The key idea is not to replace the traditional form, but to provide employees with <b>alternative to accomplish the same task</b>:</p>
<ul>
  <li><b>Manual route</b> → Structured and familiar </li>
  <li><b>AI route</b>  → Conversational and guided </li>
</ul>

  </br>
<a href= "https://www.github.com/hueeylow"> << Back </a>
