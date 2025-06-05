# _config
Master file for setting site wide settings like URL, theme, etc

# _sass
Folder for setting appearance of the website. 
- Set custom themes (by creating different `.scss` files)
- Customize layout (by adjusting `base.scss`, `_navigation.scss`, `_sidebar.scss`)
- Use mixins and variables to avoid repeat code (via `_mixins.scss`)

# _layouts
Folder with html templates for setting the structure/layout of different pages of your website. These are liquid templates that dynamically pull content from other folders and styles from _sass. Jekyll applies these layouts dynamically to keep things updated. 

# _includes
Folder for storing reuseable html scripts that can be inserted into different pages using `{% include %}`. 
- Stores header and footer components
- Does SEO and Metadata through files like `head.html`

