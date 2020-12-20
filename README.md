## Using banded alignment to fight 🦠 (and save time)
The COVID-19 pandemic has affected the world in so many different, unfathomable ways, and has been dominating the global news ever since its onset. Naturally, there have been a lot of comparisons between the current coronavirus and some of the other coronaviruses the world has seen before. Our key motivation for this project was the potential to explore how similar the coronaviruses actually are through the knowledge we’ve gained from this class. Hence, we decided to conduct this exploration and compare sequences of some of the proteins they have in common using pairwise sequence alignment - specifically, optimal global alignment based on the Needleman-Wunsch algorithm. Since the viruses stem from the same family, we expected the sequences to be fairly similar to each other. Hence, we chose to use banded alignment as an optimization of the algorithm to improve the running time of the algorithm. Our project discusses the optimal global sequence alignment of the protein sequences in two parts. The first part compares the protein sequences by applying the optimized global alignment algorithm to their genomic sequences. We further explore how changes in bandwidth affect the runtime of said algorithm and consequently, its efficiency in order to determine the significance of using the banded alignment optimization. We extended the project to have a second part, where we constructed a web tool that allows the user to enter a specific pair of nucleotide sequences, a bandwidth, and a scoring function of their choice, and then outputs a visualization of the optimal global alignment score along with its alignment matrix that depicts how banded alignment works on the sequences. The hope is that both parts of this project combined will show why banded alignment improves the running time of global alignment, especially with really large sequences.

## Running the Visualization
In the Coronaviruses-analysis directory, run the following command: "python -m http.server". The visualization should be running on port 8000, and can be seen by going to "http://localhost:8000/Visualization/".

## Running the Analysis
All of the analysis is in a Jupyter notebook called "Analysis.ipynb". If you're unable to open the notebook on github, copy and paste the link onto [this](https://nbviewer.jupyter.org/) website.
