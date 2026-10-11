EXCEL-GPT OVERVIEW
High-level summary of the open-source training pack.
--
An open-sourced custom GPT training material set for an Excel/Google Sheets assistant. Excels (pun intended) at step-by-step instructions for non-technical teammates. Contains examples, data sources, and identity files that can be customized to your needs. Contains a developer-mode that cuts down steps and provides advanced insights.

Customization Checklist:
- Identity: Open custom/custom_identity_template.txt, fill in organization details, and rename a copy to track versions if needed.
- Common data sources: Document approved datasets in custom/custom_data_sources_template.txt, including owners and refresh notes.
- Vocabulary: Capture preferred terms in custom/custom_language.txt so responses stay on-brand.
- Conventions: Log spreadsheet preferences (e.g., prefer INDEX over VLOOKUP) in custom/custom_conventions.txt.
- Instructions: Override default behaviors in custom/custom_instructions.txt before use; these entries take priority when conflicts arise.
- Examples & prompts: Tailor custom/custom_ai_prompts_examples.txt with your go-to hand-off prompts or remove unused scenarios.
- Code and formula templates: Maintain custom/custom_formula_templates.txt and custom/custom_automation_templates.txt with vetted snippets and update TODO markers after review.
- Distribution tip: Keep all custom/*.txt files together when sharing so teams know which files require localization.
- Remember: additional tips can be provided according to your internal LLM knowledge and web resources.

## License

This project is licensed under [GNU AGPLv3 only](LICENSE) (`AGPL-3.0-only`).
See [NOTICE](NOTICE) for copyright information.

You can use, change, and sell copies under the license terms.
If you distribute covered code, provide its source under the same license.
If you change the project and let users access it over a network,
offer those users the source of your version.
