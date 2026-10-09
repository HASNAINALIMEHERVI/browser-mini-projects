# Browser Mini Projects

Six personal HTML/CSS/JavaScript learning demos by Hasnain Ali Mehervi (Sunny). These are practice projects, not commissioned client work or full business/e-commerce websites.

Open `index.html` for the demo list, then select a demo. No installation is needed. For clipboard and consistent browser behavior, serve the folder with `python -m http.server 8080` and open `http://localhost:8080`.

| Demo | Implemented behavior |
| --- | --- |
| Number guessing | Whole-number validation, valid-attempt counting, round completion and reset |
| Rock-paper-scissors | First-to-five scoring, terminal button state and reset |
| Temperature converter | Finite Celsius input and Fahrenheit output |
| Multiplication table | Bounded integer input and ten safe text-rendered rows |
| Math Function Explorer | Deterministic arithmetic, statistics, unit and circuit formulas; small matrix calculations; bounded integer validation |
| Jokes and speech | Local sample jokes, browser speech synthesis, voice selection, clipboard and cancellable segmented playback |

There is no backend, account system, payment service, real storefront or data collection. Speech depends on browser/OS voice availability; clipboard may require a secure context. Browser speech uses the Web Speech API, not Python `pyjokes` or `pyttsx3`. No microphone access is needed.

Input and game logic checks were run in a simulated DOM. Visual browser QA and real speech playback remain to be completed before publication. Personal desktop screenshots, the sample certificate, repetitive private messages and raw text fixtures are excluded.

Math Function Explorer is repaired from the supplied `index(2).html`. Ads and unverified marketing claims were removed. It is not an AI model. Fourteen calculation regression checks and JavaScript syntax checks passed; full formula coverage, visual QA and near-singular matrix accuracy remain unverified. Trigonometric inputs are radians, variance is population variance and month/year conversions use averages. Mode currently returns one most frequent value, choosing the first to reach the highest count in a tie.
