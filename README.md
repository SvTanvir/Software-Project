<p align="center">
  <img src="hstu_logo_.png" alt="hstu_logo_.png" width="250" height="300">
</p>
<h1 align="center">
  <b>Online Product Recommendation System</b>
</h1>
<h3 align="center">
  <br>
  <b>Level-3 Semester-I Project Report</b>  
</h3>
<h3 align="center">
  Course Code: CSE 305 
</h3>

<h3 align="center">
  Course Title: Software Engineering
</h3>
<br>
<h3 align="center">
  Submitted by 
</h3>
<h3 align="center">
<b>Md.Tanvir Ahmmed Shuvo (ID: 2102054) </b> </h3>
<br>

<h3 align="center">
  Submitted To 
</h3>

<h3 align="center"><b>Pankaj Bhowmik  </b></h3>
<h3 align="center"><b>Lecturer, Department of CSE</b></h3>
<br>
<h3 align="center"> <b>Department of Computer Science and Engineering </b></h3>
<h3 align="center"><b>Hajee Mohammad Danesh Science and Technology University  
Dinajpur-5200</b></h3>

  ---


# Online Product Recommendation System

---

## Table of Contents
1. [Project Overview](#project-overview)  
2. [SDLC Phases with Verified Implementation](#sdlc-phases-with-verified-implementation)  
   - [Phase 1: Planning](#phase-1-planning)  
   - [Phase 2: Requirement Analysis](#phase-2-requirement-analysis)  
   - [Phase 3: System Design](#phase-3-system-design)  
   - [Phase 4: Implementation](#phase-4-implementation)  
   - [Phase 5: Testing](#phase-5-testing)  
   - [Phase 6: Deployment](#phase-6-deployment)  
   - [Phase 7: Maintenance](#phase-7-maintenance)  
3. [Figures](#figures)  
4. [Conclusion](#conclusion)  

---

## 1. Project Overview
The Online Product Recommendation System is a web-based application designed to enhance the shopping experience by providing personalized product recommendations. Using customer data, such as browsing history and preferences, it delivers accurate, relevant suggestions. The project adheres to the SDLC methodology, ensuring a structured and effective development lifecycle.

---

## 2. SDLC Phases with Verified Implementation

### [Phase 1: Planning](#table-of-contents)
**Objective Verification:**  
- Develop a system to recommend products based on user behavior.  
- Enhance customer satisfaction and increase sales.

**Verified Target Audience:**  
- E-commerce platform users seeking tailored shopping experiences.

**Verified Goals:**  
1. Provide personalized and real-time recommendations.  
2. Improve engagement through intuitive design and responsiveness.  
3. Ensure compatibility with multiple devices.

**Outcome:**  
The planning stage successfully identified objectives, audience, and measurable goals.

---

### [Phase 2: Requirement Analysis](#table-of-contents)
**Functional Requirements:**  
1. Collect and analyze user browsing and purchase data.  
2. Recommend products based on user preferences and trends.  
3. Display suggestions dynamically on the user interface.

**Non-Functional Requirements:**  
1. Ensure high system scalability for large datasets.  
2. Guarantee fast response times for real-time suggestions.  
3. Provide cross-platform compatibility.

**Constraints:**  
- Recommendations rely on the availability and accuracy of user data.  
- Integration with an e-commerce platform requires robust APIs.

---

### [Phase 3: System Design](#table-of-contents)
**Architecture:**  
The system uses a modular design comprising a data preprocessing module, recommendation engine, and frontend interface.

**Components:**  
1. **Data Collection Module:** Gathers user activity data from the e-commerce platform.  
2. **Recommendation Engine:**  
   - Implements collaborative and content-based filtering.  
3. **Frontend UI:** Displays recommended products dynamically.

**UI Design Verified:**  
- **Color Scheme:** Neutral colors for a clean look.  
- **Font Choices:** Sans-serif fonts for readability.  
- **Layout:** Recommendations positioned prominently to attract user attention.

**Outcome:**  
The design ensures modular functionality and an intuitive interface.

---

### [Phase 4: Implementation](#table-of-contents)
**Development Stack:**  
- Backend: Python (Flask/Django)  
- Frontend: React.js, HTML/CSS  
- Database: MongoDB for user data storage  

**Key Features:**  
1. **Collaborative Filtering:** Analyzes user similarities to suggest products.  
2. **Content-Based Filtering:** Matches product attributes to user preferences.  
3. **Hybrid Approach:** Combines collaborative and content-based models for improved accuracy.

**Code Structure:**  
- The `generateRecommendations()` method processes input data and returns suggestions.

**Example Recommendation Logic:**  
- **Input:** User browses for "smartphones and accessories."  
- **Output:** Suggests phone cases, chargers, and compatible earbuds.

---

### [Phase 5: Testing](#table-of-contents)
**Test Plan:**  
1. Simulate user interactions and evaluate recommendation accuracy.  
2. Validate the system’s responsiveness under heavy loads.  
3. Verify cross-platform compatibility.

**Testing Results:**

| **Test Case** | **Input**                               | **Expected Output**              | **Actual Output** | **Status** |
|---------------|-----------------------------------------|-----------------------------------|-------------------|------------|
| TC1           | Browsed "laptops and keyboards"         | Suggest relevant accessories      | Same              | Pass       |
| TC2           | No user history (new user)              | Display trending/popular items    | Same              | Pass       |
| TC3           | 1000 simultaneous user interactions     | Real-time recommendations         | Same              | Pass       |

---

### [Phase 6: Deployment](#table-of-contents)
**Platform:**  
Deployed on AWS with scalable instances for high availability.

**User Guide:**  
1. Log in to the e-commerce platform.  
2. Browse or search for products.  
3. View personalized recommendations on the homepage or product pages.

---

### [Phase 7: Maintenance](#table-of-contents)
**Regular Updates Include:**  
1. Fine-tuning algorithms with new data.  
2. Adding contextual recommendations (e.g., seasonal trends).  
3. Resolving bugs and performance optimization.

---

## 3. Figures

### System Architecture Diagram:
1. **User Activity Data** → **Data Collection Module** → **Preprocessing Module**  
2. Preprocessed Data → **Recommendation Engine (Collaborative + Content-Based)** → **Frontend UI**

### UI Mockup:
- **Search Bar**  
- **Popular Items Section**  
- **Recommendations Section**  
  - Product 1 | Product 2 | Product 3  

---

## 4. Conclusion
The Online Product Recommendation System effectively combines user behavior analysis and machine learning to provide personalized shopping experiences. Following the SDLC methodology ensured a structured development process, from requirements gathering to deployment. Future improvements include advanced contextual and location-based recommendations.

---

### Example Input:
- **User Browsing History:** Electronics and books.  
- **Output:** Recommends headphones, e-readers, and related accessories.
