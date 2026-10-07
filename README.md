<p align="center">
  <img src="https://raw.githubusercontent.com/MIXYANG/MIXYANG/main/assets/header.svg" alt="MIXYANG — Go and AI agent development" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/pulseaiclub/phi">Open-source work</a> &nbsp; / &nbsp;
  <a href="mailto:ruixingxingxing@gmail.com">Say hello</a>
</p>

## A little about me / 关于我

Hi, I'm **MIXYANG**. My focus is **Go backend development and AI agents** — especially model integrations, streaming protocols, and the state that makes agent sessions work.

**Guangzhou University · School of Artificial Intelligence**  
广州大学人工智能学院 · 关注 Go 后端、AI Agent 与开源工程实践。


## Areas of focus


| Backend & protocols | Agent engineering | Engineering practice |
| :--- | :--- | :--- |
| Go · HTTP · SSE | LLM integrations · Tool calls · Session state | Regression tests · Linting · Code review |

## Selected open-source contributions

Contributing to [**phi**](https://github.com/pulseaiclub/phi), an open-source coding agent written in Go.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>01 · Session continuity</h3>
      <p>Preserved ordered Anthropic thinking, signatures, and native content across tool continuation and saved sessions, with compatibility checks and regression coverage.</p>
      <p>修复会话续接中的 thinking 状态丢失，保留原生内容顺序与签名。</p>
      <p><a href="https://github.com/pulseaiclub/phi/pull/267"><strong>Merged PR #267 →</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <h3>02 · Streaming reliability</h3>
      <p>Surfaced Anthropic error events arriving after HTTP 200, preventing partial responses from being reported as completed. Added an HTTP/SSE regression test.</p>
      <p>修复流式响应错误被忽略的问题，避免将部分输出误报为成功完成。</p>
      <p><a href="https://github.com/pulseaiclub/phi/pull/295"><strong>Merged PR #295 →</strong></a></p>
    </td>
  </tr>
</table>

## Connect / 联系

Technical conversations, interesting ideas, and open-source collaboration are welcome.

**Email:** [ruixingxingxing@gmail.com](mailto:ruixingxingxing@gmail.com)

---

<p align="center"><sub>Explore. Test. Iterate.</sub></p>
