# Codeigniter Custom Logs
> **Note: Saved records are stored in the logs folder as year, month and day.**

## Install
```php
$this->load->library('Logs');
```

### Example
```php
Logs::view("Products page has been viewed");
Logs::insert("New product added");
Logs::update("Product updated");
Logs::delete("Product deleted");
Logs::other("Custom text");
```

<pre><code>Logs
├── 2019
│   ├── 06
│   │   ├── 16.06.2019.json
│   │   ├── 23.06.2019.json
│   ├── 10
│   │   ├── 03.10.2019.json
│   │   ├── 11.10.2019.json
</code></pre>
