# Fruit-Machine
Fruit Machine v2.5, a Wordpress Plugin
=== Fruit Machine Slot Game ===
Contributors: MikeNL
Tags: slot, game, casino, fruit machine, gambling, entertainment
Requires at least: 5.0
Tested up to: 6.5
Stable tag: 2.4
Requires PHP: 7.2
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

A complete fruit machine slot game for WordPress with user management, daily spins, leaderboard, and multi-language support.

== Description ==

Fruit Machine is a fully-featured slot game plugin for WordPress that provides an engaging gaming experience for your users.

**Key Features:**

✅ **5-Reel Slot Machine** - Exciting 5-reel gameplay with multiple winning combinations
✅ **Multi-Language Support** - English and Dutch with auto-detection and user preferences
✅ **User Management** - Login required, user profiles, and statistics tracking
✅ **Daily Free Spins** - Configurable daily spin limits (default: 25 per day)
✅ **Buy Me A Coffee Integration** - Support system with extra spins rewards
✅ **Monthly Leaderboard** - Competitive ranking system with regular resets
✅ **Complete History** - Track every spin with detailed statistics
✅ **Sound Effects** - Immersive audio with toggle control
✅ **Responsive Design** - Works perfectly on desktop, tablet, and mobile
✅ **Admin Dashboard** - Full control over settings and user statistics
✅ **Export Functionality** - Export leaderboard data as CSV
✅ **Keyboard Shortcuts** - Quick access to game functions
✅ **Security** - Nonce verification, input validation, and rate limiting

**Game Mechanics:**
- 5 reels with 8 different symbols
- Win conditions: 3+ matching symbols or cherries
- Payouts: 5x = 500x, 4x = 100x, 3x = 50x, 🍒 = 1x each
- Multiple bet amounts configurable by admin
- Starting credits: 100 per user

**Admin Features:**
- Configure daily spins and bet amounts
- View detailed user statistics
- Export leaderboard data
- Monitor spin history
- Reset leaderboard manually

**Sound System:**
- Preloaded sound effects
- Separate sound toggle (top-right corner)
- Volume controls for different sound types
- Fallback beep system

== Installation ==

1. Upload the `fruit-machine` folder to `/wp-content/plugins/`
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Create a new page and add the `[fruit_machine]` shortcode
4. Configure settings in WordPress Dashboard → Fruit Machine

**Optional: Add sound files**
Create a `sounds` folder in `/wp-content/plugins/fruit-machine/assets/` and add:
- click.mp3
- spin.mp3
- win.mp3
- lose.mp3
- jackpot.mp3

If no sound files are present, the plugin will use fallback beep sounds.

== Frequently Asked Questions ==

**Q: Do users need to register to play?**
A: Yes, users must be logged in to play the game. This ensures proper tracking of spins and credits.

**Q: How do I change the daily spin limit?**
A: Go to Fruit Machine → Settings and adjust the "Daily Free Spins" value.

**Q: Can I change the bet amounts?**
A: Yes, in the settings you can specify comma-separated bet amounts.

**Q: How does the Buy Me A Coffee integration work?**
A: Users can support you via Buy Me A Coffee. After payment, they receive extra spins (default: 1500).

**Q: Is the game mobile-friendly?**
A: Yes, the game is fully responsive and works on all devices.

**Q: Can I translate the game to other languages?**
A: Yes, the plugin uses WordPress translation system. Create translation files in `/languages/` folder.

**Q: How do I reset the leaderboard?**
A: In admin settings, click "Reset Leaderboard Now" or set automatic reset to monthly/weekly.

**Q: Can I export user data?**
A: Yes, you can export the leaderboard as CSV from the admin settings page.

== Screenshots ==

1. Game interface with 5 reels
2. Admin settings page
3. Leaderboard display
4. User statistics page
5. Mobile responsive view

== Changelog ==

= 2.4 =
* Complete code overhaul and bug fixes
* Added spin history tracking
* Enhanced admin statistics page
* Improved sound system with fallbacks
* Added keyboard shortcut documentation
* Fixed all CSS positioning issues
* Enhanced mobile responsiveness
* Added export functionality
* Improved error handling and validation

== Shortcodes ==

`[fruit_machine]` - Display the game
`[fruit_machine show_login_message="false"]` - Hide login message (for custom login pages)
`[fruit_machine redirect_url="https://yoursite.com/custom-login/"]` - Custom login redirect

== Keyboard Shortcuts ==

* Space: Spin
* 1-5: Select bet amount (based on configured bets)
* A: Toggle auto spin
* M: Toggle sound
* L: Switch language
* Escape: Close modals

== Support ==

For extra spins, visit: https://buymeacoffee.com/nlbiertjenl

Please report bugs and issues on the WordPress support forum or GitHub repository.

== Credits ==

Developed by MikeNL

== License ==

GPLv2 or later
