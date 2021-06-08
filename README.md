This is a test repository.

We will use this repository to do python excercises.

First, clone [usrp_sciprog](https://github.com/changgoo/usrp-sciprog) and copy the files under day2/ 

```
cp -rp your_path_to_the_usrp_repo/usrp-sciprog/day2/* .
```

Replace _your_path_to_the_usrp_repo_ to the correct one. In my case, it was `/Users/ckim/Sources/usrp_sciprog`.

Second, create a clean environment for this excercise (you don't need to do if you are familiar with python already).

```
conda create --name usrp python=3.8
```

Install basic packages 

```
conda install matplotlib numpy jupyter ipython
```

Run jupter notebook

```
conda jupyter notebook --no-browser
```

You will see something like this:

```
(usrp) DESKTOP-643AC19 [~/new_project] git:master (!) % jupyter notebook --no-browser
[I 18:56:40.257 NotebookApp] Serving notebooks from local directory: /home/changgoo/new_project
[I 18:56:40.257 NotebookApp] Jupyter Notebook 6.4.0 is running at:
[I 18:56:40.257 NotebookApp] http://localhost:8888/?token=49f92fcbfc3c71727ec12b74314684ffb47831ae785c2adb
[I 18:56:40.257 NotebookApp]  or http://127.0.0.1:8888/?token=49f92fcbfc3c71727ec12b74314684ffb47831ae785c2adb
[I 18:56:40.257 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[C 18:56:40.261 NotebookApp]

    To access the notebook, open this file in a browser:
        file:///home/changgoo/.local/share/jupyter/runtime/nbserver-4379-open.html
    Or copy and paste one of these URLs:
        http://localhost:8888/?token=49f92fcbfc3c71727ec12b74314684ffb47831ae785c2adb
     or http://127.0.0.1:8888/?token=49f92fcbfc3c71727ec12b74314684ffb47831ae785c2adb
```

Copy/paste the URL on your favorite browser.

Let's learn python!

```
git clone git@github.com:jakevdp/WhirlwindTourOfPython.git
```
