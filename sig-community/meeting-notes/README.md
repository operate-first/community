# Meeting notes folder for SIG Community

Every meeting should produce an A/V recording and a set of notes, sometimes referred to as _minutes_.

The A/V recording is made or uploaded to YouTube and added to the [Op1st playlist](https://www.youtube.com/c/OperateFirst/playlists).
The link to the recording is added to the date-specific meeting notes file.

The set of notes are committed to this git repo in a single folder, which exists within the SIG, subproject, or working group that produced the minutes.

For example:
- Notes from the SIG Community meeting are in `operate-first/community/sig-community/meeting-notes/`
- Notes from a SIG Community subproject are in `operate-first/community/sig-community/subproject-name/meeting-notes/`
- Notes from a working group started by SIG Community are in `operate-first/community/sig-community/wg-name-of-working-group/meeting-notes/`
- When a new SIG is created, it becomes the top-level for it's own tree of subprojects and instantiated working groups.

The file should be have the date first so the files are sortable chronologically by name.
This supports having all of the meeting notes for a subproject, WG, or SIG in a single folder. Even when it grows to 100 or 200 files within a few years, sorting by alphanumerics results in date order.

`yyyymmdd-meeting_notes-[sig,wg,NULL][-]name-of-group[-subproject].md`

In the example, `NULL` means to put nothing in that location, including the second `-`.

For example:
- `20220315-meeting-notes-wg-contrib_x-docs.md`
- `20220314-meeting-notes-sig-ops.md`
- `20220401-meeting-notes-april-fools-subproject.md`
``
