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
