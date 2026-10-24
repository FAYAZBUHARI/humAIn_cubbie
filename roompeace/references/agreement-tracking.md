# Minimal agreement tracking

Read when saving or revising a proposal, checking its acceptance, or creating a reminder. Use Cubbie's available memory after consent; no external database or shared household record is provided by this skill.

## What to record

Keep one short record per issue, scoped to this student:

- Short identifier, topic, and version.
- Participant aliases chosen by the student; no contact details unless needed for an approved action.
- Exact responsibilities, each owner and local due date/time/time zone.
- Any reciprocal turn: owner, task and date or clearly defined turn. Resolve ambiguity before acceptance.
- Status and latest update time.
- Acceptance for each affected person, the version accepted, and source: direct student statement, student-reported roommate acceptance, or student-provided reply.
- Student's permission to retain this summary.
- Optional reminders: purpose, scheduled time, creation status and returned identifier if available.

Do not retain raw complaints, private screenshots, grades, course contents, diagnoses, inferred motives or a ranking of roommates. Record only that academic constraints were considered, if needed; no course details are necessary.

## States and transitions

| State | Meaning | What permits the next step |
| --- | --- | --- |
| Draft | Wording prepared privately | Student reports delivering it, or an approved supported sending ability confirms delivery → proposed |
| Proposed | Exact terms shared, response pending | Acceptance of this version by every affected person → accepted; refusal → declined; changed terms → revised |
| Revised | A new version is being considered | Sharing the revision → proposed; preserve older version as superseded, not currently agreed |
| Accepted | Every affected person accepted this version | Completion report → completed; requested change → revised; explicit withdrawal → cancelled |
| Declined | One or more affected people refused | Student chooses to prepare a new version → revised; otherwise stop |
| Completed | All agreed tasks, including reciprocal tasks, reported done | No further reminders for these tasks |
| Cancelled | Agreement/proposal withdrawn or stopped | No further action without a new proposal |

Record partial completion per task; do not mark a two-part swap completed after the first chore. One person can withdraw their own commitment, but the assistant cannot claim the others accepted cancellation or release from obligations. Record whose withdrawal was reported and offer a draft to communicate it.

Silence, a read receipt, a reaction with unclear meaning, “maybe,” or the student's “send it” cannot establish roommate acceptance. In a three-person household, two approvals do not bind the third. If acceptance is reported without enough detail, confirm that it applies to the precise current terms. Do not present student-reported acceptance as independently verified.

## Reminders and changes

For a pending proposal, offer a reminder to the student to check for a response. For an accepted agreement, offer a reminder for the student's own responsibility. Include RoomPeace, record identifier/version, task and time in the scheduled instruction so it makes sense later. Use neutral notification text that does not expose the original complaint.

Scheduled instruction pattern: “RoomPeace check-in for [identifier/version]. First check whether this record is still current, accepted, and unfinished. If so, remind the student of their agreed [task] due [local date/time/time zone]. If cancelled, revised, completed or missing, do not assert that the obligation is current. Do not message anyone else.”

On revision, completion or cancellation, cancel or update superseded reminders using available abilities. Confirm actual results; if cancellation fails, disclose the remaining reminder and how the student can manage it. Do not silently create a second schedule. A pending change does not erase an earlier commitment; explain which terms remain disputed/current until clarified.

On a forget request, remove the accessible saved record and cancel associated reminders if possible. Do not claim deleting RoomPeace memory erases platform chat history. Without memory, return a minimal copyable summary; never say it was saved.
