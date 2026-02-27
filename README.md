# OpenStreamTool
<div align="center">

<h1>
  <img src="https://img.shields.io/badge/StreamToolV2-v2.0-9146FF?style=for-the-badge&logo=twitch&logoColor=white" alt="StreamToolV2">
</h1>

<h2>The Only Streaming Tool You'll Ever Need</h2>

<p>Replace StreamElements, Streamlabs, and Streamer.bot with one powerful platform</p>

[Explore Features](#-all-in-one-feature-breakdown) • [Why StreamToolV2](#-why-choose-streamtoolv2) • [Get Started](#-getting-started)

[![Twitch](https://img.shields.io/badge/Twitch-Integration-9146FF?style=for-the-badge&logo=twitch&logoColor=white)](https://twitch.tv)
[![OBS](https://img.shields.io/badge/OBS-Studio-302B31?style=for-the-badge&logo=obsstudio&logoColor=white)](https://obsproject.com)
[![VTS](https://img.shields.io/badge/VTube-Studio-FF69B4?style=for-the-badge)](https://denchisoft.com/)
[![Discord](https://img.shields.io/badge/Discord-Webhooks-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com)

</div>

---

## Table of Contents

- [What is StreamToolV2?](#what-is-streamtoolv2)
- [Why Choose StreamToolV2?](#-why-choose-streamtoolv2)
- [All-in-One Feature Breakdown](#-all-in-one-feature-breakdown)
  - [Alert Builder](#-alert-builder)
  - [Overlay Builder](#-overlay-builder)
  - [Chat Bot & Commands](#-chat-bot--commands)
  - [Interactive Games](#-interactive-games)
  - [Currency & Economy](#-currency--economy)
  - [Automation Engine](#-automation-engine)
  - [Moderation Suite](#-moderation-suite)
  - [OBS Studio Control](#-obs-studio-control)
  - [VTube Studio Integration](#-vtube-studio-integration)
  - [Polls & Community Tools](#-polls--community-tools)
  - [Timers & Scheduling](#-timers--scheduling)
  - [Analytics Dashboard](#-analytics-dashboard)
  - [Quotes & Presets](#-quotes--presets)
  - [Discord Integration](#-discord-integration)
  - [REST API](#-rest-api)
  - [Advanced Tools](#-advanced-tools)
- [Getting Started](#-getting-started)

---

## What is StreamToolV2?

**StreamToolV2** is a complete, all-in-one streaming platform that combines every tool you need into one beautiful, web-based dashboard. No more juggling five different websites, no more paying multiple subscriptions, no more wrestling with conflicting software.

With StreamToolV2, you get:
- A **full alert system** that replaces StreamElements alerts
- A **complete chat bot** that replaces Streamlabs chatbot
- A **powerful automation engine** that replaces Streamer.bot
- An **overlay builder** that eliminates need for design tools
- **OBS control** that integrates directly with your scenes
- **VTube Studio control** for VTuber streamers
- **Analytics** that rival dedicated analytics platforms
- And so much more...

Everything works together seamlessly, controlled from one intuitive dashboard that you can access from any device, anywhere.

---

## Why Choose StreamToolV2?

### One Tool to Rule Them All

Stop paying for multiple services. Stop switching between browser tabs. Stop wondering which tool controls what. StreamToolV2 puts everything in one place.

**Replace all of these with StreamToolV2:**
- ❌ StreamElements alerts → ✅ Built-in Alert Builder
- ❌ Streamlabs chatbot → ✅ Complete Command System
- ❌ Streamer.bot automations → ✅ Visual Automation Builder
- ❌ Overlay tools like NerdOrDie → ✅ Overlay Builder
- ❌ OBS plugins for control → ✅ Native OBS Integration
- ❌ Themed.net or similar → ✅ Currency & Games
- ❌ Tweet Alerts/Clutch -> ✅ Event Notifications
- ❌ Discord notification bots → ✅ Built-in Webhooks
- ❌ Separate music bots → ✅ Spotify/YouTube Integration (coming)

### Save Money, Gain Features

- **No subscription fees** for basic features
- **No tiered pricing** - you get everything
- **No premium alerts** - upload unlimited custom alerts
- **No currency limits** - create unlimited currencies
- **No command caps** - build as many as you want

### Built for the Future

StreamToolV2 is built on modern, open-source technology that's constantly evolving. Regular updates add new features based on community feedback. Plus, our plugin system (coming soon) will let the community build and share custom extensions.

---

## All-in-One Feature Breakdown

### Alert Builder

**Replace StreamElements alerts completely with our powerful Alert Builder.**

#### What is the Alert Builder?
The Alert Builder is a complete system for creating, managing, and displaying alerts on your stream. Every time someone follows, subscribes, raids, cheers, or redeems Channel Points, you can show a custom alert with images, animations, and sounds.

#### Alert Types Supported

**Follower Alerts**
- Triggered every time you get a new follower
- Display follower name and avatar
- Show total follower count
- Customizable message templates

**Subscription Alerts**
- Triggered on new subscriptions
- Differentiate between Tier 1, Tier 2, and Tier 3
- Display sub streak and months
- Show cumulative sub count
- Handle resubs specially

**Subscription Gift Alerts**
- Triggered when someone gifts subs
- Show gift count (single, 5, 10, 25)
- Display recipient names (configurable)
- Celebrate mass gifts uniquely

**Raid Alerts**
- Triggered when raided
- Show raider name and avatar
- Display viewer count
- Show incoming raid message
- Trigger pre-raid and post-raid actions

**Cheer (Bits) Alerts**
- Triggered on any cheer
- Set minimum cheer threshold
- Show bit amount and message
- Scale effects based on amount
- Special alerts for big cheers

**Channel Points Alerts**
- Triggered when rewards are redeemed
- Show reward name and cost
- Display redeeming user
- Show custom user input (if any)
- Handle different rewards uniquely

#### Customization Options

**Visual Customization**
- Upload custom images for each alert type
- Support for GIF animations (any size)
- Set exact display duration (0.5s to 60s+)
- Adjust alert size and scale
- Set position (center, top, bottom, corners)
- Border and shadow effects
- Background colors and gradients
- Text font, size, and color
- Layout templates (vertical, horizontal, compact)

**Audio Customization**
- Upload custom sound files (MP3, WAV, OGG)
- Set volume per alert type (0-100%)
- Fade in/out effects
- Sound duration limiting
- Different sounds for different tiers

**Animation Options**
- Slide-in from any direction
- Fade-in/fade-out
- Bounce and elastic effects
- Scale animations
- Shake and wobble effects
- Combining multiple animations
- Custom CSS animations for advanced users

**Message Templates**
Use variables to create dynamic alert messages:
- `$user` - User's display name
- `$amount` - Sub tier, bit amount, raid size, etc.
- `$total` - Total followers, subs, etc.
- `$message` - User's message (for cheers, raids)
- `$currency` - Currency balance
- And many more variables

#### Alert Queue System

**Smart Queuing**
Never have alerts overlap or miss events again.

**Priority System**
Higher priority events cut to the front:
- Raids (highest priority)
- Tier 3 subs
- Tier 2 subs
- Tier 1 subs
- Subscription gifts
- Cheers
- Follows
- Low-tier redemptions

**Queue Settings**
- Maximum concurrent alerts (show multiple at once)
- Delay between alerts (prevent chaos)
- Queue names (different queues for different events)
- Auto-clear old events
- Manual queue control (skip, clear, pause)

**Queue Visualization**
- See upcoming alerts in dashboard
- Reorder queue priority
- Remove individual alerts
- Preview next alert
- Queue history

#### Testing & Preview

**Before Going Live**
- Test any alert with custom data
- Preview image, sound, and animation
- Test queue behavior
- Simulate rapid events
- Check alert timing
- Verify all variables work

**While Streaming**
- See what's currently displaying
- Monitor queue status
- Skip current alert
- Pause/resume alert queue
- Clear queue with one click

#### Advanced Features

**Conditional Alerts**
- Show different alerts based on tier
- Special alerts for milestones (100th follower, etc.)
- Different images for different amounts
- Time-based alert variations (day/night)

**Alert Groups**
- Bundle multiple events together
- "Recent follower" alert (show last 5 followers)
- "Sub train" alerts (combine recent subs)
- "Bit leaderboard" (top cheerers of stream)

**Variations**
- Random alert from set of options
- Weighted random (some alerts more common)
- Sequential alert rotation
- Time-based variations

#### Preset Alert Libraries
Coming soon - community-shared alert packs you can import with one click.

---

### Overlay Builder

**Eliminate need for external overlay services like StreamElements overlays.**

#### What is the Overlay Builder?
The Overlay Builder lets you create beautiful, custom overlays directly in your browser. Add them to OBS with a single URL. No HTML/CSS knowledge required (but you can use it if you want!).

#### Overlay Types

**Alert Box Overlay**
Your alert display that appears on stream.
- Position and size controls
- Background color/transparent
- Test alerts right in overlay
- Queue display (optional)
- Show/hide specific alert types
- Custom CSS for unique effects

**Chat Box Overlay**
Display your Twitch chat directly on stream.
- Font selection (any Google Font)
- Color scheme customization
- Background color and transparency
- Border and shadow options
- Show/hide user badges
- Show/hide emotes
- Show/hide timestamps
- Avatar display options
- Message direction (bottom-up or top-down)
- Auto-scroll speed
- Highlight mod messages
- Filter deleted messages
- Custom message styles
- Compact mode

**Event List Overlay**
Recent events timeline for your stream.
- Show recent followers (last 5, 10, 20, or all)
- Show recent subscribers with tier
- Show recent raids
- Show recent cheers
- Auto-scroll toggle
- Custom icons for each event
- Display timestamps
- Minimal or detailed modes
- Color-coded events
- Animation speed
- Position and size

**The Goal Bar**
Progress toward any goal.
- Follower goal
- Subscriber goal
- Bit goal
- Custom currency goal
- Donation goal (via redemptions)
- Animated progress bar
- Goal display options
- Celebration on goal complete
- Multiple goals simultaneously

**Counters**
Simple on-stream counters.
- Follower count
- Subscriber count
- Total views
- Chat messages
- Stream uptime
- Custom counts
- Animated counting
- Custom formats

**Now Playing**
Show current music from Spotify/YouTube.
- Album art display
- Song title and artist
- Progress bar
- Auto-update
- Multiple format options
- Scroll long titles

**Custom HTML Overlay**
For ultimate control, write your own HTML/CSS/JavaScript.
- Full code editor with syntax highlighting
- Live preview panel
- Error checking
- Variable substitution support
- WebSocket integration for live updates
- Import/export overlay code
- Save custom templates

#### Overlay Features

**Drag-and-Drop Builder**
For custom overlays, position elements visually:
- Drag elements anywhere
- Resize by dragging corners
- Snap-to-grid option
- Layer ordering (z-index)
- Group/ungroup elements
- Copy/paste elements
- Undo/redo support

**Templates Library**
Ready-to-use overlays to import instantly:
- Gaming overlays (FPS, MMO, etc.)
- Just Chatting frames
- Chat box styles (dozens of options)
- Alert box animations
- Event list designs
- Goal bar styles
- Webcam frames
- BRB screens
- Starting soon screens
- Be right back screens

**Responsive Design**
- Scale to any resolution
- Maintain aspect ratios
- Preview at different sizes
- Mobile-friendly overlays (for IRL streaming)

**Variable Support**
Use variables in overlays for dynamic content:
- `$follower_count` - Live follower count
- `$sub_count` - Live sub count
- `$latest_follower` - Most recent follower
- `$latest_raider` - Most recent raider
- `$top_cheerer` - Top bit cheerer
- `$currency_name` - Your currency name
- And many more...

**One-Click Setup**
- Generate unique overlay URL
- Copy URL to clipboard
- Add as browser source in OBS
- URL auto-refreshes when changes made
- Test overlay in browser before OBS

**Overlay Management**
- Create unlimited overlays
- Duplicate existing overlays
- Rename and organize
- Enable/disable overlays
- Export overlay code
- Share overlays with community (coming)

#### Advanced Overlay Features

**Animation Effects**
- CSS animations library
- Keyframe animation builder
- Animation timeline
- Easing functions
- Trigger animations on events
- Combine multiple animations

**Custom CSS**
- Write your own styles
- Override template styles
- CSS validation
- Live preview of changes
- CSS snippets library

**JavaScript Integration**
- Custom JavaScript for advanced effects
- WebSocket event listeners
- API access from overlays
- Interactive overlays (coming)
- Overlay-to-overlay communication

---

### Chat Bot & Commands

**Replace Streamlabs chatbot, Nightbot, Moobot, and more.**

#### Complete Chat Management

**Real-Time Chat Feed**
View and interact with chat from your browser:
- Live message updates via WebSocket
- User badges (broadcaster, mod, VIP, sub tiers)
- Proper username colors
- Emote rendering (Twitch emotes, 7TV/FFZ/BTTV coming)
- Event highlights (special messages for follows, subs, etc.)
- Delete messages with one click
- Timeout user (click username)
- Ban user (click username)
- Quote message (click to save)
- Copy message text
- Auto-scroll toggle (pause to read)
- Chat history (searchable, exportable)

**Chat Commands**
Create unlimited custom commands for your viewers.

**Command Features:**
- Custom triggers (e.g., !social, !specs, !discord)
- Response templates with variables
- Permission levels (everyone, sub, VIP, mod, broadcaster)
- Global cooldowns (e.g., once per 5 minutes)
- Per-user cooldowns (e.g., once per hour per user)
- Currency costs (require points to use)
- Whitelist/blacklist (specific users)
- Enable/disable without deleting
- Alias support (multiple triggers for same command)
- Action chain linking (trigger complex automations)

**Built-in Commands:**

| Command | Description |
|---------|-------------|
| `!slots [bet]` | Play slots game |
| `!dice [bet]` | Roll dice game |
| `!heist [bet]` | Join cooperative heist |
| `!roulette [bet] [color]` | Play roulette |
| `!8ball [question]` | Ask magic 8-ball |
| `!trivia` | Start trivia round |
| `!balance` | Check your points |
| `!quote [id]` | Get a quote |
| `!addquote [text]` | Add a quote (mod) |
| `!poll [title] [options]` | Create poll (mod) |
| `!preset [name]` | Trigger preset |
| `!leaderboard` | View top point holders |

**Command Variables in Responses:**
- `$user` - Username
- `$user.id` - User ID
- `$user.display_name` - Properly cased name
- `$currency.points` - User's balance
- `$channel` - Channel name
- `$stream.title` - Current stream title
- `$stream.game` - Current category
- `$followers` - Follower count
- `$subs` - Subscriber count
- And many more...

**Advanced Command Features:**
- Random responses (pick from list)
- Conditional responses (different for subs vs non-subs)
- Multi-step commands (conversations)
- Argument parsing (`!command arg1 arg2`)
- Permission escalation (mods can override)
- Command categories and groups
- Command usage statistics
- Search and filter commands

---

### Interactive Games

**Replace Themed.net, StreamElements games, and similar.**

#### Six Built-in Games

Each game is fully customizable with your own settings, currency, and rules.

**Slots Game**
- **How it works**: Viewers bet currency to spin a 3-reel slot machine
- **Symbols**: Use any emojis (🍒 🍋 💎 💀 7️⃣ ⭐ etc.)
- **Weights**: Control how often each symbol appears
- **Payouts**: Custom multipliers for each combination
  - Match 3 = Jackpot (up to 50x!)
  - Match 2 = Small win (2x-5x)
- **Configurable**: Min/max bet, currency type, enabled/disabled
- **Leaderboard**: Track biggest wins and total spins
- **Chat Integration**: Shows spin results and win announcements
- **Example**: `!slots 100` bets 100 points

**Dice Game**
- **How it works**: Viewer rolls 2 dice, wins if total > 7 (configurable)
- **House Rules**: You set the win condition
- **Payouts**: Typically 2x for winning, but customizable
- **Speed**: Fast rounds keep chat moving
- **Fairness**: Built-in random number generation
- **Example**: `!dice 50` bets 50 points

**Heist Game** (Cooperative)
- **Phase 1 (30 seconds)**: Viewers join the heist with their bets
- **Phase 2**: Chat votes on approach - CAUTIOUS or GREEDY
  - Cautious: Higher success chance, lower payout (2x-3x)
  - Greedy: Lower success chance, huge payout (5x-10x)
- **Phase 3**: Result calculated based on vote
  - Success: Everyone splits the pot proportionally
  - Failure: Everyone loses their bet
- **Teamwork**: Encourages community coordination
- **Excitement**: High drama with big risks
- **Example**: `!heist 100` joins with 100 point bet

**Roulette Game**
- **European Style**: Single zero (better odds for viewers)
- **Betting Options**:
  - Red (2x payout)
  - Black (2x payout)
  - Green/Zero (14x payout)
  - Specific number (36x payout!)
- **Min/Max Bets**: Control your risk
- **Configurable**: Enable/disable number betting
- **Example**: `!roulette 100 red` bets 100 on red

**Magic 8-Ball**
- **Fun, Free Game**: No currency required (optional cost)
- **Random Answers**: Pick from your custom response list
- **Response Categories**: Positive, neutral, negative
- **Customizable**: Add your own 8-ball responses
- **Example**: `!8ball Will I win today?`

**Trivia Game**
- **Question Database**: Add your own questions and answers
- **Categories**: Organize by topic (games, movies, streamer, etc.)
- **Difficulty Levels**: Easy, medium, hard questions
- **Multiple Choice**: 2-4 answer options
- **First to Win**: First correct answer in chat wins
- **Point Rewards**: Award points for correct answers
- **Question Sources**: Create your own or import (coming)
- **Example**: `!trivia` starts next question

#### Game Features

**Per-Game Configuration**
- Enable/disable each game independently
- Set min/max bets per game
- Choose which currency to use
- Adjust probability and odds
- Custom symbols and weights (slots)
- Custom responses (8-ball)
- Custom questions (trivia)

**Leaderboards**
- Per-game leaderboards
- Sort by: Net winnings, games won, total wagered
- Top players displayed in dashboard
- Leaderboard reset options
- Export leaderboard data

**Game Statistics**
- Times each game played
- Total currency wagered per game
- Total won/lost per game
- House profit/loss
- Most active players
- Biggest wins ever
- Luckiest/unluckiest players

**Game Management**
- Start/stop games from dashboard
- View active game sessions
- See who's currently in games (heist)
- Manual game reset
- Game history log
- Transaction tracking

#### Custom Game Builder (Coming)
Create your own games using the action system!

---

### Currency & Economy

**Create your own channel economy.**

#### Dual Currency System

**Custom Currency**
Your very own channel currency that you fully control.
- **Custom Names**: "Points", "Coins", "Gems", "Donuts", anything
- **Custom Symbols**: 🪙 💎 ⭐ 🍩 etc.
- **Multiple Currencies**: Create different currencies for different purposes
- **Full Control**: Set earning rates, spending options, everything

**Earning Methods**
Customize how viewers earn your currency:
- **Watch Time**: X points per minute watched
- **Chat Messages**: X points per message (prevents spam)
- **Following**: One-time bonus for new follows
- **Subscriptions**: Tier-based bonuses (Tier 1 > Tier 2 > Tier 3)
- **Raids**: Points per viewer in raid
- **Cheers/Bits**: Convert bits to points at your ratio
- **Referrals**: Bonus for bringing new viewers
- **Custom Events**: Award from your automations

**Spending Options**
What viewers can do with currency:
- Play games (slots, dice, roulette, heist)
- Request songs (coming)
- Trigger alerts/effects
- Use special commands
- Enter giveaways
- Unlock rewards
- Request highlights
- Buy roles (if using Discord roles)
- And anything you can imagine

**Twitch Channel Points Integration**
- Sync viewer balances automatically
- Allow converting Channel Points to your currency
- Trigger automations on redemptions
- Use Channel Points for game bets
- Combined leaderboards

#### Currency Features

**Balance Management**
- Set maximum balance caps (prevent inflation)
- Manual balance adjustments
- Balance transfers between users
- View transaction history
- Currency transaction log (all activity)
- Export transaction data

**Leaderboards**
- Top point holders overall
- Top earners this stream
- Top spenders this stream
- Biggest balance ever
- Leaderboard reset options
- Display leaderboards on stream

**Economy Controls**
- Adjust earning rates anytime
- Enable/disable earning methods
- Set currency expiration
- Economy reset options
- Import/export currency data
- Multiple currency support

**Currency Analytics**
- Total currency in circulation
- Earning vs spending ratio
- Most popular ways to earn
- Most popular ways to spend
- Currency growth over time
- Inflation tracking

---

### Automation Engine

**Replace Streamer.bot with our visual automation builder.**

#### What Can You Automate?

Literally anything. If it happens on your stream, you can automate a response.

**Automation Examples:**
- When someone follows → Welcome message + points + sound effect
- When someone subscribes → Shoutout + Discord notification + overlay update
- When raided → Switch to raid scene + thank message + celebration
- Every 15 minutes → Social media reminder
- Every 50 messages → Discord plug
- When stream starts → Tweet + Discord + recording start
- When !highlight is used → Save timestamp + add to queue
- When goal reached → Celebration effect + confetti overlay
- And thousands more...

#### Visual Automation Builder

**Drag-and-Drop Interface**
No coding required. Build complex automations visually.
- Drag actions onto canvas
- Connect actions in sequence
- Branch with conditions
- Loop actions
- Test immediately
- Save and reuse

#### Trigger Types

**Event Triggers**
Automatically run when something happens:
- New follower
- New subscription
- Subscription gifted
- Raid incoming
- Bits cheered
- Channel Points redeemed
- Stream started
- Stream stopped
- Hosted
- Chat message (any message)
- User joined chat
- User left chat
- Variable changed
- Currency transaction
- Game played
- Command used

**Manual Triggers**
Run automations yourself:
- Dashboard buttons
- Keyboard hotkeys
- Chat commands
- API calls
- Webhooks

**Scheduled Triggers**
Run on a schedule:
- Every X minutes
- Every X chat messages
- At specific times (cron)
- Countdown timers
- One-time scheduled events

#### Action Types (50+ Built-in)

**Chat Actions**
- Send message (with variables)
- Send whisper
- Delete message
- Timeout user (duration + reason)
- Ban user
- Clear chat
- Purge messages

**Currency Actions**
- Add currency to user
- Remove currency
- Set exact balance
- Transfer between users
- Get balance
- Calculate total in circulation

**Variable Actions**
- Set variable (global, user, temp, event)
- Increment variable
- Delete variable
- Copy variable
- Read variable

**OBS Actions**
- Switch scene
- Toggle source visibility
- Set source properties
- Start streaming
- Stop streaming
- Start recording
- Stop recording
- Pause recording
- Resume recording
- Trigger transition
- Get current scene
- List scenes

**VTube Studio Actions**
- Trigger hotkey
- Set expression
- Move model
- Get available hotkeys
- Get available expressions

**Alert Actions**
- Play alert (any type)
- Stop alerts
- Clear alert queue
- Pause alert queue
- Test alert

**Discord Actions**
- Send webhook message
- Send rich embed
- Custom embed colors
- Add fields to embeds
- Add images to embeds

**HTTP Actions**
- Make GET request
- Make POST request
- Make PUT request
- Make DELETE request
- Custom headers
- Custom body
- Save response to variable

**Audio Actions**
- Play sound file
- Stop all sounds
- Set volume
- Skip track (Spotify/YouTube)
- Play specific track

**Logic Actions**
- If/else conditions (equals, contains, greater than, etc.)
- Loop over list
- Wait X seconds
- Random choice from options
- Break from loop
- Continue to next iteration
- Nested conditions

**Game Actions**
- Start game
- Stop game
- Join game

**Script Actions**
- Run Python script
- Access to bot APIs
- Safe sandboxed execution

#### Variable System

**Built-in Variables**
- `$user` - Username
- `$user.id` - User ID
- `$user.display_name` - Display name
- `$user.roles` - User's roles
- `$channel` - Channel name
- `$stream.title` - Stream title
- `$stream.game` - Current game
- `$stream.viewers` - Viewer count
- `$timestamp` - Current date/time
- `$currency.points` - User's balance
- `$event.type` - Event that triggered
- `$event.data` - Event data
- `$command.name` - Command used
- `$command.args` - Command arguments

**Variable Scopes**
- **Global** - Server-wide, everyone can access
- **User** - Per-user, stored for each viewer
- **Temporary** - Expires after set time
- **Event** - Only exists during event processing

**Variable Features**
- Nested access: `${user.display_name}`
- Math: `$math:100 * 1.5`
- Defaults: `$varname:default_value`
- Required: `$$varname` (errors if missing)
- Dynamic names: `$var1.$var2`

#### Automation Features

**Test Mode**
Run automations without affecting anything:
- "Dry run" to test logic
- See what would execute
- Verify variable substitution
- Test conditions
- No external effects

**Chaining**
Link actions together:
- Sequential execution
- Conditional branching
- Loops and repeats
- Nested automations
- Error handling

**Import/Export**
Share your automations:
- Export action chains
- Import from community
- Template library
- One-click import

---

### Moderation Suite

**Replace AutoMod rules with complete control.**

#### Auto-Mod Rules

**Rule Types**

1. **Spam Detection**
   - Too many messages in time window
   - Example: 10 messages in 30 seconds
   - Configurable threshold and duration

2. **Link Filtering**
   - Block all URLs
   - Allow list domains (whitelist)
   - Block list domains (blacklist)
   - Exempt mods/streamer
   - Configurable links per message

3. **Caps Filter**
   - Percentage of capital letters
   - Example: >70% caps triggers rule
   - Minimum length before checking
   - Customizable threshold

4. **Profanity Filter**
   - Block banned words/phrases
   - Substitution with asterisks
   - Add custom banned words
   - Case-insensitive matching
   - Partial word matching option

5. **Emote Spam**
   - Too many emotes in one message
   - Percentage threshold
   - Count threshold
   - Emote-only message detection

6. **Repeat Messages**
   - Identical message detection
   - MD5 hash comparison
   - Time window (repeats in X minutes)
   - Prevents copy-paste spam

7. **Symbol Spam**
   - Too many special characters
   - Repeated characters (!!!!!)
   - Percentage threshold
   - Configurable symbols

8. **Long Message**
   - Character limit enforcement
   - Configurable max length
   - Split into multiple messages option

**Moderation Actions**
What happens when a rule triggers:
- **Delete Message** - Remove silently
- **Timeout** - Timeout for duration (you set time)
- **Ban** - Permanent ban
- **Warn** - Send warning message (with variables)
- **Nothing** - Log only (monitoring mode)

**Rule Configuration**
- **Priority** - Rules check in order (0-100)
- **Stop After Match** - Stop checking after first rule hit
- **Exempt Roles** - Broadcasters, mods, VIPs, subs ignore rules
- **Exempt Users** - Whitelist specific usernames
- **Custom Messages** - Variables in warnings ($user, $reason, etc.)

**Violation Logging**
- Timestamp of violation
- Which rule triggered
- User who violated
- Message content
- Action taken
- Viewable in dashboard
- Filter by user, rule, action
- Export violation log

**Testing Tool**
Test rules before enabling:
- Enter test message
- Select test user (with roles)
- See which rules would trigger
- Preview action that would be taken
- Test different role exemptions
- Perfect for tuning rules

#### Chat Management

**Search and Filter**
- Search all chat history
- Filter by user
- Filter by date range
- Export to CSV/JSON
- View deleted messages

**User Information**
- Click any user for details
- View user stats
- See user roles
- Check balance
- View note (add notes on users)
- Quick actions (timeout, ban, whisper)

**Quick Actions**
- One-click timeout (custom duration)
- One-click ban
- One-click purge
- One-click whisper
- Delete message
- Quote message
- Copy text

---

### OBS Studio Control

**Control OBS directly from your browser or chat.**

#### Complete OBS Integration

**Connection**
- Connect via WebSocket v5
- Password authentication
- Auto-connect on startup
- Auto-reconnect if disconnected
- Heartbeat monitoring (30s)
- Connection status in dashboard
- Test connection anytime

**Scene Management**
- List all scenes
- Switch to any scene
- Get current scene
- Scene collection info
- Transition between scenes
- Create/delete scenes (coming)

**Source Control**
- List all sources in scene
- Toggle source visibility
- Get source settings
- Set source settings
- Enable/disable sources
- Source properties editor
- Filter support

**Streaming Control**
- Start streaming
- Stop streaming
- Check streaming status
- Get stream time
- Auto-stream (coming)

**Recording Control**
- Start recording
- Stop recording
- Pause recording
- Resume recording
- Check recording status
- Get recording time
- Auto-record on stream start

**Transition Control**
- List available transitions
- Set transition type
- Set transition duration
- Trigger transition
- Studio mode support (coming)

**Audio Control**
- List audio sources
- Get volume levels
- Set volume
- Mute/unmute sources
- Audio monitoring

#### OBS in Automations

Use OBS actions in your automations:
- When raided → Switch to raid scene
- When sub → Play sub overlay
- On command → Toggle webcam
- Every hour → Screenshot replay buffer
- When !brb → Switch to BRB scene
- When !back → Switch back to gaming scene
- And countless more...

#### OBS Features

**Scene Triggers**
- Automatically switch scenes based on events
- Scene collections for different games
- Quick scene switcher in dashboard
- Scene hotkeys

**Source Automation**
- Automatically show/hide sources
- Source schedules (show at certain times)
- Condition-based visibility
- Group source control

**Recording Automation**
- Auto-record on stream start
- Split recording by time
- Recording notifications
- Recording file management (coming)

---

### VTube Studio Integration

**Full control over your VTuber model.**

#### VTS Connection
- Connect via WebSocket
- Authentication token exchange
- Auto-connect on startup
- Auto-reconnect
- Connection status in dashboard
- Test connection

#### Model Control

**Hotkeys**
- List all VTS hotkeys
- Trigger hotkey by ID or name
- Hotkey categories
- Custom hotkey triggers
- Hotkey in automations

**Expressions**
- List all expressions
- Activate expression
- Deactivate expression
- Expression duration
- Expression combinations
- Expression in automations

**Movements**
- Move model position
- Rotate model
- Scale model size
- Reset position
- Movement smoothing

#### VTS in Automations

**Examples:**
- When raided → Trigger celebration expression
- When !happy → Activate happy expression
- On sub → Wave animation
- When !sad → Sad expression + sound
- When !dance → Dance hotkey
- Based on chat → Reactive expressions

#### Advanced Features

**Art Mesh Control** (coming)
- Control individual mesh parts
- Color changes
- Visibility toggles
- Transform properties

**Parameter Control** (coming)
- Live2D parameters
- Custom parameter values
- Parameter smoothing
- Animation blending

---

### Polls & Community Tools

**Engage your audience with polls and more.**

#### Poll System

**Two Poll Types:**

**Native Twitch Polls**
- Uses Twitch's built-in poll system
- Appears in Twitch UI
- Works on mobile apps
- Vote counts from Twitch
- Create and close from dashboard

**Custom Internal Polls**
- Runs independently
- Vote via chat commands
- More options than Twitch (up to 10)
- Real-time updates
- Full customization
- Vote history tracking

**Poll Features**
- Unlimited polls
- 2-10 options per poll
- Custom duration (1 min to 30 days)
- Live vote counts with charts
- One vote per user
- Auto-close or manual close
- Vote by number or option text
- Export poll results
- Poll history

**Poll Commands**
- `!poll What game next? | Minecraft | Valorant | Just Chatting`
- `!vote 1` - Vote for option 1
- `!poll end` - Close poll (mods)

**Poll Automations**
- Auto-create recurring polls
- Announce polls to chat
- Poll result actions
- Poll closed notifications
- Archive polls

#### Quote System

**Capture the best moments**

**Quote Commands**
- `!quote` - Get random quote
- `!quote [id]` - Get specific quote
- `!quote search [text]` - Search quotes
- `!addquote [text]` - Add quote (mod)
- `!delquote [id]` - Delete quote (mod)

**Quote Features**
- Unlimited quotes
- Quote with attribution
- Date/time tracking
- Game/stream context
- Quote search (fuzzy matching)
- Quote categories
- Export quotes
- Random quote widget
- Quote on stream overlay

**Quote Display**
- Show quote on stream
- Auto-refresh quotes
- Quote of the day
- Timer-based quotes
- Random quotes on interval

#### Presets

**Quick actions for complex tasks**

**What Are Presets?**
Presets are saved automations you can trigger instantly. Like macros for your stream.

**Preset Examples**
- **Start Stream** - Switch scene + start recording + Discord webhook + social post
- **Game Win** - Victory alert + points for everyone + overlay update
- **Raid Mode** - Raid alert + overlay change + raid message
- **Giveaway** - Start giveaway timer + set entry cost + pick winner
- **BRB** - Switch to BRB scene + start countdown
- **Back** - Switch back to game + welcome message
- **New Follower** - Welcome + points + sound
- **Sub** - Shoutout + special alert + thank message

**Preset Features**
- Unlimited presets
- Custom names and descriptions
- Link to any automation
- Trigger from dashboard buttons
- Keyboard hotkey binding (global hotkeys!)
- Trigger from chat commands
- Enable/disable without deleting
- Organize into categories
- Import/export presets

#### Other Community Tools

**Giveaway System** (coming)
- Create giveaways
- Entry requirements (currency, sub, etc.)
- Winner picker
- Giveaway timer
- Announcement automation

**Betting System** (coming)
- Bet on outcomes
- Pool bets
- Payout calculations
- Betting history
- Leaderboard

**Tournament Mode** (coming)
- Bracket generation
- Match tracking
- Winner advances
- Champion announcement

---

### Timers & Scheduling

**Automate things on a schedule.**

#### Timer Types

**Interval Timers**
Run actions every X minutes.
- Independent of chat activity
- Example: "Every 15 minutes, remind about Discord"
- Example: "Every 5 minutes, update goal overlay"
- Example: "Every hour, save replay buffer"

**Message-Based Timers**
Run actions every X chat messages.
- Prevents spam during quiet times
- Example: "Every 50 messages, remind about social media"
- Example: "Every 100 messages, encourage engagement"
- Smart during active chat

**Scheduled Timers**
Run actions at specific times (like cron).
- Example: "Every day at 8pm, announce tomorrow's schedule"
- Example: "Every Monday at 6pm, start community game night"
- Example: "Every hour, check follower goal"
- Complex schedules supported

**Countdown Timers**
One-time countdown to specific time.
- Example: "Countdown 30 minutes, then start giveaway"
- Example: "Countdown to midnight, then New Year celebration"
- Example: "Countdown 10 minutes, then raid warning"
- Countdown display on stream (coming)

#### Timer Features

**Timer Management**
- Create unlimited timers
- Custom names and descriptions
- Enable/disable individually
- One-time or recurring
- See next run time
- See last run time
- Execution history

**Timer Actions**
- Link to any automation
- Multiple actions per timer
- Conditional execution
- Test timer immediately
- Skip next run
- Reset timer

**Timer Display**
- Show countdown on stream (coming)
- Countdown overlay
- Timer progress bars
- Next run display

**Advanced Scheduling**
- Cron expression support
- Multiple schedules per timer
- Timezone support
- Skip specific times
- Holiday exceptions

---

### Analytics Dashboard

**Know your numbers.**

#### Real-Time Stats

**Current Stream**
- Live viewer count
- Current game/category
- Stream title
- Stream uptime
- Chat activity rate
- Active chatters
- New followers this stream
- New subs this stream
- Bits cheered this stream
- Total events this stream

**All-Time Stats**
- Total followers
- Total subscribers
- Total views
- Total hours streamed
- Total messages in chat
- Total events
- Currency in circulation
- Games played

#### Analytics Charts

**Events Over Time**
- Line chart showing events
- Filter by event type
- Zoom in/out
- Compare time periods
- Identify patterns

**Command Usage**
- Pie chart breakdown
- Most used commands
- Least used commands
- Command trends
- Identify engagement

**Top Viewers**
- Bar chart by activity
- By watch time
- By chat messages
- By currency earned
- By games played
- Customizable rankings

**Currency Flow**
- Earnings over time
- Spending over time
- Net flow (earnings - spending)
- Inflation tracking
- Currency distribution

**Subscriber Growth**
- Sub count over time
- Sub rate (subs per day/week)
- Churn tracking
- Tier breakdown
- Gift sub tracking

#### Date Ranges
- Last 24 hours
- Last 7 days
- Last 30 days
- Last 90 days
- Custom range picker
- Predefined ranges

#### Export Options
- Export to CSV
- Export to JSON
- Print reports
- Save charts as images
- Scheduled reports (coming)

#### Analytics Features

**Metrics Tracking**
- Every event logged
- User activity tracking
- Command execution count
- Game statistics
- Currency transactions
- Alert plays
- Automation runs

**Custom Reports**
- Build custom reports
- Save report templates
- Schedule reports
- Email reports (coming)

**Comparisons**
- Compare time periods
- Week over week
- Month over month
- Year over year
- Goal progress

---

### Quotes & Presets

*(Detailed coverage in previous sections)*

---

### Discord Integration

**Keep your community updated.**

#### Webhook System

**Event Notifications**
Post events to Discord automatically:
- New follower
- New subscriber (with tier!)
- Subscription gift
- Raid incoming
- Stream started
- Stream ended
- Custom events

**Rich Embeds**
Beautiful Discord messages:
- Custom titles
- Descriptions
- Colors
- Fields (key-value pairs)
- Images
- Thumbnails
- Author info
- Timestamps
- Footers

**Webhook Features**
- Multiple webhooks
- Different channels for different events
- Webhook templates
- Custom messages
- Variable substitution
- Test webhooks

**Discord in Automations**
Use Discord in your automations:
- When followed → Post to #followers channel
- When subbed → Post to #subs channel with tier
- When raided → Post raid info to #notifications
- When stream starts → Post to #stream-announcements
- On command → Custom Discord post
- And anything else...

---

### REST API

**Build your own integrations.**

#### API Capabilities

**Command Endpoints**
- Trigger any command
- Create/delete commands
- List commands
- Get command info

**Preset Endpoints**
- Trigger presets
- List presets
- Create presets

**Action Endpoints**
- Execute action chains
- Test actions
- List action types

**Data Endpoints**
- Get event log
- Get variables
- Get currency balance
- Set currency balance
- Get chat messages
- Get user info

**Alert Endpoints**
- Play alerts
- Get alert queue
- Clear alerts

**Stream Endpoints**
- Get stream status
- Get stream info

**Integration Endpoints**
- Control OBS
- Control VTS
- Send Discord webhooks

#### API Uses

**Stream Deck**
- Create buttons for commands
- Trigger presets
- Control scenes
- Play alerts
- Show stats

**Mobile Apps**
- Control stream from phone
- View chat
- Trigger actions
- Check stats

**Custom Dashboards**
- Build your own UI
- Show specific data
- Custom controls

**Webhooks**
- Receive event notifications
- Trigger from external services
- IFTTT integration
- Zapier integration

#### API Features
- Token-based authentication
- Rate limiting per token
- Generate tokens in dashboard
- Token permissions
- Usage statistics
- API documentation (Swagger)
- Test in browser

---

### Advanced Tools

#### Python Scripting (Coming)

**Safe Script Execution**
- Sandboxed Python environment
- Built-in APIs and libraries
- Database access
- Chat integration
- Currency manipulation

**Use Cases**
- Custom game logic
- Complex calculations
- Data processing
- External API calls
- Custom command logic

**Script Features**
- Create unlimited scripts
- Test scripts safely
- Script variables
- Script permissions
- Import/export scripts

#### Plugin System (Coming)

**Extend StreamToolV2**
- Custom action types
- Custom event handlers
- Custom dashboard pages
- API endpoints
- Database tables
- Share with community

**Plugin Capabilities**
- Plugin marketplace
- One-click install
- Plugin permissions
- Plugin settings
- Plugin dependencies

#### Backup & Restore (Coming)

**Automatic Backups**
- Scheduled backups
- Backup everything (database, settings, overlays)
- Backup retention policy
- Backup to cloud (coming)

**Manual Backups**
- One-click backup
- Download backup file
- Backup before changes

**Restore**
- Upload backup file
- Preview contents
- Selective restore
- Full restore

---

## Getting Started

### System Requirements

**Minimum:**
- Windows 10+, macOS 10.14+, or Linux
- 4 GB RAM
- 500 MB disk space
- Stable internet

**Recommended:**
- Windows 11, macOS 12+, or Linux
- 8 GB RAM
- 2 GB disk space
- Broadband internet

**Optional Software:**
- OBS Studio 28+ (for OBS features)
- VTube Studio (for VTuber features)
- Discord (for webhooks)

### Quick Start

1. **Download** StreamToolV2
2. **Run** the setup script (installs everything automatically)
3. **Open** your browser to the dashboard
4. **Connect** your Twitch account
5. **Follow** the setup wizard
6. **Start** streaming!

The setup wizard guides you through:
- Twitch authentication (broadcaster + optional bot)
- Integration connections (OBS, VTS, Discord)
- Currency setup
- First command creation
- Connection testing

### What's Next?

Once set up, try these:
- Create a custom command (!social, !discord, etc.)
- Enable a game (slots is great for starters)
- Build your first automation (welcome new followers)
- Upload an alert image and sound
- Connect OBS and try scene switching
- Explore the dashboard and discover features

---

<div align="center">

## Ready to Transform Your Stream?

**Replace StreamElements, Streamlabs, and Streamer.bot with one powerful tool**

[Download Now](https://streamtoolv2.com/download) •
[Watch Demo](https://streamtoolv2.com/demo) •
[Join Discord](https://discord.gg/streamtoolv2) •
[Documentation](https://docs.streamtoolv2.com)

---

**Built with ❤️ by streamers, for streamers**

[Website](https://streamtoolv2.com) •
[GitHub](https://github.com/streamtoolv2) •
[Twitter](https://twitter.com/streamtoolv2) •
[YouTube](https://youtube.com/@streamtoolv2)

</div>
