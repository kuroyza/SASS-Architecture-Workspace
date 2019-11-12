# SASS Architecture Workspace
The 7-1 Pattern -  The Popular And Effectively Modular Way To Structure SASS Projects (Kuroyza)

## 7-1 SASS Pattern 
sass/<br>
|<br>
|– abstracts/<br>
|&nbsp;&nbsp;&nbsp;|– _functions.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Sass Functions<br>
|&nbsp;&nbsp;&nbsp;|– _variables.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Sass Variables<br>
|&nbsp;&nbsp;&nbsp;|– _mixins.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Sass Mixins<br>
|
|– base/<br>
|&nbsp;&nbsp;&nbsp;|– _base.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# base setup<br>
|&nbsp;&nbsp;&nbsp;|– _typography.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Typography rules<br>
|&nbsp;&nbsp;&nbsp;|– _animation.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Sass Animation<br>
|&nbsp;&nbsp;&nbsp;|– _utulities.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Sass Utulities<br>
|<br>
|<br>
|– layout/<br>
|&nbsp;&nbsp;&nbsp;|– _navigation.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Navigation<br>
|&nbsp;&nbsp;&nbsp;|– _header.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Header<br>
|&nbsp;&nbsp;&nbsp;|– _footer.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Footer<br>
|&nbsp;&nbsp;&nbsp;|– _sidebar.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Sidebar<br>
|&nbsp;&nbsp;&nbsp;|– _forms.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Forms<br>
|<br>
|– components/<br>
|&nbsp;&nbsp;&nbsp;|– _buttons.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Buttons<br>
|&nbsp;&nbsp;&nbsp;|– _card.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Card<br>
|<br>
|– pages/<br>
|&nbsp;&nbsp;&nbsp;|– _home.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Home specific styles<br>
|&nbsp;&nbsp;&nbsp;|– _contact.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Contact specific styles<br>
|<br>
|– themes/<br>
|&nbsp;&nbsp;&nbsp;|– _theme.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Default theme<br>
|&nbsp;&nbsp;&nbsp;|– _admin.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Admin theme<br>
|<br>
|– vendors/<br>
<br>
 – main.scss&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Main Sass input file