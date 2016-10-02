# WP Custom Excerpt Length
WP Custom Excerpt Length is a wordpress plugin to customize your wordpress website content or excerpt by word limit or character limit.

#== Description ==
WP Custom Excerpt Length is a wordpress plugin to customize your wordpress website content or excerpt by word limit or character limit.

You can set your custom content length or custom excerpt length by using this plugin. Need to replace your content or excerpt by our defined function. Also 

you can set up content by word limit or character limit.

#= Usage =
* Go to your Dashboard after installation and navigate to "Settings >> Excerpt Settings" to configure the content or exceprt lenth & type.

#= Features =
  * Very easy installation
  * Flexible and easy to use
  * Admin Setting option
  * Plugin tested with IE6+, FF 20+, Chrome, Safari


#== Installation ==
1. Upload 'wp-custom-excerpt-length' to the '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to your Dashboard after installation and navigate to "Settings >> Excerpt Settings" to configure the content or exceprt lenth & type.
4. Replace <?php the_conent(); ?> by <?php echo conent(25); ?> - 25 word will be shown. 
OR
Replace <?php the_excerpt(); ?> by <?php echo excerpt(25); ?> - 25 word will be shown.
OR
Replace <?php the_excerpt(); ?> by <?php echo substr(get_the_excerpt(), 0,100) ?> - 100 character will be shown. 
