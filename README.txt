APP SITE FOLDER: what to upload to GitHub (repository jbeim/flight-study)
=========================================================================
Upload EVERYTHING in this folder, keeping the folder structure:
  index.html                  the study app, version 2.6.3 (2.3 MB: three.js, SheetJS, JSZip and the two lounge pictures are built in)
  data/telemetry.js           aircraft track and drone geometry for all 12 cards (the app scores presses with it)
  media/answers_reveal.mp4    "where the drones were" video (GitHub holds the 9.6 MB web copy from Media\answers_reveal_web_9.6MB_for_GitHub)
  test.html                   the earlier playback test page
  audio/narration/*.mp3       Jason's narration. 01 and 02 are no longer played by 2.5 but can stay.
                              04, 06, 07, 10 replaced 11 Sep 2026; 14, 16, 17 and 18 to 22 added the same day.
                              15_flight_ready is not used by 2.6 and is not on the site, so the setup screen
                              lists it as an optional piece that is not recorded; that is expected.
  audio/radio/R13_papi_advisory.mp3
  audio/clips/TC01_audio.mp3 ... TC12_audio.mp3   the finished clip soundtracks (rebuilt 6 Sep 2026)
  audio/clips/TAKEOFF_audio.mp3   the takeoff soundtrack (made 11 Sep 2026; see Pass-Card Folders\00_Takeoff\00_READ_ME_Takeoff_Clip.txt)
The video clips (12 approaches and the takeoff) are NOT uploaded; they stay on the headset.
State of the site on 11 Sep 2026: every file above uploaded by Claude and checked against this folder (git blob hashes).
How: github.com/jbeim/flight-study -> Add file -> Upload files -> drag the
files in -> Commit changes. Wait about two minutes for the site to rebuild.
Desktop preview: double-click index.html here.

See RESEARCHER_QUICK_GUIDE.txt for how a session runs.
