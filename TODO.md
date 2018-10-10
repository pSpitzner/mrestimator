ToDo
====

General
-------

- [x] logging module + log file, beware only import/manipulate logging module for our module
- [ ] change logging to load config from file -> here take care not to overwrite existing loggers
- [ ] use python 3.5 for development
- [ ] test suite to check min dependencies through to latest
- [ ] import modules into _variables? No: check what numpy does via __all__
- [ ] check that input_handler is fast when getting data in the right format
- [x] add date to log file
- [ ] draw fits behind coefficients but in legend data still first, matplotlib z-index?
- [ ] add all function arguments to log/resulting container

Wrapper Function
----------------

- [x] plot
- [ ] replace member samples with bootsamples and trials
      function call parameters as dict in result of wrapper, coefficients and fit
- [ ] coefficients(): bootstrap for ts method, too
- [ ] just do the bootstrapping for coefficients and make bs of fit optional (fitting takes ages)
      fit use numboots from wrapper, if none only do bs for ceoffs
- [ ] numboot doesnt do anything so far
- [ ] results file mit function pars of all called steps