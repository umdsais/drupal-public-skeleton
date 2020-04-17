Themes allow you to change the look and feel of your Drupal site. You can use
themes contributed by others or create your own.

WHAT TO PLACE IN THIS DIRECTORY?
--------------------------------

Put your downloaded and custom themes here. 
Placing downloaded and custom themes in this directory separates downloaded and
custom themes from Drupal core's modules that DIT put in a separate docroot directory. This allows for us to update Drupal core without overwriting these files.

DOWNLOAD ADDITIONAL THEMES
--------------------------

Contributed themes from the Drupal community may be downloaded at
https://www.drupal.org/project/project_theme.

ORGANIZING MODULES IN THIS DIRECTORY
------------------------------------

You may create subdirectories in this directory, to organize your added modules,
without breaking the site. Some common subdirectories include "contrib" for
contributed modules, and "custom" for custom modules. Note that if you move a
module to a subdirectory after it has been enabled, you may need to clear the
Drupal cache so it can be found.

There are number of directories that are ignored when looking for modules. These
are 'src', 'lib', 'vendor', 'assets', 'css', 'files', 'images', 'js', 'misc',
'templates', 'includes', 'fixtures' and 'Drupal'.