# Perplexity Spaces Template for Custom AI Agent Creator - Version 2.0
# Author: Product Management Agent (Copilot)
# Date: 2025-09-18

meta:
  title: "Custom AI Agent Creator for Claude Code"
  description: >
    This version externalizes the curated Link Library to a dedicated GitHub repository,
    leveraging the Perplexity Spaces Links Feature for reference management.
    It embeds formal collaboration guidelines, SRE-inspired iterative workflow steps,
    and instructions on how to utilize and update the external Link Library repository.
  author: "Product Management Agent (Copilot)"
  version: "2.0"
  created: "2025-09-18"
  tags:
    - AI Agents
    - Claude Code
    - Multi-Agent Systems
    - Agent Engineering
    - Prompt Engineering
    - Site Reliability Engineering
    - Link Library Externalization

custom_instructions:
  overview: >
    This Space guides users through the autonomous, collaborative creation of Claude Code Custom AI Agents
    by coordinating three domain expert profiles, following rigorous SRE-based methodologies.
    The curated Link Library is externally maintained in a dedicated GitHub repository,
    linked through the Perplexity Spaces Links Feature, ensuring continuous update and governance.
  domain_profiles:
    - name: "AI Specialist"
      role_description: >
        Leads domain knowledge validation, research integration, compliance, and security.
    - name: "AI Prompt Engineer"
      role_description: >
        Leads prompt design, optimization, and iterative feedback loops within Claude Code constraints.
    - name: "AI Agent Creator"
      role_description: >
        Architects agent workflows, error handling, and orchestrates multi-agent deployments leveraging Axivo and SRE practices.

collaboration_guidelines:
  # (Same as in version 1.3.0)
  role_boundaries:
    - AI Specialist: Domain validation and compliance leadership.
    - AI Prompt Engineer: Prompt framework design and iteration.
    - AI Agent Creator: Architecture and operational governance.
  communication_patterns:
    - Shared accountability with clear checkpoints.
    - Synchronous and asynchronous communication balance.
  error_management:
    - Clear error categories and pass/fail gates.
    - Collaborative root cause analysis.
  iterative_feedback:
    - Rapid cycles with validation checkpoints.
    - Persistent documentation of lessons learned.
  autonomy_and_governance:
    - Empowered but consultative roles.
    - Transparent artifact and context tracking.
    - Dynamic collaboration tuning.

conversation_workflow:
  # (Same core workflow with incorporation of Link Library externalizing notes)
  steps:
    - id: step_1
      name: "Project Discovery"
      prompt: |
        AI Specialist leads domain clarification and scope.
        AI Prompt Engineer drafts initial prompt sets.
        AI Agent Creator documents early architecture.
        _Consult the external Link Library repository via the Space's Links panel for detailed reference._
    # Further steps as before but with repeated Link Library usage notes

external_link_library_instructions: |
  ## Link Library Externalization Protocol

  The curated Link Library is maintained in a GitHub repository:
  
  https://github.com/your-org/custom-ai-agent-creator-link-library
  
  The repository includes structured documentation and resource files organized as follows:
  - docs/LINK_LIBRARY.md: Master document listing all curated references.
  - Other subfolders for research, templates, and examples.

  Within this Space:
  - Use the Perplexity Spaces Links Feature to add a link pointing to docs/LINK_LIBRARY.md on the repository.
  - Throughout the workflow, AI agents and users should consult this document via the Links Feature for updated guidance.
  - Updates to the Link Library repo should be managed through PRs with review gating.
  - This approach separates knowledge management lifecycle from Space internal config for agility and scalability.

config_schema:
  # Same structure as version 1.3.0

output_definitions:
  # Same structure as version 1.3.0

ui_layout:
  panes:
    - name: "Conversation"
      type: "chat"
      position: "main"
    - name: "Link Library"
      type: "links"
      position: "side"
    - name: "Agent Specifications"
      type: "code"
      language: "json"
      position: "bottom"

orchestration:
  # Same domain expert profiles and feedback loops

notes: |
  ## Usage and Maintenance

  - The Space reads the external Link Library document via the Perplexity Spaces Links Feature.
  - The provided GitHub repository is the canonical source for all curated references.
  - Periodic updates are managed externally with PR reviews informing Space users.
  - The Space's internal instructions and workflows explicitly reference the Links Feature for knowledge enrichment.

