CodeIgniter-Skeleton
====================

# Include

* [CodeIgniter](https://github.com/EllisLab/CodeIgniter) 2.1.4 (last updated: Jul 8, 2013)
* [Modular Extensions - HMVC](https://bitbucket.org/wiredesignz/codeigniter-modular-extensions-hmvc) 5.4 (last updated: Jul 31, 2013)
* [jQuery](https://github.com/jquery/jquery) 1.10.2 (last updated: Jul 3, 2013)
* [Bootstrap](https://github.com/twbs/bootstrap) 3.0 (not include Glyphicons, last updated: Aug 19, 2013)
* Custom Template library (base view is a mix between Bootstrap and [HTML5 Boilerplate](https://github.com/h5bp/html5-boilerplate) template)

# Usage

* Set your base URL in `application/config/config.php` file.

Example: `$config['base_url'] = 'http://localhost/ciske/';`

* Edit `RewriteBase` in `.htaccess` file.

Example: `RewriteBase /ciske/`

* Use `assets_url()` to access js / css / img resources.
* Use `$this->template->load_view()` instead of `$this->load->view()` to render page.
* Only use `$this->load->view()` to render pagelet / widget.