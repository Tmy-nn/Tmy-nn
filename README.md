# Tomoya Nishimura

**Founder, ACLab · AI & Automation Engineer**

I turn business workflows into working software: clarify the process, build a pilot, connect the data, and document how to use it. I also help global AI and SaaS teams implement their products for Japanese customers.

[Explore my portfolio](https://aclabtech.com/en/) · [Discuss your workflow](https://aclabtech.com/en/#contact) · [LinkedIn](https://www.linkedin.com/in/5t-nishimura/)

## Featured project: StockFlow

For teams sharing inventory, **StockFlow demonstrates a request-and-approval workflow before stock changes**. A reviewer can inspect the proposed movement, then see the resulting inventory and activity history together.

[![StockFlow inventory, request review and activity history with fictional data](https://stockflow.ai-knowledge-board.workers.dev/stockflow-workflow.jpg)](https://stockflow.ai-knowledge-board.workers.dev/)

The screenshot shows a completed approval and a separate preview for the next request.

**Example with fictional data:** a staff member requests equipment for a workshop → a reviewer checks the proposed quantity → approval updates stock and records the movement. You can play both roles in the demo; company role authentication is not implemented.

[Try the workflow](https://stockflow.ai-knowledge-board.workers.dev/) · [Inspect the code](https://github.com/Tmy-nn/stockflow) · [Discuss an inventory or approval workflow for your business](https://aclabtech.com/en/#contact)

The Cloudflare Workers + D1 implementation includes duplicate protection, stock-conflict detection, workspace isolation and transactional activity history. Technical details and public-demo limits are documented in the repository.

## Other demos

| Project | Who it is for and what to try | Live demo |
| --- | --- | --- |
| **[Word Lens](https://github.com/Tmy-nn/word-lens)** | For language learners: scan an everyday object, select it and explore vocabulary in different languages. | [Try it](https://word-lens.ai-knowledge-board.workers.dev/) |
| **[CSV Bridge](https://github.com/Tmy-nn/csv-bridge)** | For operations teams preparing CSV imports: map columns, check invalid rows and export a normalized file locally in the browser. | [Try it](https://csv-bridge.ai-knowledge-board.workers.dev/) |
| **[Japan Pilot Desk](https://github.com/Tmy-nn/japan-pilot-desk)** | For AI and SaaS teams planning a Japanese customer pilot: turn a scenario into draft requirements, acceptance criteria and open questions. | [Try it](https://japan-pilot-desk.ai-knowledge-board.workers.dev/) |

These are independent portfolio demos. StockFlow uses fictional inventory and simulated reviewer actions; it is not connected to a customer system. Word Lens detects a limited set of object categories and can make mistakes. CSV Bridge is a bounded local preparation tool; Japan Pilot Desk generates a rule-based draft for review, not a compliance assessment.

## How I work

- Map the existing workflow and agree on acceptance criteria.
- Build a small working pilot with explicit data boundaries and failure handling.
- Connect the required systems, then provide documentation and practical onboarding.

**Languages:** English and Japanese. **Delivery:** remote.

Have an inventory, approval or data-preparation workflow to build? **[Discuss your process with ACLab](https://aclabtech.com/en/#contact)**. The [portfolio](https://aclabtech.com/en/) explains the work I can help with; these repositories show the implementation, and the demos let you try it.
