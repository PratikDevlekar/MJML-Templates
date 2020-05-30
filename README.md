## Email-templates
A collection of responsive email templates coded in [MJML](https://mjml.io/).

## Compiling templates to HTML
You can render all templates at once by using the `-w` command (just make sure to first create the folder where you want the HTML files to be created). 

```
mkdir templates/html
mjml -w ./templates/*.mjml -o ./templates/html/
```
