README.txt

This project generates a .docx file in the same folder where the project is executed.

The generated .docx in which you can automatically generate the Table of Contents of a book. From this point, the workflow is intentionally semi-automated:

1. Open the generated .docx file.
2. Create and Copy the Table of Contents.
3. Paste it into a Large Language Model (LLM) of your choice.
4. Use the four prompts provided in the file prompts.txt.
5. Format the docx file as you desire

These four prompts are designed to generate all the necessary data for publishing a book on Amazon KDP, including:
- Title and subtitle ideas (SEO optimized)
- Book cover instructions
- Amazon KDP product description
- Amazon KDP keywords and categories

IMPORTANT NOTES

- You must insert your own API key before running the program.
  The original key has been removed for security reasons.
- You should customize publisher-specific information inside the prompts
  (for example: publisher name, branding, or stylistic preferences).
- All prompts used in this workflow are located in the file:
  prompts.txt

This project does not automatically publish content to Amazon.
It provides a structured pipeline to generate publishing-ready data
that can be reviewed, edited, and uploaded manually to Amazon KDP.

Use responsibly.
