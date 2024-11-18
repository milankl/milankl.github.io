---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

A list of projects that I can envisage for Master and/or PhD projects.
This list is not complete but should give prospective students an idea about
possible projects. Do reach out with your own ideas too!

### Differentiable atmospheric modelling: Learning from data between Earth’s and exoplanetary climates

supervised with [Tad Komacek](https://www.physics.ox.ac.uk/our-people/komacek) (Oxford)

Atmospheric general circulation models are the backbone of climate models, being used to understand and predict climate change on Earth.
Founded in physical laws, general circulation models can be generalised to exoplanetary atmospheres. While many atmospheric processes on
Earth are well understood and accurately simulated as evident through the success of weather forecasting, some processes such as cloud
formation and precipitation are less certain. Societally-relevant surface climate and extreme events like heat waves, however, strongly
depend on those. At the same time, observations can constrain such uncertainties, improving climate predictions on Earth. On exoplanets
this will reveal insights about the parameter regimes in which planetary habitability is possible. How to make atmospheric models
automatically learn from observational data? 

This project will build on top of SpeedyWeather, an atmospheric general circulation model written in the Julia programming language.
SpeedyWeather is easy to use and extend, inspired by modern software engineering, covering functionality from data visualisation to
high-performance computing. The candidate will continue to develop its differentiability through the automatic differentiation
framework Enzyme. Differentiating through SpeedyWeather, we can optimise the unknown or less certain parameters determining the
planetary surface climate and resulting habitability in the same way as neural networks are trained towards observations.
And we can add neural networks to SpeedyWeather forming a hybrid physics and data-driven model. 

For exoplanets, observations of gas giants down to hot terrestrial planets are currently used to constrain their atmospheric composition
and thermal structure. Critically, upcoming space missions such as the Large Interferometer for Exoplanets and Habitable Worlds Observatory
will have the ability to measure the thermal emission and reflected light of Earth-like exoplanets, enabling a direct test of our Earth-based
understanding of planetary climate. This SpeedyWeather/Enzyme framework will enable novel rapid inverse characterization of exoplanetary
atmospheres with a 3D model that can be applied to exoplanet observations.

Part 2 of this project will scale up the same method to the Earth’s atmosphere, increasing data and complexity. For earth, the current surface
climate is observable, but a model may still mispredict frequencies and intensities of extreme events like heat waves under global warming.
But with automatic differentiation we can train the model to correct for the missing physics of heat waves towards a more reliable generalisation
into future climates, assessing the Earth’s habitability under global warming.

This PhD project will bridge several fields: The applicant is expected to have a strong background on the spectrum between physics,
mathematics, and computer science, with enthusiasm for computer science and machine learning. Prior experience with Julia is not
required, but experience with another programming language like Python, Matlab, C(++), or Fortran is preferred.

Posted here [https://www.physics.ox.ac.uk/study/postgraduates/dphil-atmospheric-oceanic-and-planetary-physics/climate-physics](https://www.physics.ox.ac.uk/study/postgraduates/dphil-atmospheric-oceanic-and-planetary-physics/climate-physics)

### Project 2

### Project 3
