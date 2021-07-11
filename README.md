# new-machine-learninng-app-in-python-using-streamlit

required joblib
numpy pandas streamlit 

The homepage of joblib with user documentation is located on:

https://joblib.readthedocs.io
Getting the latest code

To get the latest code using git, simply type:

git clone git://github.com/joblib/joblib.git

If you don’t have git installed, you can download a zip or tarball of the latest code: http://github.com/joblib/joblib/archives/master
Installing

You can use pip to install joblib:

pip install joblib

from any directory or:

python setup.py install

from the source directory.
Dependencies

    Joblib has no mandatory dependencies besides Python (supported versions are 2.7+ and 3.4+).
    Joblib has an optional dependency on Numpy (at least version 1.6.1) for array manipulation.
    Joblib includes its own vendored copy of loky for process management.
    Joblib can efficiently dump and load numpy arrays but does not require numpy to be installed.
    Joblib has an optional dependency on python-lz4 as a faster alternative to zlib and gzip for compressed serialization.
    Joblib has an optional dependency on psutil to mitigate memory leaks in parallel worker processes.
    Some examples require external dependencies such as pandas. See the instructions in the Building the docs section for details.

