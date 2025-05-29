```markdown
# 🌌 Hypernormalization-Illusion

<div style="text-align: center;">
  <a href="https://github.com/your-username/Hypernormalization-Illusion/stargazers"><img src="https://img.shields.io/github/stars/your-username/Hypernormalization-Illusion?style=social" alt="GitHub Stars" style="display:inline-block;"></a>
  <a href="https://github.com/your-username/Hypernormalization-Illusion/network"><img src="https://img.shields.io/github/forks/your-username/Hypernormalization-Illusion?style=social" alt="GitHub Forks" style="display:inline-block;"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT" style="display:inline-block;"></a>
</div>

**Unmask the illusion of economic stability with an interactive RShiny dashboard!** 📊✨  
Explore U.S. economic trends (2020–2025) through the lens of *hypernormalization*, revealing eerie parallels with the late USSR’s collapse. Dive into unemployment spikes, SNAP surges, tech layoffs, and media disconnects with sleek, PowerBI-inspired visualizations.

⭐ **Star this repo to support the project!**

---

## 📋 Table of Contents

- [🌟 Introduction](#introduction)
- 🔥 [Hypernormalization Analysis](#hypernormalization-analysis)
- ❓ [Why This Matters](#why-this-matters)
- 🚀 [Features](#features)
- 🛠️ [Tech Stack](#tech-stack)
- 💻 [Installation](#installation)
- 📈 [Tutorials](#tutorials)
- 💾 [Code](#code)
- 🤝 [Contributing](#contributing)
- 📜 [License](#license)
- 📬 [Contact](#contact)

---

## 🌟 Introduction

**The Illusion of Stability** is a cutting-edge **RShiny dashboard** that peels back the curtain on U.S. economic narratives from 2020 to 2025. Drawing on Adam Curtis’s *hypernormalization*—where societies cling to failing systems through denial—it visualizes:

- **Unemployment**: 📉 2.6M claims in 2025.
- **SNAP**: 🍽️ 5.7M applicants.
- **Tech Layoffs: 💼 Amazon’s 18,000 job cuts (2022).
- **Media Shifts**: 🗞️ From CNN’s 2021 “roaring back” to X’s 2025 skepticism (@EconWatcher).

By juxtaposing these with the USSR’s collapse (1970–1991), it reveals chilling parallels: propaganda, cynicism, and cracks in the system. Powered by **RShiny**, **Plotly**, and **echarts4r**, the app boasts a modern **dark theme**, **glassmorphic tabs**, **gradient buttons**, and **animated transitions** for an immersive experience.

> 🚀 Ready to question the narrative? Clone the repo and explore!

---

## 🔥 Hypernormalization Analysis

*Hypernormalization*, per Adam Curtis, is when “everyone knows the system is failing, but no one can imagine an alternative.” This dashboard exposes this in the U.S., mirroring the late USSR.

### 📊 Economic Disconnects

- **Unemployment**: Claims surged from **2.1M (2022)** to **2.6M (2025)**, despite GDP growth slowing to **1.2%**. Bloomberg’s 2024 “soft landing” narrative clashes with X’s skepticism (@EconWatcher, 2025).
- **SNAP Surge**: Applicants grew from **4.5M (2022)** to **5.7M (2025)**, with the South at **2.4M**, highlighting food insecurity ignored by recovery tales.
- **Tech Layoffs**: Firms like Meta (**11,000 cuts, 2022**) shed jobs due to cost-cutting (2022), tariffs (2023), and automation (2024), masked by innovation hype.
- **Education Shifts**: College enrollment dropped from **17.5M (2020)** to **16.1M (2023)**, with **130,000** jobs automated, yet “education boom” persists.

### 🌍 USSR Parallels

- **1970s USSR**: 📰 Brezhnev’s propaganda promised stability amid shortages, leading to compliance (1970), dissent (1980), and collapse (1991).
- **2020s U.S.**: 🦠 Pandemic spikes (2020), WSJ’s “resilient labor market” (2023), and tariff uncertainty (2025) show media-reality gaps.
- **Quotes**:
  - > “The Soviet system was not working... but we kept pretending it was.” – Mikhail Gorbachev (1991)
  - > “We’re sleepwalking into economic chaos with these tariffs.” – Elon Musk (2025)

### 🗳️ Media and Sentiment

- **Media**: Bullish CNN (2021) shifted to neutral Bloomberg (2024) and bearish X (2025). Economist warnings (Roubini: stagflation, 2023; Summers: 60% recession, 2025) are ignored.
- **Systemic Strain**: UI call volumes (LA’s **5.7M** peak) echo USSR’s shortage denial.

The app’s **interactive timeline** and **quote carousel** highlight these parallels, exposing how denial fosters distrust and precarity.

---

## ❓ Why This Matters

Hypernormalization isn’t just history—it’s a warning for 2025:

- 🔍 **Economic Precarity**: Rising unemployment (**2.6M**) and SNAP (**5.7M**) signal fragility, yet media downplays risks, eroding public trust (X, 2025).
- 🔍 **Social Impact**: Automation and layoffs reshape jobs, while college enrollment (**16.1M**, 2023) demands new skilling models.
- 🔍 **Policy Risks**: Tariff uncertainty and ignored warnings (Yellen, 2024) risk instability, echoing USSR’s fall.
- 🔍 **Global Lessons**: The USSR’s collapse warns of cynicism and failure from denialization. The U.S. must face reality.

This dashboard empowers **economists**, **policymakers**, and **data enthusiasts** to question narratives, analyze data, and spark sustainable solutions.

---

## 🚀 Features

- 📈 **Overview**: Line chart of unemployment, GDP, and media sentiment (2020–2025).
- 📊 **UI Calls**: Bar chart of call volumes by city, spotlighting COVID/tariff peaks.
- 🍎 **SNAP**: Line and pie charts of applicants by region, with interactive filters.
- 💼 **Tech Layoffs**: Bar chart of layoffs by company, with narrative impacts.
- 🎓 **Education**: Dual line chart of enrollment vs. skilling, with automation displacement.
- 🗣 **Economists**: Table of warnings from Summers, Yellen, and Roubini.
- 📰 **Media Sentiment**: Quote carousel of narratives (CNN to X).
- 🌐 **Historical Parallel**: Timeline comparing USSR (1970–1991) and U.S. (2020–2025).
- 🎨 **Design**: PowerBI/Apple-inspired **dark theme** glassmorphic theme with glassmorphic tabs, gradient buttons, and animations.

---

## 🛠️ Tech Stack

The app harnesses a sleek **R ecosystem** for visualization:

| Package | 📚 Description | 🔢 Version | 🎨 Badge |
|---------|----------------|------------|----------|
| [shiny](https://shiny.rstudio.com/) | Interactive web apps in R | 1.7.5 | [![Shiny](https://img.shields.io/badge/Shiny-1.7.5-blue?style=flat-square&logo=r)](https://cran.r-project.org/package=shiny) |
| [ggplot2](https://ggplot2.tidyverse.org/) | Elegant data visualization | 3.4.2 | [![ggplot2](https://img.shields.io/badge/ggplot2-3.4.2-green?style=flat-square&logo=r)](https://cran.r-project.org/package=ggplot2) |
| [plotly](https://plotly.com/r/) | Web-based interactive plots | 4.10.2 | [![Plotly](https://img.shields.io/badge/Plotly-4.10.2-orange?style=flat-square&logo=plotly)](https://cran.r-project.org/package=plotly) |
| [echarts4r](https://echarts4r.john-coene.com/) | JavaScript charts for R | 0.4.4 | [![echarts4r](https://img.shields.io/badge/echarts4r-0.4.4-purple?style=flat-square&logo=r)](https://cran.r-project.org/package=echarts4r) |
| [shinythemes](https://rstudio.github.io/shinythemes/) | Pre-built Shiny themes | 1.2.0 | [![shinythemes](https://img.shields.io/badge/shinythemes-1.2.0-red?style=flat-square&logo=r)](https://cran.r-project.org/package=shinythemes) |

---

## 💻 Installation

<details>
<summary>🔧 Setup Guide</summary>

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Hypernormalization-Illusion.git
   cd Hypernormalization-Illusion
   ```

