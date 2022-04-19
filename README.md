
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
https://www.nngroup.com/articles/empathy-mapping/

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

### Important Interaction Design Concepts
The following concepts have three purposes:
1. They help interaction designers develop a mental model of concept of *Interaction Design*.
2. They provide a shared vocabulary for communication between interaction designers.
3. They can be used activly as mental tools in the design process.

#### Conceptual Models

#### Affordances, Signifiers, and Constraints
**Affordances**

An affordance is simply put anything that means an action is available. The commonly used example is that of sitting on a chair. The chair is designed in such a way that a person can sit on it - it affords "sitting on it". It is important to understand that an affordance is a relationship between one entity and another. A chair that can support a child but not an adult, affords sitting to the child but not the adult. This is important in relation to the first **Design Thinking** principle (human-centered) and process step (empathise). Another important thing to understand about the concept of affordances is that in principle, a window sill, a coffee table, or a bucket up-side-down has approximatly the same affordance: You can sit on them. An affordance is not nececarily linked to the original intention, however, in the world of digital design this is rarely a concern. As all behaviour has to be defined from scratch, sometimes a digital design does less than it was supposed to, but rarely more. The entire screen on your smartphone affords a "touch" action. On the same screen, the "Login" button on your favourite streaming service affords you logging in so you can binge, but unlike the bucket, and possibly the touch screen, it is unlikely to be used a drum.

**Anti-affordances**

As an **affordance** is available actionability, an anti-affordance is the opposite. Actionability made unavailable. A roadblock, a bike lock, a disabled button, or an overlay that blocks the user from interacting with the news website unless they buy a monthly subscription. Anti-affordances are equally important to pay attention to, and to use conciously to guide the user to where they need to go.

The relevence of thinking about a design in terms of affordances comes as we turn to the concept of **signifiers**.

**Signifiers**

A signifier is a cue of any kind, telling the user that they can *do something* - that here is an affordance.  The inventor of the concepts of **affordances** and **signifiers**, Don Norman have a concept named after him: The Norman Door.

<strong style="color:red">TODO: Contextual signifiers (type matters)</strong>.

...

Turning to the digital, the colour contrast of a button **signifies** actionability. There may even be an animation when you point your mouse over the button to help making this point across. The designers job is to make sure that each affordance has the appropriate signifier. An afforance with a bad signifier will not be used.

This leads us the important concept of *false signifiers*. It is possible, indeed common, for designers to introduce signifiers that are not perfectly aligned with their affordances. Reusing the subject of buttons, if a text block has a different background colour, this may be mistaken for a button. Similarily, if a link item has a different background colour, but only has the text clickable people will try to click outside of the text, as they see the text and background colour as the same item - false signifier. False signifiers will cause at best temporary confusion, at worst users leaving in frustration. Note that false signifiers can also be intentional. This is common in the real world - think about any stop sign that does not actually provide a physical barrier, but rarely found in the digital world.

<strong style="color:red">TODO: Zeeguu menu items clickability.</strong>.

<strong style="color:red">TODO: Link to list of affordance/signifier examples.</strong>.

**Mapping**

The concept of mapping is about making **signifiers** fit **affordances** according to a user's **Conceptual Model**. To move something up, you move the controls up, or push the up-key on a keyboard. To turn on the lights in the right side of the auditorium, you flip the right light switch. These are examples of design using natural mapping. In contrast we have cultural (or learned) mapping. As a good example, take the instruments in a car. When the wheel is turned to the right, the car steers to the right, when turned to the left, the car steers to the left. However, when either the gas or the break pedal is pressed downwards, the car does not go down. In fact the instruments for making the car speed up or slow down are almost identical, save for their position. Yet experienced drivers do not have to think about which pedal to press. They have learned that left means "slow down" and right means "speed up".

<strong style="color:red">TODO: Link to list of mapping examples.</strong>.

**Constraints**

Where **signifiers** cue the user to an affordance, a constraint cues the user to an anti-affordance.

Turning to the digital you can think disabled buttons, 🚫-shaped cursors, etc.

Just like **signifiers**, false constraints also exist. 


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