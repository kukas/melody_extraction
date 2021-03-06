# Melody Extraction
Web application implementing and visualising state-of-the-art methods for melody extraction

## About
This is a semestral project that precedes my bachelor thesis on the same subject. 

## Installation

To install virtual environments (needed for running the algorithms), please run `algorithms/environments/install-environments.sh`.

The _SourceFilterContoursMelody_ algorithm requires [Essentia](http://essentia.upf.edu/documentation/) which needs to be installed to the respective _virtualenv_.

The application itself requires Python 3.6 and Flask. You can install it by running:
`pip install flask`

Also `shntool` is required for uploaded wav file verification

## Running

To run the server execute:
`python app.py`

## goals

* frontend
	* create a graphical interface for visualising and interacting with selected algorithms
		* uploading audio
			* optional: add youtube as a possible source for extraction
		* setting parameters using a custom API
		* plotting extracted melody on piano-roll
			* plotting gold standard, if available
	* compare evaluation results between algorithms
* backend
	* automated evaluation of selected algorithm according to MIREX evaluation procedure
	* 

## technologies
* front-end: javascript
	* 

## selected methods



Upload audio
sanitizing, checking formats, …
Evaluate extraction, including OrchSet
incl. visualization
MIDI visualization
State of the art metody, API pro nové extrahovací metody
Baseline extrakce
Případně: Batch processing of data?
Syntetická data?
