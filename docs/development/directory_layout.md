# Food app

## Top level directory layout

    .
    ├── config                                                             # Configuration files (ex. webpack)
    │   
    ├── docs                                                               # Documentations
    │   ├──── design                                                       # Design docs
    │   └──── development                                                  # Development docs
    │   
    ├── public
    │   ├──── assets                                                       # Holds static assets
    │   └──── index.html                                                   # Main html file
    │   
    ├── src                                                                # Source files
    │   ├──── components
    │   │     │   
    │   │     ├──── features                                               # Application features
    │   │     │      │ 
    │   │     │      ├──── [feature name]
    │   │     │      │           ├──── index.js                            # Feature main file
    │   │     │      │           ├──── style.css                           # Styles related to the feature
    │   │     │      │           ├──── helperMethods.js <optional>         # Component related helper methods
    │   │     │      │           ├──── routes.js <optional>                # Routes related to feature
    │   │     │      │           │  
    │   │     │      │           ├──── [component name]                    # Sub component related to feature
    │   │     │      │           │          ├──── style.css                # Styles related to the component
    │   │     │      │           │          └──── index.js                 # Component main file
    │   │     │      │           │  
    │   │     │      │           └──── [component name]
    │   │     │      │                       .
    │   │     │      │                       .
    │   │     │      │                       .
    │   │     │      │
    │   │     │      └──── [feature name]
    │   │     │                 .
    │   │     │                 .
    │   │     │                 .
    │   │     ├──── layout                                                 # Application layout
    │   │     │      │      
    │   │     │      ├──── index.js                                        # Main layout file
    │   │     │      │      
    │   │     │      ├──── [component name]
    │   │     │      │     ├──── styles                                    # Styles related to the component
    │   │     │      │     └──── index.js                                  # Component main file
    │   │     │      │     
    │   │     │      └──── [component name]
    │   │     │                 .
    │   │     │                 .
    │   │     │                 .
    │   │     │
    │   │     └──── ui                                                     # Reusable components (ex. button)
    │   │            │ 
    │   │            ├──── [component name]
    │   │            │     ├──── styles                                    # Styles related to the component
    │   │            │     └──── index.js                                  # Feature main file
    │   │            │     
    │   │            └──── [component name]
    │   │                       .
    │   │                       .
    │   │                       .
    │   │
    │   │     
    │   ├──── App.js                                                       # Main file
    │   ├──── index.js                                                     # Entry file
    │   └──── routes.js                                                    # Entry level routes
    │
    │
    ├──── utils                                                            # Application utils
    │      └──── helperMethods.js                                          # Reusable methods
    │
    │
    ├── .gitignore
    ├── package-lock.json
    ├── package.json
    └── README.md
