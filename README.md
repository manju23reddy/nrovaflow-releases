# Nrova Flow downloads

Nrova Flow is a visual review tool: point at the running product, explain what should change, and review the result.

This repository holds the downloads only. Get the latest build from [Releases](../../releases).

## Requirements

- A Mac with Apple Silicon (M1 or later), macOS 12 or newer
- There is no Intel Mac or Windows build yet

## Install

1. Download the `.dmg` from the latest release and open it.
2. Drag **Nrova Flow** to **Applications**.
3. Open it. macOS will block the first launch, because this early build is not notarized by Apple yet.
4. Go to **System Settings → Privacy & Security**, scroll down, and click **Open Anyway**.

If "Open Anyway" does not appear, run this once in Terminal:

```bash
xattr -dr com.apple.quarantine "/Applications/Nrova Flow.app"
```

## First launch

- The app downloads a browser for its live preview the first time it starts. This needs a network connection and takes a minute.
- This is an early test build. Expect rough edges.
