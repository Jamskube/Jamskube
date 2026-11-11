# Nicolas Jamin

Software developer · Applied AI & automation · Brussels, Belgium

I build web and desktop applications, integrate language models into document workflows, and work on audio AI. My projects combine interface development with practical constraints such as memory use, data privacy and application packaging.

## Selected projects

### [Doku](https://github.com/Jamskube/Doku)

A desktop application for Markdown, DOCX and PDF, with an AI copilot that runs locally by default. It includes document search, retrieval-augmented generation and answers linked to their sources.

**Stack:** Tauri 2, Svelte 5, TypeScript, Rust and Ollama.

For a closer look:
- [Architecture decisions](https://github.com/Jamskube/Doku/tree/main/docs/adr), including the trade-offs behind local embeddings and retrieval.
- [RAG tests](https://github.com/Jamskube/Doku/blob/main/src/lib/rag.test.ts), covering chunking, vector search and index integrity.
- [Build and test workflows](https://github.com/Jamskube/Doku/actions).

### [KubeClean](https://github.com/Jamskube/KubeClean)

A disk-cleaning desktop application with a Rust engine and an Electron/Svelte interface. It separates scanning from cleanup and communicates progress through a JSON-lines protocol. The repository contains Windows and macOS implementations.

**Stack:** Rust, Electron, Svelte and TypeScript.

- [Engine source](https://github.com/Jamskube/KubeClean/tree/main/core/src).
- [macOS build and test workflow](https://github.com/Jamskube/KubeClean/blob/main/.github/workflows/macos.yml).

## How I work

I work on product scope, interfaces and technical integration, using AI coding agents as part of development. I care about being able to explain the decisions behind an application and check what it actually does.

My background in music is also part of what led me to audio AI.

## Contact

[LinkedIn](https://www.linkedin.com/in/nicolas-jamin-ia/) · [Email](mailto:j.nicolas.data@gmail.com)
