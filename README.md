# Custom Post Type Multiroutes
== Description ==

Custom Post Type Multiroutes is a Wordpress plugin that allows you to manage, add, edit and update multiple routes for your Custom Post Types. Minimum configuration needed. Install it, type your routes for your posts and refresh permalinks.

== Installation ==

1. Upload the entire `Custom-Post-Type-Multiroutes` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.

== Use case == 

Say you have a custom post type called 'Galleries' and you want it to appear on two archive pages:

`/news/gallery/`
`/media/album/`

And its single pages to be: `/news/gallery/<gallery-name>` and `/media/album/<gallery-name>`

All you have to do is:

1. Go to Settings > CPT Multiroutes (you will se a list of your custom post types)
2. Click on "Add Route" for your 'Galleries' post.
3. Fill the new imput for that new route, in this case 'news/gallery'
4. Repeat 2&3 per route you want to add.
5. Select the checkbox 'Rewrite this post type archive to these routes' if you want that route to be your archive page for the custom post type.
6. Click Save Routes.

Additionally a custom Metabox will appear on each of those custom post types on its admin edit page, there you will be able to choose individually on which route you wish the post to be visible. By default it will be visible on all defined routes.

If you are using WPML for multilanguage, when you add a route, an input for each acive language will appear so you can translate those new routes.
