Big Commerce FTP Server
-----------------------

Congratulations on successfully connecting to your store via FTP.

The document below outlines the purpose of the directories
available to your store via FTP and how you can make use of them.
If you do need further assistance, please feel free to contact us
either via phone, or lodge a support issue with our ticket system.

*** IMPORTANT ***

To learn everything you need to know to customize your store, please
read the template customization guide here:
 http://www.bigcommerce.com/pdf/Big_Commerce_Template_Guide_1.0.pdf

content/ - Directory for Any Additional Website Content
-------------------------------------------------------

You can upload any additional content/files you may need for your
store to this directory.

It is accessible at http://www.store.com/content/
 (Where 'www.store.com', is the URL of your BigCommerce store)

import_files/ -Temporary Directory for Importable Content
----------------------------------------------------

Big Commerce allows for CSV (comma separated values) imports of
your products, customers, variations etc. Normally, you'd upload
your CSV file via your web browser in to one of the importers. If
however, your CSV file is too large to upload via the web based
interface, you can upload it in to this directory and then select
it during the import wizard.

product_downloads/ - Directory for All Digital Product Files
------------------------------------------------------------

This directory contains all of the digital product files you've
uploaded to your store. When uploaded via the store, files are
placed in a random a-z directory.

The 'import' directory is a special directory you can use to
store product files for products you're importing from a CSV file.
When the products are imported, if a file with a matching name
(based on your 'Downloadable File' column in your CSV file) is found
in this directory, it will be assigned to that product.

product_images/ - Directory for All Product Images
--------------------------------------------------

This directory contains all of the product images for the products
you've created in your store. When images are uploaded for a product,
the files are placed in a random a-z directory.

The 'import' directory is a special directory you can use to store
product images for products you're importing from a CSV file. When
the products are imported, if a file with a matching name (based on
your 'Product Image' column in your CSV file is found in this directory,
then it will be assigned to that product.

The 'uploaded_images' directory contains all of the images you've uploaded
via the WYSIWYG editor as well as any images uploaded via the Website Content
> Image Manager page.

template/ - Directory for Your Store Design
-------------------------------------------

The template/ directory allows you to customize the appearance of
your store. For more information, navigate to the template/ directory
and download README.txt.