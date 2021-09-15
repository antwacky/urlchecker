# urlchecker

Simple tool to check the response from a given set of URLs.

```
usage: urlchecker [-h] --input INPUT [--threads THREADS] [--quiet]

Check for errors in urls

optional arguments:
  -h, --help            show this help message and exit
  --input INPUT, -i INPUT
                        input urls file (one url per line)
  --threads THREADS, -t THREADS
                        threads to use
  --quiet, -q           hide successes
```

Example output:

```
success => https://www.example.com/
success => https://www.example.com/
failure => https://www.example.com/1
success => https://www.example.com/
success => https://www.example.com/
success => https://www.example.com/
```
