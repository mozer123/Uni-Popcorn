# Exploring Unicorn Companies with a Zoomable Sunburst

## Intro

Welcome to Charlie and Mert's Project 3: Interactive Visualization repo for [DSC106](https://dsc106.com/), a project-centered course that covers fundamental principles and techniques in data visualization! 

The dataset we used comes from: <https://www.kaggle.com/datasets/shubhamoujlayan/all-the-unicorns-in-the-world/data>.

The D3 zoomable sunburst inspiration code comes from: <https://observablehq.com/@d3/zoomable-sunburst>

## Rationale for Design Decisions

Our project aimed to visualize the distribution of unicorn companies across different countries and sectors globally. We chose a zoomable sunburst diagram over multiple pie charts to effectively represent hierarchical data within a single interactive interface. This approach allowed us to explore different levels of the hierarchy seamlessly. 

**Visual Encodings:**
- **Rainbow Color Scheme:** We selected this to clearly differentiate between nodes, ensuring visual clarity and appeal.
- **Opacity in Final Layer:** To indicate the absence of further levels to explore, we applied an opacity effect in the last layer.
- **Roboto Font:** This font was chosen for its modern appearance and readability, providing a consistent look across the visualization.

**Interaction Techniques:**
- **Click to Zoom:** This interaction allows users to dynamically explore different levels, facilitating intuitive navigation.
- **Smooth Transitions:** As users zoom in and out, the arcs and labels smoothly update their positions and visibility, enhancing the overall user experience.

Initially, we intended to create three layers: countries, industries, and companies. However, we added a continents layer to address the excessive number of clickable elements in the country layer, particularly for large areas like the US. This addition reduced the complexity of the country layer and enhanced the user’s ability to explore the data in more ways. We considered other visualization techniques but found that the zoomable sunburst diagram best met our needs for displaying hierarchical data in an engaging and efficient manner.

## Overview of Development Process

Our development process began with a discussion about our plans and objectives for the project. We decided to use this project as part of our final assignment. With this in mind:

- **Charlie** conducted Exploratory Data Analysis (EDA) on the raw dataset, uncovering interesting features within the data.
- **Mert** focused on exploring strategies to deploy the website and identified the necessary steps to achieve our end goal.

After these initial tasks, we reconvened to decide on the most appropriate interactive graph for our dataset and how it would fit into our larger final project. After much deliberation, we settled on an interactive sunburst plot. 

- **Charlie** transformed the data for the plot and created the sunburst visualization.
- **Mert** structured the layout to create a responsive, visually appealing interface with clear text design.

The entire development process took approximately 20 hours. The most time-consuming aspects were the deployment strategies and debugging the interaction code. Finding effective deployment strategies took roughly 5 hours, and debugging the interaction code took roughly 10 hours.

This collaborative approach allowed us to efficiently divide the workload and leverage each team member's strengths, resulting in a cohesive and functional final product.
