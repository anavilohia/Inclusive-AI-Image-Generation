# Best Practices for Inclusive Image Generation

### For Users generating images
- Add details to your prompts: Models struggle with consistency when given vague instructions (e.g., "person in a shop" vs. "a person in a coffee shop buying a drink").
- Be specific about demographic requirements: Generic prompts may lead some models to default to a certain demographic (e.g., white, male, young)
- Avoid euphemisms, idioms, and other colloquial phrases.
- Utilize adjectives and descriptive language: Words such as 'confidently' and 'successfully' can help eliminate inherent assumptions in the models about how a person from a certain demographic might complete an acitvity.
- Review generated images for biases: Examine generated images for biases or stereotypes, and adjust prompts or parameters as needed to mitigate them.

### For AI Researchers, Engineers, and Product Teams building image generators
- Prioritize intersectionality in training: Ensure training data represents a variety of identities within a category. For instance, when generating images of Blind and Low Vision users, include diverse representations of age, gender, and race, in addition to variations in vision disabilities.
- Test responsiveness to prompt requirements: Assess how well models respond to prompts requesting equal probabilities of gender representation, for example.
- Diversify training data: Expand datasets to include diverse identities beyond conventional definitions. For example, including gender non-conforming individuals.
- Implement feedback loops: If initial outputs do not meet user expectations, incorporate feedback mechanisms based on user responses or modified prompts.
