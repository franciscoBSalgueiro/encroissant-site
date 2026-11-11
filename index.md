---
layout: home

title: En Croissant - The Ultimate Chess Toolkit

hero:
  name: "En Croissant"
  text: "The Ultimate Chess Toolkit"
  tagline: An open-source, cross-platform chess GUI that aims to be powerful, customizable and easy to use.
  image:
    src: /large-logo.webp
    alt: EnCroissant
  actions:
    - theme: brand
      text: Download
      link: /download
    - theme: alt
      text: View on Github
      link: https://github.com/franciscoBSalgueiro/en-croissant

features:
  - title: Game Analysis
    icon: 📈
    details: Get a detailed analysis report of your games, including a graph of the evaluation over time, a heatmap of the board and a list of the best moves.
  - title: Personal database
    icon: 📁
    details: Do you play both in Lichess and Chess.com? With En Croissant, you can easily import your games from both platforms and keep them up to date in a single place.
  - title: Download manager
    icon: 📥
    details: En Croissant comes with a built-in download manager that allows you to get the latest engines and databases with a single click.
---

<section :class="$style.extensions" aria-labelledby="browser-extensions">
  <div :class="$style.extensionCopy">
    <h2 id="browser-extensions">Browser extensions</h2>
    <p>Open completed Chess.com and Lichess games in the En Croissant desktop app for analysis.</p>
  </div>
  <div :class="$style.extensionLinks">
    <a href="https://addons.mozilla.org/en-US/firefox/addon/analyze-in-en-croissant/">Get for Firefox <span aria-hidden="true">↗&#xfe0e;</span></a>
    <a href="https://chromewebstore.google.com/detail/mllbeokflemnjecafneljcdomkgaameb">Get for Chrome <span aria-hidden="true">↗&#xfe0e;</span></a>
  </div>
</section>

<figure :class="$style.showcase">
	<img src="/showcase.webp" alt="Board" width="1550" />
	<figcaption>
		En Croissant's analysis screen
	</figcaption>
</figure>

<style module>
.extensions {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 16px 24px;
  margin-top: 24px;
  padding: 24px;
  border: 1px solid var(--vp-c-divider);
  border-radius: 12px;
  background: var(--vp-c-bg-soft);
}

.extensionCopy {
  flex: 1 1 360px;
}

.extensions h2 {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 20px;
  line-height: 28px;
}

.extensions p {
  margin: 4px 0 0;
  color: var(--vp-c-text-2);
  font-size: 14px;
  line-height: 24px;
}

.extensionLinks {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

.extensionLinks a {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  min-height: 44px;
  padding: 0 16px;
  border: 1px solid var(--vp-c-divider);
  border-radius: 22px;
  background: var(--vp-c-bg);
  color: var(--vp-c-text-1);
  font-size: 14px;
  font-weight: 600;
  text-decoration: none;
}

.extensionLinks a:hover {
  border-color: var(--vp-c-text-2);
  color: var(--vp-c-text-1);
}

.extensionLinks a:focus-visible {
  outline: 2px solid var(--vp-c-text-1);
  outline-offset: 2px;
}

@media (max-width: 480px) {
  .extensionLinks {
    width: 100%;
  }

  .extensionLinks a {
    flex: 1 0 auto;
    padding: 0 12px;
  }
}

.showcase {
  margin-top: 2rem;
  margin-left: auto;
  margin-right: auto;
  padding: 1.5rem;
  max-width: 80rem;
}

figcaption {
  font-size: 0.8em;
  text-align: center;
  margin-top: 1rem;
}
</style>
