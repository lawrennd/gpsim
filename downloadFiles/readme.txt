GPSIM software
Version 0.1211		Tuesday 19 May 2009 at 11:09

Version 0.1211
--------------

Minor bug fix in demBarenco1.m

Version 0.121
-------------

Minor fixes of the code for dealing with white noise handling in multiKern.

Version 0.12
------------

Release with first draft of journal paper.

Version 0.111
-------------

Mistakenly the technical noise was not being added in the kernel computation, change to gpsimUpdateKernels.m.

Version 0.11
------------

Release with scripts to recreate results in NIPS paper and at NIPS workshop talk. Updated release with correction to Hessian for non-linear response model and modular code for the MAP approximation. Removed update of kernel parameters 'Hessian correction'.

Version 0.1
-----------

A quick and dirty release for the results to be submitted to the GPIP workshop.


MATLAB Files
------------

Matlab files associated with the toolbox are:

gpsimXGradient.m: ...
distfit.m: Fit a distribution to given parameter percentiles
gpsimLoadBarencoTestData.m: Load in Martino Barenco's test data as processed by mmgMOS.
demBarencoVariational1.m: Optimise model using variational approximation with RBF kernel and exponential response.
gpsimMapEcoliResults.m: Plot the results from the MAP script.
gpsimLoadBarencoPUMAData.m: Load in Martino Barenco's data as re-processed by mmgMOS.
demBarencoRank.m: Do ranking experiments on data from Barenco et al in Genome Biology.
cgpsimExpandParam.m: Expand params into model structure.
gpsimToolboxes.m: Toolboxes for the GPSIM software.
gpsimTest.m: Test the gradients of the GPSIM model.
gpsimMapUpdateYpred.m: Update the stored numerical prediction for y.
gpdisimExtractParam.m: Extract the parameters of a GPDISIM model.
gpsimMapFunctionalLogLikelihood.m: Compute the log likelihood of a GPSIMMAP model.
gpdisimLogLikelihood.m: Compute the log likelihood of a GPDISIM model.
gpsimModelFunctions.m: Update the nonlinear transformation of f.
gpsimMapUpdatePosteriorCovariance.m: update the posterior covariance of f.
gpsimArtificialProtein.m: Generate an artifical protein sequence.
demEcoliMap1.m: Optimise model using MAP approximation with MLP kernel and multiple repression response, using SCG optimisation and Ecoli data set.
gpsimAddCandidate.m: Add candidate genes to a GPSIM model.
demBarencoMap1.m: Optimise model using MAP approximation with MLP kernel and MM activation response, using SCG optimisation and new PUMA processed data.
gpsimCandidateLogLikeGradients.m: Compute the gradients for the parameters of candidate genes.
expvarMeanOut.m: Output of an EXPVARMEAN model.
cgpdisimExpandParam.m: Expand params into model structure.
gpsimMapWGradient.m: Compute the gradients of W with respect to the parameters of the k-th gene.
demToyProblem3.m: Generate an artifical data set and solve with GPSIM.
gpdisimLogLikeGradients.m: Compute the gradients of the log likelihood of a GPDISIM model.
gpsimMapGradients.m: Compute the gradients of the log likelihood of a GPSIMMAP model.
gpsimMapUpdateG.m: Update the nonlinear transformation of f.
gpsimMapObjective.m: Compute the objective function  of the GPSIMMAP model.
gpsimSampleTest.m: Test the single input motif code.
gpsimMapUpdateYpredVar.m: Update the variance for y.
gpsimMapFunctionalWGradient.m: computes the implicit part of the gradient
gpsimCandidateLogLikelihood.m: Compute the log likelihood of a gene.
gpsimSampleHMC.m: Do HMC sampling for the GPSIM model.
gpsimMapUpdateF.m: Update posterior mean of f.
cgpsimLogLikeGradients.m: Compound GPSIM model's gradients.
demBarencoMap3.m: Optimise model using MAP approximation with MLP kernel and linear response, using SCG optimisation and new PUMA processed data with noise variance estimation.
gpsimLogLikeGradients.m: Compute the gradients of the log likelihood of a GPSIM model.
gpsimMapUpdateKernels.m: Updates the kernel representations in the GPSIMMAP structure.
gpdisimOptimise.m: Optimise the GPSIM model.
drosPlotExpPcts.m: Plot expression values
gpsimMapTest.m: Tests the gradients of the GPSIMMAP model.
gpsimCandidateCovGrads.m: Sparse objective function gradients wrt Covariance function.
gpsimDisplay.m: Display a Gaussian process model.
gpsimMapExtractParam.m: Extract the parameters of a GPSIMMAP model.
gpsimMapFunctionalExtractParam.m: Extract the function values from a GPSIMMAP model.
gpsimMapFunctionalUpdateW.m: Update the data component of the Hessian.
gpsimCandidateOptimise.m: Optimise the GPSIM model for candidate genes.
gpsimLoadBarencoData.m: Load in Martino Barenco's data as processed by mmgMOS.
gpsimArtificialGenes.m: Give artifical genes from given parameters.
gpsimCandidateExpandParam.m: Expand the given parameters for a candidate gene.
demBarenco1.m: Run experiments on data from Barenco et al in Genome Biology.
demGpdisimMef2.m: Run experiments on Mef2 data. The raw data is pre-processed by the PUMA package.
demBarencoMap2.m: Optimise model using MAP approximation with MLP kernel and exp response, using SCG optimisation and new PUMA processed data.
expvarMeanCreate.m: Creates an the mean function for the EXP kernel.
gpsimMapLogLikelihood.m: Compute the log likelihood of a GPSIMMAP model.
cgpsimLogLikelihood.m: Compound GPSIM model's log likelihood.
cgpdisimLogLikelihood.m: Compound GPDISIM model's log likelihood.
gpsimMapLogLikeGradients.m: Compute the gradients of the log likelihood of a GPSIMMAP model.
demBarenco2.m: Run experiments on data from Barenco et al in Genome Biology.
gpsimMapMarginalLikeliGradient.m: Compute the gradients of the log marginal likelihood of a GPSIMMAP model with respect to the model parameters.
cgpsimExtractParam.m: Extract parameters from compound GPSIM model.
gpsimMapGradFuncWrapper.m: wraps the log-likelihood function and the gradient function 
cgpdisimLogLikeGradients.m: Compound GPDISIM model's gradients.
demToyProblem1.m: Generate an artifical data set and solve with GPSIM.
gpsimCreate.m: Create a GPSIM model.
gpsimOptimise.m: Optimise the GPSIM model.
gpsimGradient.m: Gradient wrapper for a GPSIM model.
expvarMeanExpandParam.m: Update expvarMean mapping with new vector of parameters.
gpsimMapInitParam.m: Creates a set of options for a GPSIMMAP model as the initial parameters.
expvarMeanExtractParam.m: Extract weights and biases from an EXPVARMEAN mapping.
demToyProblem2.m: Display results from toy problem point at a time.
gpdisimGradient.m: Gradient wrapper for a GPDISIM model.
gpdisimExpandParam.m: Expand the given parameters into a GPDISIM structure.
demToyProblem5.m: Generate an artifical data set and solve with GPSIM.
drosFindTargets.m: returns a sorted list of targets
drosGetGeneinds.m: returns indices of given genes in the given data
gpsimMapFunctionalLogLikeGradients.m: Compute the functional gradient for GPSIMMAP.
gpsimMapBarencoResults.m: Plot the results from the MAP script.
gpsimMapFunctionalLogLikeHessian.m: Compute the functional Hessian for GPSIMMAP.
gpdisimCreate.m: Create a GPDISIM model.
gpsimCandidateObjective.m: Wrapper function for GPSIM candidate gene objective.
gpsimLoadEcoliFullData.m: Load in E. coli full data for the repression case.
gpsimMapCreate.m: Create a GPSIMMAP model.
gpsimUpdateKernels.m: Updates the kernel representations in the GPSIM structure.
gpsimObjective.m: Wrapper function for GPSIM objective.
gpsimMapLikeGradientImplicit.m: computes the implicit part of the gradient
gpsimLoadBarencoMASData.m: Load in Martino Barenco's data as processed by MAS5.
cgpdisimExtractParam.m: Extract parameters from compound GPDISIM model.
gpsimExpandParam.m: Expand the given parameters into a GPSIM structure.
gpsimExtractParam.m: Extract the parameters of a GPSIM model.
gpdisimGetDrosData.m: Get Drosophila data as processed by mmgMOS.
gpsimCandidateUpdateKernels.m: Updates the kernel representations in the GPSIM candidate structure.
gpsimOptions.m: Creates a set of default options for a GPSIM model.
gpsimLoadEcoliData.m: Load in E. coli data for the represion case.
gpsimMapFunctionalExpandParam.m: Expand the given function values into a GPSIMMAP structure.
gpdisimObjective.m: Wrapper function for GPDISIM objective.
gpsimMapExpandParam.m: Expand the given parameters into a GPSIMMAP structure.
gpsimLogLikelihood.m: Compute the log likelihood of a GPSIM model.
gpsimCandidateExtractParam.m: Extract the parameters of a GPSIM model.
gpsimMapOptions.m: Creates a set of default options for a GPSIMMAP model.
gpsimMapFunctionalLikeGrad2.m: Compute the functional gradient for GPSIMMAP.
drosFindSIMTargets.m: returns a list of targets only controlled by given tf
