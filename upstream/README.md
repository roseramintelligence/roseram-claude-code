# Roseram with OpenCode

Install [OpenCode V2](https://opencode.ai/docs/). Merge [opencode.json](opencode.json) into the test project's `opencode.json`, set `ROSERAM_API_KEY` in your shell, and run `opencode` in the project. Select `roseram/roseram` if the session already has a different model selected.

The configuration uses the OpenAI-compatible provider package and Roseram's Chat Completions endpoint. It asks before file edits, shell commands and access outside the project. Begin with source review in a test repository.

Upstream source and license: [OpenCode, MIT](https://github.com/anomalyco/opencode). This setup uses OpenCode's interface and runtime.
