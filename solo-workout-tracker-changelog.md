# Solo Workout Tracker - Changelog

## v1.2 - 16 April 2026
- Added export data functions on home page (JSON and CSV formats)
- Export buttons always visible (disabled until at least one session is logged)
- RPE buttons now show reps-in-reserve (RIR) labels for 6-10 (e.g. "8 | 2 RIR")
- RPE 1-5 dimmed visually since they are rarely used for working sets
- Added sleep hours tracking per session (input accepts decimals, e.g. 7.5)
- Added RPE tracking per exercise (1-10 scale separate from score)
- Added pain/discomfort flag per exercise with optional note field
- Added exercise guide modal accessible from info icon on each exercise card
- Each guide includes: setup instructions, numbered execution cues, key tip, and YouTube video link
- 35 exercises covered with curated guides and demo video searches
- Progress view now displays RPE and discomfort flags alongside existing data
- CSV export includes all metrics for spreadsheet analysis

## v1.1 - 14 April 2026
- Removed fixed day labels (no Wednesday/Friday association)
- Added exercise library with slot-based selection
- Lower body slots: Squat (7 exercises), Hinge (6 exercises), Core (6 exercises)
- Upper body slots: Push (6 exercises), Pull (5 exercises), Vertical Push (5 exercises)
- Exercise picker shown during new session creation with radio-style selection per slot
- New sessions auto-populate exercise choices from most recent session of the same type
- Previous session weight comparison now tracks per exercise across sessions (handles exercise swaps)
- Movement pattern label shown on each exercise card during session logging
- Storage key updated to v2 (fresh start, no migration from v1.0)
- Version number displayed at bottom of home screen (visible)

## v1.0 - 14 April 2026
- Initial release (standalone HTML, localStorage)
- Two workout types: Lower Body (Wednesday) and Upper Body (Friday)
- Lower body exercises: Goblet Squat, DB Romanian Deadlift, Dead Bug
- Upper body exercises: DB Bench Press, Bench-Supported Row, Seated Shoulder Press
- Adjustable dumbbell weights: 4kg to 40kg in 1.5kg increments with +/- buttons
- Per-set rep logging (3 sets per exercise) with placeholder targets
- Session score per exercise (1 = Easy, 2 = Hard, 3 = Failed)
- Wake energy level tracking (1-5 scale)
- Workout duration tracking (minutes)
- Variation notes per exercise
- Session notes field
- Previous session comparison: shows prior reps beneath each set input and weight delta
- New session auto-populates weights from most recent session of same type
- Progress view with week-over-week history per workout type
- Log past sessions via date picker
- Delete sessions with confirmation
- Persistent storage across conversations
- Dark theme, mobile-first design
