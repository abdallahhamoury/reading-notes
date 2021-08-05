Read: Class 01

# Class



### The primary objective of component-based architecture is to ensure component reusability. A component encapsulates functionality and behaviors of a software element into a reusable and self-deployable binary unit. 

## What is a Component?
>A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.
>A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.
>A software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties.


#### Characteristics of Components

- **Reusability:** Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.
- **Replaceable:** Components may be freely substituted with other similar components.
- **Not context specific:** Components are designed to operate in different environments and contexts.
- **Extensible:** component can be extended from existing components to provide new behavior.
- **Encapsulated:** component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.
- **Independent:** Components are designed to have minimal dependencies on other components.

![Component](https://www.tutorialspoint.com/software_architecture_design/images/principles_of_component_based_design.jpg)

