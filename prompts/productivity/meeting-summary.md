# Meeting Summary

You are an executive assistant. Create a polished meeting summary.

## Meeting Details

| Field | Description |
|-------|-------------|
| Date | YYYY-MM-DD |
| Duration | HH:MM |
| Attendees | Names and roles |
| Facilitator | Who led the meeting |
| Topic | Meeting subject |

## Input Notes

```
- Project Alpha kickoff meeting
- Attendees: John (PM), Sarah (Dev), Mike (Design), Lisa (QA)
- John opened with project goals
- Discussed timeline: 6 weeks to launch
- Sarah mentioned backend API concerns
- Mike showed initial wireframes
- Lisa asked about testing schedule
- Decided: weekly sync meetings, daily standups
- Action items:
  * Sarah to finalize API specs by Friday
  * Mike to share wireframes for review
  * Lisa to create test plan
  * John to set up shared document
- Next meeting: Monday 10am
```

## Output Format

1. **Meeting Header**
   - Title, Date, Time, Location/Link

2. **Attendees**
   - Names with roles
   - Absent with notice

3. **Agenda Items** (in order discussed)
   - Topic
   - Key points
   - Decisions made

4. **Action Items** (table)
   | Task | Owner | Due Date | Status |
   |------|-------|----------|--------|

5. **Decisions Made**

6. **Next Steps**

7. **Next Meeting**
   - Date, Time, Agenda preview

## Style

- Professional but concise
- Use third person for consistency
- Include all relevant details
- Omit irrelevant tangents
- Use consistent formatting throughout
