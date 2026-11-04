# AyoBaca

AyoBaca is a browser-based early literacy app for children learning letters and beginning to read in Indonesian. It combines letter-sound practice, syllables, word blending, handwriting practice, and a gentle quiz in one responsive page.

## Features

- **Alphabet and phonics:** Explore A-Z, uppercase and lowercase letters, letter names, sounds, vowel/consonant labels, illustrated example words, syllable breaks, and example sentences. Play individual sounds or read through the alphabet.
- **Open syllables:** Choose a consonant to hear and practice its combinations with the vowels A, I, U, E, and O, with an example word for each selection.
- **Blend words:** Practice words by tapping their syllable or sound boxes, then hear the complete word. Browse the available word examples.
- **Trace letters:** Draw over a guide letter on a touch-friendly canvas, choose a crayon color, and replay the letter sound. Progress shows how much of the letter is covered, and a traced letter earns one star.
- **Sound quiz:** Listen to a prompt and choose the matching letter from three options. Correct answers earn stars; incorrect answers get a friendly retry prompt.
- **English (hidden):** English content and interface text are included, but the language button is currently hidden, so the app runs in Indonesian.
- **Speech:** All speech uses cloud Indonesian text-to-speech. Adjust the speech speed from 0.65× to 1.05× and play a test sample.
- **Progress and preferences:** Stars and speech speed are saved in the browser's local storage. If storage is blocked, the app still works but doesn't remember them.
- **Parent and teacher guide:** An in-app guide describes the learning approaches and includes references.

## Run locally

No build tools, package installation, or backend are required. Open `index.html` in a modern browser, or serve the project directory locally:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Connectivity and audio

The app is a static HTML page. Tailwind CSS, Google Fonts, Twemoji illustrations, and confetti are loaded from external CDNs, so an internet connection is needed for those assets. Speech comes from Google Translate's text-to-speech service, so sounds also need an internet connection. There is no offline voice.

## Project files

- `index.html` contains the app interface, styles, learning content, and JavaScript behavior.
- `LICENSE` contains the GNU General Public License, version 3.

## License

This project is distributed under the GNU GPL v3. See [LICENSE](LICENSE) for the full text.