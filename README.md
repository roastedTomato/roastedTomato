# Hi, I'm roastedTomato 👋

I build web, desktop and wearable applications, explore machine learning, and contribute fixes to open-source software.

## Open-source contributions

I contribute to [Mealie](https://github.com/mealie-recipes/mealie), an open-source recipe management application. My work spans frontend behaviour, Python backend fixes, PWA reliability and developer tooling.

### Merged contributions

| Contribution | What I changed | PR |
| --- | --- | --- |
| Recipe navigation and state | Updated referenced-recipe links to navigate in the same page and preserved ingredient checkbox state across navigation using sessionStorage. Added regression tests. | [#8323](https://github.com/mealie-recipes/mealie/pull/8323) |
| Ingredient parsing | Added a prompt rule to keep compound ingredient input as a single parsed item, with secondary quantities in notes. Added a regression test and documented manual verification. | [#8138](https://github.com/mealie-recipes/mealie/pull/8138) |
| Frontend package management | Pinned pnpm and aligned package-manager configuration so Corepack selects the intended version. | [#8322](https://github.com/mealie-recipes/mealie/pull/8322) |

### Open pull requests

| Proposed improvement | What the PR changes | PR |
| --- | --- | --- |
| PWA startup reliability | Adds Nuxt build metadata to the PWA precache and makes backend metadata caching revalidate, with regression tests for metadata and regular assets. | [#8392](https://github.com/mealie-recipes/mealie/pull/8392) |
| Ingredient review layout | Stacks fields in parsing dialogs to keep long unit names readable. Includes documented desktop/mobile checks and lint validation. | [#8604](https://github.com/mealie-recipes/mealie/pull/8604) |

PR statuses last checked on **2 October 2026**. Each link provides the implementation, discussion and latest status. AI assistance is disclosed in the individual PRs.

## Selected projects

| Project | Focus |
| --- | --- |
| [Wear OS Sensor Companion](https://github.com/roastedTomato/wearos-sensor-companion) | Kotlin and Jetpack Compose phone/watch apps for motion and heart rate readings, Data Layer communication and live charts. |
| [Java Inventory & POS](https://github.com/roastedTomato/java-inventory-pos) | Java Swing inventory management, cart checkout, receipt generation and JSON storage. |
| [AG News BiLSTM Classifier](https://github.com/roastedTomato/ag-news-bilstm-classifier) | Four-class news classification with TensorFlow/Keras, text vectorisation and a bidirectional LSTM. |
| [Jena Climate Forecasting](https://github.com/roastedTomato/jena-climate-forecasting) | Seven-observation temperature forecasting with Conv1D + LSTM and a persistence baseline. |
| [UAV Crop-Weed Segmentation](https://github.com/roastedTomato/uav-crop-weed-segmentation) | **In progress:** dataset auditing and source-image splits for RGB crop/weed segmentation; model experiments are planned. |
| [Six-Letter Wordle](https://github.com/roastedTomato/six-letter-wordle) | A vanilla JavaScript guessing game with keyboard input, colour feedback and saved game state. |

## Technologies I work with

- **Applications:** JavaScript, TypeScript, Vue/Nuxt, Java/Swing, Kotlin/Jetpack Compose
- **Machine learning:** Python, NumPy, TensorFlow, Keras, Jupyter
- **Development:** Git, Gradle, pnpm, pytest and Vitest
