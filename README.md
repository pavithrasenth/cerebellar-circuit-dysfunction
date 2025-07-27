# cerebellar-circuit-dysfunction


--- Computational Modeling of Cerebellar Circuit Dysfunction

This project focuses on simulating cerebellar neural circuits using Spiking Neural Networks (SNNs) to study motor deficits observed in cerebellar ataxia. It integrates both healthy and lesioned Purkinje neuron models, real gait signal inputs, and circuit-level simulations using Brian2 and NEURON simulators — all implemented in Google Colab.


--- Tools and Technologies Used

Python – Core programming language

Brian2 – For spiking neural network simulations

NEURON – For biologically detailed Hodgkin-Huxley Purkinje cell modeling

Google Colab – Code execution environment

Pandas, NumPy, Matplotlib – For data handling and visualization



--- Dataset

Source: Real-world gait signal data was used to mimic cerebellar dysfunction.

Dataset: Ataxia Gait Features - Mendeley Data

The dataset includes stride features such as LeftStrideSpeed, which was normalized and fed into our simulation as input signals.



--- What This Project Does

✅ Healthy vs Lesioned Neuron Simulation:

Simulated healthy Purkinje neurons using Brian2 and NEURON.

Simulated lesioned Purkinje neurons by disrupting membrane dynamics and inputs.


✅ Real Gait Signal as Input:

Used real ataxia gait features (e.g., stride speed) to simulate how motor dysfunction affects neural activity.


✅ Circuit-Level Modeling -

Built a small cerebellar circuit including:

Purkinje cells

Granule cells

Interneurons


Modeled their connectivity and observed spiking patterns across the network.


✅ Simulated Lesions

Modeled neurodegeneration by turning off synaptic inputs or adjusting membrane parameters.

Compared voltage responses between healthy and lesioned models.



--- Output Highlights

Voltage graphs showing neuron responses (healthy vs impaired).

Firing patterns of multiple neurons in a circuit.

Comparison of motor signal propagation under healthy vs damaged conditions.



--- Project Structure

healthy_brian2_model.ipynb – Simulation of healthy Purkinje neurons using Brian2

neuron_hh_model.ipynb – NEURON-based Hodgkin-Huxley model

circuit_model.ipynb – Full cerebellar microcircuit with multiple neuron types

lesion_simulation.ipynb – Simulating damage to study motor impairment

ataxia_features_1.csv – Dataset used for driving motor input

