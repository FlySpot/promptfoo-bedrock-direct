# promptfoo-bedrock-direct
promptfoo tests for LLM on bedrock

First of all you need to have installed python and configured virtual environment for it.
```
python3 -m venv .venv
ource .venv/bin/activate
```
To get started, set your AWS environment variables:
```
export AWS_ACCESS_KEY_ID="<Copy from AWS access portal Access keys>"
export AWS_SECRET_ACCESS_KEY="<Copy from AWS access portal Access keys>"
```
Next, edit promptfooconfig.yaml.

Then run:
```
promptfoo eval
```

Afterward, you can view the results by running `promptfoo view`


