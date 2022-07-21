# fitness-assay-simulations
Jupyter notebooks for exploring how different experimental parameters influence fitness estimation from bulk fitness assays. There are three main notebooks:

- Simulating DFE with Poisson Noise.ipynb

Here, I estimate how much variation in the distribution of fitness effects (inferred from bulk assays) is expected purely from Poisson noise.

- Error in Fitness Estimate based on coverage and "true" fitness.ipynb

Here, I explore upper and lower bounds in errors in fitness estimates for a range of true fitness effects

- More Insertions vs More Depth per Insertion?.ipynb

Is it better to have fewer insertions at higher depth, or more insertions at lower depth for accurate fitness estimates?

You can tweak various population genetic parameters, and figure out how much sequencing depth, bottleneck size, etc. is necessary to get a desired precision of fitness estimates for your experiments


### Disclaimer: the predicted errors in fitness (for various experimental parameters) should not be taken as the absolute truth. My goal with these notebooks was to play around and build intuition for which how experimental parameters impact fitness measurements, and which ones are worth modifying/optimizing.
