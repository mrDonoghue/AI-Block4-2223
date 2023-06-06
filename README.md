# Links link
<base target="_blank">


* [copy, rename, and share this nb](https://colab.research.google.com/drive/1VoNTDhRorGa27xtgYq8CyOHpt6lW6RU6?usp=sharing)


## Today's class

```python
!wget https://raw.githubusercontent.com/karpathy/char-rnn/master/data/tinyshakespeare/input.txt
```
## Old

* check the announcemnt on myViewpoint!
* [nb3](https://colab.research.google.com)

```python
def our_plot(xish):
  c0 = xish[y.squeeze() == 0].detach()
  c1 = xish[y.squeeze() == 1].detach()
  plt.scatter(c0[:, 0], c0[:, 1], label="0", color="red", marker="x")
  plt.scatter(c1[:, 0], c1[:, 1], label="1", color="blue", marker="o")

  # Label the axes and add a legend
  plt.xlabel("f1")
  plt.ylabel("f2")
  plt.legend()

  # Show the plot
  plt.show()
```




* [formative](https://app.formative.com/formatives/643464176fc04258279ce43f)
* [SGDLab](https://colab.research.google.com/drive/1GkfznyWpRY9UG2KOd5582CW3GNkNAxTq?usp=sharing)
* [SGDHints](https://docs.google.com/document/d/1hKkVE020ATYQwF9Jiz63d-RLW67xCelBpIjW-dFbU8E/edit?usp=sharing)
* [3v7](files/3v7Logistic.md)
* [Colab](https://colab.research.google.com)


## Using Colab Reminders:
* Colab does ***NOT*** autosave!!!
* Cmd+O -> Github tab
* Look for the right repository in the `Repository` dropdown. If it's not there, put Viewpoint-School-Computer-Science in the `Enter a GitHub URL or search by organization or user` search box and try again
* ***MAKE SURE*** we're using GPU
    - Runtime -> Change Runtime Type -> Select GPU
* Always run the first few cells
* Save work whenever you've finished a meaningful "chunk" of work and definitely at the end of class
    - File -> Save a copy in Github.
    - Look at the Repository dropdown and make sure it's the right name, fixing if not
    - ***CHANGE*** the commit message to something meaningful that captures what has happened in the file since the last save
    - Make sure the `Include a link to Colaboratory` checkbox is checked
    - Hit `OK`

## Old old
* If you haven't finished yet, follow the instructions in [this file](files/semEnd.md)
* [Explainer0](files/Explainer0.md)
* [MNIST Baseline](files/MNIST%20Baseline%20Lab.md)
## Notebooks
* [nb0](https://classroom.github.com/a/33Mmonxf)
* [nb1](https://classroom.github.com/a/fBX28OVT)
* [nb2](https://classroom.github.com/a/se-cm7LL)

