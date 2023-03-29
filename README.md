# USB Mailbox Friends Alert

## USB Device Info

VID: `1D34` (Dream Cheeky)

PID: `000A` (Mailbox Friends Alert)

## HID Set Report

| Action          | Data                         |
| --------------- | ---------------------------- |
| Set LED         | `00_RR_GG_BB_00_00_00_1F_05` |
| LED 1 (disable) | `00_07_3F_00_00_00_00_1F_03` |
| LED 1 (enable)  | `00_1F_02_00_5F_00_00_1F_03` |
| LED 2 (disable) | `00_07_3F_00_00_00_00_1F_04` |
| LED 2 (enable)  | `00_00_02_00_5F_00_00_1F_04` |

## References

- [Product page](https://web.archive.org/web/20230329100321/http://usb.brando.com/usb-mail-box-friends-alert_p01725c0035d015.html)
- [WebMail Notifier 2](https://web.archive.org/web/20230329095933/https://usb.brando.com/file/WebMailNotifier2.zip)
- <https://github.com/onelife/PyUsbLamp>
