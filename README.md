## project structure for code documentation

- use this set up for your project and you can have beautiful docs

Workflow:

- update code and docs
- execute in docs directory
```bash
sphinx-build -b html source _build   
```
- open in browser
```bash
firefox _build/index.html
```