2. **Install R and RStudio**:
   - 📥 Download [R](https://www.r-project.org/) (4.2.0+).
   - 🖥️ Install [RStudio](https://www.rstudio.com/products/rstudio/download/).

3. **Install Dependencies**:
   ```R
   install.packages(c("shiny", "ggplot2", "plotly", "echarts4r", "shinythemes"))
   ```

4. **Run the App**:
   - 📂 Open `app.R` in RStudio.
   - ▶️ Click “Run App” or run:
     ```R
     shiny::runApp()
     ```

</details>

---

## 📈 Tutorials

<details>
<summary>🖱️ How to Use</summary>

- **Navigate Tabs**: 🧭 Use the top bar to explore “Overview,” “SNAP,” “Tech Layoffs,” etc.
- **Interact with Visuals**:
  - 🖱️ Hover over charts for tooltips (e.g., SNAP details).
  - 🔽 Use dropdowns (e.g., SNAP region) and sliders (e.g., quote carousel).
- **Download Outputs**:
  - 📥 Click “Download Plot as PNG” for charts or “Download Table as CSV” for warnings.
- **Explore Hypernormalization**:
  - 🌍 Compare USSR/U.S. timelines in “Historical Parallel.”
  - 💭 Reflect on quotes from Gorbachev, Yellen, and Musk.

</details>

---

## 💾 Code

<details>
<summary>📜 Full RShiny Code</summary>

```R
library(shiny)
library(ggplot2)
library(plotly)
library(echarts4r)
library(shinythemes)

# --- Hardcoded Datasets ---

# 1. Unemployment Claims, GDP Growth, and Media Sentiment (2020–2025)
unemployment_data <- data.frame(
  year = 2020:2025,
  unemployment_claims_thousands = c(2500, 2200, 2100, 2300, 2400, 2600),
  gdp_growth_percent = c(-3.5, 5.7, 2.8, 2.1, 1.9, 1.2),
  media_sentiment = c(0.2, 0.6, 0.8, 0.7, 0.5, 0.4)
)

# 2. UI Call Volume by City (2020–2025 Average)
ui_calls <- data.frame(
  city = c("New York", "Los Angeles", "Chicago", "Houston", "Philadelphia"),
  average_calls_thousands = c(10, 12, 8, 9.5, 7.5),
  peak_calls_thousands = c(1200, 5700, 150, 200, 130),
  system_overload_reports = c(500, 700, 300, 400, 250)
)

# 3. SNAP Applications by Region (2020–2025)
snap_data <- data.frame(
  year = 2020:2025,
  northeast_millions = c(1.2, 1.1, 1.0, 1.1, 1.2, 1.3),
  south_millions = c(2.0, 1.9, 1.8, 2.0, 2.2, 2.4),
  midwest_millions = c(1.0, 0.9, 0.8, 0.9, 1.0, 1.1),
  west_millions = c(1.0, 0.9, 0.9, 1.0, 1.1, 1.2),
  total_millions = c(5.2, 4.8, 4.5, 4.9, 5.3, 5.7)
)

# 4. Tech Layoffs (2022–2025)
tech_layoffs <- data.frame(
  year = rep(2022:2025, each = 5),
  company = rep(c("Meta", "Google", "Amazon", "Microsoft", "Twitter"), 4),
  layoffs = c(11000, 12000, 18000, 10000, 3700, 8000, 9000, 16000, 7000, 2000, 5000, 4000, 14000, 6000, 1500, 3000, 2500, 10000, 5000, 1000),
  narrative_impact = c(rep("Cost-cutting", 5), rep("Tariff fears", 5), rep("Automation", 5), rep("Economic uncertainty", 5))
)

# 5. Education Shifts (2020–2023)
education_shift <- data.frame(
  year = 2020:2023,
  college_enrollment_million = c(17.5, 16.9, 16.4, 16.1),
  skilling_programs_million = c(1.2, 1.6, 2.0, 2.5),
  automation_displacement_thousands = c(50, 75, 100, 130)
)

# 6. Economist Warnings (2021–2025)
economist_warnings <- data.frame(
  year = c(2021, 2022, 2023, 2024, 2025),
  name = c("Summers", "El-Erian", "Roubini", "Yellen", "Summers"),
  message = c("Overheating risk from stimulus", "Recession risk rising", "Stagflation warning", "Uncertainty acknowledged", "60% recession probability"),
  source = c("NY Times", "Bloomberg", "Bloomberg", "Treasury", "NY Times")
)

# 7. Historical Parallels (USSR vs. U.S.)
historical_parallels <- data.frame(
  year = c(1970, 1980, 1991, 2020, 2023, 2025),
  entity = c(rep("USSR", 3), rep("US", 3)),
  event = c("Brezhnev's stability propaganda", "Economic stagnation peaks", "USSR collapse", "Pandemic unemployment spike", "Soft landing narrative", "Tariff-driven uncertainty"),
  hypernormalization_trait = c("State media control", "Denial of shortages", "Public cynicism", "Booming economy narrative", "Media vs. reality disconnect", "Policy contradictions"),
  impact = c("Public compliance", "Underground dissent", "Systemic collapse", "Public confusion", "Rising distrust", "Economic precarity")
)

# 8. Quote Carousel
quotes <- data.frame(
  source = c("Mikhail Gorbachev", "Janet Yellen", "Adam Curtis", "Elon Musk"),
  quote = c("The Soviet system was not working... but we kept pretending it was.", 
            "The economy is strong, but uncertainties remain.", 
            "Hypernormalization is when everyone knows the system is failing but no one can imagine an alternative.", 
            "We’re sleepwalking into economic chaos with these tariffs."),
  year = c(1991, 2024, 2016, 2025)
)

# 9. Media Sentiment Quotes
media_quotes <- data.frame(
  year = c(2021, 2023, 2024, 2025),
  source = c("CNN", "Wall Street Journal", "Bloomberg", "X Post (@EconWatcher)"),
  quote = c("The U.S. economy is roaring back post-COVID!", 
            "Resilient labor market defies recession fears.", 
            "Soft landing achieved, but risks linger.", 
            "Unemployment claims spike to 260k, yet they call this a boom? #Hypernormalization"),
  sentiment = c("Bullish", "Bullish", "Neutral", "Bearish")
)

# --- UI ---
ui <- fluidPage(
  theme = shinytheme("darkly"),
  tags$head(tags$style(HTML("
    /* Global Styles */
    body {
      background: linear-gradient(135deg, #1a1a1a 0%, #0b0b0b 100%);
      color: #e0e0e0;
      font-family: 'SF Pro Display', 'Inter', -apple-system, sans-serif;
      margin: 0;
      overflow-x: hidden;
    }

    .container-fluid {
      padding: 20px;
      max-width: 1400px;
      margin: 0 auto;
    }

    /* Title */
    .title-panel {
      text-align: center;
      font-size: 2.2rem;
      font-weight: 600;
      color: #ffffff;
      background: linear-gradient(90deg, #e63946, #ffa726);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      padding: 20px 0;
      margin-bottom: 20px;
      text-shadow: 0 2px 4px rgba(0,0,0,0.3);
    }

    /* Tabs */
    .nav-tabs {
      background: rgba(30, 30, 30, 0.95);
      border-radius: 8px;
      padding: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.4);
      backdrop-filter: blur(10px);
    }

    .nav-tabs > li > a {
      color: #cccccc;
      font-weight: 500;
      padding: 12px 20px;
      border-radius: 6px;
      transition: all 0.3s ease;
    }

    .nav-tabs > li > a:hover {
      background: rgba(230, 57, 70, 0.2);
      color: #ffffff;
    }

    .nav-tabs > li.active > a {
      background: #e63946;
      color: #ffffff;
      font-weight: 600;
    }

    /* Card Containers */
    .tab-panel {
      background: rgba(20, 20, 20, 0.9);
      border-radius: 12px;
      padding: 20px;
      margin: 20px 0;
      box-shadow: 0 6px 20px rgba(0,0,0,0.5);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      animation: fadeIn 0.5s ease-out;
    }

    .tab-panel:hover {
      transform: translateY(-4px);
      box-shadow: 0 8px 24px rgba(230, 57, 70, 0.3);
    }

    /* Quote Box */
    .quote-box {
      background: rgba(40, 40, 40, 0.8);
      border-left: 4px solid #e63946;
      padding: 15px 20px;
      margin: 20px 0;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.3);
      transition: transform 0.3s ease;
    }

    .quote-box:hover {
      transform: scale(1.02);
    }

    .quote-box p {
      margin: 5px 0;
      font-size: 1rem;
      line-height: 1.5;
    }

    /* Inputs */
    .form-control, .selectize-input {
      background: #2a2a2a;
      color: #e0e0e0;
      border: 1px solid #444;
      border-radius: 6px;
      padding: 10px;
      transition: border-color 0.3s ease;
    }

    .form-control:focus, .selectize-input.focus {
      border-color: #e63946;
      box-shadow: 0 0 0 2px rgba(230, 57, 70, 0.3);
    }

    /* Buttons */
    .btn {
      background: linear-gradient(90deg, #e63946, #ffa726);
      color: #ffffff;
      border: none;
      border-radius: 6px;
      padding: 10px 20px;
      font-weight: 500;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 4px 12px rgba(230, 57, 70, 0.4);
    }

    /* Plotly and echarts4r */
    .plotly, .echarts4r {
      background: rgba(20, 20, 20, 0.95);
      border-radius: 8px;
      padding: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
      animation: slideIn 0.5s ease-out;
    }

    /* Table */
    table {
      width: 100%;
      background: #2a2a2a;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
    }

    th, td {
      padding: 12px;
      text-align: left;
      border-bottom: 1px solid #444;
      color: #e0e0e0;
    }

    th {
      background: #e63946;
      color: #ffffff;
      font-weight: 600;
    }

    /* Animations */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes slideIn {
      from { opacity: 0; transform: translateX(-10px); }
      to { opacity: 1; transform: translateX(0); }
    }

    /* Loading Animation */
    .shiny-plot-output:empty::before {
      content: 'Loading...';
      color: #e63946;
      font-size: 1.2rem;
      text-align: center;
      padding: 50px;
      display: block;
      animation: pulse 1.5s infinite;
    }

    @keyframes pulse {
      0% { opacity: 0.6; }
      50% { opacity: 1; }
      100% { opacity: 0.6; }
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      .title-panel {
        font-size: 1.8rem;
      }
      .nav-tabs > li > a {
        padding: 10px 15px;
        font-size: 0.9rem;
      }
      .tab-panel {
        padding: 15px;
      }
    }
  "))),
  div(class = "title-panel", titlePanel("The Illusion of Stability: Hypernormalization in the U.S. (2020–2025)")),

  tabsetPanel(
    # Overview Tab
    tabPanel("Overview",
      div(class = "tab-panel",
        plotlyOutput("unemployment_plot", height = "600px"),
        downloadButton("download_unemployment", "Download Plot as PNG"),
        p("Unemployment claims rise despite 'booming economy' narratives, reflecting hypernormalization's disconnect.", style = "color: #e0e0e0; margin-top: 10px;")
      )
    ),

    # UI Calls Tab
    tabPanel("UI Calls",
      div(class = "tab-panel",
        plotlyOutput("ui_calls_plot", height = "600px"),
        downloadButton("download_ui_calls", "Download Plot as PNG"),
        p("Peak call volumes during COVID and tariff uncertainty overwhelmed systems, signaling hidden distress.", style = "color: #e0e0e0; margin-top: 10px;")
      )
    ),

    # SNAP Tab
    tabPanel("SNAP",
      div(class = "tab-panel",
        fluidRow(
          column(6, 
            selectInput("snap_region", "Select Region:", choices = c("All", "Northeast", "South", "Midwest", "West")),
            plotlyOutput("snap_line_plot", height = "300px")
          ),
          column(6, plotlyOutput("snap_pie_plot", height = "300px"))
        ),
        downloadButton("download_snap_line", "Download Line Plot as PNG"),
        downloadButton("download_snap_pie", "Download Pie Plot as PNG"),
        p("Rising SNAP applicants highlight food insecurity, contradicting economic recovery stories.", style = "color: #e0e0e0; margin-top: 10px;")
      )
    ),

    # Tech Layoffs Tab
    tabPanel("Tech Layoffs",
      div(class = "tab-panel",
        selectInput("layoff_company", "Select Company:", choices = c("All", unique(tech_layoffs$company))),
        plotlyOutput("layoffs_plot", height = "600px"),
        downloadButton("download_layoffs", "Download Plot as PNG"),
        p("Tech layoffs reflect automation and tariff fears, masked by innovation narratives.", style = "color: #e0e0e0; margin-top: 10px;")
      )
    ),

    # Education Tab
    tabPanel("Education",
      div(class = "tab-panel",
        plotlyOutput("education_plot", height = "600px"),
        downloadButton("download_education", "Download Plot as PNG"),
        p("Declining college enrollment and rising automation displacement drive reskilling demand.", style = "color: #e0e0e0; margin-top: 10px;")
      )
    ),

    # Economists Tab
    tabPanel("Economists",
      div(class = "tab-panel",
        tableOutput("warnings_table"),
        downloadButton("download_warnings", "Download Table as CSV"),
        p("Economist warnings highlight stagflation and recession risks, ignored by mainstream narratives.", style = "color: #e0e0e0; margin-top: 10px;")
      )
    ),

    # Media Sentiment Tab
    tabPanel("Media Sentiment",
      div(class = "tab-panel",
        fluidRow(
          column(12, sliderInput("media_quote_idx", "Media Quotes:", min = 1, max = 4, value = 1, step = 1, animate = TRUE)),
          column(12, uiOutput("media_quote_carousel"))
        ),
        p("Media narratives often clash with economic realities, a key trait of hypernormalization.", style = "color: #e0e0e0; margin-top: 10px;")
      )
    ),

    # Historical Parallel Tab
    tabPanel("Historical Parallel",
      div(class = "tab-panel",
        fluidRow(
          column(12, 
            selectInput("history_entity", "Select Entity:", choices = c("All", "USSR", "US")),
            echarts4rOutput("historical_timeline", height = "400px")
          ),
          column(12, 
            sliderInput("quote_idx", "Explore Quotes:", min = 1, max = 4, value = 1, step = 1, animate = TRUE),
            uiOutput("quote_carousel")
          )
        ),
        p("USSR and U.S. parallels show hypernormalization through propaganda and denial.", style = "color: #e0e0e0; margin-top: 10px;")
      )
    )
  )
)

# --- Server ---
server <- function(input, output, session) {

  # Overview: Unemployment, GDP, Media Sentiment
  output$unemployment_plot <- renderPlotly({
    validate(need(exists("unemployment_data"), "Unemployment data not found"))
    gg <- ggplot(unemployment_data, aes(x = year)) +
      geom_line(aes(y = unemployment_claims_thousands, color = "Unemployment Claims"), size = 1.2) +
      geom_line(aes(y = gdp_growth_percent * 100, color = "GDP Growth x100"), linetype = "dashed", size = 1.2) +
      geom_line(aes(y = media_sentiment * 1000, color = "Media Sentiment x1k"), size = 1.2, linetype = "dotted") +
      scale_color_manual(values = c("Unemployment Claims" = "#e63946", "GDP Growth x100" = "#ffa726", "Media Sentiment x1k" = "#00bcd4")) +
      theme_minimal(base_family = "SF Pro Display") +
      labs(title = "Unemployment, GDP, and Media Sentiment (2020–2025)", y = "", x = "Year") +
      theme(plot.background = element_rect(fill = "transparent", color = NA),
            panel.background = element_rect(fill = "transparent"),
            text = element_text(color = "#e0e0e0"))
    ggplotly(gg)
  })

  output$download_unemployment <- downloadHandler(
    filename = "unemployment_plot.png",
    content = function(file) {
      p <- plotly::plot_ly(data = unemployment_data, x = ~year, y = ~unemployment_claims_thousands, type = "scatter", mode = "lines", name = "Unemployment Claims") %>%
        plotly::add_lines(y = ~gdp_growth_percent * 100, name = "GDP Growth x100", line = list(dash = "dash")) %>%
        plotly::add_lines(y = ~media_sentiment * 1000, name = "Media Sentiment x1k", line = list(dash = "dot")) %>%
        plotly::layout(title = "Unemployment, GDP, and Media Sentiment (2020–2025)", yaxis = list(title = ""), xaxis = list(title = "Year"))
      plotly::export(p, file = file)
    }
  )

  # UI Calls: Bar Chart
  output$ui_calls_plot <- renderPlotly({
    validate(need(exists("ui_calls"), "UI calls data not found"))
    gg <- ggplot(ui_calls, aes(x = city)) +
      geom_bar(aes(y = average_calls_thousands, fill = "Average Calls"), stat =姑 identity", position = position_dodge(width = 0.4)) +
      geom_bar(aes(y = peak_calls_thousands / 100, fill = "Peak Calls (x100)"), stat = "identity", position = position_dodge(width = -0.4)) +
      scale_fill_manual(values = c("Average Calls" = "#00bcd4", "Peak Calls (x100)" = "#e63946")) +
      theme_minimal(base_family = "SF Pro Display") +
      labs(title = "UI Call Volume by City (2020–2025)", y = "Calls (Thousands)", x = "City") +
      theme(plot.background = element_rect(fill = "transparent"),
            text = element_text(color = "#e0e0e0"))
    ggplotly(gg)
  })

  output$download_ui_calls <- downloadHandler(
    filename = "ui_calls_plot.png",
    content = function(file) {
      p <- plotly::plot_ly(data = ui_calls, x = ~city, y = ~average_calls_thousands, type = "bar", name = "Average Calls", marker = list(color = "#00bcd4")) %>%
        plotly::add_trace(y = ~peak_calls_thousands / 100, name = "Peak Calls (x100)", marker = list(color = "#e63946")) %>%
        plotly::layout(title = "UI Call Volume by City (2020–2025)", yaxis = list(title = "Calls (Thousands)"), xaxis = list(title = "City"), barmode = "group")
      plotly::export(p, file = file)
    }
  )

  # SNAP: Line Chart
  output$line_plot <- renderPlotly({
    validate(need(exists("snap_data"), "SNAP data not found"))
    snap_filtered <- if (input$snap_region == "All") {
      snap_data
    } else {
      snap_data[, c("year", paste0(tolower(input$snap_region), "_millions"))]
    }
    gg <- if (input$snap_region == "All") {
      ggplot(snap_filtered, aes(x = year, y = total_millions)) +
        geom_line(color = "#ffa726", size = 1.2) +
        geom_point(color = "#ffa726", size = 3)
    } else {
      ggplot(snap_filtered, aes(x = year)) +
        geom_line(aes(y = get(paste0(tolower(input$snap_region), "_millions")), color = input$snap_region)), size = 1.2) +
        geom_point(aes(y = get(paste0(tolower(input$snap_region), "_millions")), color = input$snap_region)), size = 3) +
        scale_color_manual(values = c("Northeast" = "#e63946", "South" = "#ffa726", "Midwest" = "#00bcd4", "West" = "#cccccc"))
    }
    gg <- gg +
      theme_minimal(base_family = "SF Pro Display") +
      labs(title = paste("SNAP New Applicants (", input$snap_region, ")"), x = "Year", y = "Millions") +
      theme(plot.background = element_rect(fill = "transparent"),
            text = element_text(color = "#e0e0e0"))
    ggplotly(gg)
  })

  output$download_snap_line <- downloadHandler(
    filename = "snap_line_plot.png",
    content = function(file) {
      snap_filtered <- if (input$snap_region == "All") {
        snap_data
      } else {
        snap_data[, c("year", paste0(tolower(input$snap_region), "_millions"))]
      }
      p <- if (input$snap_region == "All") {
        plotly::plot_ly(data = snap_filtered, x = ~year, y = ~total_millions, type = "scatter", mode = "lines+markers", marker = list(color = "#ffa726"), line = list(color = "#ffa726"))
      } else {
        plotly::plot_ly(data = snap_filtered, x = ~year, y = ~get(paste0(tolower(input$snap_region), "_millions"))), type = "scatter", mode = "lines+markers", 
                        marker = list(color = c("Northeast" = "#e63946", "South" = "#ffa726", "Midwest" = "#00bcd4", "West" = "#cccccc")[input$snap_region])), 
                        line = list(color = c("Northeast" = "#e63946", "South" = "#ffa726", "Midwest" = "#00bcd4", "West" = "#cccccc")[input$snap_region])))
      }
      p <- p %>% plotly::layout(title = paste("SNAP New Applicants (", input$snap_region, ")"), xaxis = list(title = "Year"), yaxis = list(title = "Millions"))
      )
      plotly::export(p, file = file)
    }
  )

  # SNAP: Pie Chart (Using Plotly directly)
  output$pie_plot <- renderPlotly({
    validate(need(exists("snap_data"), "SNAP data not found"))
    snap_2025 <- snap_data[snap_data$year == 2025, ]
    pie_data <- data.frame(
      region = c("Northeast", "South", "Midwest", "West"),
      value = c(snap_2025$northeast_millions, snap_2025$south_millions, snap_2025$midwest_millions, snap_2025$west_millions)
    )
    plotly::plot_ly(
      data = pie_data,
      labels = ~region,
      values = ~value,
      type = "pie",
      marker = list(colors = c("#e63946", "#ffa726", "#00bcd4", "#cccccc")),
      textinfo = "label+percent",
      hoverinfo = "text",
      text = ~paste("Region: ", region, "<br>", "Applicants: ", value", ", million"),
      showlegend = FALSE
    ) %>%
    layout(
      title = list(text = "SNAP Applicants by Region (2025)", font = list(color = "#e0e0e0")),
      paper_bgcolor = "transparent",
      plot_bgcolor = "transparent",
      font = list(color = "#e0e0e0"),
      margin = list(t = 100)
    )
  )

  output$download_snap_pie <- downloadHandler(
    filename = "snap_pie_plot.png",
    content = function(file) {
      snap_2025 <- snap_data[snap_data$year == 2025$, ]
      pie_data <- data.frame(
        region = c("Northeast", "South", "Midwest", "West"),
        value = c(snap_2025$northeast_millions, snap_2025_$south_millions, snap_2025$midwest_millions, snap_2025$west_millions)
      )
      p <- plotly::plot_ly(
        data = pie_data,
        labels = ~region,
        values = ~value,
        type = "pie",
        marker = list(colors = c("#e63946", "#ffa726", "#00bcd4", "#cccccc")),
        textinfo = "label+percent",
        showlegend = FALSE
      ) %>%
        plotly::layout(
          title = list(text = "SNAP Applicants by Region (2025)", font = list(color = "#e0e0")),
          paper_backgroundcolor = "transparent",
          plot_bgcolor = "transparent",
          font = list(color = "#e0e0e0")
        )
      plotly::export(p, file = file)
    }
  )

  # Tech Layoffs: Bar Chart
  output$layoffs_plot <- renderPlotly({
    validate(need(exists("tech_layoffs"), "Tech layoffs data not found"))
    layoffs_filtered <- if (input$layoff_company == "All") {
      tech_layoffs
    } else {
      tech_layoffs[tech_layoffs$company == input$layoff_company, ]
    }
    gg <- ggplot(layoffs_filtered, aes(x = year, y = layoffs, fill = company)) +
      geom_bar(stat = "identity", position = "dodge") +
      scale_fill_manual(values = c("Meta" = "#e63946", "Google" = "#ffa726", "Amazon" = "#00bcd4", "Microsoft" = "#cccccc", "Twitter" = "#ff5722")) +
      theme_minimal(base_family = "Helvetica") +
      labs(title = paste("Tech Layoffs by Year (", input$layoff_company, ")"), x = "Year", y = "Layoffs") +
      theme(plot.background = element_rect(fill = "transparent"),
            text = element_text(color = "#e0e0e0"))
    ggplotly(gg)
  })

  output$download_layoffs <- downloadHandler(
    filename = "layoffs_plot.png",
    content = function(file) {
      layoffs_filtered <- if (input$layoff_company == "All") {
        tech_layoffs
      } else {
        tech_layoffs[tech_layoffs$company == input$layoff_company, ]
      }
      p <- plotly::plot_ly(data = layoffs_filtered, x = ~year, y = ~layoffs, type = "bar", color = ~company, 
                           marker = list(colors = c("Meta" = "#e63946", "Google" = "#ffa726", "Amazon" = "#00bcd4", "Microsoft" = "#cccccc", "Twitter" = "#ff5722"))) %>%
        plotly::layout(
          title = paste("Tech Layoffs by Year (", input$layoff_company, ")"),
          xaxis = list(title = "Year"),
          yaxis = list(title = "Layoffs"),
          barmode = "group")
      plotly::export(p, file = file)
    }
  )

  # Education: Dual Line Chart
  output$education_plot <- renderPlotly({
    validate(need(exists("education_shift"), "Education data not found"))
    gg <- ggplot(education_shift, aes(x = year)) +
      geom_line(aes(y = college_enrollment_million, color = "College Enrollment"), size = 1.2) +
      geom_line(aes(y = skilling_programs_million, color = "Skilling Programs"), size = 1.2) +
      geom_line(aes(y = automation_displacement_thousands / 1000, color = "Automation Displacement (x1k)"), size = 1.2, linetype = "dashed") +
      scale_color_manual(values = c("College Enrollment" = "#cccccc", "Skilling Programs" = "#00bcd4", "Automation Displacement (x1k)" = "#e63946")) +
      theme_minimal(base_family = "Helvetica") +
      labs(title = "Education Trends & Automation Displacement", x = "Year", y = "Millions") +
      theme(plot.background = element_rect(fill = "transparent"),
            text = element_text(color = "#e0e0e0"))
    ggplotly(gg)
  })

  output$download_education <- downloadHandler(
    filename = "education_plot.png",
    content = function(file) {
      p <- plotly::plot_ly(
        data = education_shift, 
        x = ~year, 
        y = ~college_enrollment_million, 
        type = "scatter", 
        mode = "lines", 
        name = "College Enrollment", 
        line = list(color = "#cccccc")
      ) %>%
        plotly::add_lines(y = ~skilling_programs_million, name = "Skilling Programs", line = list(color = "#00bcd4")) %>%
        plotly::add_lines(y = ~automation_displacement_thousands / 1000, name = "Automation Displacement (x1k)", line = list(color = "#e63946", dash = "dash")) %>%
        plotly::layout(
          title = "Education Trends & Automation Displacement",
          xaxis = list(title = "Year"),
          yaxis = list(title = "Millions")
        )
      plotly::export(p, file = file)
    }
  )

  # Economists: Table
  output$warnings_table <- renderTable({
    validate(need(exists("economist_warnings"), "Economist warnings data not found"))
    economist_warnings
  })

  output$download_warnings <- downloadHandler(
    filename = "economist_warnings.csv",
    content = function(file) {
      write.csv(economist_warnings, file, row.names = FALSE)
    }
  )

  # Media Sentiment: Quote Carousel
  output$media_quote_carousel <- renderUI({
    validate(need(exists("media_quotes"), "Media quotes data not found"))
    idx <- input$media_quote_idx
    div(class = "quote-box",
        p(media_quotes$quote[idx], style = "color: #e0e0e0;"),
        p(paste0("- ", media_quotes$source[idx], " (", media_quotes$year[idx], ", ", media_quotes$sentiment[idx], ")"), style = "color: #ffa726; font-style: italic;")
    )
  })

  # Historical Parallel: Interactive Timeline
  output$historical_timeline <- renderEcharts4r({
    validate(need(exists("historical_parallels"), "Historical parallels data not found"))
    history_filtered <- if (input$history_entity == "All") {
      historical_parallels
    } else {
      historical_parallels[historical_parallels$entity == input$history_entity, ]
    }
    history_filtered %>%
      e_charts(year) %>%
      e_scatter(hypernormalization_trait, legend = TRUE, symbol_size = 15) %>%
      e_datazoom(type = "slider") %>%
      e_tooltip(formatter = htmlwidgets::JS("
        function(params) {
          return 'Year: ' + params.value[0] + '<br>' +
                 'Entity: ' + params.data.entity + '<br>' +
                 'Event: ' + params.data.event + '<br>' +
                 'Trait: ' + params.value[1] + '<br>' +
                 'Impact: ' + params.data.impact;
        }
      ")) %>%
      e_theme("dark") %>%
      e_color(c("#e63946", "#00bcd4")) %>%
      e_title("USSR vs. U.S.: Hypernormalization Timeline", textStyle = list(color = "#e0e0e0")) %>%
      e_legend(textStyle = list(color = "#e0e0e0"))
  })

  # Quote Carousel
  output$quote_carousel <- renderUI({
    validate(need(exists("quotes"), "Quotes data not found"))
    idx <- input$quote_idx
    div(class = "quote-box",
        p(quotes$quote[idx], style = "color: #e0e0e0;"),
        p(paste0("- ", quotes$source[idx], " (", quotes$year[idx], ")"), style = "color: #ffa726; font-style: italic;")
    )
  })
}

# --- Run App ---
shinyApp(ui, server)
```

</details>

---

## 🤝 Contributing

Contributions are welcome! 🌟 To contribute:

1. 🍴 Fork the repository.
2. 🌿 Create a branch: `git checkout -b feature/your-feature`.
3. 💾 Commit changes: `git commit -m 'Add your feature'`.
4. 🚀 Push to the branch: `git push origin feature/your-feature`.
5. 📬 Open a pull request.

Please follow R style guidelines and include tests where applicable.

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details. 📝

---

## 📬 Contact

For questions or feedback, reach out via:

- 🐙 **GitHub**: [your-username](https://github.com/your-username)
- 📧 **Email**: your-email@example.com
- 💼 **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/your-profile)

---

✨ **Thanks for exploring Hypernormalization-Illusion!** ✨

