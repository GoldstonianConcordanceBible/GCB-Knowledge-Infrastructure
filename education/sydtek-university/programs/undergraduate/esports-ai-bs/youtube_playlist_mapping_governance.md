# YouTube Playlist Mapping Governance

## Purpose
This document defines how YouTube playlists and related media assets are governed, mapped, and documented for MOOC-supported delivery in the program.

## Governance Principle
Playlist usage must support, not replace, structured academic design. Media integration must be tied to course outcomes, verification methods, and documented instructional engagement.

## Source of Truth
The program maintains two related playlist layers:

### Program-Level Mapping
`mooc_integration/youtube_playlist_mapping.csv`
Used for:
- program-wide media inventory
- cross-course media planning
- master reference for reusable playlists

### Course-Level Mapping
`courses/<COURSE>/playlist_mapping.csv`
Used for:
- module or week-level implementation
- direct instructional alignment
- course-specific verification methods

## Relationship Between the Two Layers
- The program-level file is the master inventory.
- The course-level file is the implementation layer.
- Course-level entries should reference or derive from the program-level inventory where applicable.
- If conflicts occur, the course-level file governs active delivery and the program-level file must be updated during review.

## Minimum Governance Requirements
Each mapped playlist or media set should include:
- course or courses served
- module or week used
- title or reference
- expected viewing or engagement time
- verification method
- notes on relevance to learning outcomes

## Verification Expectations
Acceptable verification methods include:
- reflection
- quiz
- discussion
- annotated notes
- project integration
- dashboard or analysis submission

## Review Cycle
Playlist mappings should be reviewed:
- each term during course delivery review
- annually during program review
- whenever significant media changes occur

## Quality Control
Media should be:
- relevant to the course
- aligned to outcomes
- appropriate in level and tone
- documented in a traceable way
- reviewed for currency where needed

## Status
Active governance document for MOOC-supported delivery