To install angular cli globally
npm install -g @angular/cli
# ---------------
To check cli version
from command prompt  -> ng --version
# ---------------------------------------
To create a new angular application without standalone component
$ ng new tailwind-angular-app --standalone=false
# ---------------------------------------
create a non-standalone Angular component explicitly is:
ng g c my-component --no-standalone
ng g c search --no-standalone
# ---------------------------------------
ng new my-app --standalone=false

--standalone=false: Ensures that the AppComponent is not created as a standalone component, and instead, it will use the traditional NgModule-based setup.
**In Angular CLI version 16 and above, Angular applications are created with standalone components by default.  
