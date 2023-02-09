### Setup Instructions

I would recommend setting up a virtual environment to manage dependencies and keep everything self contained:

```
pip3 install virtualenv

virtualenv venv

source venv/bin/activate

```

Then install the dependencies:

NOTE: MacOS tensorflow package does not work with GPUs and is seperate from the Windows/Linux versions. 'pip3 install -r requirements.txt' will only work on MacOS, as the repository was initially set up on that OS.

```
// Linux/Windows
pip3 install pandas matplotlib scikit-learn tensorflow

// MacOS
pip3 install -r requirements.txt
```

### Dataset

The dataset can be found [here](https://drive.google.com/file/d/1ZIJC-SiGwfKudhPY2d1PhVEkMpmi3eM-/view?usp=share_link). It needs to be placed in the root directory of the repository.
