# Test Case: Instructor Uploads Valid Answer Sheet

**Test Case ID:** TC-OMR-001
**Test Suite:** Backend: OMR & Scanning

**Feature:** Exam Paper Scanning
**Test Objective:** Verify that the system can successfully process a valid, clearly scanned answer sheet image uploaded by an instructor.

---

### Pre-conditions
*   The user must be logged in as an Instructor.
*   An exam profile must already be created with a defined answer key.
*   A valid answer sheet image file (e.g., `.jpg`, `.png`) is available and correctly filled out.

---

### Test Steps
1.  Navigate to the "Exams" dashboard.
2.  Select the corresponding exam for the answer sheet to be uploaded.
3.  Click the "Upload Answer Sheets" button.
4.  Select the valid answer sheet image file from the local machine.
5.  Confirm the upload and wait for the processing to complete.

---

### Expected Result
*   The image is uploaded successfully without errors.
*   The backend OMR service processes the image and correctly identifies all marked answers.
*   The system calculates the score based on the predefined answer key.
*   The processed result appears in the instructor's verification queue with the correct score.

---

### Actual Result
*   [To be filled in during test execution]

### Status
*   [Pass / Fail / Blocked]

### Notes
*   Test with different lighting conditions and scan resolutions to check robustness.
