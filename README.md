# AI Design: A Responsible AI Framework for Pre-filling Impact Assessment Reports

A semi-automatic framework to help organizations create AI impact assessment reports required by regulations like the EU AI Act.

## Overview

AI Design simplifies the complex and costly process of creating impact assessment reports for high-risk AI systems. The framework consists of two main components:

- **StakeLinker** - Interactive tool for gathering stakeholder input
- **FillGen** - LLM-powered tool for generating pre-filled reports

## Key Features

- **Comprehensive Coverage**: Addresses system use, risks, mitigation strategies, and benefits
- **Multi-stakeholder Input**: Collects perspectives from different roles (designers, engineers, managers)
- **Automated Generation**: Uses GPT-4 to pre-fill reports based on stakeholder input
- **Regulatory Compliance**: Aligned with EU AI Act, Human Rights, and Sustainable Development Goals
- **Role-based Interface**: Adapts content based on user role and AI system phase

## How It Works

### 1. StakeLinker
- Presents 32 curated statements covering all aspects of AI system assessment
- Card-based interface that adapts to user role and system development phase
- Outputs stakeholder responses in PDF and JSON formats

### 2. FillGen
Four specialized prompts process stakeholder input:
- **SysInfoGen**: Generates system description in 5-component format
- **RiskGen**: Identifies risks using EU AI Act, Human Rights, and SDG guidelines
- **BenefitGen**: Discovers potential benefits and positive impacts
- **MitigationGen**: Suggests risk mitigation strategies

## Target Users

- Small and medium companies struggling with AI compliance costs
- AI practitioners (developers, designers, managers) 
- Regulatory compliance teams
- Organizations deploying high-risk AI systems

## Benefits

- **Cost Reduction**: Reduces compliance burden by 10-14% of development costs
- **Time Saving**: Automates initial report creation process
- **Comprehensive**: Covers all required sections for impact assessment
- **Standardized**: Uses consistent format applicable across AI systems
- **Expert Review Ready**: Generates reports suitable for regulatory expert review

## Research Validation

- Tested with 21 AI practitioners across two user studies
- Successfully generated reports for crime analysis, vocational training, and disaster assessment systems
- High usability scores and positive expert feedback

## Getting Started

1. Define your AI system and identify stakeholders
2. Use StakeLinker to collect input from relevant team members
3. Process stakeholder responses through FillGen
4. Review and refine the generated report with regulatory experts

## Authors

**Nokia Bell Labs Cambridge (UK)**
- Edyta Bogucka (edyta.bogucka@nokia-bell-labs.com)
- Marios Constantinides
- Sanja Šćepanović
- Daniele Quercia

## Publication

Published in IEEE Internet Computing. Full paper available at: https://social-dynamics.net/docs/ai-design.pdf

## Project Website

Visit https://social-dynamics.net/ai-design for additional resources and example reports.

---

*Note: This framework provides a starting point for impact assessment reports but still requires expert review and customization for specific AI systems and regulatory contexts.*
