# EdgeLite — On-Device AI like Google AI Edge Gallery

This is a lightweight Android app that runs LLMs locally using Google's MediaPipe LLM Inference API (tasks-genai:0.10.14).

Features:
- Load .task or .bin models (Gemma 2B, Phi-2, Falcon-RW-1B, StableLM-3B)
- 100% offline inference
- Chat UI built with Jetpack Compose
- Similar flow to Google AI Edge Gallery

## How to build APK

1. Install Android Studio Hedgehog or newer
2. Open folder `EdgeLite`
3. Sync Gradle
4. Build > Build APK(s)
5. APK will be at `app/build/outputs/apk/debug/app-debug.apk`

## Add a model
- Download Gemma 2B int8 from Kaggle: https://www.kaggle.com/models/google/gemma-2/tfLite/gemma2-2b-it-cpu-int8
- Copy to phone: `/sdcard/Android/data/com.edgelite.app/files/models/`
- In app, tap "Find Local" then "Load Model"

## Based on
- Google AI Edge Gallery: https://github.com/google-ai-edge/gallery【5619192082786312251†L6-L8】
- MediaPipe LLM Inference API experimental【3916685413923552657†L24-L26】
