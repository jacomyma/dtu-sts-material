The Python notebooks come in two versions because you have two options.

1. Run notebooks online with Google Colab. Open the [```notebook/colab/```](https://github.com/jacomyma/dtu-sts-material/tree/main/notebooks/colab) folder, click on a notebook in the list, then click on "Open in Colab" on top. This will create a copy of the notebook in your Google Drive and open it in Colab (see intro above). This will require you to authorize each script to access your Google account so that it can access the online version of the document.
1. Run notebooks locally with Jupyter (or another compatible system like VS Code). We recommend that you download, install, and run [Anaconda Navigator](https://www.anaconda.com/download/success) and from there to run Jupyter. You can then run the notebooks from the GitHub repository in the [```notebook/local/```](https://github.com/jacomyma/dtu-sts-material/tree/main/notebooks/local) folder. Those do not require any Google account, but you have to set up the notebook environment and download the notebooks and the data.

Note: the repository also contains the dataset as a CSV in the data/ folder.

Here is a quick description of what each notebook does and how you should use it:

- **Query examples**: read it carefully to understand how to compose queries in the language of Pandas. Suggestion: make a copy of that notebook and add your own queries in the end, that will be useful for copy-pasting them into other notebooks.
- **Retrieve subcorpus - Filter and export**: assuming you have a query, use it to filter the actor statements matching it (i.e. the "subcorpus"), and export it as a CSV or as a text file. The CSV allows you to analyze the subcorpus into another tool like a spreadsheet. The text file is to make it easier for you to read through the statements, which is very important for qualitative moments of the analysis.
- **Semantic map - Explore (interactive)**: generates a zoomable plot that you can explore interactively. It allows you to read statements by semantic proximity, which is useful to explore different parts of the controversy. It matches the annotated renderings of the atlas.
- **Semantic map - Filter and explore (interactive)**: same as above, but allows you to highlight certain statements with a query. Useful to check if a query gives semantically similar results.
- **Semantic map - Filter and render**: same as above including the ability to query, but produces a high-resolution, non-interactive rendering, which is better suited to copy-paste into documents.
- **Timeline - Filter and render**: renders a timeline of the volume of statements over time, as a bar chart. Requires a query, and produces 4 variations to choose from. Read the pros and cons of each variation to understand which one is the most appropriate in your situation.
- **Visualize by actor - Filter and render**: Generates bar charts of the volume of statements by actor. Requires a query.
- **Visualize by cluster - Filter and render**: Generates bar charts of the volume of statements by cluster. Requires a query.
- **Visualize by issue X - Filter and render**: Generates bar charts of the volume of statements by issue (you have to precise which issue you want to focus on). Requires a query.
- **Visualize by organization (represented by an actor) - Filter and render**: Generates bar charts of the volume of statements by column "represented by" which indicates which organization is represented by the statement's author (if any). Requires a query.
- **Visualize by source name - Filter and render**: Generates bar charts of the volume of statements by source name. Requires a query.
- **Visualize by source type - Filter and render**: Generates bar charts of the volume of statements by source type. Requires a query.

Note: the purpose of the "Visualize by..." notebooks is always to produce query-based measurements of the corpus. Each one may or may not be relevant to you depending on what you will focus on in your policy brief.
