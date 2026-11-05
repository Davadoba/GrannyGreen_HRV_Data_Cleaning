## Current Task: Cardiac / HRV & Synchronization

### Overall Goals:
- Cleaning is NOT hypothesis testing. Today we define how each data stream becomes trustworthy, documented, reproducible, and ready for later analysis.										
- Cleaning-stage question: Can this data stream be prepared reproducibly so we know what is usable, what is questionable, what is missing, and what must be documented?	

### Task 1: What Needs To Be Cleaned / Prepared?
- HR/PPG cardiac files, time-sync files, respiration context

### Task 2: What Needs Cleaning / QA?
- Missing segments, implausible values, motion artifact, PPG quality, timing gaps, usable phases, respiration context for HRV. Polar H10 ECG Belt is not in Case Study 1.
    - Implausible Values refers to measurement values that are too high or low to be plausible and thus seriously considered in analysis.
    - Motion Artifacts refer to windows where the participant(and naturally the emotibit) are moving too much for that window of HRV data to be reliable.
    - Respiration Context refers to the fact that HRV data is most reliable when the participant is breathing at between 9-24 breaths per minute. Sections where breathing is outside of this range should be flagged or dropped depending on wider context.
