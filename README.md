# EV Charging Station Placement Optimization Project

The global transportation industry has long faced environmental challenges due to the reliance on internal combustion engines (ICEs) and their harmful contributions to climate change. As fossil fuel resources decline and concerns about greenhouse gas emissions—especially carbon dioxide—grow, the urgency to find sustainable transportation alternatives increases. Electric vehicles (EVs), powered by electricity from renewable sources, present a viable solution, significantly reducing greenhouse gas emissions with zero tailpipe emissions. However, the widespread adoption of EVs depends on the development of extensive public charging infrastructure. Strategic placement of EV Charging Stations (EVCS) is crucial to supporting this transition.

---

## Project Overview

This project focuses on addressing key goals related to the demand, dataset creation, and optimal placement of EV charging stations:

### 1. Understanding Demand
We explored how geographical and socio-economic factors can help gauge the demand for EV charging stations in Germany. This includes identifying patterns that reflect the need for infrastructure development in specific areas.

### 2. Dataset Creation
We developed a comprehensive dataset that reflects the socio-demographic characteristics of Germany, incorporating factors such as population density, income distribution, and urbanization.

### 3. Optimal Placement
Using traditional machine learning (ML) techniques, we tackled the challenge of identifying optimal locations for new EV charging stations. By analyzing various geographical and infrastructure-related data points, we aimed to pinpoint locations that would provide the most impact.

### 4. Model Assessment
We evaluated various machine learning models, comparing their effectiveness in predicting the best locations for EVCS placement. This involved testing model performance and accuracy across different algorithms.

### 5. Practical Applications
Our findings aim to improve the understanding of optimal EVCS placement and support automated decision-making for expanding EV charging infrastructure. This research offers valuable insights for urban planners, policymakers, and EV infrastructure developers.

![image](https://github.com/user-attachments/assets/4ddde4d1-3e86-4e94-8bf8-c69202f8ed4b)

---

## Dashboard Overview

Our dashboard, built with [Streamlit](https://streamlit.io/), is an interactive web application that visualizes the results of the project. Hosted on [Hugging Face](https://huggingface.co/), the dashboard provides an interactive map of **Saarbrücken, Germany**, highlighting:

- **Points of Interest (POIs)**: Marking key areas such as residential, commercial, and public spaces.
- **Existing EV Charging Stations**: Locations of current EV charging stations in the region.
- **Optimal EVCS Placement**: Predicted locations for new charging stations based on our machine learning models.

<figure style="text-align:center">
  <img
  src="/figures/dashboard.png"
  alt="pipeline">
  <figcaption>Data Collection Pipeline</figcaption>
</figure>

The dashboard offers additional features, such as exploratory data analysis (EDA) visualizations, including:

- **Pie Chart**: Representing the distribution of different types of infrastructure in Saarbrücken.
- **Feature Insights**: A view of features collected and used for training the model, enhancing understanding of the model’s performance and predictions.

---

## How to Use the Dashboard

- **Interactive Map**: Explore the map of Saarbrücken to see optimal charging station placements along with existing infrastructure.
- **Data Visualizations**: Use the EDA features to gain insights into the geographical and socio-economic factors that influenced the model’s predictions.
- **Model Analysis**: Understand the model performance through comparative charts and visualized results.

---

## Conclusion

This project demonstrates the potential of using machine learning techniques to optimize the placement of EV charging stations. By leveraging geographical, socio-demographic, and infrastructure-related data, we can support the development of a sustainable, future-ready transportation network. The dashboard allows for interactive exploration of our findings and offers actionable insights for expanding EV infrastructure in urban areas.

---

## License

This project is licensed under the MIT License.

---

## Acknowledgments

Special thanks to BuzzOnEarth Team for Providing such an amazing and exciting problem statement to promote sustainable technological development.
