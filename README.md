# nomi-tool-connect

This repository contains codes for Nomis to connect to external tools.

Currently supported tool connectivity includes :
- LLM (Gemini only)
- Browser via browser-use
- Google Docs

Future integrations and support :
- Human in Loop : It is understandable that toll call which may include LLM calls will incur cost to user. Hence, to improve accuracy of Nomi's prompt to tools user (humans) will approve the comms if human_in_loop tag in .env file is set to "yes"
- Other LLM integrations e.g. OpenAI, Anthropic etc
- Loop back LLM output to Nomi for them to read and infer and build on that information

