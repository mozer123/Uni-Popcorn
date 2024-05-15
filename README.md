# Exploring Unicorn Companies with a Zoomable Sunburst

## Intro

Welcome to Charlie and Mert's Project 3: Interactive Visualization repo for [DSC106](https://dsc106.com/), a project-centered course that covers fundamental principles and techniques in data visualization! 

The dataset we used comes from: <https://www.kaggle.com/datasets/shubhamoujlayan/all-the-unicorns-in-the-world/data>.

The D3 zoomable sunburst inspiration code comes from: <https://observablehq.com/@d3/zoomable-sunburst>

## Rationale

Here is a revised version of your writing for improved clarity and better alignment with the question:

---

### Rationale for Design Decisions

Our project aimed to visualize the distribution of unicorn companies across different countries and sectors globally. We chose a zoomable sunburst diagram over multiple pie charts to effectively represent hierarchical data within a single interactive interface. This approach allowed us to explore different levels of the hierarchy seamlessly. Initially, we intended to create three layers: countries, industries, and companies. However, we added a continents layer to address the excessive number of clickable elements in the country layer, particularly for large areas like the US. This addition reduced the complexity of the country layer and enhanced the user’s ability to explore the data in more ways.

**Visual Encodings:**
- **Rainbow Color Scheme:** We selected this to clearly differentiate between nodes, ensuring visual clarity and appeal.
- **Opacity in Final Layer:** To indicate the absence of further levels to explore, we applied an opacity effect in the last layer.
- **Roboto Font:** This font was chosen for its modern appearance and readability, providing a consistent look across the visualization.

**Interaction Techniques:**
- **Click to Zoom:** This interaction allows users to dynamically explore different levels, facilitating intuitive navigation.
- **Smooth Transitions:** As users zoom in and out, the arcs and labels smoothly update their positions and visibility, enhancing the overall user experience.

We considered other visualization techniques but found that the zoomable sunburst diagram best met our needs for displaying hierarchical data in an engaging and efficient manner.

---

This revision aims to provide a clear and concise explanation of your design choices and how they address the project's requirements.

## Development

We started off discussing our plans and objectives for the project, which we both agreed to use it as a part of the final project. With that in mind, Mert explored strategies to deploy the website and figured out the steps we would need to take towards the end goal. Meanwhile, Charlie performed some Exploratory Data Analysis on the raw dataset, finding some interesting features about the data. Then, we gathered again to discuss what kind of interactive graph would be the most appropriate for the dataset, and how would it fit into the scope of our bigger final project. After much deliberation, we settled on the interactive sunburst plot, and Charlie went off to transform the data for the plot and creating the plot itself, while Mert structured the layout to create a responsive, visually appealing interface with clear text design. The whole process took around 20 hours, with finding deployment strategies and debugging the interaction’s code taking the most time of roughly 15 hours.
