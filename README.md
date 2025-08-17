Processkit is a lightweight Python toolkit for working with stochastic processes. Its goal is to make it easy to simulate, analyze, and compare noise and random dynamics using a consistent set of tools.

Why is this useful? Today, common tasks like simulating an Ornstein–Uhlenbeck process, estimating its power spectrum, and checking for changepoints require mixing several libraries and a lot of ad-hoc glue code. That makes workflows hard to reproduce, extend, or teach. Processkit fixes this by providing:
	•	Clear abstractions (NoiseProcess, SDE, SpectralEstimator, Channel)
	•	A common TimeSeries container (values, units, sampling rate)
	•	End-to-end workflows: simulate, estimate and diagnose in a few lines of code

The result is a compact, domain-neutral toolkit that works for physics, engineering, biology, and beyond—while also making it easier to build specialized extensions like dedicated noise toolkits.
