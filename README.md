<div align="center">
  <img 
    src="https://cdn-uploads.huggingface.co/production/uploads/61b8e2ba285851687028d395/2b08LKpev0DNEk6DlnWkY.png" 
    alt="Liquid AI" 
    style="width: 100%; max-width: 100%; height: auto; display: inline-block; margin-bottom: 0.5em; margin-top: 0.5em;"
  />
  <div style="display: flex; justify-content: center; gap: 0.5em;">
    <a href="https://playground.liquid.ai/"><strong>Try LFM</strong></a> • 
    <a href="https://docs.liquid.ai/lfm"><strong>Documentation</strong></a> • 
    <a href="https://leap.liquid.ai/"><strong>LEAP</strong></a> • 
    <a href="https://discord.com/invite/liquid-ai"><strong>Discord</strong></a>
  </div>
</div>
</br>

This repository contains **examples**, **tutorials**, and **applications** built with Liquid AI open-weight models (LFM) and the open-source LEAP SDK.

Whether you're looking to customize models, deploy to laptops, edge devices, or build complete applications, you'll find resources here to get started:

- 🤖 [Examples of local AI apps](#-examples-of-local-ai-apps) that showcase the power of our LFM model family.
- 📱 [Mobile app deployment](#-mobile-app-deployment) with the LEAP SDK.
- 🎯 [Fine-tuning notebooks](#-fine-tuning-notebooks) to increase the performance of LFM2 models for your specific use case.
- 📚 [End-to-end tutorials](#-end-to-end-tutorials) that cover the whole path from data collection, evaluation, fine-tuning, and deployment.
- 🌟 [Examples built by our community ](#-examples-built-by-our-community) that showcase what is possible with Liquid AI models.
- 🕐 [60-minute technical deep dives](#-recorded-sessions-60-minute-technical-deep-dives) every month in the Liquid [Discord community](https://discord.com/invite/liquid-ai).

## 🤖 Examples of local AI apps

| Name | Description |
|-------|-----------|
| 🧾 [invoice-parser](./examples/invoice-parser/README.md) | A Python CLI that extracts structured data from invoice pdfiles using LFM2-VL-3B |
| 🎙️ [audio-transcription-cli](./examples/audio-transcription-cli/) | A Python CLI for real-time audio-to-text transcription using LFM2-Audio-1.5B with llama.cpp |
| ✈️ [flight-search-assistant](./examples/flight-search-assistant/README.md) | A Python CLI that helps you find and book plane tickets using LFM2.5-1.2B-Thinking with tool calling |
| 🚗 [audio-car-cockpit](./examples/audio-car-cockpit/README.md) | A voice-controlled car cockpit demo combining LFM2.5-Audio-1.5B (TTS/STT) with LFM2-1.2B-Tool for real-time local inference |
| 🔊 [audio-webgpu-demo](./examples/audio-webgpu-demo/README.md) | Run LFM2.5-Audio-1.5B entirely in your browser with WebGPU for speech recognition, text-to-speech, and interleaved audio/text conversation |
| 📹 [vl-webgpu-demo](./examples/vl-webgpu-demo/README.md) | Real-time video captioning with LFM2.5-VL-1.6B running in-browser using WebGPU |

## 📱 Mobile app deployment

The [LEAP Edge SDK](https://leap.liquid.ai/docs/edge-sdk/overview) is our native framework for running LFM2 models on mobile devices.

Written for Android (Kotlin) and iOS (Swift), the goal of the Edge SDK is to make Small Language Model deployment as easy as calling a cloud LLM API endpoint, for any app developer.

### Android

| Example | Description |
|---------|-------------|
| [LeapChat](https://github.com/Liquid4All/LeapSDK-Examples/tree/main/Android/LeapChat) | A comprehensive chat application with real-time token streaming, persistent message history, and modern chat UI featuring message bubbles and typing indicators |
| [SloganApp](./examples/leap-slogan-example-ios/README.md) | Single turn generation for marketing. The UI is implemented with Android Views. |
| [ShareAI](https://github.com/Liquid4All/LeapSDK-Examples/tree/main/Android/ShareAI) | Website summary generator |
| [Recipe Generator](https://github.com/Liquid4All/LeapSDK-Examples/tree/main/Android/RecipeGenerator) | Structured output generation with the LEAP SDK |
| [Visual Language Model example](https://github.com/Liquid4All/LeapSDK-Examples/tree/main/Android/VLMExample) | Visual Language Model example |

### iOS

| Example | Description |
|---------|-------------|
| [LeapChat](https://github.com/Liquid4All/LeapSDK-Examples/tree/main/iOS/LeapChatExample) | A comprehensive chat application demonstrating advanced LeapSDK features including real-time streaming, conversation management, and modern UI components. |
| [LeapSloganExample](https://github.com/Liquid4All/LeapSDK-Examples/tree/main/iOS/LeapChatExample) | A simple SwiftUI app demonstrating basic LeapSDK integration for text generation. |
| [Recipe Generator](https://github.com/Liquid4All/LeapSDK-Examples/tree/main/iOS/RecipeGenerator) | Structured output generation |
| [Audio demo](https://github.com/Liquid4All/LeapSDK-Examples/tree/main/iOS/LeapAudioDemo) | A SwiftUI app demonstrating audio input and output with the LeapSDK for on-device AI inference. |

## 🎯 Fine-tuning notebooks

TBD.

## 📚 End-to-end tutorials

Complete end-to-end tutorials that take you from setup to deployment.

| Tutorial | Repository |
|----------|------------|
| Super fast and accurate image classification on edge devices | [Link](https://github.com/Paulescu/image-classification-with-local-vlms) ![GitHub Repo stars](https://img.shields.io/github/stars/Paulescu/image-classification-with-local-vlms) |
| Let's build a Chess game using small and local Large Language Models | [Link](https://github.com/Paulescu/chess-game) ![GitHub Repo stars](https://img.shields.io/github/stars/Paulescu/chess-game) |

## 🌟 Examples built by our community

Working applications that demonstrate Liquid models in action.

| Project | Repository |
|---------|------------|
| TranslatorLens: Building An Offline Translation Camera | [Link](https://github.com/linmx0130/TranslatorLens) ![GitHub Repo stars](https://img.shields.io/github/stars/linmx0130/TranslatorLens) |
| Food Images Fine-tuning | [Link](https://github.com/benitomartin/food-images-finetuning) ![GitHub Repo stars](https://img.shields.io/github/stars/benitomartin/food-images-finetuning) |
| Meeting Intelligence CLI | [Link](https://github.com/chintan-projects/meeting-prompter) ![GitHub Repo stars](https://img.shields.io/github/stars/chintan-projects/meeting-prompter) |
| Private Doc Q&A: On-device document Q&A with RAG and voice input | [Link](https://github.com/chintan-projects/private-doc-qa) ![GitHub Repo stars](https://img.shields.io/github/stars/chintan-projects/private-doc-qa) |
| Photo Triage Agent: Private photo library cleanup using LFM vision model | [Link](https://github.com/chintan-projects/photo-triage-agent) ![GitHub Repo stars](https://img.shields.io/github/stars/chintan-projects/photo-triage-agent) | 
| LFM-Scholar: Automated literature review agent capable of finding and citing papers | [Link](https://github.com/gyunggyung/LFM-Scholar) ![GitHub Repo stars](https://img.shields.io/github/stars/gyunggyung/LFM-Scholar) |
| LFM2-KoEn-Tuning: Fine-tuned LFM2 1.2B model specialized for Korean-English translation | [Link](https://github.com/gyunggyung/LFM2-KoEn-Tuning) ![GitHub Repo stars](https://img.shields.io/github/stars/gyunggyung/LFM2-KoEn-Tuning) |
| Chat with LEAP SDK on React Native | [Link](https://github.com/glody007/expo-leap-sdk) ![GitHub Repo stars](https://img.shields.io/github/stars/glody007/expo-leap-sdk) |
| Private Summarizer: 100% local text summarization with multi-language support | [Link](https://github.com/Private-Intelligence/private_summarizer) ![GitHub Repo stars](https://img.shields.io/github/stars/Private-Intelligence/private_summarizer) |
| Tiny-MoA: Running Mixture of Agents on CPU: LFM2.5 Brain (1.2B) + Multi-Agent | [Link](https://github.com/gyunggyung/Tiny-MoA) ![GitHub Repo stars](https://img.shields.io/github/stars/gyunggyung/Tiny-MoA) |

## 🕐 Recorded sessions: 60-minute technical deep dives

| Date | Topic |
|---------|------------|
| 2025-11-06 | [▶️ Fine-tuning LFM2-VL for image classification](https://www.youtube.com/watch?v=00IK9apncCg) |
| 2025-11-27 | [▶️ Building a 100% local Audio-to-Speech CLI with LFM2-Audio](https://www.youtube.com/watch?v=yeu077gPmCA) |
| 2025-12-26 | [▶️ Fine-tuning LFM2-350M for browser control with GRPO and OpenEnv](https://www.youtube.com/watch?v=gKQ08yee3Lw) |
| 2026-01-22 | [▶️ Local video-captioning with LFM2.5-VL-1.6B and WebGPU](https://www.youtube.com/watch?v=xsWARHFoA3E) |

Wanna participate in the next session? [Join the Liquid Discord community](https://discord.com/invite/liquid-ai) and head to the `#live-events` channel!

## Contributing

We welcome contributions!

- Open a PR with a link to your project github repo in the `Examples built by our community` section.

## Support

- 📖 [Liquid AI Documentation](https://docs.liquid.ai/)
- 💬 [Join our community on Discord](https://discord.com/invite/liquid-ai)
