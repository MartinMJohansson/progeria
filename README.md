# Progeria
Analysis of cell painting data of one progeria family.
Proband = P387,
Mother = M388,
Father = F389,
Plate = PB000188.
Cells were treated with Lonafarnib, Baricitinib and combinations there of.
Both proband and parents were treated with compounds.
Plate contains classical control compound from two different batches for control comparison.

This notebook trains a Logistic Regression model on cells from proband and mother with DMSO only.
Then it classifies the treated cells according to the model.
