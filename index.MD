---
layout: default
---

<!-- <h1> Open-Source Pretrained Language Models </h1>

Only open-source models with published checkpoints are included. -->

<table>
<tr>
  <th>Model Name</th>
  <th>Size in parameters</th>
  <th>Release (YY/MM)</th>
  <th>Link to paper</th>
  <th>Link to model</th>
  <th>Author</th>
  <th>Architecture</th>
  <th>English-only/Multilingual</th>
  <th>Commercial use (Don't trust me ask a lawyer!)</th>
  <th>Random comment</th>
</tr>
<tr>
  <td>T0pp</td>
  <td>11e9</td>
  <td>21/10</td>
  <td><a href="https://arxiv.org/abs/2110.08207">Paper</a></td>
  <td><a href="https://huggingface.co/bigscience/T0pp">Model</a></td>
  <td>BigScience</td>
  <td>Encoder-Decoder</td>
  <td>English</td>
  <td><a href="https://github.com/bigscience-workshop/t-zero/blob/master/LICENSE">✅</a></td>
  <td>First open-source real competitor to GPT-3. Change my mind!</td>
</tr>
<tr>
  <td>T0_3B</td>
  <td>3e9</td>
  <td>21/10</td>
  <td><a href="https://arxiv.org/abs/2110.08207">Paper</a></td>
  <td><a href="https://huggingface.co/bigscience/T0_3B">Model</a></td>
  <td>BigScience</td>
  <td>Encoder-Decoder</td>
  <td>English</td>
  <td><a href="https://github.com/bigscience-workshop/t-zero/blob/master/LICENSE">✅</a></td>
  <td>Like T0pp but smaller and not better</td>
</tr>
<tr>
  <td>T0</td>
  <td>11e9</td>
  <td>21/10</td>
  <td><a href="https://arxiv.org/abs/2110.08207">Paper</a></td>
  <td><a href="https://huggingface.co/bigscience/T0">Model</a></td>
  <td>BigScience</td>
  <td>Encoder-Decoder</td>
  <td>English</td>
  <td><a href="https://github.com/bigscience-workshop/t-zero/blob/master/LICENSE">✅</a></td>
  <td>Like T0pp but not smaller and not better</td>
</tr>
<tr>
  <td>OPT-IML-30B</td>
  <td>30e9</td>
  <td>22/12</td>
  <td><a href="https://arxiv.org/abs/2212.12017">Paper</a></td>
  <td><a href="https://github.com/facebookresearch/metaseq/tree/main/projects/OPT-IML">Model</a></td>
  <td>Meta</td>
  <td>Decoder-only</td>
  <td>English (?)</td>
  <td>❌</td>
  <td>December 2022 is a crazy month</td>
</tr>
<tr>
  <td>OPT-IML-Max-30B</td>
  <td>30e9</td>
  <td>22/12</td>
  <td><a href="https://arxiv.org/abs/2212.12017">Paper</a></td>
  <td><a href="https://github.com/facebookresearch/metaseq/tree/main/projects/OPT-IML">Model</a></td>
  <td>Meta</td>
  <td>Decoder-only</td>
  <td>English (?)</td>
  <td>❌</td>
  <td>Like OPT-IML-30B but morer tasks</td>
</tr>

<tr>
  <td>GPT-JT</td>
  <td>6e9</td>
  <td>22/11</td>
  <td><a href="https://www.together.xyz/blog/releasing-v1-of-gpt-jt-powered-by-open-source-ai">Blog Post</a></td>
  <td><a href="https://huggingface.co/togethercomputer/GPT-JT-6B-v1">Model</a></td>
  <td><a href="https://www.together.xyz/">Together</a></td>
  <td>Decoder-only</td>
  <td>English</td>
  <td>❔</td>
  <td>They have an <a href="https://huggingface.co/spaces/togethercomputer/GPT-JT"> online demo</a></td>
</tr>

<tr>
  <td>GPT-J 6B</td>
  <td>6e9</td>
  <td>21/08</td>
  <td><a href="https://arankomatsuzaki.wordpress.com/2021/06/04/gpt-j/">Blog</a>, <a href="https://github.com/kingoflolz/mesh-transformer-jax">GitHub</a></td>
  <td><a href="https://huggingface.co/EleutherAI/gpt-j-6B">Model</a></td>
  <td><a href="https://www.together.xyz/">Together</a></td>
  <td>Decoder-only</td>
  <td>English</td>
  <td>✅</td>
  <td>More popular than T0pp for some reason. Go T5!</a></td>
</tr>

<tr>
  <td>BLOOMZ</td>
  <td>176e9</td>
  <td>22/11</td>
  <td><a href="https://arxiv.org/abs/2211.01786">Paper</a></td>
  <td><a href="https://huggingface.co/bigscience/bloomz">Model</a></td>
  <td><a href="https://bigscience.huggingface.co/">BigScience</a></td>
  <td>Decoder-only</td>
  <td>Multilingual</td>
  <td><a href="https://huggingface.co/spaces/bigscience/license">❔</a></td>
  <td>Run if on CPU if you want your eyes to bleed, and on GPU if you want your eyes to explode. Prefer BLOOMZ-mt for non-English prompts. </td>
</tr>

<tr>
  <td>mT0-xxl</td>
  <td>13e9</td>
  <td>22/11</td>
  <td><a href="https://arxiv.org/abs/2211.01786">Paper</a></td>
  <td><a href="https://huggingface.co/bigscience/mt0-xxl">Model</a></td>
  <td><a href="https://bigscience.huggingface.co/">BigScience</a></td>
  <td>Encoder-Decoder</td>
  <td>Multilingual</td>
  <td><a href="https://huggingface.co/spaces/bigscience/license">❔</a></td>
  <td>Prefer mT0-xxl-mt for non-English prompts. </td>
</tr>

<tr>
  <td>BLOOMZ-mt</td>
  <td>176e9</td>
  <td>22/11</td>
  <td><a href="https://arxiv.org/abs/2211.01786">Paper</a></td>
  <td><a href="https://huggingface.co/bigscience/bloomz-mt">Model</a></td>
  <td><a href="https://bigscience.huggingface.co/">BigScience</a></td>
  <td>Decoder-only</td>
  <td>Multilingual</td>
  <td><a href="https://huggingface.co/spaces/bigscience/license">❔</a></td>
  <td>Does "Crosslingual Generalization" means it also understands Klingon?</td>
</tr>

<tr>
  <td>mT0-xxl-mt</td>
  <td>13e9</td>
  <td>22/11</td>
  <td><a href="https://arxiv.org/abs/2211.01786">Paper</a></td>
  <td><a href="https://huggingface.co/bigscience/mt0-xxl-mt">Model</a></td>
  <td><a href="https://bigscience.huggingface.co/">BigScience</a></td>
  <td>Encoder-Decoder</td>
  <td>Multilingual</td>
  <td><a href="https://huggingface.co/spaces/bigscience/license">❔</a></td>
  <td>I can't undertand how BigScience isn't better-known.</td>
</tr>

</table>
