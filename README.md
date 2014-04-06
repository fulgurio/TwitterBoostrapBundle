Fulgurio Twitter Bootstrap bundle
========================

This bundle will be use with others bundles whose uses Twitter 
bootstrap for Symfony 2.

## Installation

### Step 1: Download FulgurioTwitterBootstrapBundle using composer

Coming soon

### Step 2: Enable the bundle

Enable the bundle in the kernel:

``` php
<?php
// app/AppKernel.php

public function registerBundles()
{
    $bundles = array(
        // ...
        new Fulgurio\TwitterBootstrapBundle\TwitterBootstrapBundle(),
    );
}
```

How to use
----------------------------------
It's easy, just use {{ asset('bundles/fulguriotwitterbootstrap/css/bootstrap.css') }} 
into your template to include bootstrap files (in this case bootstrap.css)
