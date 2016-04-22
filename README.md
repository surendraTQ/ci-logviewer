# ci-logviewer

CI Logviewer is a simple Log library that shows CodeIgniter generated Log files.

# Requirements

CodeIgniter 3

# Documentation

Copy the logviewer library in application/libraries

```php
//load the Log library
$this->load->library('logviewer');

// get logs data
$data = $this->logviewer->get_logs();

```

There is an example controller and a simple view that uses Twitter Bootstrap v3.

