# LLM之核心-模型

![avator](../10%20Assets/Model/fig2_updated_time_line.png)

### LLM 列表

<table class="tg">
<thead>
  <tr>
    <th class="tg-nrix" align="center" rowspan="2">Category</th>
    <th class="tg-baqh" align="center" rowspan="2">model</th>
    <th class="tg-0lax" align="center" rowspan="2">Release Time</th>
    <th class="tg-baqh" align="center" rowspan="2">Size(B)</th>
    <th class="tg-0lax" align="center" rowspan="2">Link</th>
  </tr>
  <tr>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix" align="center" rowspan="33">Publicly <br>Accessbile</td>
    <td class="tg-baqh" align="center">T5</td>
    <td class="tg-0lax" align="center">2019/10</td>
    <td class="tg-baqh" align="center">11</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/1910.10683">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">mT5</td>
    <td class="tg-0lax" align="center">2021/03</td>
    <td class="tg-baqh" align="center">13</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2010.11934">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">PanGu-α</td>
    <td class="tg-0lax" align="center">2021/05</td>
    <td class="tg-baqh" align="center">13</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2104.12369">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">CPM-2</td>
    <td class="tg-0lax" align="center">2021/05</td>
    <td class="tg-baqh" align="center">198</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2106.10715">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">T0</td>
    <td class="tg-0lax" align="center">2021/10</td>
    <td class="tg-baqh" align="center">11</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2110.08207">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">GPT-NeoX-20B</td>
    <td class="tg-0lax" align="center">2022/02</td>
    <td class="tg-baqh" align="center">20</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2204.06745">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">CodeGen</td>
    <td class="tg-0lax" align="center">2022/03</td>
    <td class="tg-baqh" align="center">16</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2203.13474">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Tk-Instruct</td>
    <td class="tg-0lax" align="center">2022/04</td>
    <td class="tg-baqh" align="center" align="center">11</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2204.07705">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">UL2</td>
    <td class="tg-0lax" align="center">2022/02</td>
    <td class="tg-baqh" align="center">20</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2205.05131">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">OPT</td>
    <td class="tg-0lax" align="center">2022/05</td>
    <td class="tg-baqh" align="center">175</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2205.01068">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">YaLM</td>
    <td class="tg-0lax" align="center">2022/06</td>
    <td class="tg-baqh" align="center">100</td>
    <td class="tg-0lax" align="center"><a href="https://github.com/yandex/YaLM-100B">GitHub</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">NLLB</td>
    <td class="tg-0lax" align="center">2022/07</td>
    <td class="tg-baqh" align="center">55</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2207.04672">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">BLOOM</td>
    <td class="tg-0lax" align="center">2022/07</td>
    <td class="tg-baqh" align="center">176</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2211.05100">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">GLM</td>
    <td class="tg-0lax" align="center">2022/08</td>
    <td class="tg-baqh" align="center">130</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2210.02414">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Flan-T5</td>
    <td class="tg-0lax" align="center">2022/10</td>
    <td class="tg-baqh" align="center">11</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2210.11416">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">mT0</td>
    <td class="tg-0lax" align="center">2022/11</td>
    <td class="tg-baqh" align="center">13</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2211.01786">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Galatica</td>
    <td class="tg-0lax" align="center" align="center" align="center">2022/11</td>
    <td class="tg-baqh" align="center" align="center">120</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2211.09085">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">BLOOMZ</td>
    <td class="tg-0lax" align="center">2022/11</td>
    <td class="tg-baqh" align="center">176</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2211.01786">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">OPT-IML</td>
    <td class="tg-0lax" align="center">2022/12</td>
    <td class="tg-baqh" align="center">175</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2212.12017">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Pythia</td>
    <td class="tg-0lax" align="center">2023/01</td>
    <td class="tg-baqh" align="center">12</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2304.01373">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">LLaMA</td>
    <td class="tg-0lax" align="center">2023/02</td>
    <td class="tg-baqh" align="center">65</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2302.13971v1">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Vicuna</td>
    <td class="tg-0lax" align="center">2023/03</td>
    <td class="tg-baqh" align="center">13</td>
    <td class="tg-0lax" align="center"><a href="https://lmsys.org/blog/2023-03-30-vicuna/">Blog</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">ChatGLM</td>
    <td class="tg-0lax" align="center">2023/03</td>
    <td class="tg-baqh" align="center">6</td>
    <td class="tg-0lax" align="center"><a href="https://github.com/THUDM/ChatGLM-6B">GitHub</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">CodeGeeX</td>
    <td class="tg-0lax" align="center">2023/03</td>
    <td class="tg-baqh" align="center">13</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2303.17568">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Alpaca</td>
    <td class="tg-0lax" align="center">2023/03</td>
    <td class="tg-baqh" align="center">7</td>
    <td class="tg-0lax" align="center"><a href="https://crfm.stanford.edu/2023/03/13/alpaca.html">Blog</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Koala</td>
    <td class="tg-0lax" align="center">2023/04</td>
    <td class="tg-baqh" align="center">13</td>
    <td class="tg-0lax" align="center"><a href="https://bair.berkeley.edu/blog/2023/04/03/koala/">Blog</a></td>
  </tr>
    <tr>
    <td class="tg-baqh" align="center">Mistral</td>
    <td class="tg-0lax" align="center">2023/09</td>
    <td class="tg-baqh" align="center">7</td>
    <td class="tg-0lax" align="center"><a href="https://mistral.ai/news/announcing-mistral-7b/">Blog</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Qwen2.5</td>
    <td class="tg-0lax" align="center">2024/04</td>
    <td class="tg-baqh" align="center">72</td>
    <td class="tg-0lax" align="center"><a href="https://github.com/QwenLM/Qwen2.5">GitHub</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">DeepSeek-V2</td>
    <td class="tg-0lax" align="center">2024/05</td>
    <td class="tg-baqh" align="center">236</td>
    <td class="tg-0lax" align="center"><a href="https://github.com/deepseek-ai/DeepSeek-V2">GitHub</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">LLaMA3</td>
    <td class="tg-0lax" align="center">2024/04</td>
    <td class="tg-baqh" align="center">405</td>
    <td class="tg-0lax" align="center"><a href="https://github.com/meta-llama/llama3">GitHub</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Mixtral-8x7B</td>
    <td class="tg-0lax" align="center">2023/12</td>
    <td class="tg-baqh" align="center">47</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/pdf/2401.04088.pdf">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Gemma</td>
    <td class="tg-0lax" align="center">2024/02</td>
    <td class="tg-baqh" align="center">27</td>
    <td class="tg-0lax" align="center"><a href="https://github.com/google/gemma_pytorch">GitHub</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Phi-3</td>
    <td class="tg-0lax" align="center">2024/04</td>
    <td class="tg-baqh" align="center">14</td>
    <td class="tg-0lax" align="center"><a href="https://github.com/microsoft/Phi-3-mini">GitHub</a></td>
  </tr>
  <tr>
    <td class="tg-nrix" align="center" rowspan="32">Closed<br>Source</td>
    <td class="tg-baqh" align="center">GShard</td>
    <td class="tg-0lax" align="center">2020/01</td>
    <td class="tg-baqh" align="center" align="center">600</td>
    <td class="tg-0lax" align="center"><a href="http://arxiv.org/abs/2006.16668v1">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">GPT-3</td>
    <td class="tg-0lax" align="center">2020/05</td>
    <td class="tg-baqh" align="center">175</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2005.14165">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">LaMDA</td>
    <td class="tg-0lax" align="center">2021/05</td>
    <td class="tg-baqh" align="center">137</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2201.08239">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">HyperCLOVA</td>
    <td class="tg-0lax" align="center">2021/06</td>
    <td class="tg-baqh" align="center">82</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2109.04650">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Codex</td>
    <td class="tg-0lax" align="center">2021/07</td>
    <td class="tg-baqh" align="center">12</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2107.03374">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">ERNIE 3.0</td>
    <td class="tg-0lax" align="center" align="center">2021/07</td>
    <td class="tg-baqh" align="center">10</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2107.02137">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Jurassic-1</td>
    <td class="tg-0lax" align="center">2021/08</td>
    <td class="tg-baqh" align="center">178</td>
    <td class="tg-0lax" align="center"><a href="https://assets.website-files.com/60fd4503684b466578c0d307/61138924626a6981ee09caf6_jurassic_tech_paper.pdf">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center" align="center">FLAN</td>
    <td class="tg-0lax" align="center">2021/10</td>
    <td class="tg-baqh" align="center">137</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2109.01652">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">MT-NLG</td>
    <td class="tg-0lax" align="center">2021/10</td>
    <td class="tg-baqh" align="center">530</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2201.11990">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Yuan 1.0</td>
    <td class="tg-0lax" align="center">2021/10</td>
    <td class="tg-baqh" align="center">245</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2110.04725">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Anthropic</td>
    <td class="tg-0lax" align="center">2021/12</td>
    <td class="tg-baqh" align="center">52</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2112.00861">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">WebGPT</td>
    <td class="tg-0lax" align="center">2021/12</td>
    <td class="tg-baqh" align="center">175</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2112.09332">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Gopher</td>
    <td class="tg-0lax" align="center">2021/12</td>
    <td class="tg-baqh" align="center">280</td>
    <td class="tg-0lax" align="center"><a href="http://arxiv.org/abs/2112.11446v2">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">ERNIE 3.0 Titan</td>
    <td class="tg-0lax" align="center">2021/12</td>
    <td class="tg-baqh" align="center">260</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2112.12731">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">GLaM</td>
    <td class="tg-0lax" align="center">2021/12</td>
    <td class="tg-baqh" align="center">1200</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2112.06905">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">InstructGPT</td>
    <td class="tg-0lax" align="center">2022/01</td>
    <td class="tg-baqh" align="center">175</td>
    <td class="tg-0lax" align="center"><a href="http://arxiv.org/abs/2203.02155v1">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">AlphaCode</td>
    <td class="tg-0lax" align="center">2022/02</td>
    <td class="tg-baqh" align="center">41</td>
    <td class="tg-0lax" align="center"><a href="http://arxiv.org/abs/2203.07814v1">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Chinchilla</td>
    <td class="tg-0lax" align="center">2022/03</td>
    <td class="tg-baqh" align="center">70</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2203.15556">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">PaLM</td>
    <td class="tg-0lax" align="center">2022/04</td>
    <td class="tg-baqh" align="center">540</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2204.02311">Paper</a></td>
    <tr>
    <td class="tg-baqh" align="center">Cohere</td>
    <td class="tg-0lax" align="center">2022/06</td>
    <td class="tg-baqh" align="center">54</td>
    <td class="tg-0lax" align="center"><a href="https://cohere.ai/">Homepage</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">AlexaTM</td>
    <td class="tg-0lax" align="center">2022/08</td>
    <td class="tg-baqh" align="center">20</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2208.01448">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Luminous</td>
    <td class="tg-0lax" align="center">2022/09</td>
    <td class="tg-baqh" align="center">70</td>
    <td class="tg-0lax" align="center"><a href="https://docs.aleph-alpha.com/docs/introduction/luminous/">Docs</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Sparrow</td>
    <td class="tg-0lax" align="center">2022/09</td>
    <td class="tg-baqh" align="center">70</td>
    <td class="tg-0lax" align="center"><a href="http://arxiv.org/abs/2209.14375v1">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">WeLM</td>
    <td class="tg-0lax" align="center">2022/09</td>
    <td class="tg-baqh" align="center">10</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2209.10372">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">U-PaLM</td>
    <td class="tg-0lax" align="center">2022/10</td>
    <td class="tg-baqh" align="center">540</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2210.11399">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Flan-PaLM</td>
    <td class="tg-0lax" align="center">2022/10</td>
    <td class="tg-baqh" align="center" align="center">540</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2210.11416">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Flan-U-PaLM</td>
    <td class="tg-0lax" align="center">2022/10</td>
    <td class="tg-baqh" align="center">540</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2210.11416">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">GPT-4</td>
    <td class="tg-0lax" align="center">2023/3</td>
    <td class="tg-baqh" align="center">-</td>
    <td class="tg-0lax" align="center"><a href="http://arxiv.org/abs/2303.08774v2">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">PanGU-Σ</td>
    <td class="tg-0lax" align="center">2023/3</td>
    <td class="tg-baqh" align="center">1085</td>
    <td class="tg-0lax" align="center"><a href="https://arxiv.org/abs/2303.10845">Paper</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">GPT-4o</td>
    <td class="tg-0lax" align="center">2024/05</td>
    <td class="tg-baqh" align="center">-</td>
    <td class="tg-0lax" align="center"><a href="https://openai.com/index/hello-gpt-4o/">Blog</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Claude 3</td>
    <td class="tg-0lax" align="center">2024/03</td>
    <td class="tg-baqh" align="center">-</td>
    <td class="tg-0lax" align="center"><a href="https://www.anthropic.com/claude">Blog</a></td>
  </tr>
  <tr>
    <td class="tg-baqh" align="center">Gemini 1.5</td>
    <td class="tg-0lax" align="center">2024/02</td>
    <td class="tg-baqh" align="center">-</td>
    <td class="tg-0lax" align="center"><a href="https://deepmind.google/technologies/gemini/">Blog</a></td>
  </tr>
</tbody>
</table>

##### 其他资源

| 资源描述      | 来源   | 相关资源                                                                    |
| ------------- | ------ | --------------------------------------------------------------------------- |
| LLM survey    | github | [source](https://github.com/RUCAIBox/LLMSurvey)                                |
| LLM最新进展   | 微信   | [LLM最新进展](https://mp.weixin.qq.com/s/IkqwITZ_nqnCOAPLX7xv7A)               |
| MOE发展史     | 微信   | [MOE发展史](https://mp.weixin.qq.com/s/LoKmxYB9K3X4vpTg-STVUg)                 |
| MOE提升表现   | 微信   | [MOE让8个7B模型效果逼近70B](https://mp.weixin.qq.com/s/UAytYCGGgiYTnYiBJHGHTQ) |
| MOE代码解读   | 微信   | [MOE代码解读](https://mp.weixin.qq.com/s/PaHmvwbXcZJ3Cn-2NMcLxA)               |
| LLaMA代码解读 | 微信   | [LLaMA代码解读](https://mp.weixin.qq.com/s/oO7nkY0Fcgd4Y7en3Sx2Xw)             |
