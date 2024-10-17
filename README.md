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
1. [x] type MessageOrigin struct{}
1. [x] type PhotoSize struct{}
1. [x] type Update struct{}
1. [x] type User struct{}

### To Do

Complete next types:

1. [ ] type ChatPhoto struct{}
1. [ ] type Birthdate struct{}
1. [ ] type BusinessIntro struct{}
1. [ ] type BusinessLocation struct{}
1. [ ] type BusinessOpeningHours struct{}
1. [ ] type ReactionType struct{}
1. [ ] type ChatPermissions struct{}
1. [ ] type ChatLocation struct{}
1. [ ] type ExternalReplyInfo struct{}
1. [ ] type TextQuote struct{}
1. [ ] type Story struct{}
1. [ ] type LinkPreviewOptions struct{}
1. [ ] type Animation struct{}
1. [ ] type Audio struct{}
1. [ ] type Document struct{}
1. [ ] type PaidMediaInfo struct{}
1. [ ] type Sticker struct{}
1. [ ] type Video struct{}
1. [ ] type VideoNote struct{}
1. [ ] type Voice struct{}
1. [ ] type Contact struct{}
1. [ ] type Dice struct{}
1. [ ] type Game struct{}
1. [ ] type Poll struct{}
1. [ ] type Venue struct{}
1. [ ] type Location struct{}
1. [ ] type Invoice struct{}
1. [ ] type SuccessfulPayment struct{}
1. [ ] type RefundedPayment struct{}
1. [ ] type UsersShared struct{}
1. [ ] type ChatShared struct{}
1. [ ] type WriteAccessAllowed struct{}
1. [ ] type PassportData struct{}
1. [ ] type ProximityAlertTriggered struct{}
1. [ ] type ChatBoostAdded struct{}
1. [ ] type ChatBackground struct{}
1. [ ] type ForumTopicCreated struct{}
1. [ ] type ForumTopicEdited struct{}
1. [ ] type ForumTopicClosed struct{}
1. [ ] type ForumTopicReopened struct{}
1. [ ] type GeneralForumTopicHidden struct{}
1. [ ] type GeneralForumTopicUnhidden struct{}
1. [ ] type GiveawayCreated struct{}
1. [ ] type Giveaway struct{}
1. [ ] type GiveawayWinners struct{}
1. [ ] type GiveawayCompleted struct{}
1. [ ] type VideoChatScheduled struct{}
1. [ ] type VideoChatStarted struct{}
1. [ ] type VideoChatEnded struct{}
1. [ ] type VideoChatParticipantsInvited struct{}
1. [ ] type WebAppData struct{}
1. [ ] type InlineKeyboardMarkup struct{}
1. [ ] type MaybeInaccessibleMessage struct{}
1. [ ] type MessageAutoDeleteTimerChanged struct{}
1. [ ] type BusinessConnection struct{}
1. [ ] type BusinessMessagesDeleted struct{}
1. [ ] type MessageReactionUpdated struct{}
1. [ ] type MessageReactionCountUpdated struct{}
1. [ ] type InlineQuery struct{}
1. [ ] type ChosenInlineResult struct{}
1. [ ] type CallbackQuery struct{}
1. [ ] type ShippingQuery struct{}
1. [ ] type PreCheckoutQuery struct{}
1. [ ] type PaidMediaPurchased struct{}
1. [ ] type PollAnswer struct{}
1. [ ] type ChatMemberUpdated struct{}
1. [ ] type ChatJoinRequest struct{}
1. [ ] type ChatBoostUpdated struct{}
1. [ ] type ChatBoostRemoved struct{}
1. [ ] type ReplyParameters struct{}
1. [ ] type InputFile struct{}