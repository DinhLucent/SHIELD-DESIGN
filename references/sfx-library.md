# SFX Library Â· shield-design

> å…¨éƒ¨ç”± ElevenLabs Sound Generation API ç”Ÿæˆï¼Œè‹¹æžœå‘å¸ƒä¼šçº§éŸ³è´¨ã€‚
> äº§å“çº§ SFX èµ„äº§åº“ï¼Œè¦†ç›–èŠ±å”åŠ¨ç”»/æ¼”ç¤º/äº§å“ Demo å…¨åœºæ™¯ã€‚

**èµ„äº§ä½ç½®**ï¼š`assets/sfx/<category>/<name>.mp3`
**æ€»æ•°**ï¼š37 ä¸ª SFXï¼ˆ30 æ‰¹é‡ç”Ÿæˆ + 7 ä¸ª v7b ä¿ç•™ï¼‰
**ç”Ÿæˆæ¨¡åž‹**ï¼šElevenLabs Sound Generation APIï¼ˆprompt_influence 0.4ï¼‰
**éŸ³è´¨**ï¼š44.1kHz MP3ï¼Œè‹¹æžœå‘å¸ƒä¼šçº§æ¸…æ™°åº¦ï¼Œæ— é¢å¤–æ··å“

---

## ç›®å½•ç»“æž„

```
assets/sfx/
â”œâ”€â”€ keyboard/      type, type-fast, delete-key, space-tap, enter
â”œâ”€â”€ ui/            click, click-soft, focus, hover-subtle, tap-finger, toggle-on
â”œâ”€â”€ transition/    whoosh, whoosh-fast, swipe-horizontal, slide-in, dissolve
â”œâ”€â”€ container/     card-snap, card-flip, stack-collapse, modal-open
â”œâ”€â”€ feedback/      success-chime, error-tone, notification-pop, achievement
â”œâ”€â”€ progress/      loading-tick, complete-done, generate-start
â”œâ”€â”€ impact/        logo-reveal, logo-reveal-v2, brand-stamp, drop-thud
â”œâ”€â”€ magic/         sparkle, ai-process, transform
â””â”€â”€ terminal/      command-execute, output-appear, cursor-blink
```

---

## å¿«é€Ÿç´¢å¼•

### âŒ¨ï¸ Keyboardï¼ˆé”®ç›˜è¾“å…¥ï¼‰

| æ–‡ä»¶ | æ—¶é•¿ | ç”¨é€” | Prompt è¦ç‚¹ |
|---|---|---|---|
| `sfx/keyboard/type.mp3` | 0.5s | å•é”®æ•²å‡»ï¼ˆmechanical keyboard single keyï¼‰ | mechanical keyboard single key press |
| `sfx/keyboard/type-fast.mp3` | 1.5s | è¿žç»­å¿«é€Ÿæ‰“å­—ï¼ˆæ¼”ç¤ºè¾“å…¥æç¤ºè¯ï¼‰ | fast continuous typing rhythm, apple magic keyboard |
| `sfx/keyboard/delete-key.mp3` | 0.5s | backspace å›žåˆ  | single backspace key, low pitched thud |
| `sfx/keyboard/space-tap.mp3` | 0.5s | ç©ºæ ¼é”®è½»å‡» | soft spacebar tap, wide flat |
| `sfx/keyboard/enter.mp3` | 0.5s | å›žè½¦ç¡®è®¤ï¼ˆv7b ä¿ç•™ï¼‰ | enter key press, crisp tactile |

### ðŸŽ¯ UIï¼ˆç•Œé¢äº¤äº’ï¼‰

