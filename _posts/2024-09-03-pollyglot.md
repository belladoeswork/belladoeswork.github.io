---
layout: post
title:  "AI-Powered Translation Companion"
categories: ["NextJS ", "OpenAI ", "Elevenlabs"]
---

Living in an international environment, trying to communicate with people who speak different languages, the struggle is real.

<img src="/assets/images/translate.png" />
    
`_The problem`: 
Having to switch between different apps for text input, translation, and voice output is a hassle we could all do without. I was wondering if I could leverage the power of LLMs to build something similar to a Google translate app with speech to text and also document translation. 

`_The solution`:
Enter PollyGlot - a unified translation platform that combines the power of OpenAI for natural translations, Whisper for speech recognition, and ElevenLabs for lifelike text-to-speech. Not just another translation tool; it's my personal language bridge.

`_Key features`:
- Voice-to-text input using OpenAI's Whisper
- Natural translations powered by GPT-4
- Lifelike text-to-speech with ElevenLabs
- Support for multiple languages (French, German, Spanish)
- File upload capabilities for text documents (better implementation for translating documents coming soon)
- Clean, intuitive interface built with shadcn/ui components

`_Technical highlights`:
The project gave me hands-on experience with:
- React hooks for state management
- Next.js API routes for backend services
- Real-time voice processing
- Responsive design principles

`_Learning outcomes`:
This project showed me how to work with multiple AI APIs in harmony, managing complex state in React applications and building accessible user interfaces.


Check out the [code][github].

[github]: https://github.com/belladoeswork/pollyglot.git

`_Future plans`:
I'm working on adding support for PDF translation