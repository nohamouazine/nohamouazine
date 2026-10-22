<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <img src="./assets/banner-light.svg" alt="ParadoxalAI: our own French language model, Vertigo. Runs on your device, checks before it answers." width="100%">
</picture>

Hi, I'm Noham. I'm 16, I live in France, and with my friend [Reel](https://github.com/Vyn042) I run **[ParadoxalAI](https://paradoxalai.vercel.app)**.

We build our own language models: our code, our data, our training runs, on a gaming graphics card and free GPUs. Small models that check before they answer, and that run on the device of the person using them.

### What we're building

| | |
|---|---|
| **Vertigo** | A French assistant that runs on your phone or computer, even offline. It looks facts up instead of guessing, and every answer comes with a receipt: what was checked, where, and how much energy it took. Share the receipt, and anyone can replay the check. Nothing you write leaves your device. |
| **PARADOXAL Code** | A coding agent in the desktop app and in your terminal. It reads your project, proposes a plan, writes one file at a time, runs your checks, and changes nothing without your yes. Works with our model, or with the one you already use. |
| **PARADOXAL Entreprises** | Drop your company's accounting export (FEC) in the browser: it finds the money you are losing (invoices paid twice, late customers, duplicate subscriptions, penalties), writes the reminder letters, and projects your cash 90 days ahead. Computed from the entries, never guessed, and nothing is uploaded. |
| **Möbi** | Our mascot. A loop with one side, drawn in pixels from our logo. It looks around while Vertigo thinks. |

**Try it:** [chat in your browser or on your phone](https://paradoxalai.vercel.app/chat) · [desktop app](https://paradoxalai.vercel.app/download) · [terminal, one command](https://paradoxalai.vercel.app/cli) · [analyse a company's books](https://paradoxalai.vercel.app/entreprises)

### How we work

- **A lab, not opinions.** Every idea becomes an experiment with a written hypothesis; the results table is sorted best first, and nothing enters a model until it has won twice, with two different random seeds. Dozens of runs so far, the failures recorded like the wins.
- **Receipts everywhere.** An answer, a code change, an accounting finding: each one says what was verified and by what. A small model that proves its work beats a large one you have to trust.
- **On the device.** Our own TypeScript engine runs the models in the browser, on the phone and in the desktop app. Our Python trainer runs on a RTX 4060 and on free Kaggle and Colab GPUs, session after session.
- **Our own code.** PyTorch for training, TypeScript for everything people touch, no borrowed model code and no borrowed weights.

### What I work with

Python and PyTorch · TypeScript, React and Next.js · Electron · a bit of C++ and Win32

### Elsewhere

[paradoxalai.vercel.app](https://paradoxalai.vercel.app) · [LinkedIn](https://www.linkedin.com/in/noham-ouazine-245620348/)

The view is different when you’re leading. 🦅
