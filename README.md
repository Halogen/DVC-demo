
1.  Setting up the whole pipeline which includes
1.  Setting up DVC to version data & model
1.  Setting up a gitlab pipeline to automate the execution
1.  Workflow
1.  Training everything once, and committing everything necessary
1.  Replacing the ML model with something new and training that
1.  Replacing the data with more data and running that through the pipeline.
1.  Going further
    ...

## Setup

The project uses pipenv, you simply need to run
`$ pipenv install`
to install the right python version as well as the dependencies. For reference:

- dvc
- dvc[s3] as we use AWS S3 for storage.

then run `$ pipenv shell` to enter the interactive env.

## 1. Setup DVC

