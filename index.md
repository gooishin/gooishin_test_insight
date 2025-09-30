---
layout: default
title: Home
---

# Intel Edge Developer Kit Reference Scripts

Welcome to the Intel Edge Developer Kit Reference Scripts repository. This collection provides reference implementations and examples for edge computing applications.

## Quick Start

1. Clone this repository
2. Follow the setup instructions in each script directory
3. Refer to the documentation for detailed usage

## Available Scripts

{% for script in site.scripts %}
- [{{ script.title }}]({{ script.url | relative_url }})
{% endfor %}

## Documentation

- [Getting Started](./docs/getting-started.md)
- [API Reference](./docs/api-reference.md)
- [Examples](./docs/examples.md)

## Support

For issues and questions, please use the [GitHub Issues](https://github.com/intel/edge-developer-kit-reference-scripts/issues) page.
