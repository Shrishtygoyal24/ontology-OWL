# Ontology-Based Intelligent Education Support System — Capstone Edition

## Overview

This `.owl` ontology is an advanced, customizable model for an intelligent education support system. It features extended entities, relationships, and properties to power smart recommendations, skill tracking, department support, and more.

## Unique Features

- **Expanded classes:** Includes Department, Semester, Skill.
- **Performance & Recommendations:** Assessments have scores, teachers recommend materials.
- **Relations for capstone:** Students track skills, courses belong to departments and semesters.
- **More example individuals:** Shows how ontology works in practice.

## Core Classes

- **Student**: Learners, each with skills and course enrollments.
- **Teacher**: Educators, who recommend and teach courses.
- **Course**: Learning units, tied to topics, assessments, department, and semester.
- **Topic**: Subject matter focus within courses.
- **Assessment**: Exams, quizzes, projects (with scores).
- **LearningMaterial**: Books, notes, guides for topics.
- **Department, Semester, Skill**: Model institutional structure, time periods, and student capabilities.

## Key Properties

- **enrolledIn**: Which courses students take.
- **teachesCourse**: Which courses teachers teach.
- **hasTopic / hasAssessment**: Content and assessment for each course.
- **belongsToTopic**: Learning materials for each subject.
- **studentHasSkill**: Skills acquired by students.
- **courseOfDepartment / courseSemester**: Extra context for course organization.
- **hasScore**: Quantitative student performance.
- **recommendsMaterial**: Smart suggestions by educators.

## Example Individuals

- Students: Alice (Critical Thinking), Bob (Lab Skills), Carol (Problem Solving)
- Teachers: Dr. Smith (AlgebraBook), Miss Jones (BiologyGuide), Prof Ray (PythonNotes)
- Courses: Math101 (Algebra), Biology102 (Genetics), Programming101 (PythonBasics)
- Departments: Science, IT
- Semesters: 1, 2
- Skills: Critical Thinking, Lab Skills, Problem Solving

## How to Use

1. **Open** `edu-support-capstone.owl` in [Protégé](https://protege.stanford.edu/).
2. **Explore** the classes, properties, and individuals. See advanced capstone-level modeling.
3. **Extend**: Add grades, prerequisites, advanced relationships, more individuals, or SWRL rules for recommendations or predictions.
4. **Document** your project and justify design decisions.

## Capstone Expansion Ideas

- Add rules for automatic recommendations (using SWRL in Protégé).
- Model group projects or collaborative assessments.
- Connect more courses and cross-department offerings.
- Include feedback or self-assessment entities.

## Author

*Shrishtygoyal24 & Team — 2024-2025 Capstone*
