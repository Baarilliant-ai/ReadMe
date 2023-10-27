# Baa the LLM client https://baarilliant.ai

![](https://firebasestorage.googleapis.com/v0/b/reflect-prod.appspot.com/o/users%2Fj0U5ZwvyBWXo6Ag9TucfUoaCtfi1%2F109ceb2cf8014686a4d86a812ecc2ce4?alt=media\&token=7f1918fd-be9a-4748-ae78-bdc30a4347f8)

## 🎉 Features and Roadmap.

I've crafted Baa, an LLM client for the web and desktop. Useful features for anyone working with LLMs! Chat, handling prompts, construct functions, and run experiments with multiple models from OpenAI and Anthropic. Here's some early details on what Baa is, what Baa can do.
See [Whats Next](#now-i-have-created-baa-heres-where-i-want-it-to-go) 

## 👨‍💻 Development

I created Baa because I was struggling to find an existing LLM client that was spot on for my needs. AI and LLMs have fundamentally changed how I work, more and more frequently what I do. But I struggled to find a way to use them that suited me.

### As a IT professional...

- Smart, use every where, every model, modern UI.
- Own data, local and cloud.
- No vendor lock-in.
- Self host.
- Desktop Apps.
- Sharing features.
- Developer features.

## Here's what Baa can do.

- **Multiple agents (OpenAI and Anthropic)**: Switch between different AI agents, such as OpenAI and Anthropic, to benefit from their respective capabilities and expertise.
- **Desktop Web App: **Use Baa as an App on your desktop, Baa will continue to use Online services for data and auth.

**Chat**: The usual Chat with GPT, but Baa has some useful additions such as system prompts, forking chats and multiple models.

![](https://firebasestorage.googleapis.com/v0/b/reflect-prod.appspot.com/o/users%2Fj0U5ZwvyBWXo6Ag9TucfUoaCtfi1%2F8be3089a2f8e4f068ed14c5f7b4dedc0?alt=media\&token=a4af1e6b-907b-46da-8ae1-a4ddd0fa9602)

When working with code or queries, there's some useful utilities like, forking a chat, downloading files, starting experiments, and copy of course.

![](https://firebasestorage.googleapis.com/v0/b/reflect-prod.appspot.com/o/users%2Fj0U5ZwvyBWXo6Ag9TucfUoaCtfi1%2F3d009585f9e447bba16c8c830f1feee1?alt=media\&token=79e73ead-f7e8-4b05-b910-1205ef2eca35)

**Handle prompts**: Organise, create, edit and share your prompts.

![](https://firebasestorage.googleapis.com/v0/b/reflect-prod.appspot.com/o/users%2Fj0U5ZwvyBWXo6Ag9TucfUoaCtfi1%2F87d0fc57a33540c5a347ddefb4671f64?alt=media\&token=894577ed-a119-44c3-9e60-f222056eea2f)

![](https://firebasestorage.googleapis.com/v0/b/reflect-prod.appspot.com/o/users%2Fj0U5ZwvyBWXo6Ag9TucfUoaCtfi1%2Fc3ee0f441fb84459bde237b4e26661ef?alt=media\&token=09f471ef-a081-40e2-849a-f968a23c52ad)

**Construct functions**: Create edit organise and share functions.

![](https://firebasestorage.googleapis.com/v0/b/reflect-prod.appspot.com/o/users%2Fj0U5ZwvyBWXo6Ag9TucfUoaCtfi1%2F51d7f5d28f5f486094fd0302e450b12d?alt=media\&token=763cea96-ad79-4430-9bc1-2a823aeeca1b)

**Experiment**: Experiment with different approaches or ideas, save and iterate AI functions, completions, chains and agents.

![](https://firebasestorage.googleapis.com/v0/b/reflect-prod.appspot.com/o/users%2Fj0U5ZwvyBWXo6Ag9TucfUoaCtfi1%2F736a1ac3b68c4d5ba0d4c061c9011f7d?alt=media\&token=7e121893-5fa9-416b-9613-88998e82ac9a)

**Sharing Chats**: You can now share chats from the chat screen. A shared chat is a point in time copy (the prompt and current chat thread), the chat and its link are public, as such cannot be undone. The chat will also be listed at Community (https://baarilliant.ai/share/)
# n

## Now I have created Baa here's where I want it to go?
- LM Studio integrate (https://lmstudio.ai)
- Desktop App everything local auth, storage and LLMs. Remove any cloud dependencies.
- Local models, support local LLMs.
- Local storage, store chats, prompts, functions and experiments locally.
- Local auth, authenticate using local authentication.
- Open interpretor, integrate https://openinterpreter.com
- VS Code integration, open file, open experiments in VS Code.
- Two way audio, home assistant and agents.
- Multimodal and vision
- OpenAI Plugins \*complete

## Interesting

- Anthropic integrated in 30minutes

Recently Anthropic widened access to Claude2 it took 30 minutes to integrate there api with Baa! Think what we can do to improve the UI of local LLMs.
- Closed & open source

I'm not sure please, truly please, let me know your thoughts. Email Me (hello@baarilliant.ai)
- How Baa is developed?

Node.js 18 (https://nodejs.org/en): an open-source, cross-platform JavaScript runtime environment.

Next.js 13 (https://nextjs.org/docs): enables you to create full-stack web applications by extending the latest React features

NextAuth.js (https://next-auth.js.org/): configurable authentication framework for Next.js 13

LangChain JS (https://www.langchain.com/): AI orchestration layer to build intelligent apps

Tailwind CSS (https://tailwindcss.com/): is a utility-first CSS framework that provides a series of predefined classes that can be used to style each element by mixing and matching

shadcn/ui (https://ui.shadcn.com/): re-usable components built using Radix UI and Tailwind CSS.

Azure Cosmos DB (https://learn.microsoft.com/en-GB/azure/cosmos-db/nosql/): fully managed platform-as-a-service (PaaS) NoSQL database to store chat history

https://www.helicone.ai (https://www.helicone.ai/dashboard): Experienced first-hand the pain of managing internal tools and monitoring for LLMs at scale ? Use Helicone to solve these problems for you.
- Whats stopping Baa from release?

For Cloud - Actually one! or maybe two things. How to securely (like really) manage API Keys provided by you, or how to bill you for API Usage.

For Local - our Electron App Exists, so does Auth. Currently light weight document storage is the blocker, I'll likely write a JSON file API for langchain same as Azure Cosmos.
- Why a Sheep why Baa?

_-soon- but i'm Welsh _🏴󠁧󠁢󠁷󠁬󠁳󠁿.
- Why build this?

_-soon-_
- Build this for mobile?

-soon- but no.

## Coming soon & Roadmap.

Working on this now, as of early October 2023. Let's go.
