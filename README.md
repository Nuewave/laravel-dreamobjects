# joexanderson\DreamObjects
Laravel Client for DreamObjects to work with Amazon S3 API.
Forked from arleslie\DreamObjects

# Installation
`composer require arleslie/dreamobjects-client`

In `config\filesystems.php` add the following under `'disks' => [`
```
        'dreamobjects' => [
            'driver' => 'dreamobjects',
            'key'    => '<key>',
            'secret' => '<secret>',
            'bucket' => '<bucket name>'
        ],
```

Add the ServiceProvider: `arleslie\DreamObjects\ServiceProvider` to your `app.php`.
