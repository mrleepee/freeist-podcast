## Summary: "LLMs Hallucinate A Lot"

This video explores the pervasive problem of hallucinations in Large Language Models from a software developer's perspective.

### Key Points

- **Hallucinations are extremely common**: Even experienced developers are now paranoid about trusting LLM outputs
- **Types of hallucinations**:
  - **Factual errors**: LLMs generate false information (e.g., Google's BARD incorrectly claiming JWST took first pictures of exoplanets)
  - **Intrinsic hallucinations**: Contradicting information provided within the conversation
  - **Extrinsic hallucinations**: Inventing information not present in the conversation
  - **Fabricated entities**: Creating non-existent packages, laws, government departments, etc.
  - **Contextual inconsistency**: Ignoring or contradicting explicitly provided context (Air Canada chatbot case)
- **Why hallucinations happen**:
  - Training is essentially compression—massive data squished into smaller form, losing details
  - LLMs are trained to guess because benchmarks reward correct answers over admissions of uncertainty
  - "You miss all the shots you don't take"—companies want top leaderboard positions
- **How to work around them**:
  - Always provide intrinsic information (documents, code, data) rather than relying on training knowledge
  - Use prompts like "Use your search tool" to force web searches and citations
  - Verify critical information (legal, health, financial) independently
- **Conclusion**: LLMs are still valuable tools, but should never be trusted implicitly—use them for what they're good at (coding, analyzing provided documents) rather than as authoritative knowledge sources.