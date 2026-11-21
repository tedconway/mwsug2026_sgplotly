### [MWSUG](https://www.mwsug.org/) 2026 - Paper DV-102 - %SGPLOTLY: A SAS® Macro for Specifying and Creating Plotly Sunburst Charts

#### Abstract
Even when LLM-based agents produce visually effective charts, cautions Microsoft in a just-published research paper, the resulting specifications and generated code are often verbose and fragile. Microsoft's answer to this problem is Flint, its new visualization language that compiles simple, human-editable specifications into complete, executable specifications for multiple target grammars, including Plotly. It's a concept that's very familiar to users of SAS macros, which have enabled SAS programmers for decades to quickly and easily define and use their own high-level language extensions that compile into deterministic executable code. In this session, we'll take a look at SAS macros - designed in the spirit of PROC SGPLOT - that allow one to easily specify the parameters for Plotly Sunburst charts. We'll also touch on options for executing the emitted Python code directly from SAS (e.g., SASPy, X commands, PROC PYTHON). Finally, we'll take a quick look into how non-deterministic LLMs can be used to help get ideas for the deterministic macros (design, code, and documentation!) that constitute our domain-specific language (DSL) for visualization. This session is intended for all levels of SAS programmers.

#### Links
**Paper** <a href="https://tedconway.github.io/mwsug2026_sgplotly/DV-102.pdf">pdf</a> <a href="https://tedconway.github.io/mwsug2026_sgplotly/DV-102.docx">docx</a>
**Slides** <a href="https://tedconway.github.io/mwsug2026_sgplotly/MWSUG DV-102.pdf">pdf</a> <a href="https://tedconway.github.io/mwsug2026_sgplotly/MWSUG DV-102.pptx">pptx</a>
**Code** *coming soon!*

#### Interactive Plotly Chart Examples on GitHub Pages
[NBA Salary Sunburst Plot](https://tedconway.github.io/mwsug2026_sgplotly/nba_sunburst.html) [NBA Salary Icicle Plot](https://tedconway.github.io/mwsug2026_sgplotly/nba_icicle.html) [NBA Salary Treemap Plot](https://tedconway.github.io/mwsug2026_sgplotly/nba_treemap.html)
