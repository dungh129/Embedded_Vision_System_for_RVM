# Online Survey Summary

## Overview

This section presents the results of an **online survey (77 responses)** conducted to understand
user behavior, motivation, and preferences related to recycling and automated recycling systems.

The purpose of this survey is to inform the design of an embedded vision-based bottle classification
system for use in a Reverse Vending Machine (RVM).

**Note:**
Stakeholder interviews and field observations are documented separately in
`stakeholder_interviews.md`.

---

## Respondent Scope

The majority of respondents were located within a single city in the Sacramento region.

As a result, the findings primarily reflect local recycling behavior and perceptions in this area.
While these insights are valuable for urban deployment scenarios, they may not fully generalize
to other regions with different infrastructure or demographics.

---

## Survey Structure

The survey was organized into five key areas:

1. User behavior
2. Motivation
3. Feature importance
4. Trends and location
5. Limitations and trade-offs

---

## Key Findings

### 1. Recycling Frequency

* 26 respondents rarely or never recycle, or recycle only once or twice per year
* 10 recycle every 2–3 months
* 20 recycle weekly or monthly
* 21 recycle daily

**Insight:**
A significant portion of users do not recycle consistently, indicating a gap between awareness and regular behavior.

---

### 2. Amount Recycled per Visit

* 28 respondents recycle between 50 to over 100 items per visit
* 17 recycle between 11–50 items
* 11 recycle fewer than 10 items
* 20 do not track quantity

**Insight:**
Systems must accommodate both high-volume users and occasional recyclers.

---

### 3. Motivation for Recycling *(multiple selections allowed)*

* 54: environmental concern
* 31: habit or upbringing
* 25: financial rewards
* 21: availability of nearby recycling bins
* 12: personal satisfaction
* 10: peer or community influence

**Insight:**
Environmental awareness is the primary driver, but convenience and incentives significantly influence participation.

---

### 4. Preferred Reward Types

* 62: cash
* 28: coupons
* 13: donation to charity
* 11: redeemable points
* 10: raffle entry
* 9: no preference

**Insight:**
Direct monetary rewards are the most effective incentive.

---

### 5. Financial Incentive Expectations

* 23 respondents do not require financial incentives
* 25 consider $1–$20 per month acceptable
* 18 expect more than $20 per month
* 11 would recycle for any amount

**Insight:**
Financial incentives are helpful but not essential for all users.

---

### 6. Feature Preferences

* 57 respondents would recycle more if the system automatically sorted items
* 18 emphasized fast and easy interaction

**Insight:**
Automation and ease of use are key factors in increasing adoption.

---

### 7. Preferred Machine Locations *(multiple selections allowed)*

* 71: grocery stores or supermarkets
* 37: parks and recreational areas
* Over 30: apartments, schools, offices, and public buildings

**Insight:**
Convenient, high-traffic locations significantly improve system usage.

---

### 8. App Usage for Tracking Recycling

* 33 respondents would use an app
* 27 would use it if it is simple and easy
* 17 prefer not to use an app

**Insight:**
Digital features should be optional and designed for simplicity.

---

### 9. Important Machine Qualities

* Cleanliness
* Time-saving convenience
* Cashback or rewards

**Insight:**
User experience and hygiene are critical for adoption.

---

### 10. Machine Speed Acceptability

* 40 respondents would use the system regularly at 5–10 items per minute
* 13 would use it less often
* 7 would use it only for small quantities
* 7 would use it if there is no waiting line
* 4 would avoid using it

**Insight:**
Moderate processing speed is acceptable, but waiting time affects user behavior.

---

### 11. Personalization and Accessibility

Users expressed preference for:

* wait time display
* immediate or delayed reward options
* multiple machines
* convenient locations

Only 6 respondents indicated they would not use the system.

**Insight:**
Flexibility and accessibility significantly improve user engagement.

---

### 12. Additional Feedback

Participants emphasized:

* accessibility for elderly and disabled users
* multi-language support
* clear instructions and graphics
* system security
* machine availability and wait time

**Insight:**
Inclusivity and usability are essential for real-world deployment.

---

## Engineering Impact

The survey results directly informed system design decisions:

* Dataset incorporates variation in:

  * background
  * lighting
  * position

* System priorities include:

  * automated classification
  * fast processing
  * ease of use
  * deployment in accessible locations

* Design considerations balance:

  * performance
  * user behavior
  * real-world constraints

---

## Data Privacy and Usage

* All responses are anonymous and aggregated
* No personally identifiable information (PII) is included
* Data is shared for research and educational purposes only

---

## Copyright and Attribution

© 2026 Dung H.

This work is provided for academic and educational purposes.
Please provide attribution if referenced or used.
