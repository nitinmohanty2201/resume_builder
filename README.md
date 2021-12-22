# resume_builder

A streamlit based webapp deployed at [here](https://share.streamlit.io/mehulgupta2016154/resume_builder/main)

## Contents

- LinkedIn Badge : [how to create one for your profile?](https://www.linkedin.com/pulse/how-create-linkedin-badge-your-website-amy-wallin/). Integrated using streamlit component
- Stackoverflow Flair : [how to add a stackoverflow flair?](https://meta.stackexchange.com/questions/10497/how-do-i-put-my-stackoverflow-user-flair-on-my-blogger-blog). Integrated using streamlit component
- Career Snapshot: Built using [streamlit_timeline](https://pypi.org/project/streamlit-timeline/)
- Skills & Tools: Used streamlit buttons & columns features
- Education : Plotly(library for visualization) table
- Research Paper detailed brief description : streamlit images, streamlit metrics, streamlit expander & plotly.express grouped barplot
- Achievements : streamlit markdown (great to embed HTML codes)
- Medium profile : Basic web scrapping. Profile preview generated using [pixelpoint's medium widget](https://medium-widget.pixelpoint.io/)
- Daily routine : [Graphviz library](https://pypi.org/project/graphviz/)
- ML models integrated : Vanilla & Cycle GAN built using tensorflow

## Files description
* cyclegan/ : weights for cyclegan model used for image translation
* vanilla_gan/ : weights for vanilla gan used
* images/ : images used for research paper section
* pdf/ : pdfs available for downloading on portfolio
* constant.py : File with all static data used. 
* cycle.py : cycle_gan models 
* vanilla_gan.py: vanilla_gan models
* requirements.txt : requirements file generated using [pipreqs](https://pypi.org/project/pipreqs/)
* graph_builder.py : Daily routine graph using graphviz
* timeline.json : Json file used by streamlit_timeline for career snapshot

