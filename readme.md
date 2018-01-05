# Flask simple app

```bash
gunicorn -w {cpu*n} -b 0.0.0.0:{port} server:app
```

### setup
database initialize

```python
from nick import models
models.create()
```
