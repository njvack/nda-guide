# Glossary of Terms

A lot of the confusion I've found in this has been simply in trying to understand what terms in the NDA mean. Here are some of the important ones:

## Collection

A unified dataset in the NDA. Usually seems to correspond to being one Collection per study, but I don't think this is always true.

## Structure

The definition of one "kind of data" in the NDA. "Kind of data" is something of a slippery term — there are separate structures for each questionnaire. All medical imaging data shares one structure. There are structures for many different behavioral tasks, as well as a generic "catch-all" structure for behavioral tasks. There are structures for ECG and skin conductance data, while data submitted with the EMG structure may also contain ECG and skin conductance data.

## Experiment

I don't actually know what "experiment" means in the NDA. Basically, if you need to submit data with a structure that requires an `experiment_id` field, you'll need to make an experiment.

## Task (fMRI Experiments)

As far as I can tell, in fMRI experiments, "task" means "functional run" or "scan session."

## Block design file (fMRI Experiments)

A document explaining, in prose, what happened during a scan session. PDF and Microsoft Word seem to be fine formats.
