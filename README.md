# Codex Proxy — releases

This repository only hosts the release binaries of Codex Proxy, a local proxy that lets
[OpenAI Codex CLI](https://github.com/openai/codex) use an Apigee LLM gateway.

## Install (Windows)

1. Download `codex-proxy_<version>_windows_amd64.zip` from the [latest release](../../releases/latest)
   (`windows_arm64` for ARM laptops).
2. Extract `codex-proxy.exe` to a permanent folder, e.g. `%LOCALAPPDATA%\Programs\codex-proxy\`.
3. Run `codex-proxy.exe init` once and follow the prompts.

## Update

```powershell
codex-proxy.exe update
```

The dashboard also tells you when a new version is available (press `u`). Every download is verified
against the release's `checksums.txt`.
