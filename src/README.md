Example Auth2 API

Include: 
- Api for Registration
- Api for Authorization

Use:
- orm - SQLAlchemy

Implemented:
- Start uvicorn server thought PyCharm (__main__.py + Configurations PyCharm)


Package assignment:
- src - source directory:
  - requirements.txt
  - settings.py - configuration project file
-workshop - project package:
    - __main__.py - unicorn settings for PyCharm
    - database.py -  database code: connection and session configuration
- api - package with handlers
- services - business logic package
- models - data model package
