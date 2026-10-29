# Hi 👋, I'm Alessandro Cucchi

<p>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1200&color=1B7F8C&width=620&lines=Data+Analyst;I+turn+raw+data+into+clear+answers;I+explain+results+to+the+people+who+decide" alt="Typing animation">
</p>

## 👨🏽‍🔬 Data Analyst for hire!

I'm a data analyst. I take raw numbers, work out what they really say, and explain them in plain language, helping turn data into insights that people can actually use.

- I'm drawn to questions where data can make a real difference
- I like digging into the details, finding patterns, and understanding what's behind the numbers
- I turn complex findings into clear, meaningful insights that are easy to communicate and act on
- Italian 🇮🇹 and English 🇬🇧

## 🚀 Featured project

<table>
  <tr>
    <td width="42%" align="center">
      <a href="https://github.com/AlessandroCucchi/Restaurant_Demand_Forecasting">
        <img src="assets/restaurant_icon.svg" alt="Restaurant demand forecasting icon" width="260">
      </a>
    </td>
    <td>
      <h3>Restaurant Demand Forecasting: how many covers tomorrow?</h3>
      <p><b>The question:</b> can 829 restaurants forecast tomorrow's covers better than "same as last week", using their own history and online reservations?</p>
      <p><b>What the analysis found:</b></p>
      <ul>
        <li>Daily demand is volatile: in <b>63%</b> of restaurants covers move by more than half of an average day, and Saturday brings <b>1.6x</b> Monday's covers</li>
        <li>Online reservations show only part of the demand: <b>~21%</b> of covers where they are used, <b>17%</b> known the day before</li>
        <li>A gradient boosting model cuts the forecast error from <b>41.9% to 31.8%</b>: <b>24% fewer covers misplanned</b> and <b>45% less food prepared and not served</b></li>
        <li>The model under-forecasts by <b>~9%</b>: the bias is measured and flagged as the next fix, with holidays and one-off events still planned by hand</li>
      </ul>
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white" alt="pandas">
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white" alt="scikit-learn">
      <img src="https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white" alt="Jupyter">
      <br><br>
      <a href="https://github.com/AlessandroCucchi/Restaurant_Demand_Forecasting"><b>Go to project →</b></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="42%" align="center">
      <a href="https://github.com/AlessandroCucchi/Hotel_Cancellation_Analysis">
        <img src="assets/hotel_icon.svg" alt="Hotel cancellation analysis icon" width="260">
      </a>
    </td>
    <td>
      <h3>Hotel Cancellation Analysis: which bookings will be cancelled, and what can a hotel do about it?</h3>
      <p><b>The question:</b> for a resort and a city hotel, how often are bookings cancelled, when does it cost most, and can the risk be estimated on the day of booking?</p>
      <p><b>What the analysis found:</b></p>
      <ul>
        <li><b>37% of bookings are cancelled</b>, and cancellations peak when rooms are most expensive: resort prices rise <b>3.5x</b> in summer, and so do cancellations</li>
        <li>The risk grows with lead time: from <b>9.6%</b> for bookings made a week before arrival to <b>67.7%</b> for bookings made over a year ahead</li>
        <li>"Non Refund" bookings are cancelled <b>99.4%</b> of the time: they turned out to be tour-operator room blocks, a quarter of the city hotel's cancellations</li>
        <li>A model tested on 2017 bookings ranks cancellation risk with <b>ROC AUC 0.82</b>, after removing columns that leak the outcome, and feeds risk tiers and weekly forecasts. A <a href="https://public.tableau.com/views/Presentazione_Hotel_Cancellations/Dashboard1">Tableau dashboard</a> summarises the KPIs</li>
      </ul>
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white" alt="pandas">
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white" alt="scikit-learn">
      <img src="https://img.shields.io/badge/Tableau-E97627?logo=tableau&logoColor=white" alt="Tableau">
      <img src="https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white" alt="Jupyter">
      <br><br>
      <a href="https://github.com/AlessandroCucchi/Hotel_Cancellation_Analysis"><b>Go to project →</b></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="42%" align="center">
      <a href="https://github.com/AlessandroCucchi/Online_Grocer_Analysis">
        <img src="assets/grocer_icon.svg" alt="Online grocer analysis icon" width="260">
      </a>
    </td>
    <td>
      <h3>Online Grocer Analysis: what keeps customers coming back every week?</h3>
      <p><b>The question:</b> an online grocer delivering in fixed time slots lives on repeat business. When do customers order, how often do they come back, and what do they buy again?</p>
      <p><b>What the analysis found:</b></p>
      <ul>
        <li>Weekly shoppers are <b>32% of customers</b> but place <b>57% of all orders</b>; together with bi-weekly shoppers they place <b>81%</b></li>
        <li><b>30k regular customers (15%)</b> had a last gap of at least twice their usual rhythm, most of them bi-weekly shoppers</li>
        <li>Fresh food is <b>55% of the basket</b> and the most predictable demand: reordered <b>69% of the time</b> vs 55% for other products, which makes it the best place to cut waste with order data</li>
        <li>The first basket is an early signal: new customers who buy organic family items become weekly shoppers <b>40-44% of the time</b>, vs 32% overall</li>
      </ul>
      <img src="https://img.shields.io/badge/SQL-4479A1" alt="SQL">
      <img src="https://img.shields.io/badge/DuckDB-FFF000?logo=duckdb&logoColor=black" alt="DuckDB">
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white" alt="pandas">
      <img src="https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white" alt="Jupyter">
      <br><br>
      <a href="https://github.com/AlessandroCucchi/Online_Grocer_Analysis"><b>Go to project →</b></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="42%" align="center">
      <a href="https://github.com/AlessandroCucchi/food_platform_analysis">
        <img src="assets/food_icon.svg" alt="Food platform analysis icon" width="260">
      </a>
    </td>
    <td>
      <h3>Food Platform Analysis: where does the growth come from?</h3>
      <p><b>The question:</b> can a cooking platform understand why its community is growing, which users are about to leave, and where to focus next year?</p>
      <p><b>What the analysis found:</b></p>
      <ul>
        <li>Activity grew <b>almost six-fold in three years</b> (108 to 623 cooking sessions a year) while new sign-ups stayed flat at about 6-7 a month, so growth comes from existing users cooking more, not from more users joining</li>
        <li>Users do not fall into natural groups (checked against simulated data with no groups at all), so I built four simple behavioural segments. <b>23% of users</b> used to be as active as the best ones but have been silent for about 200 days, which makes them the best group to win back</li>
        <li>Recipe type, chef, difficulty and device make <b>no real difference to ratings</b>: statistical tests found nothing beyond chance, so changing the catalogue is unlikely to be the main lever</li>
        <li>Newer sign-up groups become active <b>much faster</b> than older ones (about 1.4, 1.8 and 4.2 sessions per user in their first year), a pattern worth understanding and repeating</li>
      </ul>
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white" alt="pandas">
      <img src="https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white" alt="Jupyter">
      <br><br>
      <a href="https://github.com/AlessandroCucchi/food_platform_analysis"><b>Go to project →</b></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="42%" align="center">
      <a href="https://github.com/AlessandroCucchi/wine_cultivar_analysis">
        <img src="assets/wine_icon.png" alt="Wine cultivar analysis icon" width="260">
      </a>
    </td>
    <td>
      <h3>Wine Cultivar Analysis: which measurements tell three wines apart?</h3>
      <p><b>The question:</b> can a wine-quality laboratory recognise a wine's grape cultivar from the chemical analysis it already runs, and which measurements matter most?</p>
      <p><b>What the analysis found:</b></p>
      <ul>
        <li>The cultivar was recognised correctly <b>96-98% of the time</b>, against about 40% for a rule that always names the most common cultivar</li>
        <li><b>Three measurements</b> (flavanoids, proline and an optical-density ratio) do most of the work, but no single one is enough on its own</li>
        <li>Preparing the data matters: when the measurements were not put on the same scale, accuracy <b>dropped by about 20 points</b></li>
        <li>A perfect 100% on one test turned out to be <b>mostly luck</b>. Over 20 different reshuffles of the data it appeared only 5-25% of the time, so the result is reported as a range, not a single number</li>
      </ul>
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white" alt="pandas">
      <img src="https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white" alt="Jupyter">
      <br><br>
      <a href="https://github.com/AlessandroCucchi/wine_cultivar_analysis"><b>Go to project →</b></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="42%">
      <a href="https://github.com/AlessandroCucchi/fetal_health_classification">
        <img src="assets/healthcare_icon.png" alt="Fetal health analysis results">
      </a>
    </td>
    <td>
