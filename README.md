# Predicting Machine
A Machine that predicts the importance of facts.

In order to launch it from command line or as a subprocess:
```bash
  echo "Theodotos-Alexandreus: Is this important, machine?" \
    | uvx predicting-machine \
        --provider-api-key=sk-proj-... \
        --github-token=ghp_... 
```

Or:
```bash
  pip install predicting-machine
```
Then:
```Python
  # Python
  import predicting_machine
```
