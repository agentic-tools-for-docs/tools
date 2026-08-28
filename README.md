# agentic-tools-for-docs

This repo tracks tools that could be useful for agentic documentation, for example, retrieval or embedded assistants working over existing docs, or documentation that can act rather than simply explain. If you come across anything useful, do add it to the discussion forum: https://github.com/agentic-tools-for-docs/tools/discussions

## Retrieval / embedded assistants over existing docs 
| Service | Description | Documentation Preparation Requirements | Required Skills | Estimated Cost |
|---|---|---|---|---|
| **GitBook Assistant** <br>[AI Assistant](https://gitbook.com/docs/ai-for-your-readers/gitbook-ai-assistant) | AI assistant trained on GitBook documentation that can be embedded within documentation sites, customer portals, products, or marketing websites to answer questions using existing documentation. | Documentation should already reside in GitBook or be migrated to GitBook. Content should be organised into collections, use consistent navigation, contain comprehensive API documentation, FAQs, release notes, and be regularly maintained. | GitBook administration, documentation management, technical writing, prompt tuning, access control configuration, analytics, and website/product embedding. Minimal AI engineering required compared with custom RAG solutions. | **Free** – $0/site/month (individuals): block-based visual editor & custom blocks, sync with GitHub/GitLab, interactive API playgrounds, preview deployments, LLM optimizations.<br><br>**Paid plans**: typically £100–£500+/month depending on plan. |
| **Mintlify Agentic Retrieval** <br>[AI-native documentation](https://www.mintlify.com/docs/ai-native) | Advanced documentation retrieval where AI agents can search, retrieve, reason over documentation, and call tools rather than relying solely on semantic search. Suitable for complex developer documentation and API ecosystems. | Documentation should be comprehensive, modular, consistently formatted, linked across topics, include code examples, API references, schemas, changelogs, and structured metadata. Documentation often benefits from refactoring before indexing. | Documentation engineering, AI/RAG architecture, vector search, embeddings, LLM orchestration, prompt engineering, API integrations, tool calling, knowledge graph concepts, observability, and evaluation of AI responses. | **Starter** – $0/mo (individuals & small teams): full platform, custom domain, web editor, authentication, MCP server.<br><br>**Growth** – $450/mo (startups & growing teams): everything in Starter + Agent, Assistant, Automations, preview deployments, admin APIs.<br><br>**AI usage**: £200–£2,000+/month depending on scale and traffic. |


## Documentation that can act (not just explain) 


| Solution | Documentation Preparation Requirements | Required Skills | Typical Service Cost |
|---|---|---|---|
| **WalkMe**<br>[walkme.com](https://www.walkme.com/) | Business processes must be documented as structured workflows. Applications require mapping, element identification, and maintenance of process documentation. Content should be modular and version-controlled to support automated guidance. | Business analysis, process mapping, digital adoption platform configuration, JavaScript (for advanced customisation), UX design, change management. | Enterprise pricing. Typically US$15,000–100,000+ per year, depending on users and applications supported. |
| **Whatfix**<br>[whatfix.com](https://whatfix.com/) | Existing SOPs, user guides, and knowledge articles need to be converted into interactive, step-based guidance. Documentation should be standardised, regularly maintained, and aligned with business workflows. The Authoring Agent benefits from well-structured documentation with consistent terminology. | Technical writing, instructional design, process documentation, Whatfix platform administration, business analysis, change management. | Enterprise subscription. Typically US$20,000–150,000+ annually, depending on deployment scale and modules. |
| **Glean**<br>[glean.com](https://www.glean.com/) | Requires well-governed documentation across platforms such as Microsoft 365, Google Workspace, Confluence, SharePoint, Jira, Slack, and email. Documents should have appropriate permissions, metadata, and consistent taxonomy. Minimal rewriting is required if documentation is already well organised. | Information architecture, knowledge management, enterprise search configuration, security and access management, AI governance, system integration. | Enterprise licensing. Generally US$30–60 per user/month, with enterprise agreements often starting around US$100,000+ annually for larger organisations. |

## Clone
```bash
git clone git@github.com:agentic-tools-for-docs/tools.git
```