<h3>Fetal Health Analysis: identifying high-risk recordings early</h3>

<p>A company developing prenatal monitoring tools works with healthcare providers to help assess fetal health through heart-rate recordings collected during pregnancy. For clinics with limited resources, being able to identify recordings that may require closer attention is particularly valuable, as specialist time and more advanced monitoring equipment are not always readily available.</p>

<p>With the aim of exploring how data could support this process, the project analyzes a dataset of fetal heart-rate measurements to identify patterns associated with high-risk cases and assess whether a smaller set of measurements could provide similar results. The analysis focuses on detecting high-risk recordings reliably, while also exploring whether simpler monitoring setups could make the process more accessible.</p>

  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white" alt="pandas">
      <img src="https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white" alt="Jupyter">
      <br><br>
      <a href="https://github.com/AlessandroCucchi/fetal_health_classification"><b>Go to project →</b></a>
    </td>
  </tr>
</table>

<p align="center">
      <a href="https://drive.google.com/file/d/13VwE_DQOWgm-x9hcvJmBAFmXzyYDT0iq/view?usp=sharing" target="_blank">
        <img width="240px" src="https://res.cloudinary.com/dxctpvd8v/image/upload/v1746296413/Data_Analysis/resume_button" />
    </a>
</p>


## 🛠️ Tools

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

## 🤝 Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-LINKEDIN/)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:YOUR-EMAIL)
