# SASS Architecture Workspace
The 7-1 Pattern -  The Popular And Effectively Modular Way To Structure SASS Projects (Kuroyza)

## 7-1 SASS Pattern 
sass/
|
|– abstracts/
|   |– _functions.scss    # Sass Functions
|   |– _variables.scss    # Sass Variables
|   |– _mixins.scss       # Sass Mixins
|
|– base/
|   |– _base.scss         # base setup
|   |– _typography.scss   # Typography rules
|   |– _animation.scss    # Sass Animation
|   |– _utulities.scss    # Sass Utulities
|
|
|– layout/
|   |– _navigation.scss   # Navigation
|   |– _header.scss       # Header
|   |– _footer.scss       # Footer
|   |– _sidebar.scss      # Sidebar
|   |– _forms.scss        # Forms
|
|– components/
|   |– _buttons.scss      # Buttons
|   |– _card.scss         # Card
|
|– pages/
|   |– _home.scss         # Home specific styles
|   |– _contact.scss      # Contact specific styles
|
|– themes/
|   |– _theme.scss        # Default theme
|   |– _admin.scss        # Admin theme
|
|– vendors/

 – main.scss              # Main Sass input file