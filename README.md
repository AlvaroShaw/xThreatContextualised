Webpage: https://alvaroshaw.github.io/xThreatContextualised/

## Skills & Tools

**Data Collection & Engineering**

* **Python** — primary language for data manipulation and pipeline construction.
* **Pandas & NumPy** — data wrangling, cleaning, and coordinate-based mathematical calculations.
* **StatsBomb Open Data** — extracting, parsing, and filtering highly granular event data (2015/16 Premier League season), specifically isolating successful open-play passes and their X/Y coordinates.
* **Web Scraping** — extracting exact "minutes played" data from Fbref to accurately convert raw event volume into reliable per-90 metrics.
* **Data Merging** — joining scraped Fbref playing time with StatsBomb event datasets and applying a 900-minute threshold to filter out statistical anomalies.

**Mathematical Modelling & Advanced Metrics**

* **Expected Threat (xT) Framework** — applying Karun Singh’s pre-computed 12x8 positional probability matrix to calculate the spatial value of possession.
* **Positional Value Calculation** — mapping raw X/Y pass coordinates to the 12x8 grid and calculating *xT Added* (End xT minus Start xT).
* **Z-Score Normalisation** — standardising midfielder metrics to evaluate player impact strictly relative to the league average.
* **Tracking Data Proxies** — engineering custom proxy metrics (*Vertical Bypassing* and *Horizontal Stretching*) by calculating lateral and vertical pass distances to quantify defensive shape disruption without raw tracking data.

**Visualisation & Web Development**

* **D3.js & Vanilla JavaScript** — engineering a fully custom, interactive 12x8 football pitch heatmap with dynamic hover-states displaying zonal scoring probabilities.
* **Plotly (Graph Objects)** — building interactive, web-ready bar charts (Top 15 Playmakers) and scatter plots (Z-Score Profiles) with custom tooltips.
* **HTML / CSS** — designing a fully responsive, editorial-grade layout utilizing a premium Burgundy & Gold color palette with floating, borderless `iframes`.
* **Intersection Observer API** — implementing smooth, scroll-triggered `fade-up` animations for seamless reading experiences.
* **Responsive Design Logic** — writing custom JavaScript to dynamically scale and resize interactive Desktop-sized charts to preserve aspect ratios on mobile devices.
* **Google Fonts** — utilizing *Lora* (serif headings), *Inter* (body/data), and *Oswald* (graphical headers) for a polished, journalistic aesthetic.

**Research & Tactical Analysis**

* **Contextual Evaluation** — analysing the inherent blind spots of pure event data (e.g., ignoring defensive structures) and addressing them using spatial disruption proxies.
* **Tactical Application** — translating abstract mathematical models into actionable Opposition Analysis (e.g., dictating central compactness vs. lateral sliding based on an opponent's Z-score profile).
