
~~~
git clone https://github.com/dai-ichiro/debug_smolagents_gradio
cd debug_smolagents_gradio
~~~

~~~
docker build --force-rm=true -t debug-agent-sandbox .
~~~

~~~
uv venv
source .venv/bin/activate
uv pip install docker
uv run debug_runner.py
~~~