| æ–‡ä»¶ | æ—¶é•¿ | ç”¨é€” | Prompt è¦ç‚¹ |
|---|---|---|---|
| `sfx/ui/click.mp3` | 0.5s | æ ‡å‡† UI ç‚¹å‡»ï¼ˆv7b ä¿ç•™ï¼‰ | crisp modern interface click |
| `sfx/ui/click-soft.mp3` | 0.5s | æŸ”å’Œ UI clickï¼ˆæ¬¡è¦æŒ‰é’®/é“¾æŽ¥ï¼‰ | soft gentle button click, mid pitched |
| `sfx/ui/focus.mp3` | 0.5s | å…ƒç´ èšç„¦/é€‰ä¸­ï¼ˆv7b ä¿ç•™ï¼‰ | subtle focus tone, element highlight |
| `sfx/ui/hover-subtle.mp3` | 0.5s | æ‚¬åœæç¤ºï¼ˆå¾®ç§’çº§åé¦ˆï¼‰ | barely audible tick, air whisper |
| `sfx/ui/tap-finger.mp3` | 0.5s | ç§»åŠ¨ç«¯ tapï¼ˆiOS ç•Œé¢ï¼‰ | finger tap on touchscreen, muted thud |
| `sfx/ui/toggle-on.mp3` | 0.5s | å¼€å…³æ‰“å¼€ | ios toggle switch flip, satisfying click |

### ðŸŒŠ Transitionï¼ˆè¿‡æ¸¡ï¼‰

| æ–‡ä»¶ | æ—¶é•¿ | ç”¨é€” | Prompt è¦ç‚¹ |
|---|---|---|---|
| `sfx/transition/whoosh.mp3` | 0.5s | æ ‡å‡† whooshï¼ˆv7b ä¿ç•™ï¼‰ | air whoosh transition |
| `sfx/transition/whoosh-fast.mp3` | 0.6s | å¿«é€Ÿ whooshï¼ˆæ ‡é¢˜é—ªå…¥ã€æ ‡ç­¾åˆ‡æ¢ï¼‰ | quick fast air whoosh, cinematic |
| `sfx/transition/swipe-horizontal.mp3` | 0.7s | æ¨ªå‘æ»‘åŠ¨ï¼ˆè½®æ’­ã€tab åˆ‡æ¢ï¼‰ | smooth left-to-right air movement |
| `sfx/transition/slide-in.mp3` | 0.6s | å…ƒç´ æ»‘å…¥ï¼ˆside panelã€æŠ½å±‰ï¼‰ | smooth soft whoosh with arrival |
| `sfx/transition/dissolve.mp3` | 0.8s | æŸ”åŒ–èžåŒ–ï¼ˆå›¾ç‰‡æ·¡å‡ºæ·¡å…¥ï¼‰ | soft dissolve, airy shimmer |

### ðŸƒ Containerï¼ˆå¡ç‰‡/å®¹å™¨ï¼‰

| æ–‡ä»¶ | æ—¶é•¿ | ç”¨é€” | Prompt è¦ç‚¹ |
|---|---|---|---|
| `sfx/container/card-snap.mp3` | 0.5s | å¡ç‰‡å¸é™„/å®šä½ï¼ˆv7b ä¿ç•™ï¼‰ | card snap into place |
| `sfx/container/card-flip.mp3` | 0.7s | å¡ç‰‡ç¿»è½¬ï¼ˆå‰åŽé¢åˆ‡æ¢ï¼‰ | playing card flip, crisp snap |
| `sfx/container/stack-collapse.mp3` | 0.8s | å †å åˆæ‹¢ï¼ˆåˆ—è¡¨èšåˆï¼‰ | cards stacking, paper taps collapsing |
| `sfx/container/modal-open.mp3` | 0.6s | æ¨¡æ€æ¡†æ‰“å¼€ | modal popping open, whoosh + thud |

### ðŸ”” Feedbackï¼ˆé€šçŸ¥/åé¦ˆï¼‰

| æ–‡ä»¶ | æ—¶é•¿ | ç”¨é€” | Prompt è¦ç‚¹ |
|---|---|---|---|
| `sfx/feedback/success-chime.mp3` | 1.0s | æˆåŠŸæç¤ºï¼ˆæ”¯ä»˜æˆåŠŸã€ä»»åŠ¡å®Œæˆï¼‰ | two ascending bell tones, ios-style |
| `sfx/feedback/error-tone.mp3` | 0.7s | é”™è¯¯æç¤ºï¼ˆè­¦å‘Šã€å¤±è´¥ï¼‰ | descending two-note warning, soft |
| `sfx/feedback/notification-pop.mp3` | 0.6s | æ¶ˆæ¯å¼¹å‡ºï¼ˆtoastã€é€šçŸ¥ï¼‰ | notification bloop, ios message alert |
| `sfx/feedback/achievement.mp3` | 1.5s | æˆå°±è¾¾æˆï¼ˆé‡Œç¨‹ç¢‘ã€å¾½ç« ï¼‰ | triumphant rising arpeggio, game-style |

