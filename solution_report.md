*** ### Task 1: Choose a Business Domain***
## 1. Business Domain
Healthcare

*** ### Task 2: Define the Business Problem ***
### 1. Business Problem 
The primary problem is the Diagnosis gap in medical imaging. Since medical system follows first-come first-serve standards, Some of the Critical, serious life-threatening conditions likr brain hemorrhage (or)  lung cancer diagnosis will take longer time while a specialist reviews non-urgent cases.

## 2. Stakeholders
1. Radiologists: Radiologists are Primary users who need to prioritize urgent scans.
2. Emergency Room Physicians: Physicians who relay on life-saving interventions.
3. Hospital Administrators: Focus on patients reducing diagnostic errors.
4. Patients: The  beneficiaries of faster treatment.


### 3. Current Process
1. Linear Worklists: Images are uploaded to system and added to a chronological queue.
2. Manual Prioritization: Radiologists scan the list based on broad department priority 
(e.g., "ER" vs. "Outpatient") rather than the severity of condition.
3. Standard Reporting: Reports are dictated and transcribed, which can take anywhere from 15-20  minutes to several hours.

### 4. Limitations
1. Latency in Critical Care: There is No automated "flagging" for urgent findings immediately after a scan is completed.
2. Human Fatigue: High volume and repetitive tasks increase the risk of missing or ability to diagnose the condition because of cognitive bias.
3. Inconsistency: Variation in interpretation speed and accuracy across different hospital shifts.
4. Operational Strain: Growing scans create bottlenecks that slow down the entire hospital system.

*** ### Task 3: Identify the AI Task Type ***
### Classification: Object Detection (with a sub-component of Anomaly Detection)

### Why this AI task type is suitable:
1. Medical imaging isn’t just about finding out if something is wrong; it’s about finding exactly where the problem is and how urgent it is. Here is why Object Detection is the right tool for the job:

2. It’s not enough to tell a doctor a scan is "abnormal." The AI acts like a digital highlighter, drawing "bounding boxes" around specific issues like a tiny fracture or a blood clot. This saves the radiologist time by showing them exactly where to look first.

3. Instead of scans being reviewed in the order they were taken, the AI scans them all instantly. If it spots a life-threatening emergency—like a collapsed lung—it "taps the doctor on the shoulder" and moves that patient to the very top of the list so they get help immediately.

4. A patient might have more than one thing going on. While basic AI might only find one label for a photo, Object Detection is designed to "see" and label multiple different issues in a single scan, ensuring nothing gets missed.

5. Doctors long night shifts can make them exhausted. The AI acts as a 24/7 safety net that never gets exhausted. It flags tiny changes that are easy to overlook, helping ensure every patient gets a consistent, high-quality review.

