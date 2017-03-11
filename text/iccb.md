Modelling Spatiotemporal Extremes in Conservation Biology
=========================================================

Understanding biological responses to environmental perturbations in time and space is critical for conservation planning. With projected trends in climate forcing, for example, conservation biology will have to focus not just on mean changes, but also on variability and extremes. In ecological systems, extremes can happen in time, such as population crashes, or in space, such as rapid range contractions. Here, we introduce a statistical model that extends current methods for joint inference about temporal and spatial dynamics (spatiotemporal modelling) to allow for and detect extremes that occur simultaneously in time and space. Specifically, our model is a Bayesian predictive-process model that uses a multivariate-t distribution to describe spatial random effects. The model is easily implemented with our flexible new R package, which uses an interface that should be familiar to anyone who has worked with regression in R. We illustrate applications of our model and R package with two real-world datasets. First, we predict seasonal chlorophyll-a anomalies off the coast of Oregon, US, which may be a useful indicator of harmful algal blooms. Second, we predict tree mortality from mountain pine beetle (Dendroctonus ponderosae) outbreaks in the US Pacific Northwest over the last 16 years. In both cases, we show that our model provides more accurate and certain predictions of these ecological processes compared to traditional spatiotemporal models that do not allow for extremes. Jointly modelling ecological processes in time and space represents an important step forward to creating realistic models of anomalies, and allows us to improve predictions that feed into conservation decisions. Distributing this tool as an R package should make these models accessible to a wide range of conservation biologists and scientists in other disciplines interested in predicting extreme events.