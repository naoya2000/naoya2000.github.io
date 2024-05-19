# Starting to learn about pytorch with a shakey ground of linear algebra

I took a course on the theory of machine learning, in which I found that many of the concepts that I studied took a lot of time to comprehend deeply. I found that there were many definitions (for example, the definition of PAC-learning) that took a lot of brainpower to grapple with. I'm thinking that it probably has a lot to do with lack of a natural orientation at learning about these topics, but I also thought that I might have been lacking on my foundational knowledge of linear algebra and multivariable calculus and probability. So I hope that this reflection on how I've been learning about pytorch can help some people in the same boat.

## Initial difficulties with Einops notation

I started working through a curriculum (https://www.redwoodresearch.org/mlab) that would help people already skilled in programming to learn about the basics of machine learning in order to work on AI alignment. So far, I've been squeezing in time between the obligations of my full-time work to work on this, and I'd like to explain some of the challenges that I've been facing so far.

I've only just started working on the MLAB curriculum, and so my insight is pretty limited. Nevertheless, here are my thoughts based on the `w0l1` module.

The program is basically designed for people who are already skilled in programming. And I believe that the creators expected participants to have some working knowledge of PyTorch.

The first thing I found that I had difficulty with was Einops notation.

```python
def rearrange_1() -> t.Tensor:
    """Return the following tensor using only torch.arange and einops.rearrange:

    [[3, 4],
     [5, 6],
     [7, 8]]
    """
    pass
```

As I wasn't familiar with Einops notation at all, I had to refer to many examples on the Internet, and what likely would have taken someone skilled in the same under five minutes, it took me around an hour to figure out how to do it.

It seems that there is some value in working on these together with other people, as if someone more experienced was sitting next to me, they probably would have been able to point out my misconceptions in a few minutes. But on the other hand, when I faced this difficulty, I tried to generate a lot of ideas as to what might work, even though my understanding of Einops was shaky. I don't know how beneficial it is to essentially "trial and error" your way to the solution, but it seems like this might be important if someone wanted to learn independently.

I'm writing further thoughts, but I did want to get some initial thoughts on paper for others to reference!

\[2024-05-19\] When it comes to Einops notation, I found that taking the time to write out the process can be helpful in making me think more clearly about the tensor rearrangement process. For example, instead of trying to predict mentally what output results from a given input, if I take time to write out my prediction in advance, this helps me solidify my thoughts. Not sure if this actually is something that helps in the long term, but I did want to note that it is helpful.

You can reach me at `jsfi2010` at `hotmail.com`.