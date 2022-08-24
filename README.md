# Django Podcast Content Aggregator

## How To Run The Project

Create and activate virtual environment for Mac OS:
```bash
$ python3 -m venv venv
$ source venv/bin/activate
```

```bash
(venv) $ python3 -m pip install -r requirements.txt
```

You can find the `requirements.txt` file in `pycasts/requirements.txt`.

Navigate to `pycasts/` and start the Django development server:

```bash
(venv) $ cd pycasts
(venv) $ python3 manage.py runserver
```

You can run scraping rss news.
```bash
(venv) $ python3 manage.py startjobs
```
You can now navigate to `localhost:8000` in your browser. 