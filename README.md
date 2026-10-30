# The Rhyming Beach: A Dog on a Log Adventure

A static, responsive learning website for a Grade 2 EFL lesson (ages 5–9, A1–A2) in *Teaching English to Children*. Built with semantic HTML5, CSS, and vanilla JavaScript; no backend, build tools, accounts, or API keys.

## Project structure

- `index.html` — all learning sections and teacher documentation
- `styles.css` — responsive visual system, original CSS beach illustration, reduced-motion and print styles
- `script.js` — rhyme activities, sentence builder, scene creator, formative quiz, progress and optional browser speech
- `assets/` — reserved for optional locally licensed assets (the current version uses original CSS shapes and emoji; no external image assets are required)

## Run locally

1. Download and unzip the project.
2. Open `index.html` in a current browser. The site is static and does not require a local server.
3. Optional: for a local HTTP preview, run `python -m http.server 8000` from the project folder and open `http://localhost:8000`.
4. Internet is only needed for the optional Google Fonts and the link to the publisher's book collection. The activities themselves run locally. Browser speech is optional and varies by device.

## Publish with GitHub Pages

1. Create a repository on GitHub, for example `the-rhyming-beach`.
2. Upload `index.html`, `styles.css`, `script.js`, and `README.md` to the repository root. Keep the `assets/` directory if you add assets later.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the default branch (usually `main`) and folder `/ (root)`, then save.
6. Wait for the deployment to finish. The site will be available at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.
7. Test the published repository-subpath URL. CSS and JavaScript use relative paths (`styles.css`, `script.js`) so they work below a repository path.

## Main interactions

- **Welcome/map:** optional nickname, navigation, progress bar, shells, stage indicators.
- **Meet the story:** original paraphrase, prediction choices, vocabulary cards, optional speech, link to a publisher book collection.
- **Rhyme detective:** select rhymes, sort the -og family, listen-and-choose using browser speech when enabled, sequence the four story stages with accessible up/down buttons.
- **Build a funny sentence:** choose an animal and object, check sound-based practice pairs, use teacher prompts, optionally add an adjective, replay/reset.
- **Create your own scene:** four scene options, background-color personalization, sentence strip, role selectors, rehearsal checklist, oral-performance frames.
- **Final challenge:** three formative questions, retry-friendly feedback, self-assessment, certificate print view.
- **Teacher Corner:** GBA rationale based on the supplied project brief's reference to Herazo Rivera (2012), 55-minute lesson timing (52 minutes plus ~3 minutes transitions), observation checklist, peer-feedback prompts, teacher demo mode.

## Pedagogical and copyright notes

The website supports, but does not replace, the teacher, the original storybook, classroom talk, or the real group performance. The story description is an original paraphrase and the practice sentences are newly written examples. The site does not reproduce the book's complete text or original illustrations. The book link points to the publisher's free children's-books page; the teacher should verify and select the authorized edition for classroom use.

The rhyming word pairs are selected by sound (including dog/log/hog and tree/flea/me), rather than spelling alone. Browser speech synthesis is clearly optional and is not a recorded human voice. Teacher observation and oral performance remain essential evidence; game completion alone does not demonstrate independent language ability.

## Testing checklist

- [ ] Navigation links scroll to the right sections; layout works on mobile, tablet, and desktop/projector.
- [ ] Prediction buttons accept visual choices.
- [ ] Find-the-rhyme activity accepts log + hog and gives retry feedback.
- [ ] -og sorter accepts dog + log + hog and rejects distractors.
- [ ] Optional speech can be toggled; site remains usable when unavailable/off.
- [ ] Listen-and-choose gives feedback; sound may depend on browser/device.
- [ ] Story order can be changed by keyboard-accessible buttons and checked/reset.
- [ ] Sentence builder changes both words and sentence; rhyme status and reset work.
- [ ] Each scene updates sentence strip and role-play script; color controls work.
- [ ] Final quiz allows retries, progresses through all three questions, and completes.
- [ ] Progress bar, shell count, teacher demo toggle, and reset behave correctly.
- [ ] Teacher checklist prints legibly.
- [ ] Browser console has no errors.
- [ ] Published GitHub Pages URL works under `/<repository-name>/`.
