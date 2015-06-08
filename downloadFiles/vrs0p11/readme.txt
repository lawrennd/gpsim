GPSIM software
Version 0.11		Saturday 06 Jan 2007 at 00:06
Copyright (c) 2007 Neil D. Lawrence

Version 0.11
------------

Release with scripts to recreate results in NIPS paper and at NIPS workshop talk. Updated release with correction to Hessian for non-linear response model and modular code for the MAP approximation. Removed update of kernel parameters 'Hessian correction'.

Version 0.1
-----------

A quick and dirty release for the results to be submitted to the GPIP workshop.

MATLAB Files
------------

Matlab files associated with the toolbox are:

expvarMeanCreate.m: Creates an the mean function for the EXP kernel.
gpsimExtractParam.m: Extract the parameters of a GPSIM model.
gpsimMapExpandParam.m: Expand the given parameters into a GPSIMMAP structure.
gpsimMapUpdatePosteriorCovariance.m: update the posterior covariance of f.
gpsimMapFunctionalLogLikelihood.m: Compute the log likelihood of a GPSIMMAP model.
expvarMeanExtractParam.m: Extract weights and biases from an EXPVARMEAN mapping.
gpsimMapCreate.m: Create a GPSIMMAP model.
gpsimCreate.m: Create a GPSIM model.
expvarMeanOut.m: Output of an EXPVARMEAN model.
gpsimMapUpdateKernels.m: Updates the kernel representations in the GPSIMMAP structure.
gpsimLogLikeGradients.m: Compute the gradients of the log likelihood of a GPSIM model.
gpsimMapBarencoResults.m: Plot the results from the MAP script.
gpsimMapLogLikelihood.m: Compute the log likelihood of a GPSIMMAP model.
demBarencoVariational1.m: Optimise model using variational approximation with RBF kernel and exponential response.
gpsimDisplay.m: Display a Gaussian process model.
demToyProblem1.m: Generate an artifical data set and solve with GPSIM.
demBarenco1.m: Run experiments on data from Barenco et al in Genome Biology.
gpsimMapFunctionalExtractParam.m: Extract the function values from a GPSIMMAP model.
gpsimUpdateKernels.m: Updates the kernel representations in the GPSIM structure.
gpsimLogLikelihood.m: Compute the log likelihood of a GPSIM model.
demBarencoMap1.m: Optimise model using MAP approximation with RBF kernel and linear response.
demBarencoMap2.m: Optimise model using MAP approximation with MLP kernel and linear response.
demBarencoMap3.m: Optimise model using MAP approximation with RBF kernel and exp response.
demBarencoMap4.m: Optimise model using MAP approximation with MLP kernel and exp response.
demBarencoMap5.m: Optimise model using MAP approximation with RBF kernel and negLogLogit response.
demBarencoMap6.m: Optimise model using MAP approximation with MLP kernel and negLogLogit response.
demBarencoMap7.m: Optimise model using MAP approximation with RBF kernel and sigmoid response.
demBarencoMap8.m: Optimise model using MAP approximation with MLP kernel and negLogLogit response.
cgpsimLogLikelihood.m: Compound GPSIM model's log likelihood.
gpsimMapOptions.m: Creates a set of default options for a GPSIMMAP model.
gpsimMapFunctionalLogLikeGradients.m: Compute the functional gradient for GPSIMMAP.
expvarMeanExpandParam.m: Update expvarMean mapping with new vector of parameters.
gpsimMapFunctionalUpdateW.m: Update the data component of the Hessian.
gpsimMapUpdateF.m: Update posterior mean of f.
gpsimMapUpdateG.m: Update the nonlinear transformation of f.
cgpsimLogLikeGradients.m: Compound GPSIM model's gradients.
gpsimArtificialProtein.m: Generate an artifical protein sequence.
gpsimGradient.m: Gradient wrapper for a GPSIM model.
gpsimMapFunctionalLogLikeHessian.m: Compute the functional Hessian for GPSIMMAP.
gpsimMapExtractParam.m: Extract the parameters of a GPSIMMAP model.
gpsimMapFunctionalExpandParam.m: Expand the given function values into a GPSIMMAP structure.
cgpsimExpandParam.m: Expand params into model structure.
gpsimOptimise.m: Optimise the GPSIM model.
gpsimLoadBarencoData.m: Load in Martino Barenco's data as processed by mmgMOS.
cgpsimExtractParam.m: Extract parameters from compound GPSIM model.
gpsimArtificialGenes.m: Give artifical genes from given parameters.
gpsimExpandParam.m: Expand the given parameters into a GPSIM structure.
gpsimMapTest.m: Tests the gradients of the GPSIMMAP model.
gpsimMapUpdateYpred.m: Update the stored numerical prediction for y.
gpsimMapLogLikeGradients.m: Compute the gradients of the log likelihood of a GPSIMMAP model.
gpsimObjective.m: Wrapper function for GPSIM objective.
gpsimTest.m: Test the single input motif code.
gpsimOptions.m: Creates a set of default options for a GPSIM model.
