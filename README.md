<p align="center"><img src="banner.jpg" alt="" width="100%"></p>

<p align="center"><code>machine learning / language models / finance x ai</code></p>
<p align="center"><sub>now</sub> <b>building dimensionnews.ai</b></p>

<p align="center">
  <a href="https://portfoliofatih.vercel.app">Website</a> &nbsp;/&nbsp;
  <a href="https://huggingface.co/remehostingservices">Hugging Face</a> &nbsp;/&nbsp;
  <a href="https://t.me/sentimentbotnews">Live feed</a> &nbsp;/&nbsp;
  <a href="mailto:fetih9039@gmail.com">Get in touch</a>
</p>

I'm **Fatih**, a.k.a. **Reme**. Final-year computer engineering student. I train language models on my own data and build the system around them until someone is actually using it.

**dimensionnews.ai** is what I am building now: a terminal that matches breaking news to prediction markets.

## Start here

<table>
<tr>
<td width="50%" valign="top">

**01 / MODEL**

### [finance-news-sentiment](https://github.com/RemeDegen/finance-news-sentiment)

FinBERT fine-tuned on 40k financial headlines I labeled with a two-judge + arbiter LLM pipeline. It runs live: nine Telegram finance channels, labeled in real time at [@sentimentbotnews](https://t.me/sentimentbotnews).

[Model](https://huggingface.co/remehostingservices/finbert-finance-news-sentiment) · [Dataset](https://huggingface.co/datasets/remehostingservices/finance-news-sentiment-35k)

</td>
<td width="50%" valign="top">

**02 / AUDIT**

### [nlp-judge-audit](https://github.com/RemeDegen/nlp-judge-audit)

How reliable were those LLM labels? Eight labeling arms, calibration, arbiter bias, downstream error on the fine-tuned model. Technical report with a DOI.

[Report](https://github.com/RemeDegen/nlp-judge-audit/tree/main/report) · [DOI 10.5281/zenodo.22677220](https://doi.org/10.5281/zenodo.22677220)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**03 / SECURITY**

### PhishGuard

Multi-engine phishing analysis for URLs, emails and .eml files: three fine-tuned transformers, live URL inspection, header authentication, attachment analysis, threat-feed reputation and an LLM second opinion, each voting on its own. Graduation thesis grown into a product. Private while the email training data is rebuilt.

[About](https://portfoliofatih.vercel.app/#p1)

</td>
<td width="50%" valign="top">

**04 / TOOLS**

### Claude Code skills

Things I built for my own workflow and published.

- [gemini-fleet](https://github.com/RemeDegen/gemini-fleet) — run Gemini models as delegate agents, no API key
- [video-summary-skill](https://github.com/RemeDegen/video-summary-skill) — any video link to a timestamped summary
- [shortsmith](https://github.com/RemeDegen/shortsmith) — long-form video to original vertical shorts

</td>
</tr>
</table>

<p align="center"><sub><a href="https://portfoliofatih.vercel.app">portfoliofatih.vercel.app</a></sub></p>
