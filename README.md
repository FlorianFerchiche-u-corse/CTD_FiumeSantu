<h1 align="center">R pipeline for processing data from CTD probes monitoring the Fiume Santu estuary waters</h1>

<p align="center">
  <strong>Code repository</strong> to reproduce the processing of the dataset described in the data paper
  "Long-term high-frequency measurements across an intermittent Mediterranean river-estuary continuum".
</p>

<hr>

<h2>🎯 Repository purpose</h2>
<p>
This repository provides the R code used to load, clean, and transform the dataset associated with the data paper
<em>[Data paper reference, DOI]</em>. Its main goal is to support <strong>reproducibility</strong> and scientific reuse of the data.
</p>

<h2>📦 Contents</h2>
<ul>
  <li><code>script_processing.R</code>: main script implementing the complete data processing pipeline.</li>
  <li>R dependencies (CRAN): <code>readxl</code>, <code>dplyr</code>, <code>tidyr</code>, <code>lubridate</code>, <code>zoo</code>, <code>slider</code>, <code>hms</code>.</li>
  <li>Raw and processed data are hosted in a separate repository:
    <a href="[URL of the data repository]">[Name of the data repository]</a>.
  </li>
</ul>

<h2>🗂️ Dataset description</h2>
<p>
The dataset documented in the data paper contains time series of physico-chemical variables measured in an aquatic environment
(salinity, temperature and water level), together with metadata describing the study site,
the sensors used, and the sampling frequency. <!-- Adapt to your actual case -->
</p>
<ul>
  <li><strong>Unit of observation</strong>: high-frequency measurements in an estuarine / coastal system (continuous sensors).</li>
  <li><strong>Time coverage</strong>: [2014 - 2021].</li>
  <li><strong>File formats</strong>: tabular files (CSV/Excel) with a standardized time column and columns for environmental variables.</li>
</ul>

<h2>▶️ How to use this repository</h2>
<ol>
  <li>Install R (&gt;= 4.4.1) and RStudio (optional but recommended).</li>
  <li>Clone this repository:
    <pre><code>git clone https://github.com/[user]/[repo-name].git</code></pre>
  </li>
  <li>Install the required packages:
    <pre><code>install.packages(c("readxl", "dplyr", "tidyr", "lubridate", "zoo", "slider", "hms"))</code></pre>
  </li>
  <li>Adjust the file paths to the data.</li>
  <li>Run the main script:
    <pre><code>source("CTDprobes_treatment_finalcode.R")</code></pre>
  </li>
</ol>

<h2>📑 How to cite</h2>
<p>
If you use this code or the associated dataset, please cite:
</p>
<ul>
  <li>The data paper: submitted to Scientific Data.</li>
  <li>The data repository: Shared when published.</li>
</ul>

<h2>⚖️ License</h2>
<p>
The code in this repository is distributed under the <strong>GNU GPL 3.0</strong>. Please refer to the
<code>LICENSE</code> file for details.
</p>

<h2>📬 Contact</h2>
<p>
For questions or suggestions, please open an issue on GitHub or contact the author at: <code>[your.email@institution.fr]</code>.
</p>
