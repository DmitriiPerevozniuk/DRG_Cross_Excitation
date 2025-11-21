This is a repository for complete DRG model from 'What is happening in Dorsal Root Ganglia? A comuptational analysis of cross-excitation phenomenon' article.  
For stability and performance reasons, the simulation is ran sequentially: you shall first run the basic_model script, save its results. Then, the labyrinth is created and diffusion is performed inside created lbyrinth.
After that, the 'affected' neuron is simulated with fourth script - applying the effects of diffusion and simulating how the system will balance itself.
Note that this approach is actually the same as computing everything simulatenously: results of one neuron balancing itslef on neighbours are miniscule and lay in range of machine precision for this simulation.  
If you have any problems - you are free to contact me anytime at dmitrii.perevozniuk@skoltech.ru  
Special thanks to Mandage et al., as this work is primarly based on their work 'A biophysically detailed computational model of urinary bladder small DRG neuron soma' ( 10.1371/journal.pcbi.1006293 ), with extentions from other articles.
