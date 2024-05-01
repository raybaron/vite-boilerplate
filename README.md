# React + Vite

This template provides a minimal setup to get React working in Vite.

The structure goes as follows:
1) The public folder is used to store the images, pdf and other static files.

public 
    - images
    - pdf

2) The src folder is the where the pages, components, layouts, router & styles are present.
The folder structure for the components and pages should be followed as given below.

src
    -components ( Sub parts of UI should be present in components )
        -[Component Name]
            -index.jsx
            -[Component Name].module.scss 

    -layout (Layouts of page templates)
        -index.jsx

    -pages ( Each page will be created in a same manner as components )
        -[Page Name]
            -index.jsx
            -[Page Name].module.scss 
    
    -router ( Consists of the routers present in the application )
        -AppRouter.jsx

    -styles ( CSS used in the application should be stored in the css folder )
        - utils (Contains the boiler plate css files)
            -mixin.scss
            -variable.scss
        other .scss/css files here
    
    


