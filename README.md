## Cloning the repository

    git clone --recursive https://github.com/h908714124/hello-mnist.git
    cd hello-mnist

## Installing requirements

    pip install --user -r modules/tf-models/official/requirements.txt

## Setting python path ([intellij](https://stackoverflow.com/questions/28326362/pycharm-and-pythonpath))

    export PYTHONPATH="$PYTHONPATH:$PWD/modules/tf-models"
