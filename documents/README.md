## Design and Architecture Documentation
<p>
This directory centralizes all the structural design resources for the project.
Here you will find User Flows, the tree structure, diagrams, and graphical resources.
These documents serve as a technical reference before any modification to the interface or business logic,
thus ensuring visual and functional consistency as the site's load increases.
</p>

## Structure

- ```/flows```
    <p>
    <strong>Navigation diagrams and error logic</strong></br>
    This folder forms the logical brain of the documentation.
    It simply shows the page flow, detailing the sequence of events and conditions that dictate the application's behavior. For a 3D customization site, this is where you define how the system reacts if a model load fails, if the user is not logged in when saving their creation, or how data flows from one step to the next.</br>
    In the event of maintenance or the addition of features by new developers, these diagrams allow visualization of the impact of a modification on the overall process, thus avoiding breaking complex mechanisms by modifying a simple function.</br>
    <strong>THIS IS THE ABSOLUTE REFERENCE FOR UNDERSTANDING THE "IF THIS, THEN THAT" OF THE PROJECT.</strong>
    </p>
- ```/architecture```
    <p>
    <strong>Data structure diagrams and sitemap</strong></br>
    This document serves to outline the foundation upon which the entire technical ecosystem rests.
    It contains the sitemap, which defines the hierarchy of routes and components, as well as the data schemas. For a project targeting millions of users, this document is vital because it shows how the application is segmented to handle the load.</br>
    It will serve as a guide for backend and infrastructure developers to understand the organization of services, API management and the flow of data between the client and the server, ensuring that each software component is placed consistently with the overall vision.
    </p>
- ```/assets```
    <p>
    <strong>Graphic resources and screenshots of the mockups</strong></br>
    This folder serves as a central library for all graphic elements and visual proofs of concept needed for development.
    It contains wireframe exports, high-fidelity mockup captures, and essential graphic assets (icons, logos, reference textures) to ensure the interface remains faithful to the initial design.</br>
    Its role allows frontend developers to compare the final code rendering with the designer's intentions without having to open third-party software.  </br>
    In the future, during a UI redesign or improvement, this repository will maintain a history of the product's visual evolutions and ensure that the brand identity remains consistent, regardless of who is working on the code.
    </p>