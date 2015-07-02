Fast & Local Installs

Often, you will want a fast install from local archives, without probing PyPI.

First, download the archives that fulfill your requirements:

$ pip install --download <DIR> -r requirements.txt

Then, install using --find-links and --no-index:

$ pip install --no-index --find-links=[file://]<DIR> -r requirements.txt

