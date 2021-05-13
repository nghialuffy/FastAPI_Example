# INSTALL

```bash
pip3 install fastapi
pip3 install uvicorn
```

# RUN

```bash
uvicorn main:app --reload
```

# METHOD

You can also use the other operations:

- @app.get()
- @app.post()
- @app.put()
- @app.delete()

And the more exotic ones:

- @app.options()
- @app.head()
- @app.patch()
- @app.trace()
