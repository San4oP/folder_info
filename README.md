Roundcube Webmail Folder Info
==========

Plugin to show information message above the messages list.

Configuration Options
---------------------

Set the following options directly in Roundcube's config file (example):
```php
$rcmail_config['folder_info_messages'] = array(
   'Folder 1' => 'Messages will be deleted after {} {}.',
   'Folder 2' => 'Messages will be deleted after {} days.'
);
$rcmail_config['folder_info_messages_args'] = array(
  'Folder 1' => array(30, 'days'),
  'Folder 2' => 14
);
```

Translation
-----------

https://www.transifex.com/san4op/roundcube-folder-info-plugin/
