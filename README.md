# Streamlining Course Survey Management through Power Platform

## 📌 Project Report: Digital Transformation of Course Surveys using Microsoft Power Platform

---

## 1. Background and Existing Issues

Previously, student surveys for multiple courses were conducted using a combination of Microsoft Forms and paper-based forms.

- Surveys were manually distributed, filled, and collected.
- High risk of data redundancy and loss.
- Manual data validation and aggregation by staff caused delays and inconsistencies.

---

## 2. Objective

Digitize and centralize the survey process using Microsoft Power Platform to:

- Simplify the student survey submission experience.
- Reduce manual data handling for staff.
- Enable real-time analytics and feedback tracking.

---

## 3. Solution Overview

### Technologies Used
- Microsoft SharePoint *(Back-end data storage (one list per survey)*
- Power Apps *(Front-end for student and educator apps)*
- Power BI *(Visual reporting and analytics)*
- Microsoft 365 *(For user data integration and security)*


---

## 4. Implementation Details

### 📋 Survey Management for Students

#### SharePoint Lists
- Separate SharePoint list created per course survey.
- Columns represent survey questions and student info fields.

#### Power Apps Interface
- Unified form to select and complete course-specific surveys.
- Dynamic navigation between survey screens.
- Auto-capture of Microsoft 365 user data: student name, course, email.
- Responsive design for cross-device usability.

---

### 🎓 Survey Feedback for Educators

#### Educator Power App
- Dedicated app for reviewing student responses.
- Connected to all SharePoint lists.
- Supports feedback submission using `Patch()` function.
- Real-time updates synced with SharePoint for consistency.

---

### 📊 Data Reporting

#### Power BI Dashboard
- Connected to survey SharePoint lists.
- Provides visual insights:
  - Survey participation by course.
  - Aggregated question responses.
  - Trends in student feedback.
  - Educator feedback analytics.
- Filters/slicers for drill-down by course, date, or response type.

---

## 5. Benefits Achieved

- ✅ Reduced manual paperwork and admin load.
- ✅ Increased accuracy and completeness of data.
- ✅ Real-time analytics enabled.
- ✅ Improved student user experience.
- ✅ Strengthened student-educator feedback loop.

---

## 6. Future Enhancements

- 🔄 Integration with Power Automate for automated notifications.
- 🔐 Role-based access control for user-specific views.
- 📤 Export functionality to PDF/Excel for archival and reporting.
- 📈 KPI metrics to evaluate student satisfaction scores.

---

## 7. Screenshots and Visuals

- Student Power Apps survey form.
- Educator feedback interface.
- SharePoint survey lists.
- Power BI dashboards.

---

## 8. Conclusion

This Microsoft Power Platform-based solution has significantly improved the **efficiency**, **scalability**, and **transparency** of the course survey process.  
It serves as a **replicable model** for automating and digitizing other institutional processes.


