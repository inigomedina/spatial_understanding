# GIS

* Spatial data management
* Data analysis
* Results management

The frame where geo-referenced information makes sense. The common place
where different roles collaborate. The flow in which information is organized
and processed.

# Connecting points

Spatial analysis connects information from different fields. It gives
the connection link: where.

# Significance of where

Aprox. 70% of all the information is geo-referenced.

# GIS subsystems

* Data. I/O, storage, process.
* Visualization. Maps, labels, edition.
* Analysis. Methods, processes, formulas.

# Visualization

Visualization is a Layer with upper L. It's a key entry point for most people.
Visualization is the inherent way of managing geo-referenced information.

# Neogeography

The popularization of geo-referenced information is creating a new group of people
who use GIS for personal and professional activities.

Low-cost geo devices allow them to imagine new ways of understanding geo-referenced
information: GPS devices, IoT, etc.


# Data as the trigger

Data are the source, that has to be converted to information. Information is
data interpretation.

Information means two types of components:

- spacial, that responds to question "where?"
- thematic, that responds to question "what?"

Information is usually understood from horizontal and vertical perspectives.

The first one is related to the composition of a map with multiple frames.
A very large map can be componsed with different small maps.

The second one is related to the composition of different types of intormation.
You can manage different maps and link them through a set of operations on all
of them. The linking point is the common "where". There are different types of
variables related to that "where", so there is different thematic information
over a common spatial information.

Layer is the basic information unit over a spatial point. It could be called
"topics", since it means the informational perspective about a spatial point:
rivers, strees, population, homicides, etc.

Layer plays a key role, for it's the basic operator in which all the operations
are performed.

# Analysis

It's really more important to learn the questions you can make than the answers
you can give.

There is a kind of questions classification.

- geographical questions

  - position, extension
  - shape, distribution
  - spatial association
  - spatial interaction
  - spatial variation

- spatial questions

  - Where is it?
  - Where does it happen?
  - What is there in there?
  - Why is it not anywhere?
  - What might be there in there?
  - Might it be in other place?
  - Why does it have that shape and not other?
  - Which type of structure is it?
  - Which kind of distribution is it?
  - Is it universal?
  - Where are its limits?
  - When did it appear for the first time?
  - How dit it change over time?
  ...

Visualization is a heuristic tool to ask questions. That is specially true when we
talk about layers, its information and its relations.

# Types of Analyses

We can talk about main types of analyses as sets of questions.

## Spatial Analysis. This is probably the most simple analysis, and this is just
about the information that spatial data contain. We basically use the position of
each geographical element. For instance:

     - which type of ground we find in a coordinate (x,y)?
     - where is the town n?

They are usually analyses that can be solved looking at the map. So, it's the easiest
spatial analysis.

Well, since every spatial element has properties in terms of values, we can also check
those values. That allows us to make questions not limited to spatial information.
For instance:

    - Which are the top ten populated cities?
    - Which name towns do start with the letter A?

## Topological Analysis. We can make questions over spatial data not related to its
position but its relation to other elements on the same layer. For instance:

    - How do I go from my position to a coordinate using the current railway network?
    - Which towns do share limits with town n?


## Measurement. We can measure different types of things using the spatial data we have.
For instance:

    - Distance
    - Area
    - Perimeter

We can answer questions like these:

   - How long is the surface of treeplanted area?
   - How many kilometers does the railway network have?


## Combination.

## Transformation.

These are actions that modify entry elements and giving new output elements.

For instance, of the most popular transformations is the AOI: area of influence.

    - Which places of city n have a supermarket by less than a kilometer away?
    - If I know that people make weekend trips of 100kms, which are likely towns
    from which people come?


## Surfaces Analysis.

## Statistics.

   - Is it constant the average height over a country?
   - Is there a trend to live together?
   - Do people move in a predominant way? Or does it look random?


## Making decisions and optimization.

   - Which is the best place for building a new business?
   - Which would be the best place to build a new road?
   - Where sould be a new hospital?
