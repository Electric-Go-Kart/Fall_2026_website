# Fall_2026_website
This is the website for the fall 2026 semester, this will have all current members. 

## View locally

From the repository directory, start Python's built-in web server:

```sh
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in a browser. Stop the server with `Ctrl+C` when finished.

## Continuous integration

GitHub Actions runs the smoke test in `.github/workflows/ci.yml` on every push and pull request. It starts the same kind of local web server and checks that `index.html` is served successfully.
