# ExpoLocalAndroidDemo

Expo Android app built via **EAS Build `--local`** and uploaded to [AutoDevice](https://autodevice.io).

## Build Method

- **Platform**: Android (APK)
- **Build**: EAS Build `--local` — builds run on the CI runner itself
- **CI Runner**: `ubuntu-latest`
- **Profile**: `preview` (produces APK for internal distribution)
- **Requirements**: JDK 17, Android SDK (available on `ubuntu-latest`)

## Required Secrets

| Secret | Description |
|--------|-------------|
| `EXPO_TOKEN` | Expo access token for EAS Build authentication |
| `AUTODEVICE_API_KEY` | AutoDevice API key for uploading builds |

## Local Development

```bash
npm install
npx expo start
```
