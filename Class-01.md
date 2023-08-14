# Component-Based Architecture:  
-Focuses on the decomposition of the desin into individual functional or logical components that represent well-defined communication interfaces containing methods, events, and properties.  
-Primary objective of component-based architecture is to ensure component reusability.  
-A component encapsulates functionality and behaviors of software element into a reusable and self-deployable binary unit.  
-Examples: JavaBean, EJB, CORBA, .NET, etc.  
-Componet-oriented software design has many advantages, one of them is that it reduces time in market and the development cost by reusing existing components.  
-increased reliability with the reuse of the existing components.  
## What is a component?  
-A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.  
-It is a software object.  
-It can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only.  
## View of a component:  
-A component can be viewed in three ways: object-oriented, conventional, and process-related.  
-Object-oriented view sees it as cooperating classes with defined interfaces.  
-Conventional view sees it as a functional module with processing logic and an interface.  
-Process-related view involves building from existing components in a library.  
-UI components include grids, buttons; utility components offer subset functions.  
-Other components include resource-intensive, JIT-activated types.  
-Many invisible components in enterprise and web apps like EJB, .NET, CORBA.  
## Characteristics of Components:  
-Reusability: Components designed for reuse across applications.  
-Replaceable: Components can be freely swapped with similar ones.  
-Not context specific: Components work across various environments.  
-Extensible: Components extendable from existing ones for new behavior.  
-Encapsulated: Interfaces expose functionality, hide internal details.  
-Independent: Components have minimal dependencies on others.  
## Principles of Component-Based Design:  
-Component-level design represented through intermediary representation (graphical, tabular, text-based).  
-Design adheres to established guidelines for data structures, interfaces, and algorithms to prevent errors.  
-Software system decomposed into reusable, cohesive, encapsulated component units.  
-Each component has an interface specifying required and provided ports, hiding implementation details.  
-Extensible components allow extension without altering existing parts.  
-Abstraction-based dependence avoids reliance on concrete components, aiding expandability.  
-Connectors link components, governed by component interfaces.  
-Interaction forms: method calls, async invocations, broadcasting, message-driven, data streams, protocols.  
-Specialized interfaces for server classes cater to client categories.  
-Components can extend and offer own extension points, enabling plug-in architecture.  

## Questions:  
1. What is a “component”?
-A "component" is a modular, reusable unit of software functionality.  
2. What are the characteristics of a component?  
-Characteristics of a component include reusability, replaceability, encapsulation, extensibility, independence, and non-context specificity.  
3.What are the advantages of using component-based architecture?
-The advantages of using component-based architecture include reusability, ease of maintenance, faster development, and modular design

# What is "Props" and how to use it in React?  
-React is a component-based library for building UIs with reusable pieces.  
-Components communicate using "props," short for properties, to pass data from parent to child components in a uni-directional flow.  
-Props data is read-only  
### Using Props in React:  
-Firstly, you have to define an attribute and its value (data).  
-Then you pass it to a child component(s) by using Props.  
-Finally, you render the Props Data.  
## Questions:  
1. What is “props” short for?
-Properties
2.How are props used in React?
-Props are used in React pass data from parent to child components.
3. What is the flow of props?  
-The flow of props is uni-directional, moving from parent to child components.

## Things I want to know more about  
-N/A  
