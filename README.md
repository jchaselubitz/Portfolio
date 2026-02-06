# Portfolio
You can also find me on [LinkedIn](https://www.linkedin.com/in/jchaselubitz/)

### Overskill - A CLI for managing skills across repositories.
Tools like Claude Code offer built-in plugin systems for distributing skills. Overskill takes a different approach — skills live in your repo as plain files — and this comes with meaningful advantages:
- **Agent-agnostic**: Overskill skills work with Claude Code, Cursor, Codex, Windsurf, and any agent that can read markdown. Plugins lock you into a single tool.
- **Transparent and auditable**: Skills are visible files in your project. You can read, diff, and review them like any other code. Plugin skills are buried in global cache directories.
- **Version-locked per repo**: `.skills.lock` pins exact versions and hashes to each commit, giving you reproducible builds. Plugins are installed globally or per-user with no per-repo lockfile.
- **Team-friendly**: `skill sync` works like `npm install` — clone the repo, run one command, and everyone has the same skills at the same versions. Plugins require each developer to install them separately.
- **Full control over activation**: You decide how and when skills are loaded via `CLAUDE.md`, `.cursor/rules`, or `AGENTS.md`. Plugin activation is controlled by the agent vendor.
- **Works offline**: Once synced, skills are local files with no runtime dependency on external services.
- **No vendor dependency**: Your skills aren't tied to a plugin API that could change or be deprecated. They're markdown files — the most durable format there is.
- [Code Repository](https://github.com/jchaselubitz/overskill-cli)
- [NPM] - coming soon
- [Homebrew] - comming soon


### Drill - AI Language Learning Tools
Capturing and generating content for language learning. Drill not only lets users create study content and export to Anki (a popular study tool), but it also helps users learn to express themselves by prompting them to draft short paragraphs about a subject of there in their target language, then providing corrections and clear explanations for what it corrected.
- [Overview](https://cooperativ.io/?project=1)
- [Code Repository](https://github.com/jchaselubitz/drill-2)
- [Project Video](https://www.youtube.com/watch?v=uilJL5JW-2g)
- [Webapp](https://drillapp.xyz)
    - Nextjs (App Router) / OpenAI / Supabase / Deno
    - Podcast, recording, and upload transcription
    - Chat with AI about specific library content
    - Translation
    - Writing review and explanation of corrections
 
### Drill App - Mobile App With Spaced Repetion 
Drill helps users learn to express themselves by prompting them to draft short paragraphs about a subject of there in their target language, then providing corrections and clear explanations for what it corrected.
- [Code Repository](https://github.com/jchaselubitz/drill-app)
- [App Store Listing] (coming soon)
    - React Native with Expo Router
    - Built and submitted in one week with help from Claude, ChatGPT, and Cursor 

### NYCA - TOP (for client)
A digital operations manager for pizza shops. The client required custom workflows with an advanced scheduling engine that directs employees to complete tasks and collect equipment information at specific times. The platform also collects and presents data from temperature sensors,and allows users to interface with many functions through a custom Slack app.
- [Overview](https://cooperativ.io/?project=2)
- [Code Repository (private - availible upon request)](https://github.com/cooperativ-labs/NYCA-TOP)
- [Product Videos](https://www.youtube.com/watch?v=gJ0jTCnsPpY&list=PLdUGBxGRPWz_K4I2NzjRNHcLCMRfEV0zH)
- [WebApp](https://main--nyca.netlify.app/)
    - Nextjs (App Router) / Supabase / Deno
    - IoT integration (Mocreo tempurature sensors)
    - Ordering system integration
    - Deep Slack integration including webhooks and interactivity
    - Stripe subscription and payment management
 
### Conject - Disagree Agreeably (Work in Progress)
Social blogging that mixes the features of Substack, Google Docs, and Reddit to encourage thoughful discourse and debate on any subject. Annotations with nested comments allow users to debate specific statements, while rebuttles allow users to respond to entire conjectures.
- [Code Repository](https://github.com/jchaselubitz/conjecture)
- [Webapp](https://conject.io/)
     - Nextjs (App Router) / Supabase / Deno / Resend
     - Comprehensive newsletter functionality
     - WYSIWYG text editor with deep functionality

**Note:** I used Cursor extensively for this project in order to form better AI coding habits. Much of the code for generating HTML, for example, is Cursor-generated, as are many of the custom TipTap extensions, although the latter required considerable manual intervention.

### Syndicate (for client)
An ethereum-based platform for conducting Reg-D compliant private offerings.
- [Overview](https://cooperativ.io/?project=3)
- [Frontend repository](https://github.com/cooperativ-labs/syndicate)
- [Smart contracts](https://github.com/cooperativ-labs/private-offering-contract) (Led design, but did not code)
- [Product website](https://cooperativ.io/syndicate)
- [Demo videos](https://www.youtube.com/playlist?list=PLdUGBxGRPWz_n-tWwlKt_o6phKlHsR6CC)
    - NextJS / Typescript / GraphQL / Solidity

### Contributor Credits
A blockchain-based tool for compensating contributors to early-stage projects
- [Frontend repository](https://github.com/cooperativ-labs/contributor-credits-frontend)
- Smart contracts (Project lead. Did not code)
    - [Original Contributor Credits](https://github.com/cooperativ-labs/original-contributor-credits)
    - [Continuous Contributor Credits](https://github.com/cooperativ-labs/continuous-contributor-credits)
- [Product website](https://contributorcredits.com/)
    - NextJS / Typescript / GraphQL / Solidity / Firebase

### Voxalyze
Helping professional singers improve: A Convolutional Neural Network (and LSTM) trained to recognize proper Scales and Arpeggios.
- [Repository](https://github.com/ElsaGregoire/vocal_patterns) (contributor)
- [Live Site](https://voxalyze.streamlit.app/)
    - Python, Tensorflow, GCP
