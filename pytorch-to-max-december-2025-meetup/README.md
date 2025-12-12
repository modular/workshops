# From PyTorch to MAX

!["event image"](./meetup121125.png)

* [luma event page](https://luma.com/modularmeetup)
* [meetup page](https://www.meetup.com/modular-meetup-group/events/311998048/?eventOrigin=group_events_list/?utm_medium=referral&utm_campaign=event_card_savedevents_share_modal&utm_source=link&utm_version=v2)

An introductory workshop for PyTorch users who want to learn [MAX](https://docs.modular.com/max/)'s modeling APIs for **optimized inference**.

**Workshop Notebook:** [main.ipynb](./main.ipynb)

## What You'll Learn

1. **Tensors** - Creating and manipulating tensors
2. **Functional API** - Common operations like relu, softmax, matmul
3. **Random Module** - Random tensor generation
4. **Module System** - Building models with `nn.Module`
5. **Real Model** - Translating a HuggingFace GPT-2 attention to MAX
6. **Compilation** - Graph compilation for optimized inference
7. **Custom ops** - Mojo kernels in MAX

## Getting Started

**Prerequisites:** Python 3.12+, [uv](https://docs.astral.sh/uv/), and see [Modular package requirements](https://docs.modular.com/max/get-started)

```bash
# Set up environment
uv venv && source .venv/bin/activate

# Install dependencies
uv sync

# Launch Jupyter Lab
uv run jupyter lab
```

Open [main.ipynb](./main.ipynb) in `localhost:8888/lab` and follow along.


## Resources

- [MAX Documentation](https://docs.modular.com/max/)
- [MAX Experimental API](https://docs.modular.com/max/api/python/experimental/)
- [MAX Module V3](https://docs.modular.com/max/api/python/nn/module_v3)
- [LLM Book in MAX](https://llm.modular.com/)
- [Modular Forum](https://forum.modular.com/)
