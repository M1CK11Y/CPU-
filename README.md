# Keeping Critical Jobs Alive: A Power-Interruption-Aware Job Scheduler

**Group:** SCS1103 Group 1 – CPU Tech Innovators  
**Repository:** https://github.com/M1CK11Y/SCS1103-Group1-Job-scheduling

## Team Members and Roles

| Name                        | Registration Number | Role              |
|-----------------------------|---------------------|-------------------|
| Michael T Duri              | N02643960W          | Presenting / Coordinator |
| Yemurai Takaindisa          | N02645752X          | Build             |
| Anesu Njenge                | N02641219V          | Build             |
| Kudra Gumbo                 | N02641201W          | Build             |
| Ishmael I Shayanewako       | N02654127T          | Build             |
| Tadiwa W Mukozho            | N02642410B          | Build             |
| Tendai Matonhodze           | N02645116N          | Research          |
| Hilda Dahwa                 | N02657091M          | Research          |
| Nicole Mhofu                | N02644714Y          | Research          |
| Mitchelle Karabo            | N02641669M          | Writing           |
| Shanelle Mondy              | N02654997Y          | Writing           |
| Desire Mbiri                | N02644003X          | Writing           |
| Taruvinga Mufudzi           | N02645364W          | Presenting        |
| Cheryl Donga                | N02641879T          | Presentation      |
| Natasha Funekiwe Nkomo      | N02642892B          | Presentation      |

## Research Question
How can a power-interruption-aware job scheduler keep critical jobs alive by dynamically prioritising and rescheduling tasks around ZETDC load-shedding windows?

## Aim
To build a job planner that works around power interruptions by using real ZESA load-shedding schedules and a public cloud workload to maximise completion of critical jobs.

## Objectives
1. Identify and classify jobs by criticality and electricity dependence during load-shedding periods.  
2. Design and implement a priority-aware job scheduler that allocates jobs only to available power windows taken from the 2021 ZETDC schedule.  
3. Evaluate the scheduler by measuring critical-job completion rate and average waiting time against a simple FCFS baseline; success if critical-job completion improves by at least 20% without making non-critical jobs wait unreasonably long.

## OS Concept
Priority Scheduling (CPU Scheduling)

## Data Sources
- Jobs: Azure Functions Invocation Trace 2021  
  https://github.com/Azure/AzurePublicDataset  
- Outage times: 2021 ZETDC Load-Shedding Schedule PDF  
  https://zimlive.com/wp-content/uploads/2021/09/ZESA-LOAD-SHEDDING-SCHEDULE-2021.pdf
