The major tools in our arsenal 

* **Abstraction**  
* **Composition**  
* **Identity**

Abstraction is to get rid of unnecessary details. Things that were different because of unnecessary details are now identical.

Composition and Identity together are defined in a Category.

Categories have:

1. A 'bunch' of objects.
2. Morphisms, i.e. 'arrows' between two objects.

(Plus a composition operator, identity morphisms and associativity law, introduced later in the lecture)

The 'bunch' of objects can be a set, but it doesn't necessarily have to be. This is because there are objects that are bigger than sets<sup>1</sup> and categories can be defined for these classes too.

From a Category Theory point of view, we cannot know what an object is. An object is no properties or internal structure. It is like a 'point'. Similarly for morphisms we cannot know it's internal structure, and the only properties we know is the beginning and end object of the arrow.

[14:00](https://youtu.be/p54Hd7AmVFU?t=820)

There are many possibilities related to how arrows can exist between objects:

![Diagram 1.2a](diagram1.2a.jpg)

* Looking at any 2 objects A, B we can see that there may be zero, 1, finite, countable or un-countably infinitely many arrows connecting them in the direction A → B.
* You can (but not necessarily) have arrows going back from B → A.
* And of course, you can have arrows from A → A.
* In this sense a category is like a graph, but it can have infinitely many objects and infinitely many arrows. Or in the other extreme, no objects at all!

# Composition

[16:20](https://youtu.be/p54Hd7AmVFU?t=980)

![Diagram 1.2b](diagram1.2b.jpg)

Given any morphisms f : A → B and g : B → C, you can compose them g ∘ f : A → C and is also a morphism in the category. 

Of course there may (or may not) be other different morphisms x, y, z : A → C, as shown by red arrows above.

You could think of composition as a multiplication table that for any two arrows, you define what is the composition.

#Identity

[20:30](https://youtu.be/p54Hd7AmVFU?t=1230)

![Diagram 1.2c](diagram1.2c.jpg)

For every object A there is an arrow id : A → A that is the identity. Denoted Id<sub>A</sub>

For all f : A → B, id<sub>B</sub> ∘ f = f (left identity)
For all f : A → B, f ∘ id<sub>A</sub> = f (right identity)

#Associativity

[23:12](https://youtu.be/p54Hd7AmVFU?t=1392)



(TODO: Rest of lecture)




[1] For example the set of all sets that are not members of itself. This can't exist. See [Russell's Paradox](https://en.wikipedia.org/wiki/Russell's_paradox) and [Barber Paradox](https://en.wikipedia.org/wiki/Barber_paradox) for more details.