🧠 Beginner Python Exercises for Neuroscience Data
Load a CSV file containing neuron spike counts and display the first 5 rows using pandas.

Use NumPy to create a synthetic array of firing rates for 10 neurons over 5 time points.

Plot a line chart of firing rate over time for one neuron using matplotlib.

Create a bar chart comparing the total spike count of 5 neurons.

Calculate the mean and standard deviation of a neuron’s firing rate using numpy.

Simulate a neuron’s response to a stimulus as a sine wave using NumPy and plot it.

Use pandas to filter rows where spike count is above a threshold.

Group data by stimulus condition and compute average firing rate using pandas.

Generate a heatmap of neuron activity (neurons × time) using matplotlib’s imshow.

Label axes and add a title and legend to a plot of three neurons’ activity over time.

Detect values above threshold in a signal and mark them as spikes (binary 0/1).

Save your analysis results (e.g., summary stats) to a new CSV file using pandas.

Use seaborn to plot a violin plot showing distribution of firing rates across neurons.

Load a JSON file containing metadata for a neuron recording session and print summary info.

Plot spike times of neurons using raster plots (plt.eventplot).


# 🧪 Progressive Exercises: From Elementary to Advanced

## Beginner 🟢

1. Change the input current in the LIF model and observe its effect.
2. Modify the time constant τ and explain how it changes the membrane potential curve.
3. Plot multiple neurons' membrane potentials using different parameters.
4. Simulate a neuron that never spikes. Why doesn’t it spike?
5. Adjust spike threshold and observe firing frequency change.
6. Extract spike times and count spikes per neuron.
7. Simulate a constant voltage and compare to LIF output.
8. Explain the difference between continuous and event-driven models.

## Intermediate 🟡

1. Generate a raster plot of multiple LIF neurons spiking over time.
2. Use `scipy.signal.find_peaks` to detect calcium spikes from ΔF/F data.
3. Compute the mean and standard deviation of calcium activity across trials.
4. Add simulated synaptic input (weighted connections) between neurons.
5. Cluster neuron firing rates into groups and visualize using PCA.
6. Align calcium traces to stimulus events and compute average response.
7. Implement a simple Hebbian learning rule using numpy.
8. Smooth calcium trace with a Gaussian filter and compare results.

## Advanced 🔴

1. Simulate a recurrent network of 5 neurons using I&F dynamics.
2. Add refractory period to your neuron model and verify its effect.
3. Apply UMAP to reduce high-dimensional calcium data and visualize clusters.
4. Model different neuron types (excitatory vs inhibitory) and their effect on network activity.
5. Estimate correlation matrix between neuron pairs and visualize as a heatmap.
6. Classify stimulus conditions using spike count and a machine learning model.
7. Use spectral analysis (Fourier Transform) to detect rhythmic firing patterns.
8. Compare calcium imaging ΔF/F with deconvolved spikes side-by-side.
9. Fit a tuning curve for simulated visual neurons responding to orientation.