### â³ Progressï¼ˆè¿›åº¦/çŠ¶æ€ï¼‰

| æ–‡ä»¶ | æ—¶é•¿ | ç”¨é€” | Prompt è¦ç‚¹ |
|---|---|---|---|
| `sfx/progress/loading-tick.mp3` | 0.5s | åŠ è½½è®¡æ—¶ï¼ˆè¿›åº¦æ¡èŠ‚æ‹ï¼‰ | soft short pulse, minimal ambient |
| `sfx/progress/complete-done.mp3` | 0.8s | å®Œæˆç¡®è®¤ï¼ˆstep å®Œæˆï¼‰ | two ascending satisfying tones |
| `sfx/progress/generate-start.mp3` | 0.8s | AI å¼€å§‹ç”Ÿæˆ | soft rising shimmer, magical whoosh |

### ðŸ’¥ Impactï¼ˆå“ç‰Œ/å†²å‡»ï¼‰

| æ–‡ä»¶ | æ—¶é•¿ | ç”¨é€” | Prompt è¦ç‚¹ |
|---|---|---|---|
| `sfx/impact/logo-reveal.mp3` | 0.7s | Logo impactï¼ˆv7b ä¿ç•™ï¼‰ | logo reveal thud |
| `sfx/impact/logo-reveal-v2.mp3` | 1.5s | æ›´é•¿çš„ Logo impactï¼ˆç”µå½±æ„Ÿï¼‰ | cinematic bass hit with shimmer tail |
| `sfx/impact/brand-stamp.mp3` | 1.0s | å°ç« é‡å‡»ï¼ˆè®¤è¯ã€ç›–ç« ï¼‰ | rubber stamp thud, paper contact |
| `sfx/impact/drop-thud.mp3` | 0.7s | ç‰©ä»¶è½åœ°ï¼ˆæ’å…¥ã€æ”¾ç½®ï¼‰ | heavy thud, wood surface contact |

### âœ¨ Magicï¼ˆAI å˜æ¢ï¼‰

| æ–‡ä»¶ | æ—¶é•¿ | ç”¨é€” | Prompt è¦ç‚¹ |
|---|---|---|---|
| `sfx/magic/sparkle.mp3` | 0.8s | é­”æ³•é—ªå…‰ï¼ˆAI é«˜äº®ã€æƒŠå–œï¼‰ | bright twinkling stars, fairy dust |
| `sfx/magic/ai-process.mp3` | 1.2s | AI å¤„ç†éŸ³ï¼ˆthinking çŠ¶æ€ï¼‰ | modulating digital hum with shimmer |
| `sfx/magic/transform.mp3` | 1.0s | å˜æ¢è¿‡æ¸¡ï¼ˆmorph æ•ˆæžœï¼‰ | rising shimmer whoosh with sparkle tail |

### ðŸ’» Terminalï¼ˆå‘½ä»¤è¡Œï¼‰

| æ–‡ä»¶ | æ—¶é•¿ | ç”¨é€” | Prompt è¦ç‚¹ |
|---|---|---|---|
| `sfx/terminal/command-execute.mp3` | 0.5s | å‘½ä»¤æ‰§è¡Œ | crisp digital beep with tick, hacker ui |
| `sfx/terminal/output-appear.mp3` | 0.6s | è¾“å‡ºå‡ºçŽ° | rapid digital ticks, retro printout |
| `sfx/terminal/cursor-blink.mp3` | 0.5s | å…‰æ ‡é—ªçƒ | subtle soft digital pulse, rhythmic |

---

