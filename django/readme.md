# django

## static

Si nos tira un error 404 el get que importa los archivos static, podemos usar esto:

```bash
python manage.py findstatic --verbosity 2 css/styles.css
```

Por lo general esta en proyecto/app/static/css/style.css
