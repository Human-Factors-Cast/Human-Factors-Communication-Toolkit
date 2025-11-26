# Human-Factors-Communication-Toolkit

The communications toolkit is a set of prompts, patterns, and templates that help you communicate human factors and human-centered design work to different audiences.

It’s built for people like you who do HF/UX/HCD work and need to explain it to everyone else.

---

## Why this exists

You already know how to run studies and design systems. The hard part is:

- Explaining results to leaders who care about risk and cost  
- Translating methods into stories for press, partners, and the public  
- Adapting the same core work for students, practitioners, and executives  
- Doing all of that without rewriting from scratch every time  

This repo gives you a starting point for those communication tasks, wired into reusable prompt files and workflows.

---

## What’s in the toolkit

Planned modules (each as prompt files + usage notes):

- **Audience Packs**  
  - Leadership / executives  
  - Engineers / developers  
  - Practitioners / HF/UX peers  
  - Policy / government  
  - Media / public communication  
  - Students (undergrad, grad)  

- **Communication Patterns**
  - Mode: e.g. email, chat, call, in-person, asynchronous
  - “New / Interesting / Exciting” (NIE) summaries  
  - One-page briefs and executive summaries  
  - Show notes and podcast / talk prep  
  - Threads, posts, and short social updates  
  - Email updates and stakeholder check-ins  

- **Human Factors Translation**  
  - From paper → plain-language summary  
  - From study plan → stakeholder pitch  
  - From findings → design recommendations  
  - From tradeoffs → decision options  

---

## Repository structure

Proposed layout (update as you implement):

    communications-toolkit/
    ├─ prompts/
    │  ├─ audiences/
    │  │  ├─ executives.txt
    │  │  ├─ engineers.txt
    │  │  └─ media.txt
    │  ├─ formats/
    │  │  ├─ exec-summary.txt
    │  │  ├─ podcast-show-notes.txt
    │  │  └─ social-thread.txt
    │  ├─ research/
    │     ├─ paper-to-plain-language.txt
    │     └─ findings-to-recs.txt
    ├─ examples/
    │  ├─ before-after/
    │  └─ case-studies/
    ├─ docs/
    │  ├─ framework-overview.md
    │  └─ audience-map.md
    └─ README.md


---

## How to use it

You can use the communications toolkit with any LLM interface (ChatGPT, OpenAI API, etc.).

1. **Pick your audience**  
   - Open a prompt file under `prompts/audiences/` that matches who you’re talking to.  
   - Paste it into your LLM as a system or first message.

2. **Pick your format**  
   - Add a format prompt from `prompts/formats/` (e.g., exec summary, podcast notes).  
   - Combine with your audience prompt in the same chat or call.

3. **Add your content**  
   - Paste in your study notes, paper, transcript, or design spec.  
   - Ask for the output you need, for example:  
     - “Summarise this for a VP who cares about risk and schedule.”  
     - “Turn this article into show notes using the HFC pattern.”  

---

## Getting started

- Clone the repo:  

    git clone https://github.com/Human-Factors-Cast/Human-Factors-Communication-Toolkit.git  
    cd communications-toolkit  

- Open the `prompts/` folder and start with:
  - One audience prompt
  - One format prompt
- Try them inside your LLM of choice with a small piece of real content.

---

## Contributing

You can help improve the communications toolkit by:

- Adding new audience prompt files  
- Adding new output formats (for example, grant abstracts, conference pitches)  
- Sharing before/after examples in `examples/`  
- Opening issues with gaps, pain points, or bugs in the prompts  

When you add a prompt, include:

- Short description at the top of the file  
- Expected inputs (what the user should paste)  
- Example calls and outputs

---

## Roadmap

Planned next steps:

- Fill in core audience packs
- Add starter library for formats
- Add HF/UX-specific research translation patterns  
- Publish example flows for common tasks (for example, “paper → talk → post”)

---

## License

This project is licensed under the Creative Commons License – see the `LICENSE` file for details.
