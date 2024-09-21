# Intelligent Data Visualization Tool

This tool leverages machine learning to automate the process of data visualization. By uploading a CSV file and providing a natural language query, the tool predicts the most appropriate x-axis, y-axis, and graph type for the given data.

It uses **Llama**, a language model, to determine the best columns for the x and y axes. A custom-built machine learning model predicts the type of graph (e.g., bar chart, line chart, scatter plot) that best represents the data. Due to limited data and resources, the sentence generated by the model is sent to Llama for spelling and grammar correction before selecting the graph type from the refined sentence. This process ensures accurate and polished visualizations, streamlining data analysis and interpretation.

![Alt text](https://drive.google.com/file/d/1kI62cw413FS719LA4dtwquy1NiioihtD/view?usp=sharing)


[Link to code of the model](https://github.com/sauravreji/graph-model)