## æŒ‰åœºæ™¯æŽ¨èæ­é…

### ðŸ’» Terminal äº¤äº’æ¼”ç¤º
```
type (0.5s) â†’ enter (0.5s) â†’ command-execute (0.5s) â†’ output-appear (0.6s)
```
å¾ªçŽ¯å…ƒç´ ï¼š`cursor-blink` ä½œä¸º idle æ—¶çš„çŽ¯å¢ƒéŸ³ã€‚

### ðŸƒ å¡ç‰‡é€‰æ‹©æµç¨‹
```
hover-subtle (0.5s, UIæ‚¬åœ) â†’ click-soft (0.5s, ç‚¹å‡») â†’ card-snap (0.5s, å®šä½)
```
æˆ–è¿›é˜¶ç‰ˆï¼š`card-flip` åšå‰åŽé¢åˆ‡æ¢ã€‚

### ðŸ¤– AI ç”Ÿæˆå…¨æµç¨‹
```
generate-start (0.8s, å¯åŠ¨) â†’ ai-process (1.2s, å¤„ç†) â†’ sparkle (0.8s, é—ªçŽ°) â†’ complete-done (0.8s, å®Œæˆ)
```
é”™è¯¯æ—¶ç”¨ `error-tone` æ›¿ä»£ `complete-done`ã€‚

### ðŸŽ¬ Logo Revealï¼ˆå“ç‰Œæ—¶åˆ»ï¼‰
```
whoosh-fast (0.6s, é“ºåž«) â†’ logo-reveal-v2 (1.5s, è½ç‚¹) â†’ sparkle (0.8s, å°¾éŸµ)
```
ç®€ç‰ˆï¼š`whoosh â†’ logo-reveal`ï¼ˆç›´æŽ¥ v7b ä¸¤ä»¶å¥—ï¼‰ã€‚

### ðŸ“± UI äº¤äº’æ¼”ç¤ºï¼ˆç§»åŠ¨ç«¯ï¼‰
```
tap-finger (0.5s, ç‚¹å‡») â†’ slide-in (0.6s, é¢æ¿æ»‘å…¥) â†’ toggle-on (0.5s, å¼€å…³)
```
å®ŒæˆåŽï¼š`success-chime` æˆ– `notification-pop`ã€‚

### ðŸ“Š æ•°æ®å¯è§†åŒ–/ä»ªè¡¨ç›˜
```
loading-tick (0.5s, èŠ‚æ‹) Ã— N â†’ complete-done (0.8s, æ•°æ®åˆ°ä½) â†’ achievement (1.5s, æƒŠè‰³è½ç‚¹)
```

### ðŸŽ¯ è¡¨å•æäº¤æµç¨‹
```
click-soft (0.5s) â†’ loading-tick Ã—2 (1.0s) â†’ success-chime (1.0s)
```
å¤±è´¥åˆ†æ”¯ï¼š`error-tone (0.7s)`ã€‚

### ðŸª„ Magic Transform åœºæ™¯
```
whoosh-fast (0.6s) â†’ transform (1.0s) â†’ sparkle (0.8s)
```
é€‚åˆï¼šå…ƒç´ å˜å½¢ã€æ•ˆæžœå‰åŽå¯¹æ¯”ã€"AI é‡å†™"ç­‰æ¼”ç¤ºã€‚

---

## ä½¿ç”¨è§„èŒƒ

### éŸ³é‡å»ºè®®ï¼ˆæ¥è‡ª apple-gallery-showcase.md éŸ³é¢‘åŒè½¨åˆ¶ï¼‰
- **SFX ä¸»è½¨**ï¼š`1.0`ï¼ˆä¸åšè¡°å‡ï¼‰
- **BGM èƒŒæ™¯è½¨**ï¼š`0.4 ~ 0.5`ï¼ˆSFX æ˜Žæ˜¾ç©¿é€ï¼‰
- **å¤š SFX å åŠ **ï¼šç”¨ `amix=inputs=N:duration=longest:normalize=0` ä¿ç•™åŠ¨æ€èŒƒå›´

