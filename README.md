# An Enterprise Agentic AI Primer with n8n

In many enterprise domains, transferring vital and sensitive data into cloud repositories are not allowed due to security issues, government regukations, data governance and possible loss of vital proprietary data due to data breaches incidences. 

Low-code agentic AI tools such as n8n are being increasingly used in enterprise domains to implement agentic AI workflows. However, cloud based n8n instances could be cost prohibitive. Also, seamless installation of n8n can still be an onerous task for many Enterprise or lead AI Arcitects. 

In this, discourse, we have shown a step-by-step method by which n8n can be installed in Window based systems. 

Our final product will be a fully functional Agentic AI workflow that can do calculations. It is shown in figure 1.


<img width="707" height="381" alt="Image" src="https://github.com/user-attachments/assets/1e29fca2-6500-4cae-83ae-ef6a7dce601f" />







## Steps to Obtain the Agentic AI Workflow Shown Above

#### Navigate to n8n.io website https://n8n.io/ and click on docs
---

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/1464af68-0dc0-4c61-b57c-d86cd31aec75" />

---

#### For Windows OS self hosting, select *self host n8n* and the select *npm*. Ensure that you have installed nodejs on your Windows OS before installing n8n. Copy the command below:

```ruby
npm install n8n -g
```


---

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/5c0cb743-18e6-4ed9-bbe9-b8982db3f9b2" />

---

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/779c3e0e-f7e3-466a-9de7-f6afd09fb146" />

---

#### Paste the command on your Windows OS CMD terminal

#### After installation completes, just type *n8n* on your cmd terminal to start n8n. 



---

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/bb056e27-b2c5-4530-b735-ea7b04f1b700" />

---

#### Ideally, n8n will listen on port 5678, hence, your n8n will start on localhost:5678 on your enterprise computer. 

#### Register with an email and obtain a token that you can use to start your workflow
---

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/333c9572-f86d-4c06-b4c8-00ca946d42c3" />

---

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/2f628ee1-844e-4f71-bbed-09bb40c50303" />

---
#### Click start from scratch to create a workflow
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/c35325a8-1d36-48e7-93b0-8617774a4df0" />

---
#### Give your workflow a name 
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/97184316-e5a6-452b-befa-40e01a06dcef" />

---

#### Add tag to give more detailed explanation
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/666970d0-0a47-4a94-8471-812c2d11d42b" />

---

#### Click on *add first step* 
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/a5daf391-44d8-446a-82b9-946fffa55386" />

---

#### Click on chat message to see how the agent interfaces works
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/5d00b882-5d99-4b44-b58e-befd80575c7b" />

---

#### Chat message interface
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/502662b5-77c3-423b-8e6a-a648f4109b61" />

---

#### Click message and add some details in the Notes. Turn on Display Note in Flow and Click Back to Canvas
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/4b503fe6-76bd-4fe8-b745-bd9e8171d787" />

---

#### The chat message agent will be displayed on the canvas
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/e5c77c9a-685e-499f-98f0-ff822a5d8b9b" />

---

#### Click the 3 dots to rename the node
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/8bd4219c-fdbb-45ab-bb62-ee094b6e703c" />

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/77c5aac5-0ae1-4f0d-aea4-9751532dc4e5" />

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/0d67e55f-ce9d-4de2-a1e6-fb230fce281f" />

---

#### Click on the plus on the chat input and select AI
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/0b4ed36f-3046-451f-b683-4b4bc0c03878" />

---

#### Select AI Agent

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/381e3c46-d5b2-49fc-9230-5d0e3881b18c" />

---

#### *Click Back to Canvas*
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/3ae45836-5307-4c38-ac03-30432da998de" />

---

#### Click on the chat model and select OpenAI
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/01e06d4b-4f0d-415b-bf47-0699448e50f5" />

---


#### Click on *Create New Credential*
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/3532ae1d-5daa-4560-a12b-ff89142cd5ed" />

---

#### Create new credentials and add API secret keys from OpenAI
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/a6cf1ba7-ee48-41f7-92e6-7e4fa15636e5" />

---

#### You can rename ur OpenAI Agent, input your secret key and save
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/78ef1b30-8827-4153-aa02-3f5cb374284a" />

---

#### Save, close and select OpenAI agent from the Agent drop down menu
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/0d8a6bfa-b48f-4cd5-919b-a7fa79edbe0f" />

---

#### Select *gpt-4o-mini* to save on cost
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/72476792-de6c-4ada-96fe-7d57df6978b7" />

---

#### Go back to canvas to add memory to your agent
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/cb2792eb-a4e4-4365-8b2a-5bcd6a8d4543" />

---


#### Click on memory and select the *Simple Memory* option
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/40014712-1e3f-4266-8d4e-2d02da2a05d1" />

---

#### You can choose to keep the current memory lenght at the default value of 5
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/eb1f8fb2-d4be-4da6-bdd2-d6cc32e155dc" />

---

#### Now, add a basic tool such as a calculator
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/2d0d5e0c-ce1a-42f0-90fe-39673006eb4c" />

---

#### The basic memory and basic calculator can be used to test if your agent is working
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/4a1573ef-5d7e-4579-9b78-f5ec678e3ac3" />

---

#### Save your model and click on chat to test your workflow
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/0505dbec-b822-40fc-943f-49501ce21d6c" />

---

####  Test the model without any calculation task
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/5c721e87-b7f9-4534-a532-21e893336573" />

---

#### The workflow will run 
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/31fe993c-ae22-47b8-903b-c8eca91a7b3a" />

---

#### Some errors such as billing issues or insufficient fund on the OpenAI billing base. Fund your account adequately
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/7da58988-17b9-4cde-a38c-09bf2e58d84d" />

---


#### Now the workflow works without further issues
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/71b879ce-7f46-4a54-b862-65bfaf3c9a70" />

---

#### Agent show how to use the calculator tool
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/a58fc08b-5b99-4aec-84f1-9d29db46562b" />

---

#### All Agent executions so far
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/5dca5393-205e-4c90-8cfc-eed5371d100a" />

#### Clear the Agent chat history
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/fa0726a4-d67d-4c39-bedf-164b2ca1f2d4" />

---

#### To use this Agent in your own n8n workflow:

Setup Steps
    1. Clone this repo:


git clone https://github.com/yourusername/agentic-ai-workflow.git
cd agentic-ai-workflow

    • Import the provided workflow JSON into your n8n instance.
    • Add your API keys to environment variables or n8n credentials.
    • Start the workflow and interact with the AI agent.



































