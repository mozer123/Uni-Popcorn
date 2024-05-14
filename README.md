# Exploring Unicorn Companies with a Zoomable Sunburst

## Intro

This project is for DSC106 <https://dsc106.com/> which is a project-centered course that covers fundamental principles and techniques in data visualization. Specifically, Project 3: Interactive Visualization.

Here is the dataset used: <https://www.kaggle.com/datasets/shubhamoujlayan/all-the-unicorns-in-the-world/data>

About using zoomable sunbursts with d3: <https://observablehq.com/@d3/zoomable-sunburst>

## Rationale

Our project started with us wondering about the distribution of unicorn companies according to countries and sectors around the world. Using a zoomable sunburst diagram over multiple pie charts allowed for a more efficient and cohesive visualization of hierarchical data, enabling us to explore different levels of the hierarchy within a single, interactive interface. Although our initial goal was to create three layers, namely countries, industries and companies, we later added an extra continents category because there were too many clickable elements in the country layer and some of them, such as the US, occupied a relatively large area. In this way, we both lessened the burden on one layer and provided users with the opportunity to explore in more ways.

The rainbow color scheme was selected to clearly differentiate between nodes for visual clarity and appeal. Opacity feature was used at the last layer to indicate that there is no further levels to explore. The consistent use of Roboto font ensured modern and readable text. Interaction techniques like click to zoom were implemented to allow users to explore different levels dynamically which provided an intuitive navigation experience. Additionally, as users zoom in and out, the arcs and labels transition smoothly by updating their positions and visibility.

## Development

We started off discussing our plans and objectives for the project, which we both agreed to use it as a part of the final project. With that in mind, Mert explored strategies to deploy the website and figured out the steps we would need to take towards the end goal. Meanwhile, Charlie performed some Exploratory Data Analysis on the raw dataset, finding some interesting features about the data. Then, we gathered again to discuss what kind of interactive graph would be the most appropriate for the dataset, and how would it fit into the scope of our bigger final project. After much deliberation, we settled on the interactive sunburst plot, and Charlie went off to transform the data for the plot and creating the plot itself, while Mert structured the layout to create a responsive, visually appealing interface with clear text design. The whole process took around 20 hours, with finding deployment strategies and debugging the interaction’s code taking the most time of roughly 15 hours.
