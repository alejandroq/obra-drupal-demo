# Obra Theme Drupal 8 Demo 

This is the Drupal 8 Demo of the [Obra Theme](https://github.com/alejandroq/obra-drupal-theme) using a Drupal base from the [Drupal 8 Composer ❤'s️ Docksal Edition](https://github.com/alejandroq/drupal8-composer-docksal). 

## tl;dr
Quickly setup Obra Demo without the sales pitch? Click [here](#cut-to-the-chase).

## Setup instructions

### Step #1: Docksal environment setup

**ONE TIME INSTALLATION - Skip if you have a functional Docksal environment.**  

Follow [Docksal Environment Setup Instructions](http://docksal.readthedocs.io/en/master/getting-started/env-setup)

<a name="cut-to-the-chase"></a>
### Step #2: Project setup

1. Clone this repo into your Projects directory

    ```
    git clone https://github.com/kanopi/drupal8-composer-docksal.git obra-demo
    cd obra-demo
    ```

2. Initialize the site

    This will initialize local settings and install the site via drush

    ```
    fin init
    ```

3. **On Windows** add `192.168.64.100  drupal8.docksal` to your hosts file

4. Point your browser to

    ```
    http://obrademo.docksal
    ```

When the automated install is complete the command line output will display the admin username and password.

# Goals
- [X] Utilize Drupal Composer + Docksal for Dependency and Container management appropriately
- [X] Setup Obra Theme via Git Submodules
    - [X] `fin init` enables theme via Drush  

# Stretch Goals
- [X] Total Encapsulation in Docker Containers (Polymer CLI, Babel, etc)
- [ ] QA
    - [ ] TravisCI CI/CD (Composer + Polymer)
    - [ ] SauceLabs Cross-Browser Verification
