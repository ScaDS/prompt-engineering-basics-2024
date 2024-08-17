# Prompt Engineering Basics

This repository contains a collection of Jupyter notebooks explaining prompt engineering

https://scads.github.io/prompt-engineering-basics-2024

It is maintained using [Jupyter lab](https://jupyterlab.readthedocs.io/en/stable/) and build using [Jupyter book](https://jupyterbook.org/intro.html).

To edit this book, install depencencies like this:

```
pip install jupyterlab
pip install jupyter-book
pip install jupyterlab-spellchecker

git clone https://github.com/scads/prompt-engineering-basics-2024
cd  prompt-engineering-basics-2024
jupyter lab
```

For modifying the LLM-notebooks, make sure [ipy-llm-kernel](https://github.com/haesleinhuepf/ipy-llm-kernel?tab=readme-ov-file#installation) is properly installed. 

To build the book, you can run this from the same folder:
```
cd docs
jupyterbook build .
```

## Acknowledgements

We acknowledge the financial support by the Federal Ministry of Education and Research of Germany and by Sächsische Staatsministerium für Wissenschaft, Kultur und Tourismus in the programme Center of Excellence for AI-research „Center for Scalable Data Analytics and Artificial Intelligence Dresden/Leipzig“, project identification number: ScaDS.AI
