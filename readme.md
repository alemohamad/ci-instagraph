# CodeIgniter Library: Instagram filters

**ci-instagraph**

## About this library

This CodeIgniter's Library is used to use Instagram like filters with ImageMagick & PHP.

I'm using the [Instagraph library](https://github.com/webarto/instagraph), created by Dejan Marjanovic.

Its usage is recommended for CodeIgniter 2 or greater.  

## Usage

```php
$this->load->library('Instagraph/Instagraph');

$this->instagraph->setInput('picture-input.jpg');
$this->instagraph->setOutput('picture-output.jpg');
$this->instagraph->process('toaster');
// toaster, gotham, nashville, lomo, kelvin, tiltShift
```

## Filters

![Original](http://alemohamad.com/github/instagraph/instagraph.jpg)

### Toaster

![Toaster](http://alemohamad.com/github/instagraph/instagraph-toaster.jpg)

### Gotham

![Gotham](http://alemohamad.com/github/instagraph/instagraph-gotham.jpg)

### Nashville

![Nashville](http://alemohamad.com/github/instagraph/instagraph-nashville.jpg)

### Lomo

![Lomo](http://alemohamad.com/github/instagraph/instagraph-lomo.jpg)

### Kelvin

![Kelvin](http://alemohamad.com/github/instagraph/instagraph-kelvin.jpg)

### Tilt-Shift

![Tilt-Shift](http://alemohamad.com/github/instagraph/instagraph-tilt-shift.jpg)



![Ale Mohamad](http://alemohamad.com/github/logo2012am.png)
