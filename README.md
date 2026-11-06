# Italian Vocabulary Learning App

An AI-assisted Italian vocabulary learning app for vocabulary review, sentence practice and shadowing.

[**Try the interactive demo — no sign-in or API key required**](https://f2bd6a26ea564308bb3f1a3f31f50704.app.codebuddy.work/?demo=1)

## Try the Demo

1. Open the **interactive demo** and select **Start the guided demo**.
2. Follow one word through vocabulary details, saved AI sentence feedback, flashcard review and speaking practice.
3. On the completion page, select **Explore another saved AI example** to see how a saved AI explanation filled a missing meaning on another card, with an English summary.

The portfolio demo uses sample data and saved AI outputs. It requires no account or API key and does not generate responses live.

**Demo scope:** audio uses browser text-to-speech. Recording and automated pronunciation scoring are not included in the demo. Some saved content is Chinese; the additional AI-meaning example includes an English summary. Browser audio availability depends on the device.

[Open the full application](https://3b59dfb43ad84cc18294a37d89970a7d.app.codebuddy.work/) to explore the wider feature set. Guest browsing is available; live AI features may require your own supported API key in **Settings**. AI outputs can be inaccurate and should be checked. The screenshots below show the full application in an existing configured session.

## Screenshots

<table>
  <tr>
    <td align="center" width="50%">
      <img src="screenshots/01-vocabulary.png" alt="Word details for ferie with AI-labelled meaning, related vocabulary and an example" width="300"><br>
      <b>Vocabulary details</b><br>
      AI-labelled meaning, related vocabulary and a bilingual example.
    </td>
    <td align="center" width="50%">
      <img src="screenshots/02-review.png" alt="Vocabulary review card with Forgot, Fuzzy and Got it controls" width="300"><br>
      <b>Vocabulary review</b><br>
      Recall a word and choose Forgot, Fuzzy or Got it.
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="screenshots/03-ai-sentence-feedback.png" alt="Actual AI feedback correcting Io ha to Io ho in an Italian practice sentence" width="300"><br>
      <b>AI sentence feedback</b><br>
      A real practice submission: “Io ha…” is corrected to “Io ho…”.
    </td>
    <td align="center" width="50%">
      <img src="screenshots/04-shadowing.png" alt="Shadowing sentence with original audio and recording controls" width="300"><br>
      <b>Shadowing practice</b><br>
      Original-audio playback and recording controls for self-review.
    </td>
  </tr>
</table>

Captured from the [app instance used for the screenshots](https://9c590504dcf647afa1ae7ad5c12704c3.app.codebuddy.work/) on 5 November 2026. These show an existing learning session with AI configured; a new visitor's data and available content may differ. The interface is set to English, while some saved meanings, feedback and status text remain Chinese. Screenshots show actual outputs, not a formal quality evaluation.

## Why I Built It

I started this project from my own experience of learning Italian.

When learning new vocabulary, I found that looking up a word once was often not enough. I might understand it at the time, but later forget its meaning, recognize it without being able to use it, or struggle to practise it in context.

I wanted one place where I could collect unfamiliar words, revisit the ones I kept forgetting, practise using them in sentences, and improve listening and speaking through shadowing.

Instead of relying on several separate tools, I decided to build my own learning workflow.

## What the App Does

The app combines vocabulary collection, review, contextual practice and AI-assisted learning features in one workflow.

Key features include:

- Italian vocabulary collection and dictionary lookup
- Manual, photo, voice and document-based word capture
- Personal vocabulary book
- Review workflow with remembered, fuzzy and forgotten ratings
- Learning progress and review tracking
- AI-assisted word explanations and example sentences
- Synonyms, antonyms and related-word exploration
- AI-generated fill-in-the-blank, collocation and scenario exercises
- Sentence writing with AI feedback and corrections
- AI-generated sentence and dialogue shadowing practice
- Text-to-speech playback and voice recording for shadowing
- Multilingual interface
- Offline dictionary access after initial loading
- Cloud synchronization for registered users

## How I Use AI

I use AI as a supporting layer rather than as a replacement for the whole learning system.

AI is used to:

- supplement vocabulary explanations
- generate example sentences
- generate synonyms, antonyms and related vocabulary
- create contextual vocabulary exercises
- provide feedback on sentence-writing practice
- generate shadowing sentences and dialogues

Dictionary data, review history and other structured learning records are maintained separately from AI-generated content.

For shadowing practice, AI generates learning content, while the current version uses listening, recording, playback and self-evaluation rather than automated pronunciation scoring.

## What I Did

This is an independent personal project that I initiated based on my own Italian-learning experience.

I:

- translated problems from my own learning process into product requirements
- defined feature priorities and the overall learning workflow
- decided where AI could add value and where conventional data should be retained
- designed and refined the interaction flow
- iterated prompts and AI feature logic
- tested application functions and AI-generated outputs
- identified bugs, logic issues and usability problems
- refined the product through repeated iterations
- deployed and continued improving the application

I used AI-assisted development tools extensively throughout the project rather than writing the entire application manually.

## Development Process

I developed the app iteratively rather than starting from a fixed technical specification.

My general process has been:

**Learning problem → Product requirement → Prototype → AI-assisted implementation → Testing → Debugging → Refinement → Deployment**

For each feature, I first identified the learning problem I wanted to solve and translated it into a concrete product requirement.

I then used AI-assisted development tools to help implement the feature, tested the resulting behaviour myself, identified problems, and refined it through repeated iterations.

Through this process, I have also been learning where AI can accelerate product development and where human judgement, verification and iteration are still necessary.

## Tech Stack

- React
- Vite / PWA
- IndexedDB / Dexie
- Supabase
- Gemini API
- Groq API
- CodeBuddy for AI-assisted development

## Next Steps

Planned next steps include:

- systematically evaluating the quality of AI-generated vocabulary content
- documenting common AI failure cases
- conducting user testing with other Italian learners
- refining the review workflow based on feedback
- improving the reliability and consistency of AI-generated feedback

## Project Status

Independent personal project · 2026–Present

This public repository is a portfolio case study with documentation and screenshots. Application source code is not included.


