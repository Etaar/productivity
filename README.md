Live templates let you insert frequently-used or custom code constructs into your source code file quickly, efficiently, and accurately.

https://www.jetbrains.com/help/idea/live-templates.html

### Setup Live Templates:

1. Open git bash and go to your webstorm config directory
    - Windows: `\<your_user_home_directory>\.WebStorm\<version_number>\config\`
    - Linux: `~.WebStorm<version>/config/`
    - macOS: `~/Library/Preferences/.WebStorm<version>/`
        - NOTE : macOS doesn't need the config directory
2. Clone the templates repo into a directory named templates
	
	```
    git clone git@git.boreal-is.com:dev-productivity/templates.git templates
    ```
3. Restart webstorm
4. Open webstorm settings, search Live Templates and verify that the NodeJS dropdown is available
5. Use and create live template snippets to be more productive :)


### Webstorm live template documentation
Creating and Editing Live Templates
	https://www.jetbrains.com/help/idea/creating-and-editing-live-templates.html

Creating and Editing Template Variables
	https://www.jetbrains.com/help/idea/creating-and-editing-template-variables.html