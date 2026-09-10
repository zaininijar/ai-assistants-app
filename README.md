# ai-assistants-app

Expo experiment for a voice assistant flow (record → worker → reply + TTS).

Still carries a lot of Expo starter UI; the useful screen is the Voice Assistant tab.

## Run

```bash
npm i
npx expo start
```

Needs mic permission. The worker URL is hardcoded in `app/(tabs)/voice-assistant.tsx` — swap it for your own endpoint.

