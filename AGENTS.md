# Azure AI Story Editing Guide

## Artifact and audience

- This is a dependency-free, static GitHub Pages artifact. Keep `index.html` self-contained; do not add a framework, build step, package manager, CDN, telemetry, or external runtime dependency.
- The audience is Azure sellers and customer teams. The page must explain a business-to-architecture story, not act as a product catalog or reference architecture.
- Do not add customer names, customer data, credentials, tenant details, screenshots of customer systems, or other sensitive material to the repository.

## Narrative

- Preserve the two-board sequence: Board 1 frames a concrete business opportunity and evidence; Board 2 progressively reveals the enterprise architecture.
- Board 2 tells the story from work surfaces, to agent building, safe connection, usable capabilities, trusted data, estate governance, and finally back to measurable value.
- Agent 365 is an estate-level inventory, ownership, governance, and observability scope. It is not a runtime request path.
- API Center is design-time catalog/discovery, not a runtime hop.
- API Management / AI Gateway is optional and governs only traffic that crosses its managed boundary.
- Treat Copilot Studio and Foundry as complementary paths that can be used separately or together.
- Preserve coexistence: Microsoft Fabric/OneLake can be promoted without implying that Snowflake, Databricks, SAP, Salesforce, SQL, Excel, PTC, Siemens, or other existing systems must be replaced or migrated.

## Visual and interaction language

- Retain the restrained hand-drawn whiteboard style: warm/light board, hand-drawn SVG outlines, progressive drawing, sparse annotation, and stable semantic colors.
- Do not add product logos, decorative doodles, dense vendor mosaics, or visual effects that compete with the narrative.
- Keep explanatory microcopy where it helps a live seller conversation; put caveats and detailed technical explanation in the click-through drawer.
- Customer-question mode must dim unrelated items, use numbered color-coded routes, and keep the entire focused canvas visible beside the drawer. Do not let the drawer cover a selected node.
- Respect keyboard navigation, `prefers-reduced-motion`, responsive horizontal panning, and the existing no-resize drawer behavior on mobile.

## Technical accuracy

- Before changing claims about fast-moving Microsoft, Azure, agent, model, governance, or interoperability features, refresh official Microsoft Learn or Azure documentation and record the source URL and access date in the change handoff.
- State capability boundaries precisely. Do not imply a universal gateway, automatic third-party onboarding, automatic Agent 365 coverage, or data migration unless official documentation explicitly supports that statement.
- When mentioning external agents, distinguish integration/orchestration, Foundry registration for traces/evaluation, operational telemetry, and Agent 365 estate governance.

## Validation

- Use a tracked local static preview for visual changes and inspect the actual affected flow in a browser.
- Verify the progressive step, question route, drawer content, responsive fit, and no console errors for any changed interactive behavior.
