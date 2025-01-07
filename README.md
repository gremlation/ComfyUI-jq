# ComfyUI-jq

A ComfyUI node that runs a [jq](https://jqlang.github.io/jq/) query against input JSON and outputs the result.

![A screenshot showing usage of the node.](docs/workflow.png)

## Installation

### ComfyUI-Manager

- Open the manager
- Pick "Install via Git URL"
- Enter `https://github.com/Gremlation/ComfyUI-jq`

You may need to edit `custom_nodes/ComfyUI-Manager/config.ini` and set `security_level = normal-` first.

### Manual

Run the following commands in the terminal:

```shell
cd custom_nodes
git clone https://github.com/Gremlation/ComfyUI-jq
pip install -r ComfyUI-jq/requirements.txt
```

Then restart ComfyUI.
