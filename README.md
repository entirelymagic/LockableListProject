# LockableListProject


  The Purpose is to create a list like object that can be sliced and used like a normal list of objects,
but can be modified only when it is unlocked, otherwise it will behave like a tuple.
  It is formed as a class that has added the __getitem__, __setitem__, __add__ , __radd__, __iadd__ dunder methods.
