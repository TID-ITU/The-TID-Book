
## Introduction to TID
What is Technical Interaction Design? Interaction design is the domain of designing for the interaction between a human and a system. If you find this to read as a very broad definition, you would be correct. Even the word "system" could be argued as too specific. Interaction design is about everything from command-line programs to dishwashers, from operating systems to car dashboards, It encompasses the digital, the physical, the visual, and the tactile.

In this course, we will focus on the process of creating a web application. This is a nice and employable skill to have, but it also serves as a neat vehicle for teaching all of the principles found in field of interaction design - principles that are, to a large degree, transferable to other types of interaction design. This also speaks to the question: What do you mean by *"technical"* interaction design? We believe in learning by doing, and to "do" interaction design, implimentation is nesessary. In the technical part of this course, you will be learning how to convert your designs into software that behaves as you want it to, using modern web technologies.

However, there is more to software than what the user sees. An equally important part of the technical aspect is the software design itself. While the user may never see the code underneith, how the code is written has a tremendous impact on the outcome, be they bugs, the required effort for added features, or merely the cost of basic maintenance.

### Design thinking
Let us visit the concept of design. When some people hear or read "design" they think about art. Paintings, furniture, clothes. Depending on the art form and the artist, design may be a vital part of the artistic process. Likewise, artestry and aesthetics may play a big role in any given design. The two are *not* the same, however. Design is fundamentally about problems and solutions. Being a designer, regardless of field, is a frame of mind, a way of thinking. 

<strong style="color:red">TODO: Solution-based vs problem-based</strong>.

The framework of Design Thinking offers us 4 central principles.

#### Design Thinking Principles
**1. Human-centric**

Designing is inherently a social activity. 

> "People ignore design that ignores people." - Frank Chimero.

<strong style="color:red">TODO: Why?</strong>.

**2. Ambiguity**

<strong style="color:red">TODO: Why?</strong>.

**3. Redesign**

<strong style="color:red">TODO: Why?</strong>.

**4. Tangibility**

<strong style="color:red">TODO: Why?</strong>.

Does this still seem broad? Yes, and not directly useful. However, keep these principles forward in your mind going forward.

#### The Design Thinking Process
Now we know the guiding principles and the thoughts behind them, let us look at the *how*. The Design Thinking Process follows the five steps below. It is important to note that iteration is a core concept in all design processes. This is the case for each step below, but also for the 5-step process as a whole.

**1. Empathise**

This is the heart of the framework, and speaks to the first principle of working in a manner that is *Human-centric*. This step is about understanding the users, their needs, wants, likes, and equally importantly their dislikes. You will never in a professional setting be designing projects for yourself, so an important part of this first step is to set aside your own assumptions and put yourself in the user's shoes.

Methodology used in the **empathise** step:

Interviews

Observation

Empathy Maps

Personas

<strong style="color:red">TODO: Forward mention how/methodology</strong>.

**2. Define**

We established that design thinking is about finding solutions to problems. It would seem obvious, then, that the problem needs defining. 

Methodology used in the **define** step:

Space saturation and group

The four Ws

The five whys

Modeling the problem domain

<strong style="color:red">TODO: Forward mention how/methodology</strong>.

**3. Ideate**

Methodology used in the **ideate** step:

Defining requirements

<strong style="color:red">TODO: Forward mention how/methodology</strong>.

**4. Prototype**


Methodology used in the **prototype** step:

<strong style="color:red">TODO: Forward mention how/methodology</strong>.

**5. Test**

Methodology used in the **test** step:

<strong style="color:red">TODO: Forward mention how/methodology</strong>.

### Design Methodologies

#### User-Centered Design

#### System-Centered Design

#### Genious Design

## Web Design

### Understanding Users and Requirements

#### Mental models

### Important Interaction Design Concepts


#### Affordances, Signifiers, and Constraints
**Affordances**

An affordance is simply put anything that makes an action available. The commonly used example is that of sitting in a chair. The chair is designed in such a way that a person can sit on it. The important thing to understand about the concept of affordances is that in principle, a window sill, a coffee table, or a bucket up-side-down has approximatly the same affordance: You can sit on them. An affordance is not nececarily linked to the original intention, however, in the world of digital design this is rarely a concern. As all behaviour has to be defined from scratch, sometimes a digital design does less than it was supposed to, but rarely more. The "Login" button on your favourite streaming service affords you logging in so you can binge, but unlike the bucket, it is unlikely to be used a drum. The importance of thinking about a design in terms of affordances comes as we turn to the concept of **signifiers**

**Signifiers**

A signifier is a cue of any kind, telling the user that they can *do something* - that here is an affordance.  The inventor of the concepts of **affordances** and **signifiers**, Don Norman have a concept named after him: The Norman Door.

<strong style="color:red">TODO: Contextual signifiers (type matters)</strong>.

...

Turning to the digital, the colour contrast of a button **signifies** actionability. There may even be an animation when you point your mouse over the button to help making this point across. The designers job is to make sure that each affordance has the appropriate signifier. An afforance with a bad signifier will not be used.

This leads us the important concept of *false signifiers*. It is possible, indeed common, for designers to introduce signifiers that are not perfectly aligned with their affordances. Reusing the subject of buttons, if a text block has a different background colour, this may be mistaken for a button. Similarily, if a link item has a different background colour, but only has the text clickable people will try to click outside of the text, as they see the text and background colour as the same item - false signifier. False signifiers will cause at best temporary confusion, at worst users leaving in frustration.

<strong style="color:red">TODO: Zeeguu menu items clickability.</strong>.

<strong style="color:red">TODO: Link to list of affordance/signifier examples.</strong>.

**Constraints**
As a **signifier** tells the user "here is something you can do"
<strong style="color:red">TODO: False constraints.</strong>.


#### Feedback

#### Hick’s Law

#### Jakob’s Law


### Usability and Usefulness

#### Heuristic principles

#### Jakob Nielsen Usability Heuristics

### Prototyping


#### Types of Prototypes


### Evaluating User Interfaces

### Web Design Principles

### Modelling the Problem Domain

## Web Application Development

### Seperation of Concerns

#### The MVC Architecture

### Source Code Usability

#### File Structure

#### The DRY Principle

#### Names

#### Functions

#### Comments

#### Formatting

#### Code Smells

### Testing and Evaluation

#### Unit Testing

#### Source Code User Testing..?

### Interacting With the Backend

#### Backend-as-a-service