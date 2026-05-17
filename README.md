# Reconning-Machine
Reconning machine.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: Are language models seeking the Truth, machine?" \
  | uvx reconning-machine \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install reconning-machine
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
reconning-machine -a multilogue.txt
```
Or:
```bash
reconning-machine multilogue.txt > response.txt
```
Or:
```bash
reconning-machine -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import reconning_machine
```
