# Telegram Types for Go (Golang)

A lightweight Go package providing type definitions for the Telegram Bot API. This library includes all the available
types, making it easier to build Telegram bots in Go with type safety.

### Features

1. Lightweight: Contains only type definitions without additional dependencies.
1. Easy to Use: Simplifies interaction with the Telegram API in Go projects.

### Installation

```bash
go get github.com/enifsoft/go-telegram-types
```

### Usage

```go
import (
"github.com/yourusername/telegram-types"
)
```

### Currently supported types

1. [x] type Chat struct{}
1. [x] type ChatFullInfo struct{}
1. [x] type Message struct{}
1. [x] type MessageEntity struct{}
1. [x] type PhotoSize struct{}
1. [x] type Update struct{}
1. [x] type User struct{}

### To Do

Complete next types:

1. [ ] type ChatPhoto struct{}
2. [ ] type Birthdate struct{}
3. [ ] type BusinessIntro struct{}
4. [ ] type BusinessLocation struct{}
5. [ ] type BusinessOpeningHours struct{}
6. [ ] type ReactionType struct{}
7. [ ] type ChatPermissions struct{}
8. [ ] type ChatLocation struct{}
9. [ ] type MessageOrigin struct{}
10. [ ] type ExternalReplyInfo struct{}
11. [ ] type TextQuote struct{}
12. [ ] type Story struct{}
13. [ ] type LinkPreviewOptions struct{}
14. [ ] type Animation struct{}
15. [ ] type Audio struct{}
16. [ ] type Document struct{}
17. [ ] type PaidMediaInfo struct{}
18. [ ] type Sticker struct{}
19. [ ] type Video struct{}
20. [ ] type VideoNote struct{}
21. [ ] type Voice struct{}
22. [ ] type Contact struct{}
23. [ ] type Dice struct{}
24. [ ] type Game struct{}
25. [ ] type Poll struct{}
26. [ ] type Venue struct{}
27. [ ] type Location struct{}
28. [ ] type Invoice struct{}
29. [ ] type SuccessfulPayment struct{}
30. [ ] type RefundedPayment struct{}
31. [ ] type UsersShared struct{}
32. [ ] type ChatShared struct{}
33. [ ] type WriteAccessAllowed struct{}
34. [ ] type PassportData struct{}
35. [ ] type ProximityAlertTriggered struct{}
36. [ ] type ChatBoostAdded struct{}
37. [ ] type ChatBackground struct{}
38. [ ] type ForumTopicCreated struct{}
39. [ ] type ForumTopicEdited struct{}
40. [ ] type ForumTopicClosed struct{}
41. [ ] type ForumTopicReopened struct{}
42. [ ] type GeneralForumTopicHidden struct{}
43. [ ] type GeneralForumTopicUnhidden struct{}
44. [ ] type GiveawayCreated struct{}
45. [ ] type Giveaway struct{}
46. [ ] type GiveawayWinners struct{}
47. [ ] type GiveawayCompleted struct{}
48. [ ] type VideoChatScheduled struct{}
49. [ ] type VideoChatStarted struct{}
50. [ ] type VideoChatEnded struct{}
51. [ ] type VideoChatParticipantsInvited struct{}
52. [ ] type WebAppData struct{}
53. [ ] type InlineKeyboardMarkup struct{}
54. [ ] type MaybeInaccessibleMessage struct{}
55. [ ] type MessageAutoDeleteTimerChanged struct{}
56. [ ] type BusinessConnection struct{}
57. [ ] type BusinessMessagesDeleted struct{}
58. [ ] type MessageReactionUpdated struct{}
59. [ ] type MessageReactionCountUpdated struct{}
60. [ ] type InlineQuery struct{}
61. [ ] type ChosenInlineResult struct{}
62. [ ] type CallbackQuery struct{}
63. [ ] type ShippingQuery struct{}
64. [ ] type PreCheckoutQuery struct{}
65. [ ] type PaidMediaPurchased struct{}
66. [ ] type PollAnswer struct{}
67. [ ] type ChatMemberUpdated struct{}
68. [ ] type ChatJoinRequest struct{}
69. [ ] type ChatBoostUpdated struct{}
70. [ ] type ChatBoostRemoved struct{}
71. [ ] type ReplyParameters struct{}
72. [ ] type InputFile struct{}