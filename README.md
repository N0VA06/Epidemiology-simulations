# Epidemiology-simulations
SIR MODEL and SEIR MODEL WITH PARTIAL IMMUNITY ALONG WITH AGE DISTRIBUTION (using networkx module)
Imagine a vast network of interconnected nodes, each representing an individual in a population. Some nodes are infected with a contagious disease, while others are susceptible or already recovered. As the disease spreads, the fates of individuals intertwine, influenced by their connections and various biological factors. This is the essence of our network-based approach to simulating disease outbreaks.

Building the Population Network:
Our simulation begins with creating a virtual world inhabited by a specified number of individuals. We use algorithms from network to connect them, forming a web of relationships mimicking real-world social interactions. Each node in this network represents an individual and is assigned an initial health state: susceptible, infected, recovered, or deceased.


Tracking the Disease Spread:
Our model embraces the intricate complexity of biological variations, employing Python's uncertainties module to capture this essence. This robust tool enables us to view parameters such as recovery rates not as static figures, but as flexible ranges of potentiality. It adeptly follows these uncertainties through computations, ensuring that each individual's experience with illness, marked by distinct strengths and vulnerabilities, is intricately woven into the fabric of the model. In the end, this probabilistic approach creates a more nuanced portrayal of disease dynamics, providing the foundation for informed and data-driven decisions in the midst of an unpredictable future.

 

Partial Immunity:
Unlike traditional models that simply categorize individuals as either immune or susceptible, our approach introduces a more nuanced layer of complexity. We recognize that immunity can exist on a spectrum. We introduce a "partially immune" state, where individuals have some resistance to the disease but can still be infected under certain circumstances. This reflects the diverse range of immune responses observed in real-world populations.
 

Accounting for Age Differences:	
Age plays a vital role in figuring out the node's susceptibility, restoration price, and vulnerability to severe results. Our model contains this truth with the aid of dividing the population into age groups (younger, middle-aged, old) and assigning them correct parameters for each component. This permits us to capture the differential impact of the disorder throughout one of kind demographics.



Adaptive transmission rate:
The risk of infection is not static in our simulated world. We introduce a concept called "adaptive transmission rates," where the probability of disease transmission adjusts based on the local environment. If an individual finds themselves surrounded by many infected neighbours, their own transmission rate increases, reflecting the heightened risk of exposure. Conversely, in areas with fewer infected individuals, the transmission rate decreases, representing a lower likelihood of contagion. This dynamic approach adds a layer of realism to the simulation, accounting for the ebb and flow of disease spread in real-world communities.
