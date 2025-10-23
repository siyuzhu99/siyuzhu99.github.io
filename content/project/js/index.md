---
title: Online Mulitimodal Reading Assessment
summary: Measures how learners integrate and comprehend information across multiple modes such as text, images, and videos in an online context.
date: 2025-01-01
type: docs
math: false
tags:
  - Multimodal Reading
image:
  caption: 'Embed rich media such as videos and LaTeX math'
---

This research is conducted under the supervision of Prof. Zhu Xinhua and in collaboration with Prof. Cheong ChooMui from the University of Hong Kong.

## Background
The digital age has fundamentally transformed literacy. With the proliferation of online resources and user-generated content, multimodal texts combining images, videos, and written content have become ubiquitous in our daily information consumption. Modern literacy now extends beyond traditional reading to include the ability to navigate, comprehend, and meaningfully interact with digital technology.

Recognizing this evolution, the Progress in International Reading Literacy Study developed the e-PIRLS assessment in 2016 to evaluate students' online reading abilities through simulated web browsing experiences. Set to be implemented worldwide in 2026 across 60 participating countries and regions including Hong Kong, this initiative underscores that effective online reading has become an essential 21st-century skill.


## Research Focus

**1. Psychological Mechanisms and thier Relationships with Reading Performance**

This focus takes a person-centered approach to investigate the cognitive and psychological processes students engage during online multimodal reading. Specifically, it examines how motivational factors (such as goal orientations, emotions and self-efficacy) and cognitive factors (such as reading strategies) relate to online reading performance, with particular attention to individual differences among learners.  This is also the theme of my 
[doctoral dissertation](https://research.polyu.edu.hk/en/studentTheses/individual-profiles-in-online-reading-relations-between-default-p/).

**2. Technology-Enhanced Self-Directed Learning**

We explore innovative ways to leverage technology to support students' development as independent learners. This research focuses on designing and implementing self-directed learning approaches that empower students to improve their online multimodal reading performance autonomously and effectively.








## Test students

Provide a simple yet fun self-assessment by revealing the solutions to challenges with the `spoiler` shortcode:

```markdown
{{</* spoiler text="👉 Click to view the solution" */>}}
You found me!
{{</* /spoiler */>}}
```

renders as

{{< spoiler text="👉 Click to view the solution" >}} You found me 🎉 {{< /spoiler >}}

## Math

Hugo Blox Builder supports a Markdown extension for $\LaTeX$ math. You can enable this feature by toggling the `math` option in your `config/_default/params.yaml` file.

To render _inline_ or _block_ math, wrap your LaTeX math with `{{</* math */>}}$...${{</* /math */>}}` or `{{</* math */>}}$$...$${{</* /math */>}}`, respectively.

{{% callout note %}}
We wrap the LaTeX math in the Hugo Blox _math_ shortcode to prevent Hugo rendering our math as Markdown.
{{% /callout %}}

Example **math block**:

```latex
{{</* math */>}}
$$
\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}
$$
{{</* /math */>}}
```

renders as

{{< math >}}
$$\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}$$
{{< /math >}}

Example **inline math** `{{</* math */>}}$\nabla F(\mathbf{x}_{n})${{</* /math */>}}` renders as {{< math >}}$\nabla F(\mathbf{x}_{n})${{< /math >}}.

Example **multi-line math** using the math linebreak (`\\`):

```latex
{{</* math */>}}
$$f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
1-p_{0}^{*} & \text{if }k=0.\end{cases}$$
{{</* /math */>}}
```

renders as

{{< math >}}

$$
f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
1-p_{0}^{*} & \text{if }k=0.\end{cases}
$$

{{< /math >}}

## Code

Hugo Blox Builder utilises Hugo's Markdown extension for highlighting code syntax. The code theme can be selected in the `config/_default/params.yaml` file.


    ```python
    import pandas as pd
    data = pd.read_csv("data.csv")
    data.head()
    ```

renders as

```python
import pandas as pd
data = pd.read_csv("data.csv")
data.head()
```

## Inline Images

```go
{{</* icon name="python" */>}} Python
```

renders as

{{< icon name="python" >}} Python

## Did you find this page helpful? Consider sharing it 🙌
