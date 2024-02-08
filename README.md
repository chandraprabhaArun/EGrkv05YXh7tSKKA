# Potential Talents - Human Resources and Staffing Project
Overview

The Potential Talents Project is a data-driven initiative aimed at predicting the fitness of candidates for specific roles based on available information. The dataset used in this project is sourced through our efforts, ensuring the removal of any fields that could directly reveal personal details. Each candidate is assigned a unique identifier for privacy and security.
Dataset Attributes

    id: Unique identifier for the candidate (numeric).
    job_title: Job title for the candidate (text).
    location: Geographical location for the candidate (text).
    connections: Number of connections the candidate has; "500+" means over 500 (text).

### Output (Desired Target)

    fit: A numeric value representing how fit the candidate is for the role, ranging between 0 and 1.

Keywords

    The dataset includes candidates expressing interest in roles with keywords such as "Aspiring human resources" or "Seeking human resources."

Goals

    Predict how fit the candidate is based on their available information (variable fit).

Success Metrics

    Rank candidates based on a fitness score.
    Re-rank candidates when a candidate is starred.
