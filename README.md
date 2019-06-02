# Base Template

This is a simple  Django template that does not use any CSS external framework

This framework include Vue JS to manage DOM manipulation
## Usage

Add `base_template` to your `INSTALLED_APPS` in your django `settings.py` file

Also if you want to see as an index page add

```python
path(
    '',
    include('base_template.urls')
    
)
```

To your `urls.py` file under the `urlpattenrs` list.
