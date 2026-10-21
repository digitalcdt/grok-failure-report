# Report: Grok Bot Project Visibility Failure – “The Rise and Fall of the Dental Technician”

**Date:** October 20–21, 2026  
**User:** Kevin Miller, CDT (DigitalDental.tech)

## Summary

On October 20, 2026, I requested access to a documentary previously developed with Grok: *The Rise and Fall of the Dental Technician* (version 11). Despite multiple searches across conversation history, GitHub, and connected tools, the main Grok session repeatedly stated the project could not be found or might not have been saved.

The project **existed the entire time**. It was stored on the **Director** Grok Bot’s workspace at `/workspace/productions/dental-tech-doc/` (~17 GB). Version 11 (final cut) and earlier versions (v5–v10), along with full scripts, fact-check files, rights audits, and asset folders, were also saved to my local Downloads folder.

The main agent only located it after repeated insistence and a direct query to the Director bot. Until that point, the system behaved as if the work had disappeared.

## Version 11 Status (Current Final Cut)

- **Runtime:** 13:49.8 (829.8 seconds)
- **Resolution:** 1280×720 (720p)
- **File size:** 43.3 MB
- **Audio:** Mastered to −14 LUFS; narration in the selected AI voice with two Workshop Pulse music tracks
- **Location on bot:** `/workspace/productions/dental-tech-doc/edit/cut_v11.mp4` (with `cut_v11.srt` subtitles and `edl_v11.csv` shot list)
- **Location on PC:** `C:\Users\digit\Downloads\Rise_and_Fall_Dental_Tech_v11.mp4`
- **Script:** Narration unchanged from v10 (current script is v10; available in project folder and Downloads as `Rise_and_Fall_Dental_Tech_Script_v10.txt`)

**What v11 fixed:**
- Replaced three photos that came from company accounts or showed brand names (at ~2:45, 3:45, and 11:09) with free stock lab photos
- Replaced the repeated boardroom shot at ~6:21 with real footage of an empty office
- Removed company names from on-screen cards and credits (now generic references such as “job-site salary estimates” and “trade press”); Suno and stock site names no longer credited by name

**Earlier version fixes (for context):**
- **v10:** Rebuilt clean; lab count cards updated to “about 7,800 to under 5,000”; chart source line fully visible; state line revised to “a handful of states, including Texas, South Carolina, Kentucky and Washington” after legal verification
- **v9:** Caption and count fixes; ADA group-practice figures given with years; softer language on program counts
- **v8:** CDT number and signature blurred; specialty pay card added; extraneous articulator shot removed

**Production folder contents** (`/workspace/productions/dental-tech-doc/`, ~17 GB):
- Full cuts v1 through v11 (with subtitles and shot lists)
- Narration scripts v7–v10 plus act-by-act working scripts and backups
- Fact-check reports (`factcheck.md` through `factcheck_v8.md`)
- `rights_audit_v11.csv` listing all 187 assets and their licenses
- Shot list, budget notes, and folders for personal assets, music, stock footage, AI clips, and narration takes

Nothing is pending. The project is complete.

## Issues

- Primary Grok sessions do not automatically surface or search active Grok Bot workspaces and production files.
- Users can be told projects are missing even when they exist on a bot they own.
- No clear, reliable way for a user (or the primary agent) to list all projects across bots without manual, repeated prompting.
- This creates repeated friction, lost time, and the appearance that paid work is not retained or accessible.

## Requests

1. Improve visibility and cross-session access to Grok Bot projects and files so completed work does not appear deleted or unrecoverable.
2. Provide a straightforward way for users (and the primary agent) to list and open bot workspaces.
3. Ensure finished outputs saved to user Downloads or bot storage remain reliably discoverable.
4. Address the pattern of projects seeming to vanish until a specific bot is manually queried.

---

Kevin Miller, CDT  
DigitalDental.tech