# Introduction

This repo records my answers to all questions from the excercises of CS229
(Autumn 2017). http://cs229.stanford.edu/syllabus.html

I tried to record all details in Jupyter notebooks. If you see any
mistake, please let me know by
[opening a new issue](https://github.com/zyxue/stanford-cs229/issues/new?template=your-question-or-bug-report.md).

As for reinforcement learning, I've also implemented value iteration, policy
iteration, SARSA, and Q-learning  before in javascript for the gridworld at
https://github.com/zyxue/rljs with a web demo at https://rljs.herokuapp.com/.

I find some of the homeworks in an earlier version
(https://see.stanford.edu/Course/CS229) of this course interesting, so I chose
to do some and placed the answers in the `previous_cs229` fold.


# Development

Create virtual environment:

```
conda env create --prefix venv -f env-conda.yml
```

Start the server

```
jupyter notebook --no-browser --ip 0.0.0.0
```

Export virtual environment:

```
conda env export --prefix venv > env-conda.yml
```


# About LaTeX

For interactive LaTeX editing, you could use
https://www.codecogs.com/latex/eqneditor.php.
