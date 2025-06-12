---
sidebar_position: 100
sidebar_label: What Is OOP?
draft: true
---

# What Is Object-Oriented Programming?

So far, we have been using objects to organize data. We write classes that
contain fields which allow us to group related pieces of data, and we write
methods which allow us to easily organize and perform operations on that data.

While this is very exciting, it's not exactly _object-oriented_ programming.
Perhaps a better term to describe how we have been programming so far is
_programming with objects_. In this chapter, we will describe _object-oriented_
programming and discuss how this differs from just _programming with objects_.

This section will blast through a lot of high-level concepts quickly. Don't
worry if it feels like a lot. Try to get the main ideas and feel free to come
back to this chapter as you progress through the rest of this site.

## Object-Oriented Programming Is About Design

In introductory programming courses, the focus of learning to program is to
write small, isolated, and correct pieces of software. However, when thinking
about _object-oriented programming_, we need to shift our focus from merely
writing _correct_ code to writing _"good"_ (and correct) code.

The term "good" here is vague and will be the focus of much of the material on
object-oriented programming. But in summary, by "good" we mean we need to
consider software not only as a means to produce correct output, but as a
**resource** that contributes, interacts, and is interacted with within projects
over time. Now, aside from just asking if a piece of software is correct, with
object-oriented programming, we need to ask new questions like:

- What if we need to add new features to software after we have written it?
- How do we manage how complex our software gets as it grows?
- How do the parts of our software work together?
- How might other people use our software if we release it as a library?

To properly address these questions using object-oriented programming, we need
to start thinking about _designing_ our software using objects.

### What _Is_ Design, Anyway?

When we refer to something as having a "good design", usually we mean it is
intuitive and feels good to use. In other words, when something has been
"designed", it has been created not only to solve a problem but to account for
how we, the user, interact with it — attempting to make that _interaction_
both effective and affective.

:::tip A Case-Study on Design

Perhaps the canonical example of how items can be designed is the _Norman door_.
The term is named after [Don Norman](https://en.wikipedia.org/wiki/Don_Norman),
a design researcher and professor who had a few things to say about the design
of doors (details of which are described in his book
[The Design of Everyday Things](https://www.nngroup.com/books/design-everyday-things-revised/)).

Ideally, doors should communicate whether they should be pushed, pulled, or even
slid. Despite this, how many doors have you tried to push that ended up being
pull doors, or vice versa? A well-_designed_ door should be able to signify
whether it should be pushed or pulled without the need for any signs telling
people to push or pull.

<figure>
<img
  src="/img/what-is-oop/norman_door.svg"
  alt='A cartoon-style drawing of a class door with two metal bar handles that indicate the door should be pulled.
       However, there is a sign above each handle saying "push"'
/>
<figcaption>
An example of a Norman door—The handles signify the door should be
<em>pulled</em> open; however, there is a sign telling users they should 
<em>push</em> the door open instead.
</figcaption>
</figure>

While the function of a door is to primarily let us in and out of doorways while
otherwise being closed; a door has been _designed_ well if it takes into account
how people might perceive, interact with, and use it. This is one of the main
ideas behind design—something has been designed well if it has been created with
a focus on _how_ users will perceive and interact with it in addition to making
sure it functions correctly.

:::

[//]: # (Design is a discipline of study and practice focused on the 
interaction between a person — a ‘user’— and the man-made environment, 
taking into account aesthetic, functional, contextual, cultural and societal 
considerations. As a formalised discipline, design is a modern construct.)

### How Does Design Apply to Software?

## Object-Oriented Programming Is About Fully Using the Capabilities of Objects in Our Program Design

:::warning

Much of the material on OOP has historically treated features of Object-Oriented
languages with a "more is better" approach. However, it is now generally agreed
that while these features can be useful when designing programs, they are only
useful when used carefully. Much of the material in the rest of this website
will be directed towards knowing when and how to use these concepts – and how to
avoid overusing them.

:::

### Encapsulation

### Abstraction

### Inheritance

### Polymorphism

## Object-Oriented Programming Provides Principles to Use When Designing Programs

### Single-Responsibility

### Open-Closed

### Liskov Substitution

### Interface Segregation

### Dependency Inversion

## There Are Common Object-Oriented Design Problems That Already Have Established Solutions (i.e. Patterns)

## Summary
