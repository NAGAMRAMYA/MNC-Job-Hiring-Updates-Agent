## 📸 Project Screenshots

### Dify Workflow

![Dify Workflow](./dify-workflow.png)

### Email Output

![Email Output](./email-output.png)

## 🔄 Workflow

User Input
↓
Gemini 3.5 Flash
↓
HTTP Request
↓
Resend Email
↓
📧 Job Update

## 🎯 Future Improvements

- Automatically collect MNC job openings
- Filter jobs by role and eligibility
- Schedule regular job updates
- Send personalized job alerts

- ## 📖 How to Use

1. Enter the MNC job hiring information into the Dify workflow.
2. The User Input node receives the job information.
3. Gemini 3.5 Flash analyzes and formats the information.
4. The HTTP Request sends the generated update through Resend.
5. The job update is delivered to the configured email address.

## 📌 Example

**Input:**
TCS is hiring Software Developers for freshers.

**Output:**
A structured MNC job hiring update is generated and sent to email.

## 🔐 Security

API keys, passwords, tokens, and private credentials are not included in this repository.

## 🧠 Skills Demonstrated

- AI Agent Workflow Design
- Prompt Engineering
- LLM Integration
- Dify Workflow Automation
- Gemini 3.5 Flash
- HTTP API Integration
- Email Automation with Resend
- JSON
- Workflow Testing & Debugging
- GitHub Project Documentation

##Components

  | Component        | Purpose                              |
| ---------------- | ------------------------------------ |
| Dify             | Workflow orchestration               |
| User Input       | Receives job information             |
| Gemini 3.5 Flash | Analyzes and formats the job details |
| HTTP Request     | Sends the email request              |
| Resend           | Delivers the email                   |
| Gmail/Email      | Receives the job update              |

