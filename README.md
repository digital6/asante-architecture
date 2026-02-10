# Asante Generative AI - AWS Architecture Diagram

Interactive AWS architecture diagram for the Asante Generative AI SaaS platform, built for AWS Marketplace listing via Tackle.io.

![Asante Generative AI](https://img.shields.io/badge/Built%20on-AWS-FF9900?style=flat-square&logo=amazonaws)
![Marketplace](https://img.shields.io/badge/AWS-Marketplace-232F3E?style=flat-square&logo=amazonaws)

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ installed
- npm or yarn

### Local Development

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/asante-architecture.git
cd asante-architecture

# Install dependencies
npm install

# Start development server
npm run dev
```

Open http://localhost:5173 to view the diagram.

## 📦 Deploy to GitHub Pages

### Step 1: Update Configuration

1. Edit `package.json` - update the `homepage` field:
   ```json
   "homepage": "https://YOUR_USERNAME.github.io/asante-architecture"
   ```

2. Edit `vite.config.js` - update the `base` field:
   ```js
   base: '/asante-architecture/', // Must match your repo name
   ```

### Step 2: Build and Deploy

```bash
# Build the project
npm run build

# Deploy to GitHub Pages
npm run deploy
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under "Source", select **gh-pages** branch
4. Click **Save**

Your site will be live at: `https://YOUR_USERNAME.github.io/asante-architecture/`

## 🔗 Embed in WordPress

Once deployed, add this to a WordPress Custom HTML block:

```html
<iframe 
  src="https://YOUR_USERNAME.github.io/asante-architecture/" 
  width="100%" 
  height="900px" 
  frameborder="0"
  style="border: none; border-radius: 12px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
</iframe>
```

## 🏗️ Architecture Overview

This diagram showcases the Asante Generative AI platform architecture:

### Core Components

| Layer | Services |
|-------|----------|
| **Voice AI** | Nova Sonic V2, Amazon Connect, Kinesis, Contact Lens |
| **Chat/Messaging** | Lambda, EventBridge, ElastiCache, SQS/SNS |
| **AI/ML Core** | Amazon Bedrock, Knowledge Bases, Agents, Guardrails |
| **Storage** | S3 Vectors, Aurora DSQL, DynamoDB, S3 |
| **Security** | Cognito, WAF, Shield, KMS, IAM Identity Center |
| **Workflow** | Step Functions, Lambda, ECS Fargate, AppFlow |

### External Integrations
- Salesforce (CRM)
- Calendly (Scheduling)
- SharePoint (Knowledge Base)
- ServiceNow (ITSM)
- Slack/Teams (Messaging)
- Custom APIs

## 📄 License

© 2025 Asante Cloud Services. All rights reserved.

## 🔗 Links

- [AWS Marketplace Listing](https://aws.amazon.com/marketplace)
- [Asante Website](https://asantecloud.com)
- [Documentation](https://docs.asantecloud.com)
