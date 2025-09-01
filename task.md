# QA Checklist

| Issue                                                                 | Done | Reason/Notes |
|-----------------------------------------------------------------------|------|-------------|
| Group Chat - Voice Message Box is too large. Play Button not centered | [ ]  | UI layout issue; needs proper constraints and alignment. |
| Tablet - Only staff accounts can create groups. No groups shown if not logged in as staff. | [ ]  | Staff permission logic; should show groups for all users. |
| File sending not working                                              | [ ]  | File picker or upload logic may be broken. |
| Mobile - Group Chat shows 'Please Select a Person' after joining group | [ ]  | Selected person logic not set on join. |
| Sent message appears as a reply only once                             | [ ]  | Message reply logic or state update issue. |
| Group Create - No cross icon to remove group photo                    | [ ]  | Missing UI element for photo removal. |
| Group Chat - Enter key adds new line instead of sending message       | [ ]  | TextField should send on Enter, new line on Shift+Enter. |
| Online Chat - Name search does not filter                             | [ ]  | Search/filter logic not applied to chat list. |
| Online Chat - Voice Message Box is too large. Play Button not centered| [ ]  | UI layout issue; needs proper constraints and alignment. |
| Online Chat - Latest sent message does not scroll to top              | [ ]  | Scroll controller not updated after sending. |
| Online Chat - Message notification not shown on new message           | [ ]  | Notification logic missing or not triggered. |
| Online Chat - Enter key adds new line instead of sending message      | [ ]  | TextField should send on Enter, new line on Shift+Enter. |
| Online Chat - Sent messages only appear after tab switch              | [ ]  | State not refreshed after sending; needs immediate update. |
