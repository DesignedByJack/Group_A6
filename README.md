# Group_A6 Repository!

We've worked really hard to bring this project to everyone. We think that our project - and the __ lines of code contained herein - is compact, minimal, but staggeringly powerful.

## == Project Description ==

Some awesome description of our project that will blow your mind!

## == Explore The Code ==

Example of some of the code produced:

```python
def roam(self):

        v = self.speed
        self._vx += random.randint(-v, v)
        self._vy += random.randint(-v, v)
        self._vx = max(-v, min(self._vx, v))
        self._vy = max(-v, min(self._vy, v))

        self.x += self._vx
        self.y += self._vy
        
        self.canvas.coords(self.shape, self.x, self.y, self.x + self.size, self.y + self.size)
        self.canvas.update()        
```

* You can view the full code that the example above was taken from by clicking [here](https://github.com/DesignedByJack/Group_A6/blob/master/Robot%20Class).

## == Some Important Stuff! ==

Here... Have a look at this cute cat gif!

-![alt text](http://i.imgur.com/QnkFrG3.gif "Here... Have a look at this cute cat gif!")
