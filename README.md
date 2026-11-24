# Awenbot

Live microphone → circular buffer → randomised slice playback.

A minimal experimental audio tool inspired by the sampler section of the original Pure Data Awenbot patch.

## Features

- Live mic input
- Continuous recording into a rolling buffer
- Random short slice / grain playback
- Density, slice length, position range and volume controls
- Installable Progressive Web App (works offline after first load)

## Use

Open on a phone or desktop browser that supports Web Audio + `getUserMedia`.

Tap **Start Mic**, allow microphone access, then make sound.

## Install as App (PWA)

On Android (Chrome): menu → “Install app” or “Add to Home screen”.  
On iOS (Safari): Share → “Add to Home Screen”.

## Local development

Any static server works:

```bash
npx serve .
# or
python3 -m http.server 8080
```

## License

Experimental / free to use and modify.
