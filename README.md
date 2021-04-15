# ANDA_HMM_Course

# Metastable activity: Experimental evidence, theoretical models and applications

# Learning goals
The goal of this project is to acquire familiarity with the concepts of metastable neural dynamics, how to perform statistical analyses to discover it from data, and how to model it with attractor networks. Participants will learn to analyze single-trial population activity using hidden Markov models and perform network simulations.
 
Background. Metastable brain dynamics are characterized by abrupt, jump-like modulations so that the neural activity in single trials appears to unfold as a sequence of discrete, quasi-stationary ‘states’. Evidence that cortical neural activity unfolds as a sequence of metastable states is accumulating at a fast pace. Metastable activity occurs both in response to an external stimulus and during ongoing, self-initiated activity. Metastable states are increasingly found to support internal representations that are not locked to external triggers, including states of deliberations, attention and expectation. Decoding stimuli or decisions via metastable states can be carried out trial-by-trial, shifting our perspective from traditional concepts based on trial-averaging to models based on dynamic ensemble representations. Recent theoretical work has started to characterize the mechanistic origin and potential roles of metastable representations.
                                	
Part I - Theory
We will discuss recent experimental and theoretical findings on metastable activity; its potential role for representing internal states as well as relevant task variables; and how it may arise in biologically realistic models. We will introduce the basic concepts in the theory of attractor networks of spiking neurons as a model of metastable activity.

Part II - Statistical methods
We will introduce hidden Markov models (HMM) as a tool to analyze metatable activity. Participants will generate and fit synthetic data from an HMM. They will then fit spike trains from publicly available spike train data and from network simulations and analyze and interpret the results.

Part III - Simulations
Participants will learn how to simulate recurrent networks of spiking neurons with clustered connectivity. They will discover how these networks respond to stimuli and other external perturbations and how their metastable dynamics are modulated in different conditions.

# Exercises

Part I - Hidden Markov Model basics  (HMM)

The ssm package
Generate data from an HMM with K states (use both gaussian and Poisson emissions)
Model selection using BIC and cross-validation
Plot results (posterior probabilities, state usage)

Part II - Spiking network with metastable attractors

Spiking network of excitatory and inhibitory neurons arranged in clusters
Simulate and plot the network activity, vary the parameters to test the range of metastability
Control the cluster switching times by changing the variance of the external current 

Part III
Sample N=100 random neurons from a network simulation and fit the Poisson-HMM to their spiking activity
Model selection to choose the number of hidden states K
Plot results

Question: how does the average state duration depend on the variance of the external current?

# Slides for the course lectures [pdf](https://drive.google.com/file/d/11dZvbALlC0QOUktxH_sS3TDXV7jWt-Hp/view?usp=sharing "Slides")

# References
1.	La Camera, G., Fontanini, A. & Mazzucato, L. Cortical computations via metastable activity. Curr. Opin. Neurobiol. 58, 37–45 (2019).
2.	Litwin-Kumar, A. & Doiron, B. Slow dynamics and high variability in balanced cortical networks with clustered connections. Nat. Neurosci. 15, 1498–1505 (2012).
3.	Mazzucato, L., Fontanini, A. & La Camera, G. Dynamics of multistable states during ongoing and evoked cortical activity. J. Neurosci. 35, 8214–8231 (2015).
4.	Mazzucato, L., La Camera, G. & Fontanini, A. Expectation-induced modulation of metastable activity underlies faster coding of sensory stimuli. Nat. Neurosci. (2019).
5.    Wyrick, D.G. and Mazzucato, L., 2020. State-dependent control of cortical processing speed via gain modulation. bioRxiv.
6.    Recanatesi, S., Pereira, U., Murakami, M., Mainen, Z. and Mazzucato, L., 2020. Metastable attractors explain the variable timing of stable behavioral action sequences. arXiv preprint arXiv:2001.09600.

