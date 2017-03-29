Guidelines for Code Review

## Scientific Quality
- Does the code perform as expected?
   - clone the repo and run it a couple times.
- Has the code been tested against previously existing implementations?
   - if so, it should be described in the README
- Is the method used well justified?
   - as described in the README

## Code Quality
- Is the code readable including good variable names and spacing?
- Is the code compatible with Python 3.3 and 3.6?
- Are Python 2.6 and 2.7 included in the tests?
- Are the necessary packages listed in the REQUIREMENTS
- Does the code run efficiently
- Is the code written Pythonically.

## Testing 
- Do tests exist and is Travis setup?
- Does it pass with Python 2.6, 2.7, as well as 3.3?
- Are the inputs to the functions sufficiently tested?

## Documentation
- Does the README sufficiently describe the code and how to use it
- Is there a docstring in the function describing:
    - What the code does?
    - The format of the inputs of the function?
    - The format of the outputs of the function?
    - References to the original algorithms?
    - Any exceptions which are raised?
    - An example of running the code?
- Is the code well commented?
