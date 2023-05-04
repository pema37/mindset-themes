create new menu location

register_nav_menus(
  array(
    'header' => esc_html_( 'Header Menu Location', 'fwd' ),

  )
);

<nav id="footer-navigation" class="footer-navigation">
  <?php wp_nav_menu( array( 'theme_location' => 'footer-left') ); ?>
</nav>

<?php wp_footer()?>