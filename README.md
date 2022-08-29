# fights-example-agent

Example agent project structure for [fights](https://github.com/poapper-inc/fights) and runfights (TBA).

All files are part of the project by default. Any files to be ignored must be specified in fights-ai.yml.

## Structure

### Agent files

Agent Python files must each expose a `Agent` class that subclasses [`fights.base.BaseAgent`](https://fights.readthedocs.io/en/latest/fights.base.html#fights.base.BaseAgent). The paths are specified in fights-ai.yml.

### [fights-ai.yml](./fights-ai.yml)

fights-ai.yml must be present at the project root. It is used to specify project information such as the environment, agent file paths, and more.

### [requirements.txt](./requirements.txt)

Dependencies must be specified in requirements.txt, following the [requirements file format](https://pip.pypa.io/en/stable/reference/requirements-file-format/#requirements-file-format).
