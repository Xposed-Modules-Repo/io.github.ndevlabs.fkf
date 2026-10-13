# ForceKill Focused

LSPosed module for Samsung **OneUI 8.5** that adds a **Force kill** item
to the per-task popup menu in Recents, directly below **Keep open**.

Tapping it swipe-dismisses the task card, force-stops that one app only,
and removes its Recents card.

## Requirements

- Samsung device on OneUI 8.5
- Root via Magisk + Zygisk + LSPosed, or KernelSU + ZygiskNext + LSPosed

## Install

1. Install the APK from the release below.
2. In LSPosed Manager, enable **ForceKill Focused**.
3. Set the scope to `com.android.systemui` and
   `com.sec.android.app.launcher`.
4. Reboot, or restart SystemUI.
5. Open Recents, tap a task's icon, then tap **Force kill**.

## Source & support

https://github.com/1ndevelopment/lsp-forcekill-focused
