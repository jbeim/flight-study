APP SITE FOLDER: what to upload to GitHub (repository jbeim/flight-study)
=========================================================================
Upload EVERYTHING in this folder, keeping the folder structure:
  index.html                  the study app, version 2.8.2 (2.1 MB: three.js, SheetJS, JSZip and the two lounge pictures are built in)
  data/telemetry.js           aircraft track and drone geometry for all 12 cards (the app scores presses with it)
  data/motion/<clip>.json     picture-steadying tracks, one per clip (2.8.0). TAKEOFF.json is the only one so far;
                              the twelve approach tracks need the proxies described in
                              Claude outputs\_steadying_2026-09-13\README.txt. A clip without a track plays as recorded.
  media/answers_reveal.mp4    "where the drones were" video (GitHub holds the 9.6 MB web copy from Media\answers_reveal_web_9.6MB_for_GitHub)
  media/fieldwork_making_of.mp4   optional two-minute behind-the-scenes film offered after that video (9.5 MB web copy, 720p; the 1080p master, 110 MB, is kept outside this folder)
  test.html                   the earlier playback test page
  audio/narration/*.mp3       Jason's narration. 01 and 02 are no longer played by 2.5 but can stay.
                              04, 06, 07, 10 replaced 11 Sep 2026; 14, 16, 17 and 18 to 22 added the same day.
                              15_flight_ready is not used by 2.6 and is not on the site, so the setup screen
                              lists it as an optional piece that is not recorded; that is expected.
                              03 (how to respond) re-recorded 14 Sep 2026 (script v4.6: the trigger for any
                              outside sighting, the word drone not used; IRB_Drift_Log item 31).
  audio/radio/R13_papi_advisory.mp3
  audio/clips/TC01_audio.mp3 ... TC12_audio.mp3   the finished clip soundtracks (rebuilt 6 Sep 2026)
  audio/clips/TAKEOFF_audio.mp3   the takeoff soundtrack (made 11 Sep 2026; see Pass-Card Folders\00_Takeoff\00_READ_ME_Takeoff_Clip.txt)
The video clips (12 approaches and the takeoff) are NOT uploaded; they stay on the headset.
State of the site on 14 Sep 2026 (later): app 2.8.2 uploaded (after each lock-in the participant points at DRONE,
OTHER AIRCRAFT, BIRD or OTHER; presses outside a drone window reported as something other than a drone are scored
as OTHER SIGHTING, not FALSE ALARM; see RESEARCHER_QUICK_GUIDE.txt, "WHAT CHANGED IN 2.8.2"). Narration 03 v4.6 uploaded.
State of the site on 14 Sep 2026: app 2.8.1 uploaded (every approach is the last 2 minutes of its clip; the takeoff starts 5 s earlier on the runway; the camera's mount tilt, about 9 deg of roll and 2.5 deg of pitch, is levelled so the cockpit and the panels sit square and pointing elevations are measured level). 2.8.0 (13 Sep, evening) It fixes the engine sound in the
flight (the soundtrack was playing at zero volume inside VR), keeps the cockpit where it was put
between approaches (grip held = nose straight ahead, thumbstick = slide the picture), calibrates
the nose by pointing the laser with fine-tuning, uploads video frames once per frame, and adds
the optional picture-steadying setting. See RESEARCHER_QUICK_GUIDE.txt, "WHAT CHANGED IN 2.8.0".
State of the site on 11 Sep 2026: every file above uploaded by Claude and checked against this folder (git blob hashes).
How: github.com/jbeim/flight-study -> Add file -> Upload files -> drag the
files in -> Commit changes. Wait about two minutes for the site to rebuild.
Desktop preview: double-click index.html here.

See RESEARCHER_QUICK_GUIDE.txt for how a session runs.
