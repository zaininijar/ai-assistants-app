# ai-assistants-app

Expo app percobaan voice assistant (rekam → kirim ke worker → jawab + TTS).

Masih banyak sisa template Expo; yang dipakai utama ada di tab Voice Assistant.

## jalanin

```bash
npm i
npx expo start
```

Butuh izin mic. Worker URL lagi di-hardcode di `app/(tabs)/voice-assistant.tsx` — ganti kalau mau pakai endpoint sendiri.
