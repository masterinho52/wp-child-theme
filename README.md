# wp-child-theme
Wordpress template for a child theme

## Set and use your child theme

1. Clone repo
2. Rename the `child-theme` folder with your parent theme name plus `-child`.
  **Example:**  `astra-child`
4. Open the [`style.css`] file and change the following:  
    * `CHILD_THEME_NAME` - change this to your desired child theme name.  
      **Example:** rename to `Astra Child theme`
    * `PARENT_THEME_SLUG` - change this to the desired parent theme folder name.  
      **Example:** if you are using **Astra** WordPress theme as parent, set this to `astra`
4. Open the [`functions.php`]file and change the following:  
    * `CHILD_THEME_SLUG` - change this to your child theme's folder name, [replacing all `-` with `_`].
5. Optional: You can modify your child theme screenshot image too, a sample file is provided.
6. Now upload your modified child theme to `YOUR_WORDPRESS_ROOT_FOLDER/wp-content/themes/` folder.  
  (Or ZIP your child theme and upload it via WordPress dashboard).
8. In your WordPress dashboard got to **Appearance &raquo; Themes** and activate your child theme.

## Resources

* [WordPress Codex about child themes](http://codex.wordpress.org/Child_Themes)
* [Why child themes are so important](http://www.woothemes.com/2015/07/why-child-themes-matter/)
* [**Child Theme Check** plugin](https://wordpress.org/plugins/child-theme-check/) (and [how does it work?](https://wptavern.com/child-theme-check-plugin-helps-wordpress-users-navigate-parent-theme-updates))
* [Webmandesign child theme](https://github.com/webmandesign/child-theme)