### ffmpeg æ‹¼æŽ¥æ¨¡æ¿
```bash
# å• SFX å¯¹é½æ—¶é—´ç‚¹ï¼š
ffmpeg -i video.mp4 -itsoffset 2.5 -i sfx/ui/click.mp3 \
  -filter_complex "[0:a][1:a]amix=inputs=2:duration=longest:normalize=0[a]" \
  -map 0:v -map "[a]" output.mp4

# å¤š SFX + BGMï¼š
ffmpeg -i video.mp4 \
  -itsoffset 1.0 -i sfx/transition/whoosh-fast.mp3 \
  -itsoffset 1.6 -i sfx/impact/logo-reveal-v2.mp3 \
  -i bgm.mp3 \
  -filter_complex "[3:a]volume=0.4[bgm];[0:a][1:a][2:a][bgm]amix=inputs=4:normalize=0[a]" \
  -map 0:v -map "[a]" output.mp4
```

### é€‰åž‹å†³ç­–æ ‘
1. **æœ‰ tactile åŠ¨ä½œ**ï¼ˆæ‰“å­—/ç‚¹å‡»/æ»‘åŠ¨ï¼‰â†’ `keyboard/` or `ui/`
2. **å…ƒç´ è¿›åœº/å‡ºåœº** â†’ `transition/`
3. **å®¹å™¨å±‚æ“ä½œ**ï¼ˆå¡ç‰‡/æ¨¡æ€ï¼‰ â†’ `container/`
4. **çŠ¶æ€åé¦ˆ**ï¼ˆæˆåŠŸ/å¤±è´¥/é€šçŸ¥ï¼‰ â†’ `feedback/`
5. **è¿›åº¦/æ—¶é—´æµé€** â†’ `progress/`
6. **å“ç‰Œè½ç‚¹/é‡è¦æ—¶åˆ»** â†’ `impact/`
7. **AI é­”æ³•/å˜æ¢** â†’ `magic/`
8. **å‘½ä»¤è¡Œ/ä»£ç æ¼”ç¤º** â†’ `terminal/`

### é¿å…å éŸ³å †ç§¯
- åŒä¸€ä¸ªæ—¶é—´ç‚¹ `max 2 ä¸ª SFX` å¹¶å‘
- BGM é™åˆ° 0.3 ä»¥ä¸‹æ—¶å¯ä»¥æ”¾ 3 ä¸ª
- å“ç‰Œ impact æ—¶æ¸…ç©ºå…¶ä»– SFXï¼ˆç•™ç©º 0.2s å†è½ç‚¹ï¼‰

---

## Prompt æ’°å†™åŽŸåˆ™ï¼ˆä¾›å¤ç”¨ï¼‰

å‚è€ƒé£Žæ ¼ï¼š`apple keynote, tight, minimal, no reverb unless ambient, crisp, elegant`

**å¥½ prompt çš„ä¸‰è¦ç´ **ï¼š
1. **å£°éŸ³ç‰©ç†æè¿°**ï¼šä»€ä¹ˆç‰©ä½“ã€ä»€ä¹ˆåŠ¨ä½œï¼ˆ"mechanical keyboard single key press"ï¼‰
2. **è´¨æ„Ÿ/é£Žæ ¼é™å®š**ï¼šapple-style / ios-style / cinematic / retro
3. **åä¾‹æŽ’é™¤**ï¼šno reverb / clean studio / minimal

âŒ "click sound"
âœ… "crisp ui button click, clean modern interface sound, apple-style, high pitched"

âŒ "magic"
âœ… "bright twinkling stars sound, high pitched glittery chime, fairy dust"

---

## è¯¦è§
- éŸ³é¢‘åŒè½¨åˆ¶ä¸Ž ffmpeg æ‹¼æŽ¥ï¼š`apple-gallery-showcase.md`
- åŽŸå§‹ç”Ÿæˆè„šæœ¬ï¼š`/tmp/gen_sfx_batch.sh`ï¼ˆä¸€æ¬¡æ€§æ‰¹é‡ç”Ÿæˆå™¨ï¼‰
